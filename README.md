Miscelaneous scripts for use with Chakra Linux.

##Descriptions:

#ccrdups
Finds packages that exist with the same name in both the CCR and the main repos, and prints detailed, colorized results. This script is *slow*.

#makeccrlist
Makes a list of installed packages not in the main repos.

#makepackagelist
Makes a list of installed packages that exist in the main repos.

#pacman-size-list
Prints a list of installed packages in the format `XYZ.ABCKiB	packagename`. This script was meant to be piped through sort, like `pacman-size-list | sort -n`, in order to find the packages taking up the most space on the system. It is rather slow. 

