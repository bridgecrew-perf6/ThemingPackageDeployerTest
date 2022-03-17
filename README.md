# ThemingPackageDeployerTest

Test this in an environment where you don't have the theming module installed and confirm that the "Power Apps component framework for canvas apps" setting is "Off" in the environment

![image](https://user-images.githubusercontent.com/4499296/158817299-e72bd7b3-ce2e-49af-9bd4-6a67cb3e7a33.png)

Download release zip file

Extract contents

authenticate to the Dataverse environment using pac

Run the following command

pac package deploy --package ThemingPackageDeployerTest.dll

Confirm that the "Power Apps component framework for canvas apps" setting is "On" in the environment, theming solution is imported, and test that the theme editor app succesfully loads the PCF component (color picker)

![image](https://user-images.githubusercontent.com/4499296/158817638-a49f64da-54eb-4b8e-bc06-095214daad13.png)
