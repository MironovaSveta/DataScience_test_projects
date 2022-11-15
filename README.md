# DataScience_test_projects
Here are simple data science projects

## Excel-statistical-hypothesis

It is a project where I aggregated information from google form (https://docs.google.com/forms/d/e/1FAIpQLSehWnjNcx-RUHEjIlwOjiAMb0SMAACNYhC-HCbbFbdnYFV7ag/viewform), 
and worked with it in google docs (https://docs.google.com/spreadsheets/d/1RoAwJroM-yE9lkFzSd9UDPMoq32ybmQJI0odHyA3BF0/edit#gid=2140780274) and google colab  (https://colab.research.google.com/drive/1LdgricnmXH7Ynw61cAmq2JPbFUVV-5UU?usp=sharing).

Input: vacation info, from google forms
Output: statistical information, in google docs and google colab

The aim of the task is to check the hypothesis that MEAN(STD(hypothesis price - actual price)) = 0. 
1.  Hypothesis: MEAN(hypothesis) = 0, N is the number of actual prices
2.  Statistical significance is 0.95.
3.  T-criterion is ABS(MEAN(hypothesis)-MEAN(actual))/SQRT(STD(actual)*STD(actual)/(N-1))
4.  Probability is StudentDistribution(T-criterion,N-1,2)
5.  Probability equals 0.27. So the hypothesis is true with 27% of probability. 0.27 is less than 0.95 so the hypothesis is rejected
