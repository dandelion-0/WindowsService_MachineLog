# WindowsService_MachineLog
- Generate machine logs when the Machine Starts, Shutsdown, and at regular intervals of 30 minutes,
- also When Windows_Service is  explicitly started or terminated.
- Windows Service is programmatically scheduled to run in the Background after installation.
- Logs will be stored in .txt file with current date.

# Steps to Install Service on Machine
//this is for X64 
cd C:\Windows\Microsoft.NET\Framework64\v4.0.30319
// Install cmd
InstallUtil.exe <..\SnowDrop_WindowsService_MachineLog\SnowDrop\bin\x64\Debug\SnowDrop.exe>
// Uninstall cmd
InstallUtil.exe -u <..\SnowDrop_WindowsService_MachineLog\SnowDrop\bin\x64\Debug\SnowDrop.exe>
