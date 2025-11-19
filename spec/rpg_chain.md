# RPG IV Chain Operation

- **CHAIN.RPGLE**
  - Code: https://github.com/SjorsdeVries/RPG-examples/blob/master/RPGILE/CHAIN.RPGLE
  - Spec: This is a program written in fixed-format RPG IV (RPGLE), a language native to the IBM iSeries (AS/400). This program demonstrates a classic "green screen" database interaction. The F-Specs declare two files: `CUSTPF` (a physical database table) and `CUSTDSP` (a display UI file). The C-Specs logic loops as long as the user doesn't press F3. It executes the screen (`EXFMT`), waits for user input, and then uses the `CHAIN` operation code. `CHAIN` is a direct random-access read, using the customer number (`CUSTNR`) from the screen to fetch a specific record from the `CUSTPF` database file.