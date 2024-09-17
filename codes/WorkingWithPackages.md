install.packages("package_name")

#Example
install.packages("ggplot2")  # Installs the ggplot2 package for data visualization
Notes:
#Use quotes around the package name.
#Ensure you have an internet connection for installation.

*Loading Packages*
After installation, load the package into your R session using library().

library(package_name)
library(ggplot2)  # Loads the ggplot2 package for use

*Updating Packages*
#To keep your packages up to date, periodically update them.

update.packages()

*Removing Packages*
#If you no longer need a package, you can uninstall it.

remove.packages("ggplot2")  # Uninstalls the ggplot2 package

*Finding Packages*
#To find packages, use the search() function or browse online repositories.


*Exploring Package Contents*
#After loading a package, explore its functions and datasets.

?ggplot2  # Opens documentation for ggplot2
help(package = "ggplot2")  # Lists functions and datasets in ggplot2


