# SAL 603 Final Project

This branch contains all of the code specifically for the Final Project in SAL 603 - Intro to Python for Sports Analytics. 

This project attempts to see if velocity variations in a pitcher's fastball affect its command in an attempt to answer how much truth is put into the concept of "caring" how hard someone throws ball four. Is creating a philosophy on this issue worth it, or is there no significant command drop-off for higher-velo pitches?

Each pitcher-season from the 2022-2024 season will be included. Three groups of command metrics (InZone%, Shadow%, and Waste%) will be calculated for each pitcher: one for all fastballs within 1.5 MPH of a pitcher's average, one for fastballs whose velocity is at least 1.5 MPH slower than average, and one for all fastballs whose velocity is at least 1.5 MPH higher than average.

A significance test will be run to compare each outlier group to the average group and see whether the mean InZone%, Shadow%, and Waste% for the average and outliers are statistically different.

The video presentation of this project can be found here: https://youtu.be/NQE4TKyylag
