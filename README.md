# corners



corners test


## Automation for making 4 Corners Disk Testing more successful. ##


## The Script automates the test for the 4 best performing Latency counters for disk testing. ##
## It also has a longer test which takes over an hour to administer per node ##


Link to download and administer here: 

``` Powershell
echo corners;[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12;Invoke-Expression('$module="corners";$repo="PowershellScripts"'+(new-object net.webclient).DownloadFile('https://raw.githubusercontent.com/Louisjreeves/corners/main/Begin4corners.ps1',"Begin4corners.ps1"));Begin4corners.ps1

```


Below is some examples of what the automation looks like : 

![1](https://github.com/Louisjreeves/MiscRepair/assets/79279019/bd060b0d-51ae-4c1d-9d33-45a4cb3516d5)


![2](https://github.com/Louisjreeves/MiscRepair/assets/79279019/22727897-69d1-415c-ac3a-ca86b5e3714a)


![3](https://github.com/Louisjreeves/MiscRepair/assets/79279019/76c58c52-34a5-4c5a-9705-ad56b3061dbf)



# What this script does: 

# Below are steps and screenshots with information on setting up the disk tests. 


⦁	Unzip 4Corner_Test.7z to “C:\Temp”.  Rename diskspd.__e to diskspd.exe
⦁	Remove the “renameme” extension name. 

 

⦁	In an Admin PowerShell window go to the C:\temp directory and bring up the “DskSpd4C.ps1” file. 




⦁	Type in the Drive Letter we’re testing, the example below is using “E”. 

 


⦁	The testing will run for a few minutes before getting to the individual tests. 

 


⦁	The tests will take some time to run.  The results are in the “TestDiskSpd” folder within the “testfile.dat” file. 

 
 

⦁	Please run the test on each storage unit.  Also label them so we know which file comes from the Compellent and PowerStore units. 
⦁	Next zip files and send in for review. 

 
