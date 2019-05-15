# depdata
This repository stores the dependency data of 105 Python projects.

##1. Projects' information
**python-projects-105.csv** lists the basic information of the projects that we investigated.

##2. The dependencies extracted from source code for each project.
One folder corresonds to one project, and the folder's name is same with the project's name.

Under each folder,

1)**$project name$_dep_explicit.json** 

It stores the file-level dependencies extracted by Understand tool, that we call *explicit dependencies*.

2)**$project name$_dep_P$i$.json** (i=1,2,...,10) 

It stores the file-level dependencies extracted by our approach, that we call *possible dependencies*.

In particular,  $project name$_dep_P11.json file stores the $P_{i>10}$ possible dependencies. 

