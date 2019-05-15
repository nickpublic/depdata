# depdata
This repository stores the dependency data of 105 Python projects.

We public our collected data, aiming to provide the benchmark for dependency-based architecture analyses for dynamic languages.

## 1. Projects' information
**python-projects-105.csv** lists the basic information of the projects that we investigated.

## 2. The dependencies extracted from source code for each project
One folder corresponds to one project, and the folder's name is same with the project's name.

Under each folder,

1)**$projectname$_dep_explicit.json** 

It stores the file-level dependencies extracted by Understand tool, that we call **explicit dependencies**.

2)**$projectname$_dep_P$i$.json** (i=1,2,...,10) 

It stores the file-level dependencies extracted by our approach, that we call **possible dependencies**.

In particular,  $projectname$_dep_P11.json file stores the $P_{i>10}$ possible dependencies. 

