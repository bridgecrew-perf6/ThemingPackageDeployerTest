# ThemingPackageDeployerTest

Test this in an environment where you don't have the theming module installed and confirm that the "Power Apps component framework for canvas apps" setting is "Off" in the environment

Download release zip file

Extract contents

authenticate to the Dataverse environment using pac

Run the following command

pac package deploy --package ThemingPackageDeployerTest.dll

Confirm that the "Power Apps component framework for canvas apps" setting is "On" in the environment, theming solution is imported, and test that the theme editor app succesfully loads the PCF component 