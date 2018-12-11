# SFDX Unlocked Package Structure

While migrating from happy soup to SFDX unlock packages, it is exteamly important to have right repo structure for each of the unlock packages. 

## Description of Files and Directories

#### standard sfdx package director [packagename/main/default]
Contains actual SFDX compatible metadata components

#### folder : config
Contains project-scratch-def.json file which will have scratch org configs

#### folder : data
Contains json of sample data to be loaded in scratch orgs when doing unit testing in scratch org

#### folder : docs
Contains any documents related to package like instruction guides, etc.

#### folder : scripts 
Contains reusable shell/cmd scripts

#### folder : .ci 
This is not part of above repo yet but we will have .yml and server.key.enc files once CI is setup

#### file : README.md
Contains Introduction, package specific installation steps, Post installation steps, etc.

#### file : .gitignore
Contains list of files or directories to be ignored while push/pull

#### file : .forceignore
Contains list files or directories below to ignore them when running force:source:push, force:source:pull, and force:source:status

#### file : package.xml
Contains list of metadata components which are part of the package      
## Dev, Build and Test


## Resources

## Issues


