# Invoke-WMI-Information
Straight forward script for WMI information gathering (local or remote)

Be carefull using the -remote Commands with username and password parameter, everything is logged in Powershellv5 so everyone on your system can view the Credentials.

1) Invoke-WMI-Information -local $true

2) Invoke-WMI-Information -remote $true -Computername Domain\SomeComputername

3) Invoke-WMI-Information -remote $true -Computername Domain\SomeComputername -Username Domain\User -Password password
