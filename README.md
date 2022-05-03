# tensileTester
Collection of files related to 431 Systems Analysis + Design's tensile strength project.

The system will perform tensile material strength tests for the UAlbany Chemistry Dept.

The project is based off this paper : 
Fabrication of an Economical Arduino-Based Uniaxial Tensile Tester
Julien H. Arrizabalaga, Aaron D. Simmons, and Matthias U. Nollert
Journal of Chemical Education 2017 94 (4), 530-533
DOI: 10.1021/acs.jchemed.6b00639

All changes made to the physical design are included in the slideshow under Presentations and Reports and the required software is under Source-Code.

System Parts:
Part 1:
Pull Pressure Force S-type Load Cell Sensor with Cable (10 KG), $36.99, <https://www.amazon.com/dp/B01F6IOW4K?ref=ppx_yo2ov_dt_b_product_details&th=1>
Part 2:
Clamps
Part 3:
Motor


Standalone Matlab App can be used with any .csv file format with CM and Newtons as units listed as so:
6CM , 0N
6.5CM , 0.5N
etc...
It also comes with its own readme file for troubleshooting purposes.

Load Slope code adapted from Professor Muckells example. 
