# Windows Forensic Artifacts: User and System

<h2>Description</h2>
In this Digital Forensics task, I used registry explorer to enumerate clean system and user hives to enumerate different artifacts like user login, system id, and computer name.  

<h2>Languages and Utilities Used</h2>

- <b>Registry Explorer</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b> 

<br />
<br />
Loading the clean software hive into registry explorer. 

![1) load clean system logs into registry explorer](https://github.com/user-attachments/assets/4566b3ae-4c34-4d8f-99de-80a6d5d08228)

<br />
<br />
Going to SOFTWARE\Microsoft\Windows NT\CurrentVersion enumerates keys like SystemRoot, CurrentBuild, EditionID, InstallDate, and RegisteredOwnder to name a few. 

![2) rootmicrosoftwindowsntcurrentversion](https://github.com/user-attachments/assets/e8dffe2c-2526-43a8-abdc-b9a79804020e)

<br />
<br />  
Using Epoch Converter to convert the install date to human-readable date shows the system was isntalled on Thursday December 5th 3:32PM PST. 

![3) epoch converter](https://github.com/user-attachments/assets/d1730f8b-61c7-44ae-ac06-b8f86753b575)

<br />
<br />
Loading the clean SYSTEM hive and going to SYSTEM\CurrentControlSet\Control\Session Manager\Environment enumerates variables like ComSpec, Path, Processor Architecture, and Processor Identifier. 

![4) SYSTEMCurrentControlSetControlSetControlSession ManagerEnvironment](https://github.com/user-attachments/assets/f7f310ae-0f69-43a9-a82d-1b1cf291a711)

<br />
<br />
Going to SYSTEM\CurrentControlSet\Control\ComputerName\ComputerName will show the computer name of the computer. 

![5) SYSTEM CurrentControlSet Control ComputerName ComputerName](https://github.com/user-attachments/assets/e8308156-9a95-42df-abe6-3b1a6eeced65)

<br />
<br />  
Going to SYSTEM\CurrentControlSet\Control\TimeZoneInformation will show the time zone of the computer. 

![6) SYSTEM CurrentControlSet Control TimeZoneInformation](https://github.com/user-attachments/assets/ad420ea8-6505-4282-b006-55415f6adfdc)

<br />
<br />
Going to SYSTEM\CurrentControlSet\Services\Tcpip\PArameters\Interfaces\<GUID> will show the DhcpIPAddress, DhcpNameServer, and DhcpDefaultGateway. 

![7) SYSTEM CurrentControlSet Services Tcpip Parameters Interfaces  GUID](https://github.com/user-attachments/assets/6496ffaf-6234-4f85-9147-ea141b7a018a)

<br />
<br />  
Loading the SAM hive into registry explorer and going to SAM\SAM\Domains\Accounts\Users will show user information such as userID, groups, invalid login count, etc.  

![8) SAM SAM Domains Account Users](https://github.com/user-attachments/assets/1f79596c-2f5a-44f9-ad67-9a503c5d2d06)

<br />
<br />
Going to SAM\SAM\Domains\Builtin\Aliases will show all group names, comments about them, and users within each group. 

![9) SAM SAM Domains Builtin Aliases](https://github.com/user-attachments/assets/8e9ac9c5-97c9-4d5d-a8f0-cf3b557b88f5)

<br />
<br />
Opening the SOFTWARE hive again and going to SOFTWARE\Microsoft\Windows\CurrentVersion\Authentication\LogonUI will show information like last logged on user, user SID, and provider. 

![9) SOFTWARE Microsoft Windows CurrentVersion Authentication LogonUI](https://github.com/user-attachments/assets/8a288274-9850-4fa4-bcea-4d5bbfa9f3f8)

<br />
<br />  
