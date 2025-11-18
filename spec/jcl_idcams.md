# JCL IDCAMS Utility

- **IDCAMS.jcl**
  - Code: https://github.com/mainframed/jcl-examples/blob/master/jcl/IDCAMS.jcl
  - Spec: This file is a JCL (Job Control Language) script, the "batch file" language of IBM mainframes. It doesn't execute application logic itself but instead tells the operating system (z/OS) how to run a job. This specific job executes the `IDCAMS` utility (Access Method Services) to define a new VSAM (Virtual Storage Access Method) dataset, which is the primary way structured data is stored on mainframes. The `DEFINE CLUSTER` command specifies parameters for a new Key-Sequenced Data Set (KSDS), including its name, space allocation (`CYLINDERS`), and the location and length of its primary key (`KEYS(5 0)`).