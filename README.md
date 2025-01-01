# Windows Forensic Artifacts: User and System

<h2>Description</h2>
In this Digital Forensics task, I used registry explorer to enumerate clean system and user hives to enumerate different artifacts like user login, system id, and computer name.  

<h2>Languages and Utilities Used</h2>

- <b>Registry Explorer</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b> 

<br />
<br />
Using gkape to target the C:\ drive for ym widows 10 vm, destination to a Cases folder, using the find function to look for registry and selecting all relevant registry hives, then executing. 

![1) load clean system logs into registry explorer](https://github.com/user-attachments/assets/4566b3ae-4c34-4d8f-99de-80a6d5d08228)

<br />
<br />
Showcasing the Windows System32 config logs extracted. 

![2) rootmicrosoftwindowsntcurrentversion](https://github.com/user-attachments/assets/e8dffe2c-2526-43a8-abdc-b9a79804020e)

<br />
<br />  
Showcasing the NTUSER.DAT logs extracted. 

![3) epoch converter](https://github.com/user-attachments/assets/d1730f8b-61c7-44ae-ac06-b8f86753b575)

<br />
<br />
Showcasing the UsrClass logs extracted. 

![4) SYSTEMCurrentControlSetControlSetControlSession ManagerEnvironment](https://github.com/user-attachments/assets/f7f310ae-0f69-43a9-a82d-1b1cf291a711)

<br />
<br />
In Registry Explorer, I uploaded both ntuser.dat logs into a combined cleaned hive and saved the clean hive onto a clean hive folder. 

![5) SYSTEM CurrentControlSet Control ComputerName ComputerName](https://github.com/user-attachments/assets/e8308156-9a95-42df-abe6-3b1a6eeced65)

<br />
<br />  
Using gkape to target the C:\ drive for ym widows 10 vm, destination to a Cases folder, using the find function to look for registry and selecting all relevant registry hives, then executing. 

![6) SYSTEM CurrentControlSet Control TimeZoneInformation](https://github.com/user-attachments/assets/ad420ea8-6505-4282-b006-55415f6adfdc)

<br />
<br />
Showcasing the Windows System32 config logs extracted. 

![7) SYSTEM CurrentControlSet Services Tcpip Parameters Interfaces  GUID](https://github.com/user-attachments/assets/6496ffaf-6234-4f85-9147-ea141b7a018a)

<br />
<br />  
Showcasing the NTUSER.DAT logs extracted. 

![8) SAM SAM Domains Account Users](https://github.com/user-attachments/assets/1f79596c-2f5a-44f9-ad67-9a503c5d2d06)

<br />
<br />
Showcasing the UsrClass logs extracted. 

![9) SAM SAM Domains Builtin Aliases](https://github.com/user-attachments/assets/8e9ac9c5-97c9-4d5d-a8f0-cf3b557b88f5)

<br />
<br />
In Registry Explorer, I uploaded both ntuser.dat logs into a combined cleaned hive and saved the clean hive onto a clean hive folder. 

![9) SOFTWARE Microsoft Windows CurrentVersion Authentication LogonUI](https://github.com/user-attachments/assets/8a288274-9850-4fa4-bcea-4d5bbfa9f3f8)

<br />
<br />  
