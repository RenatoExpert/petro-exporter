# petro-exporter
Read calibration certificates for Tank Tonnage and prepare SQL commands to register their info.
## Suports readings from
- Inmetro
- Ibametro
## Process
Everything runs inside a bash script.
It gets certificates in xls (MS Office Excel) and converts to '.txt' using 'ssconvert'. Then, the content of each file is parsed to a perl script, which identifies each property.


