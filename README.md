# PFC

This is my way of sharing some of the work developed during the execution of the final degree project in Architecture (Proyecto Final de Carrera) necessary to graduate and become and Architect at the ETSA University of Seville (Escuela Técnica Superior de Arquitectura de Sevilla, Spain).


## INDEX

###### 1. Introduction
###### 2. Construction system
###### 3. 3D printable components and parametric design
###### + Notes


##  1. Introduction

The project aims to develop an advanced architecture proposal which implies many complex issues from building concept and functional program to urban planning, construction, structure and engineering design.

Although it is not required, I decided to carry out the fabrication of the modular construction system in which the project is based through 3D printed scale components. Because of my personal interest in digital fabrication and 3D printing, I assumed this elective part of my project as an additional path of learning and research.

It was also considered that this branch of the project should be based on the open source basis. This would allow other people interested in this line of research to implement further developments based on these foundations. Or maybe anyone can just simply take advantage of the work and print the scale construction system for testing or playing. In my opinion, this is a cool way of giving at least a bit of *'real'* use to the large workload required for the realization of a project of this nature.

Please do not hesitate to [contact me](mailto:angelpontesgarcia@gmail.com "angelpontesgarcia@gmail.com") for any issue.

More info about the project in [pfc.angelpontes.net](http://pfc.angelpontes.net "pfc.angelpontes.net").

<center><a href="http://pfc.angelpontes.net/" title="pfc.angelpontes.net"><img src="/IMAGES/LOGO.png" alt="LOGO" title="pfc.angelpontes.net"></a></center>


##  2. Construction system

It is a non-conventional but quite simple construction system based on the 2D fractal geometry of the equilateral triangle and the resultant hexagon. 

A kind of hexagonal *'umbrella'* is the basic modulus. It is composed by a central column with radial beams frameworks. All the components are connected by joints. The main construction material is steel and because of the modularity all the pieces would be prefabricated.

For the purpose of 3D printing the system has been simplified. The resultant scale model is just composed of the general parts of the structure (column, beams, floors, roofs) removing the unnecessary minor details.


##  3. 3D printable components and parametric design

It is possible to print the default components (v1) but the system has also been designed with parametric settings. 

> [Check here the Grasshopper definition](/PARAMETRIC DESIGN/ "GH Sheet")

Opening the GH sheet with [Grasshopper for Rhino](http://www.grasshopper3d.com/ "Grasshopper for Rhino") allows to change the variable parameters in which the system is based to set up new possible configurations.

Once all the parameters have been modified the file GH produce the 2D and 3D components required for digital fabrication. While the 2D hexagonal grid could be cut by laser, the 3D components have to be printed.

Lunchbox plugin for GH should be installed to bake the files with the default variables.

Weaver Bird plugin for GH have to be installed to run the definition.

The defined model unit is millimeter.

This is my first printing test:

<center><a href="http://blog.angelpontes.net/post/20131126-3d-print-colaboratorio" title="blog.angelpontes.net"><img src="/IMAGES/3D-PRINT-TEST-v1.jpg" alt="Test v1" title="blog.angelpontes.net"></a></center>

##  + Notes

- ***Looking for a platform for open source design processes. Why GitHub?***

Because it is **open**, straightforward and effective in promoting collaborative works. Although it is a platform optimized for code and programming, why not be used to carry out open source projects in other fields of work?

***THINK > DESIGN > MAKE > SHARE***

For the purpose of the present project GitHub provides everything needed: file spreading and storage platform, version control, 3D model viewer for STL format and plain board for documentation. This could be an interesting way to implement work tasks in fields such as engineering, architecture and design, providing a useful and easily accessible tool for projects based on open source knowledge. Beyond simply habitual sharing via Dropbox, Google Drive or through cloud storage provided by proprietary software companies, highly visible online platforms like GitHub may be a demanded alternative.

Even though such procedures and open work trends for *'tangible stuff'* are just beginning in the cloud, at the present time there are already some specific tools under development (such as [Sunglass](https://sunglass.io/ "Sunglass.io") or [Grabcad](http://grabcad.com/ "Grabcad.com")) and there were many others that can also be used with similar intentions (such as [Thingiverse](http://www.thingiverse.com/ "Thingiverse.com"). However, in this case I have chosen GitHub for its huge potential and high accessibility, because it is not necessary to be signed up to visualize repositories and in case of being interested in continue developing an existing work, it is fast and intuitive to generate new growth *'branches'* from the original project.

***

### LICENSE

*2014*

*Ángel Pontes*

<img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" title="CC BY-NC-SA 4.0">

Some rights reserved. This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/ "CC BY-NC-SA 4.0 International License").