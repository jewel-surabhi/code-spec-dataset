# Classic ASP ADO Connection

- **ado-connection.asp**
  - Code: https://github.com/rcuper/Classic-ASP-Examples/blob/master/ado-connection.asp
  - Spec: This is a Classic ASP (Active Server Pages) file, a server-side scripting technology from Microsoft that predates ASP.NET. The script is written in VBScript. Its sole purpose is to demonstrate a standard database connection using ADO (ActiveX Data Objects). It creates an `ADODB.Connection` object, sets the OLEDB provider string (in this case, for a Microsoft Access `.mdb` file), and calls the `Connection.Open` method. This pattern was the foundation for nearly all data-driven websites on Microsoft IIS in the late 90s.