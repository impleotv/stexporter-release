
<div align="center">
  <a >
    <img src="images/impleo_logo.png" alt="Logo" >
  </a>
</div>

# StExporter
**StExporter** - command line utility that adds MISB 0601.X metadata to a transport stream sent over UDP.  
More [info](https://impleotv.com/products/applications/stexporter/).

## System Requirements
OS: Windows 10 64 bit.

## Installation

**StExporter** can be downloaded as a **zip** file that contains installer.  
Unzip the **SetupStExporter.zip** file and run the **SetupStExporter.exe**  

## Download link

| Software | Version             | Download link                                                           | 
|:---------|:-------------------:|:------------------------------------------------------------------------|
| **STANAG StExporter** |  v1.8.9 | [SetupStExporter.zip](https://github.com/impleotv/stexporter-release/releases/latest/download/SetupStExporter.zip) | 

*Released on Sun, 14 Nov, 13:38 GMT+2*

## License

**StExporter** is a node locked software. In order to get the license, please install it and fill an [online form](https://docs.google.com/forms/d/e/1FAIpQLSd_XW6bDsFce1G1cpds4gMQNlwNax0CvkWzcMbscxZ5rLaIbA/viewform), providing the ***Node Info*** string (IMPORTANT!!!) for the target machine.  
***Node Info*** string can be seen when you run the application (or press N - Show NodeInfo), as shown below.

```
C:\Program Files\ImpleoTV\StExporter\Bin\x64\StExporterProc.exe
```

![NodeInfo string](images/license.png)

Please copy-paste *Node Info*, don't send an image...

You'll get back a **license** file and a **key**.

Use *--licenseFile* and *--licenseKey* as arguments, for example:
```
 --licenseFile "D:\Licenses\StExporter.lic"  --licenseKey DDD8460B-8419FF85-0B36C1B5-3FC6143C
```
If a license file is in the same directory as the .exe, you can skip the path.
