# Challenge 9: Surfs_Up Analysis

## Overview of Surfs_Up Analysis
This analysis highlights the temperature details for the month of June and Decemeber in Hawaii. The conclusions will assist in determining whether an ice cream shop business is sustainable year-round. 

The Jupyter notebook used for the analysis: [SurfsUp_Challenge.ipynb](https://github.com/Hala-INTJ/Surfs_Up/blob/main/SurfsUp_Challenge.ipynb)
## Surfs_Up Analysis Results

Three significant differences:
- The <b>mean</b> is 4 degrees cooler in December than in June.
- The <b>minimum</b> is 8 degrees cooler in December than June.
- In June, 75% of the days are <b>above</b> 73 degrees. In December, 75% of the days are <b>below</b> 74 degrees. 

| June Temperatures Summary Statistics | December Temperatures Summary Statistics |
| :---: | :---: |
| ![](https://github.com/Hala-INTJ/Surfs_Up/blob/main/June%20Temps.png) | ![](https://github.com/Hala-INTJ/Surfs_Up/blob/main/December%20Temps.png) |
## Surfs_Up Analysis Summary

Based on the above temperature data analysis, one may conclude that business would be slower in December than in June. To gain more insight, the same approach was completed using precipitation. This analysis shows there's a wide discrepency between the maximum precipitation and both the median and mean. 

| June Precipitation Summary Statistics | December Precipitation Summary Statistics |
| :---: | :---: |
| ![](https://github.com/Hala-INTJ/Surfs_Up/blob/main/June%20Precipitation.png) | ![](https://github.com/Hala-INTJ/Surfs_Up/blob/main/Dec%20Precipitation.png) |

The precipitation analysis reveals a large difference between the 75th percentile and the maximum values. This indicates that on most days with precipitation, it is light. Further analysis was done focusing on the number of days with 'heavy' precipitation -- those above the 75th percentile.

|  | June  | | December  | |
| :---: | :---: | :---: | :---: | :---: |
| Total Days | 1574 | | 1405 | |
| Rain Days | 927 | 58.9% | 895 | 63.7%  |
| 75th Percentile | 0.12 || 0.15 ||
| Heavy Rain Days | 382 | 24.3% | 341 | 24.3% |

Since the number of days with rain, and the number of days where it rains heavily, are very close between June and December, it is likely that people will purchase as much ice cream in June as in December, and the business should be viable year round.




