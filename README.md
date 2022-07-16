# What is "amdl"
This is a script to download and search installation scripts for the apps and AppImages available on [AM Application Manager](https://github.com/ivan-hc/AM-application-manager) and born from the main script itself to be used as a standalone script wherever you want.
The reason behind the creation of this script is to easily download on your Desktop the installation scripts from the main repository, the way you can check, edit and install them the way you prefer and without having to install "AM" to manage them.

# Setup
     wget https://raw.githubusercontent.com/ivan-hc/amdl/main/amdl && chmod a+x ./amdl

# Usage
     "amdl [option]"   
  	 "amdl [option] [ARGUMENT]"
 	
### Options
    
  `-d`, `download`
  USAGE: "]amdl -d $PROGRAM`"
  DESCRIPTION: Download an installation script from the "AM" repository to your desktop without installing it. This option can download scripts from both "programs" (stable scripts on the repository) and "testing" (where scripts are
  unstable and not complete at all), for your architecture.
 
  `-h`, `help`
  USAGE: "`amdl -h`"
  DESCRIPTION: Prints this message. 
  
  `-q`, `query`
  USAGE: "`amdl -q $KEYWORD`"
  DESCRIPTION: Use one or more keywords to search for in the list of available applications.

-------------------------------------------------------
# This script is part of ["AM" Application Manager](https://github.com/ivan-hc/AM-application-manager).
-------------------------------------------------------
