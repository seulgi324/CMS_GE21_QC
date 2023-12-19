# CMS_GE21_QC
GE2/1 QC2~6 reports generators! Try to run them on lxplus9 using the commands below.

# lxplus9
You need to install some packages before running them.
```bash
python3 -m pip install --user pandas
python3 -m pip install --user numpy==1.22.4
python3 -m pip install --user mplhep
python3 -m pip install --user fpdf
python3 -m pip install --user openpyxl
```

# QC2

# QC3&4
If you run QC34_report.py script, you will get 2 plots and 1 pdf report! Don't forget to change the path of data.
```bash
python3 QC34_report.py -mt [module_type] -mn [module_number] -d3 [qc3_date (YYYY/MM/DD)] -d4 [qc4_date (YYYY/MM/DD)]
```
