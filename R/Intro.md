# Quick Introduction and R *Cheat Sheet*

***R*** is a language used for mathematical and primarily statistical analysis of data sets.

## Installing Packages
*R* allows for installation of collections of functions and data sets already 
written by others, also known as *packages*.

***To Install:*** Run or execute ```install.packages("Package Name")```. 
Example: ```install.packages("ggplot2")``` to install ggplot2.

Packages are not automatically imported. You must import a package before you use it.

***To Use a Package*** Run or execute ```library("Package Name")```. 
Example: ```library("ggplot2")``` to import ggplot2 to your project.

## Variables

To assign a variable in *R*, we use ```<-``` such as ```a <- b```, which assigns the value `b` to variable `a`. If a variable `a` already exists, it will overwrite the previous value and it will be lost. If there is no variable `a`, one will be created and assigned the value `b`.

## Alternatives to installing R on Your Computer
If you are unable to install *R* to your local computer there are some alternatives. The easiest is [R Studio Cloud](https://rstudio.cloud/plan), which allows for free cloud use and an R Studio IDE to work directly from your browser. For most intro courses, R Studio Cloud's free plan should be sufficient. 

The other option is [repl.it](Repl.it) supports multiple language including *R*. You may create an *R* codespace and do your work there. This tool is not advised for first time coders because it requires some understanding of terminal commands and 
does not contain a graphical user interface like *R Studio*