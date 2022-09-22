## How to update windows from Powershell

### 1. Install powershell module 
<code>Install-Module PSWindowsUpdate</code>

### 2. To see available updates 
<code>Get-WindowsUpdate </code>

### 3. To install updates
* <code>Install-WindowsUpdate</code>

#### Or

* <code>Get-WindowsUpdate -AcceptAll -Install -AutoReboot</code>