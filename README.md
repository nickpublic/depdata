# depdata
This repository stores the data of 105 Python projects.

We publish our collected data, aiming to provide a benchmark for exploring architecture impact of possible dependencies in Python.

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

## 3. The revision history collected from git for each project

Under each project folder,
**$projectname$_gitlog.txt** and **$projectname$_history.csv** store the revision history collected from git.
