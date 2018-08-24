**How to use NEXTA to visualize the trajectory**

NGSIM data set

Version 1: Prepared by Xuesong Zhou and Pan Shang

# About **Next Generation Simulation (NGSIM)**

[https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm)



| Category | File | Remark |
| --- | --- | --- |
| Main program | NEXTA\_4\_Trajectory.exe | Open source NEXTA visualization tool |
| Input | trajectories-0400-0415 | Sample file from NGSIM  |
| Input | test\_one\_linetest\_two\_lines | Sample file from Pan Shang, for one vehicle&#39;s trajectory |
| Output | Trajectory.csv | Export to more user readable format |



**Format**

Each line is a record of trajectory

Please use space or comma to separate fields.

| No | Field Name | Example 1 | Example 2 | Unit | remark |
| --- | --- | --- | --- | --- | --- |
| 1 | Vehicle\_ID | 1 | 1 |   |   |
| 2 | Frame\_ID | 12 | 13 | 0.1 seconds |
| 3 | Total\_Frames | 884 | 884 | 0.1 seconds |
| 4 | Global\_Time | 1113433136100 | 1113433136200 | text | you can put any value |
| 5 | Local\_X | 16.884 | 16.938 |   | not used |
| 6 | Local\_Y | 48.213 | 49.463 | feet |   |
| 7 | Global\_X | 6042842.116 | 6042842.012 |   | not used |
| 8 | Global\_Y | 2133117.662 | 2133118.909 |   | not used |
| 9 | Vehicle\_Length | 14.3 | 14.3 | feet |   |
| 10 | Vehicle\_Width | 6.4 | 6.4 | feet |   |
| 11 | Vehicle\_Class | 2 | 2 |   | pax or truck |
| 12 | Vehicle\_Velocity | 12.5 | 12.5 |   |   |
| 13 | Vehicle\_Acceleration | 0 | 0 |   |   |
| 14 | Lane\_Identification | 2 | 2 |   | very important |
| 15 | Preceding\_Vehicle | 0 | 0 |   |   |
| 16 | Following\_Vehicle | 0 | 0 |   |   |
| 17 | Spacing | 0 | 0 |   |   |
| 18 | Headway | 0 | 0 |   |   |





**Steps**

Step 1: Open NEXTA.

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/1.PNG)

Step 2: Select menu Tools-NGSIM Tools- **Active Space-Time View, and then load** trajectory file for Visualizing trajectory data

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/2.PNG)

Step 3:

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/3.PNG)



Main functions

1. **Display trajectories for each lane.**

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/4.PNG)

In the menu Tools-NASIM Tools:

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/4.PNG)

You can choose each lane number to see the trajectory;

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/5.PNG)



1. You can show Vehicle ID, and you can use mouse wheeler to zoom in and zoom out the display in the certain portion.

1. You can use the mouse to click and draw a line in the space-time plate, and the NeXTA will automatically calculate the flow, density, and speed values across the line

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/6.PNG)

1. You can show cumulative flow count and density

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/7.PNG)

You can show the space-time Density Contour

![Image](https://github.com/xzhou99/NeXTA_4_Trajectory_Visualization/blob/master/8.PNG)
