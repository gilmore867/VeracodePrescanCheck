This is a simple PowerShell script to determine the status of an existing policy scan. The script may be adapted to delete scans on the Veracode platform based on a status message.

Download the PrescanCheck.ps1 file. Edit the PrescanCheck.ps1 file with the following requirements:

Give the exact name of the profile application name for $appname. Example $appname = "Test".

The PowerShell script requires access to the Veracode Java API jar file. The script uses the name "VeracodeJavaAPI.jar" filename. This file can be found at https://repo1.maven.org/maven2/com/veracode/vosp/api/wrappers/vosp-api-wrappers-java/
The -vid and -vkey variables reference the Veracode API ID and Veracode API Key from the Veracode Platform.

-vid $env:vid Your Veracode API ID from the Veracode Platform

-vkey $env:vkey Your Veracode API Secret Key from the Veracode Platform
