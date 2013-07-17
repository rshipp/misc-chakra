Miscellaneous scripts for use with Chakra Linux.

#Descriptions:

##ccrdups
Finds packages that exist with the same name in both the CCR and the main repos, and prints detailed, colorized results. This script is *slow*.

##makeccrlist
Makes a list of installed packages not in the main repos.

##makepackagelist
Makes a list of installed packages that exist in the main repos.

##pacman-size-list
Prints a list of installed packages in the format `XYZ.ABCKiB	packagename`. This script was meant to be piped through sort, like `pacman-size-list | sort -n`, in order to find the packages taking up the most space on the system. It is rather slow.

##pacstats
Prints a list of installed packages by repo, and some simple statistics.

##update-bundle-links and remove-bundle-links
The first creates links for bundles based on name (eg, firefox-11.0-1 becomes firefox); the second removes all files created by the first. These scripts were created to get over the inconvenience of having all the bundle shortcuts that are pinned to a taskbar break every time the bundle is updated, among other things.
