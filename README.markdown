# Python scripts for disambiguating patent data

The following collection of scripts performs pre- and
post-processing on patent data as part of the patent
inventor disambiguation process.

## CURRENT:

(I) DATASET PREPARATION

(1) XML Parsing

	a. Open XMLParse2008.py
	b. Set variable flder = <folder that contains all XML raw files>
	c. Run XMLParse2008.py

(2) Data Cleaning

	- scripts_v2.py should be in same directory as all sqlite3 files from XML Parsing step.
	a. Run scripts_v2.py

(3) Table Consolidation

	a. Run invpat.py
	b.

(II) RESULTS ANALYSIS

From the command line, run bmVerify_v3.py.

Use python bmVerify_v3.py ? or python bmVerify_v3.py help for more information.

(III) Other scripts

Run from command line to create files:

python patentYear.py [year] [src]
python createFullSet.py [start_year] [end_year] 

## PREVIOUS:

bmVerify compares the consolidated results with an existing benchmark

compressBlk takes a "disambiguated" dataset and consolidates it into a new dataset.

fwork.py are Python scripts I reuse

