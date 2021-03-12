# Abaqus_Scripting
This is a repository of codes I have developed to extract data from Abaqus .odb files. Not planning to develop anything, but if someone finds these codes useful feel free to use them. I will try to provide context with each code so it can be modified.

## Abaqus Python Resources:

### General Resources: 
* [Abaqus Scripting User's Manual](http://130.149.89.49:2080/v6.11/pdf_books/SCRIPT_USER.pdf) - 6.11 current can be found in local documentation. 
* [Abaqus Scripting Refrence](http://130.149.89.49:2080/v6.13/books/ker/default.htm) - Similar to the Abaqus keyword  manual
* [Abapy](https://abapy.readthedocs.io/en/latest/) - Abaqus Python “AbaPy” contains tools to build, postprocess and plot automatic finite element simulations using Abaqus. This has a *Ton* of resources but is not up to date (all based in python 2.7). Seriously a ton of information, but somewhat outdated. Source code is avaliabe [here](https://github.com/lcharleux/abapy)
* [Tips from Simulia to get started](https://info.simuleon.com/blog/7-tips-when-you-are-getting-started-with-abaqus-python-scripting)
* [A Simulia Tutorial](https://info.simuleon.com/abaqus-tutorial-setting-up-a-python-script) - Basic scripting to modify input files 

### Extracting .odb to .vtk for Paraview:
* [Paraview visualization of Abaqus output](https://www.sciencedirect.com/science/article/pii/S0098300416306926) - Paper published in 2017 on converting formats. The source code can be found [here.](.https://github.com/Liujie-SYSU/odb2vtk) For our purposes the code would need to be modfied somewhat, but it works as of 2021/03/11
* [Post-Processing with Abapy](https://abapy.readthedocs.io/en/latest/postproc.html) - Abapy outline some stuff to convert to .vtk that could be helpful in the future.

