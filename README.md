# resolvers
List of fresh resolvers, updated daily at 10am

The appoach for getting resolvers here is quite different, instead of validating public resources (which almost always have hazards or spoofed records), we analyze DNS entries from already analyzed lists. Making it hard to get bad DNS's.


# Lists used

https://raw.githubusercontent.com/proabiral/Fresh-Resolvers/master/resolvers.txt

https://raw.githubusercontent.com/BonJarber/fresh-resolvers/main/resolvers.txt

https://raw.githubusercontent.com/janmasarik/resolvers/master/resolvers.txt

# Methodology

1 - Grab lists from above gits\
2 - Run [dnsvalidator](https://github.com/vortexau/dnsvalidator) on top of those lists\
3 - Get results 
