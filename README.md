# gtf-to-csv-converter
simple python 2 gtf to csv converter 

Stores whole GTF in memory thus will fail on relatively big data. 
Single thread only.

# man
```
python gtf_to_csv.py --help
usage: gtf_to_csv.py [-h] -i INFILE [-o OUTFILE]
                     [-columns COLUMN [COLUMN ...]]

Input GTF file and optional parameters

optional arguments:
  -h, --help            show this help message and exit
  -i INFILE             input gtf file
  -o OUTFILE            output csv file, defaults to `input file name`.csv
  -columns COLUMN [COLUMN ...], -c COLUMN [COLUMN ...]
                        list of columns to write to csv, e. g. `-columns column1 column2 column3`
```