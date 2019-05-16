# ubuntu_aci
Ubuntu base images for ICS ACI singularity recipe  
List of available packages for Ubuntu:  
- 16.04: https://packages.ubuntu.com/xenial/  
- 18.04: https://packages.ubuntu.com/bionic/

Note: Ubuntu 18.04 image may not work on ACI clusters due to old kernel version.  
(Related issue: https://github.com/sylabs/singularity/issues/1275)  

Recipes here may include unnecessary packages for certain software installation. Size of the container is ~700 MB

More packages will be added in the future.

2019/5/14  
Python2.7 package and symlink are added (python = python2.7)

2019/5/16  
OpenGL support is added (libglu1-mesa-dev, freeglut3-dev, and mesa-common-dev)
