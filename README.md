# What is "amdl"
This is a script to download and search installation scripts for the apps and AppImages available on [AM Application Manager](https://github.com/ivan-hc/AM-application-manager) and born from the main script itself to be used as a standalone script wherever you want.
The reason behind the creation of this script is to easily download on your Desktop the installation scripts from the main repository, the way you can check, edit and install them the way you prefer and without having to install "AM" to manage them.

# Installation
Download the script wherever you want and made it executable:

     wget https://raw.githubusercontent.com/ivan-hc/amdl/main/amdl && chmod a+x ./amdl
if you prefer, you can push it into a `$PATH`, in this way you have not to add `./` each time you want to use it, for example:

    sudo mv ./amdl /usr/local/bin/amdl

# Usage
     "amdl [option]"   
  	 "amdl [option] [ARGUMENT]"
 	
### Options
    
  `-d`, `download`
  USAGE: "`amdl -d $PROGRAM`"
  DESCRIPTION: Download an installation script from the "AM" repository to your desktop without installing it. This option can download scripts from both "programs" ([stable scripts on the repository](https://github.com/ivan-hc/AM-Application-Manager/tree/main/programs)) and "testing" ([where scripts are
  unstable and not complete at all](https://github.com/ivan-hc/AM-Application-Manager/tree/main/testing)), for your architecture.
 
  `-h`, `help`
  USAGE: "`amdl -h`"
  DESCRIPTION: Prints this message. 
  
  `-q`, `query`
  USAGE: "`amdl -q $KEYWORD`"
  DESCRIPTION: Use one or more keywords to search for in the list of available applications.

-------------------------------------------------------
# This script is part of ["AM" Application Manager](https://github.com/ivan-hc/AM-application-manager).
-------------------------------------------------------
