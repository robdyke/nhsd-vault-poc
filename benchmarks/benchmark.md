

### poc1
`time ./poc1.sh source_csv/patients_10000.csv`

Result 2m 33s

### poc2
`time ./poc2.sh source_csv/patients_no_header_10000.csv encrypt`

Result 22m 8s

### poc3
`time ./poc3.sh source_csv/patients_no_header_10000.csv encrypt`

Result 5m 42s

`time ./poc3.sh transit_files/cipher_patients_no_header_10000.csv decrypt`

Result 6m 14s
