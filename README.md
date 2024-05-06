# A-B-testing-marketing

This R Markdown file addresses several key aspects related to RoI calculation and the analysis of sponsored search ads. It starts by highlighting the primary issue with the original (Bob's) RoI calculation, which is an overestimation of revenue due to not accounting for organic conversions that are not influenced by sponsored ads. 

First, it discusses the implementation of a first difference estimate using a linear regression model to analyze the impact of removing sponsored ads on total traffic. The analysis includes creating binary columns for treatment and post-treatment periods, running a linear regression model on Google data, and interpreting the results, which showed a decrease in average total traffic in the absence of sponsored ads.

Next, it delves into calculating the Difference-in-Differences (DiD) to assess the true impact of sponsored ads on traffic. It checks the parallel assumption between the treatment and control groups and conducts a DiD regression analysis, concluding that the absence of sponsored ads led to a significant decrease in total traffic.

Lastly, the document suggests a refinement in RoI calculation by excluding clicks from individuals already familiar with the website. It proposes using the difference in difference method to calculate true traffic driven by sponsored ads, which leads to a revised RoI calculation accounting for organic search traffic.

Overall, the R Markdown file provides a structured approach to analyzing the impact of sponsored ads on traffic and suggests improvements to RoI calculations for a more accurate assessment of advertising effectiveness.
