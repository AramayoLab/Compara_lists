**[![DOI](https://zenodo.org/badge/496398714.svg)](https://zenodo.org/doi/10.5281/zenodo.6582472)**
# **Compara_Lists**

## **Motivation**

```
The main motivation for generating this script was reproducibility and replicability, when comparing
list of IDs. Mainly, I wanted to make sure that students evaluating information present in different
files used the same set of commands, thus eliminating any possibility of error

```

## Documentation

```
########################################################################################################################################################################################################
ARAMAYO_LAB

This program is free software: you can redistribute it and/or modify it under the terms of the GNU
General Public License as published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without
even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not,
see <https://www.gnu.org/licenses/>.

SCRIPT_NAME:                       Compara_Lists_v1.0.2.sh
SCRIPT_VERSION:                    1.0.2

USAGE: ./Compara_Lists_v1.0.1.sh
       -a List A                   # REQUIRED input (e.g., listA)
       -A List A Name              # OPTIONAL (e.g., listA)
       -b List B                   # REQUIRED input (e.g., listB)
       -B List B Name              # OPTIONAL (e.g., listB)

TYPICAL COMMAND:                   Compara_Lists_v1.0.1.sh -a listA -A listA -b listB -B listB

INPUT01:          -a FLAG          Name of a single column text file containing records IDs to be compared (e.g., listA)
INPUT01_DEFAULT:                   No Default. ListA file must be provided
INPUT01_FORMAT:                    Single column text file
INPUT01_NOTES:                     Required

INPUT02:          -A FLAG          Name of the listA dataset or listA dataset label
INPUT02_DEFAULT:                   listA
INPUT02_FORMAT:                    Text
INPUT02_NOTES:                     Optional. Label will be used to name the output files

INPUT03:          -b FLAG          Name of a single column text file containing records IDs to be compared (e.g., listB)
INPUT03_DEFAULT:                   No Default. ListB file must be provided
INPUT03_FORMAT:                    Single column text file
INPUT03_NOTES:                     Required

INPUT04:          -B FLAG          Name of the listA dataset or listB dataset label
INPUT04_DEFAULT:                   listB
INPUT04_FORMAT:                    Text
INPUT04_NOTES:                     Optional. Label will be used to name the output files

DEPENDENCIES:                      GNU COREUTILS Required (https://www.gnu.org/software/coreutils/)

Author:                            Rodolfo Aramayo
WORK_EMAIL:                        raramayo@tamu.edu
PERSONAL_EMAIL:                    rodolfo@aramayo.org
########################################################################################################################################################################################################
```

## Development/Testing Environment:

```
Distributor ID:       Ubuntu
Description:          Ubuntu 20.04.4 LTS
Release:              20.04
Codename:             focal
```

## Required Script Dependencies:
### GNU COREUTILS (https://www.gnu.org/software/coreutils/)
#### Version Number: 8.30

```
comm (GNU coreutils) 8.30
Copyright (C) 2018 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Written by Richard M. Stallman and David MacKenzie.
```

#### Version Number: 8.32

```
comm (GNU coreutils) 8.32
Copyright (C) 2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Written by Richard M. Stallman and David MacKenzie.
```
