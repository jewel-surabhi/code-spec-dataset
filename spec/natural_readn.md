# Natural ADABAS Loop

- **READN-LP.NSP**
  - Code: https://github.com/SoftwareAG/adabas-natural-code-samples/blob/master/NATURAL/READN-LP.NSP
  - Spec: This program is written in Natural, the 4GL language for Software AG's ADABAS database. This code snippet demonstrates a typical data processing loop. The `READ (10) EMPLOYEES-VIEW BY NAME` statement initiates a loop to read 10 records at a time from the `EMPLOYEES-VIEW` (a data definition) and specifies that the records should be sorted by the `NAME` field. Inside the loop, it `DISPLAY`s specific fields from the current record. The `LOOP` statement marks the end of the processing for the current record.