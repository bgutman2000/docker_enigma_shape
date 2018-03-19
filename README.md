# ENIGMA Shape Analysis (Dockerized)
A dockerized version of the Medial Demons Shape Analysis tool from the Illinois Institute of Technology (IIT). This tool is also used in the ENIGMA Consortium shape analysis projects (http://enigma.ini.usc.edu/ongoing/enigma-shape-analysis/). 

After pulling the image you need to fulfill these conditions:
 - Have three separated folders:
	 - A first folder for the *groupfile.csv* file (where the database description is contained)
	 - A second folder containing the subjects after a *recon-all* processing with FreeSurfer
	 - A third folder where the output of the shape processing is going to be stored.

You can also pull the image directly from Dockerhub
  - [https://hub.docker.com/r/sssilvar/eshape_fs/](https://hub.docker.com/r/sssilvar/eshape_fs/)
