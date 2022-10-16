# Edgar.Py

##Quick Start Guide

Specify the starting year and end year and the directory to save outputs. By default, indices, forms and mdas will be saved to ./data

```
# Downloads and parses MDA section from 2021 to 2021 quarter 1 and 2, and saves to `./data/`
python edgar.py --start_year 2021 --end_year 2021 --quarters 1 2 --data_dir ./data/

```
## NOTE:

As specified in the task, the modified code downloads downloads 100 10k files, parses, and extracts the mda from these files. Checks if MDA was properly extracted from these 10k files and create a list of the files that were successfully parsed and a list of those that didn’t work.

The list of the paths of files that were successfully parsed is stored in the list ```ParsedSuccessfully``` and the list of the paths of files that weren't successfully parsed is stored in the list ```ParseFailed```
