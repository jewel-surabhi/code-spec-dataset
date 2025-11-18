# PL/I File I/O

- **FILEIO.PLI**
  - Code: https://github.com/mainframed/pli-examples/blob/master/pli/FILEIO.PLI
  - Spec: This is a program in PL/I, a high-level language developed by IBM for scientific and business use. This example shows a common batch processing pattern: reading records from one file and writing them to another. It `DECLARE`s an `INFILE` and `OUTFILE`, defines a record structure (`MYREC`), and uses an `ON ENDFILE` block to handle the end-of-file condition by setting a flag. The main loop simply reads from `INFILE` into the structure and writes the same structure to `OUTFILE` until the flag is set.