# Nextstrain-build-for-Grapevine-red-blotch-virus
This repository is for analysis, evolution and spread of Grapevine red blotch virus (GRBaV) using Nextstrain resources
## Install Nextstrain and run the build using the following commands. 
- nextstrain shell .  (This helps you enter the runtime) if you installed Nextstrain with docker runtime
- nextstrain build --cpus 1 .  (This runs the automated build with snake)
- view the results with: nextstrain view auspice/    

**Note:** if you have made changes and want to rerun Nextstrain again, delete the previous generated results with: 
- rm -rf results/ auspice/
### Acknowledgement 
Nextstrain was developed by the [Nextstrain core team](https://nextstrain.org/team), if you use this repository dont for get to give them credit, they surely did an amazing work to create an open source code for Nextstrain. 


### References 
- Hadfield, James, Colin Megill, Sidney M. Bell, John Huddleston, Barney Potter, Charlton Callender, Pavel Sagulenko, Trevor Bedford, and Richard A. Neher. "Nextstrain: real-time tracking of pathogen evolution." Bioinformatics 34, no. 23 (2018): 4121-4123. 
- https://nextstrain.org/
