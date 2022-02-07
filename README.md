# School_District_Analysis


## Overview
The purpose of this analysis was to determine what changes to our district and school summary analysis occurred when we updated Thomas High School's 9th grade students math and reading scores with N/A. There was a question with the validity of these students math and reading scores.

## Results

### District Summary 
* The district summary was relatively unchanged by the updated scores since only 461 scores were affected out of 39170 total students. However they did slightly raise the percentages passing by .3% overall, by .2% for math and .1% for reading.

![district_summary_comparison](https://github.com/sbull32/School_District_Analysis/blob/main/School_District_Analysis/Resources/district_summary_comparison.png)

### School Summary
* For our schools summary, the only changes which occured were the scores (and passing %'s) for Thomas HS which increased significantly as detailed below.

![school_summary_comparison](https://github.com/sbull32/School_District_Analysis/blob/main/School_District_Analysis/Resources/School_Summary_revised.png)

### Thomas HS
* After removing the 9th grade scores by replacing them with NaN's, Thomas HS saw a significant increase in its passing % rates (math grades increased from 66.9% to 93.2%, reading was increased from 69.7% to 97%, and overall passing went from 65.1% to 90.6%)

![Thomas_HS_summary](https://github.com/sbull32/School_District_Analysis/blob/main/School_District_Analysis/Resources/school_summary_comparison.png)

### School Spending, Size, Type and Scores by Grade
* School spending metrics only changed for the $630-$644 group which saw increased passing %'s due to the correction in Thomas HS's scores

![school_spending_comparison](https://github.com/sbull32/School_District_Analysis/blob/main/School_District_Analysis/Resources/school_scores_per_spending_revised.png)

* School size metrics only changed for the Medium group which saw increased passing %'s due to the correction in Thomas HS's scores

![school_size_comparison](https://github.com/sbull32/School_District_Analysis/blob/main/School_District_Analysis/Resources/school_scores_per_size_revised.png)

* School type metrics only changed for the Charted group which saw increased passing %'s due to the correction in Thomas HS's scores
* ![school_type_comparison](https://github.com/sbull32/School_District_Analysis/blob/main/School_District_Analysis/Resources/school_scores_per_type_revised.png)
 
## Summary

The four changes we observed once the math and reading scores from Thomas HS are listed below

1. The updates greatly increased Thomas High School's passing percentages which led to an overall increase in both scores as well as the passing rates for the district.
2. The new metrics calculated for Thomas HS pushed it into the top 5 performing schools list, up to the 3rd best in the district.
3. The new metrics also increased the scores for the spending group of $630-$644 per student which saw it's math, reading and overall passing percentages increased.
4. Finally the Medium size group as well as the Chartered type group saw their passing percentages increased due to the corrected scores.



