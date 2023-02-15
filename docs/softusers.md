#System-wide installed software

##Binaries, libraries and runtimes

Programs and associated system-wide elements that users can run on the cluster as computing tasks are installed on shared locations and configured to be accessible by SLURM. 

Most of these software elements have been built from sources, either using regular procedures or relying on automated building and dependencies management systems (EasyBuild and Spack). 

Recent common compilers and development libraries are available (gnu12, OpenMPI4, MPICH).

ALso, recent versions of Python, R, Perl, Java and other runtimes and development tools are avalible. However, users that require a high level of version and optional packages for some development environments (usually with R, Python and others) specificity, are encouraged to deploy and use their own tools and packages at user level (using some conda flavour or Singularity containers)

##Environment Modules

The lmod implementation of Environment Modules is available. Users are instructed and strongly advised to use this system for submitting computing tasks on the cluster.
