### NEEO_CustomDrivers

## Whats this?
This repository hosts all the Core-drivers that run in metadriver.
It allows dynamic update of CoreLibrary drivers in .meta.
#Please note, this repository is NOT for personal drivers (though we encourage you to always SHARE ypur development).
Personal drivers need to go into the directory for private drivers: /steady/neeo-custom/UserLibrary.

## How?
# By .meta
.Meta looks for CustomDriver.manifest, and loads/activates them if selected by the user
# Contribute
Just pull this repository, create a new branch on your own repository, then create a pull request for NEEO_CustomDrivers.
Please use the predefined directories; if there are no objects to populate a directory, leave it empty. 

# ALWAYS!! Create/update the appropriate fields in file CustomDrivers.manifest with name of driver, and fields like Author etc.

## What happens when I have created a new driver and made the necessary changes?
Create a pull-request so we can integrate your code into the Core-Library of .meta.
The driver and all resources belonging to it, will then be reviewed and once okay, the Pull-requet will be honored.
In essence, github will pick up all objects that you supplied and place them into the formal CustomDrivers repository.
From that moment on, .meta will pick up and show your driver when browsing "CoreLibrary".
## Updates
If you have any change, just follow the same update-process, creating a pull-request to update the Library.
Once the pull-request is honored, you changed driver will be available in .meta CoreLibrary.

