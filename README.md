Ransomware attacks are among the most disruptive cyber threats, causing significant financial losses while impacting productivity, accessibility, and reputation. Despite their end goals (encryption/locking), ransomware are often designed to evade detection by executing a series of pre-attack API calls, namely “paranoia” activities, for determining a suitable execution environment. 

The presented dataset was extracted from recent prominent ransomware families to build a better understanding about their behavioral characteristics through the analysis of their paranoia activities represented by their pre-attack API function calls. Hence, it can be used for effective characterization and classification of this threat (e.g., ransomware)


The following evasion API calls represent the order which follows the dataset’s columns:
1-CreateToolhelp32Snapshot
2-DeviceIoControl
3-EnumWindows
4-GetAdaptersAddresses
5-GetComputerNameA
6-GetComputerNameW
7-GetDiskFreeSpaceExW
8-GetSystemInfo
9-GetSystemMetrics
10-GetUserNameA
11-GetUserNameW
12-LdrGetProcedureAddress
13-NtClose
14-NtCreateFile
15-NtEnumerateKey
16-NtOpenDirectoryObject
17-NtOpenKey
18-NtQuerySystemInformation
19-NtQueryValueKey
20-ReadProcessMemory
21-RegCloseKey
22-SetWindowsHookExA
23-SetWindowsHookExW.


A machine learning model (Random Forest) is displayed to test this dataset.
