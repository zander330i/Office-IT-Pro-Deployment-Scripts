﻿#**Generate Office Deployment Tool Configuration XML**

This PowerShell Function generate the Office Deployment Tool Configuration XML based on the current state of the workstation and the parameters specified for the Function

###**Examples**

1. Open a PowerShell console.

		From the Run dialog type PowerShell 
		
2. Change directory to the location where the PowerShell Script is saved.

		Example: cd C:\PowerShellScripts
		
2. Run the Script. With no parameters specified the script will return the locally installed Office Version.

		Type . .\Generate-ODTConfigurationXML.ps1
		Press Enter and then if Microsoft Office is installed locally it should display. 
		By including the additional period before the relative script path you are 'Dot-Sourcing' 
		the PowerShell function in the script into your PowerShell session which will allow you to 
		run the function from the console.
	
	

	
