# Skin Effect Graph

This program takes the variables of initial current density, skin depth and wire thickness and applies them to the skin effect formula: 

![](https://user-images.githubusercontent.com/15330699/41508703-bc60c418-7240-11e8-8f61-eaf9d8c336bf.png)

The program uses a depth range from 0 to half the wire thickness, in 100 incremements, to form a graph that looks like this: 

![image](https://user-images.githubusercontent.com/15330699/41508720-f7fda450-7240-11e8-9a48-6fcfd6084c93.png)

The purpose of the program is to demonstate the exponential decay of current density when an alternating current is passed though a conductor. 
When the depth inside the conductor equals the skin depth, the current density is equal to 1/e of that of the surface density (Approximately 37%). 
This is shown by the red line on the graph.

To aid with analysis, two lines are included to demonstate a minimal and neglible value. The green line demonstrates the minimal value which is defined
as the depth at which the current density is 1% of the initial current density. The blue line demonstrated the negligible value which is defined as
the depth at which the current density is 0.1% of the inital current density.