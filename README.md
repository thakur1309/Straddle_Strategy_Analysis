# Straddle_Strategy_Analysis
This repository contains my analysis of a short straddle strategy, done as part of an internship assignment. The assignment involved entering short positions on at-the-money call and put options. The position was hedged by entering long positions on out-of-the-money call and put options, which had a strike of +/-2% about the spot price. Target and Stop-loss percentages of 80% and 30% were also used for mitigating risk, and all positions were squared off before expiry if none of these conditions were met. The deliverables involved generating a Trade Report, as well as a Performance Statistics report. 
<br<
## Submission Format
Jupyter notebook was used as the coding environment, thus the final code submission consists of three ipynb notebooks. The order of execution is: <br>
1. data_cleaning_final<br>
2. backtesting_final<br>
3. drawdown_final<br>


The notebook contains markdown cells containing comments regarding the functions used and the though-process used, along with explaining the flow of the program. The code itself is commented at various places to aid in understanding. I have also included the .py files in the submission, if needed. <br>
The submission zip file also contains two CSV files, namely TradeReport and PerformaneStats which go along the lines of the samples provided. All the values and metrics outlined in the problem statement and samples were successfully generated. The graph required, i.e., the equity curve, is added as .png file, and is also present in the drawdown_final.ipynb file. The zip file also contains the intermediate CSV files generated and exported/imported. <br>
Additionally, I have included a project report as well, outlining my thought process throughout the assignment. The report contains justification of why the functions were programmed the way they are, as well as the process followed for calculating the Performance Statistics. <br>

## Personal Comments
Admittedly, the code may not be very efficient as it mostly follows linear processing. I tried to focus more on the correctness of the output than efficiency of the code, which is noticeable at points where the runtime for a single cell reaches 4-5 minutes. The high runtime may also be attributed to the large dataset itself (as the entire dataset was used, not a subset), however transferring the entire blame to the dataset will be unfair on my part. <br>
Overall, the assignment was a wonderful challenge to take on, allowing me to brush up my skills on time-series data analysis as well as provide some insight into trading strategies. I have added generic functions, allowing the modification of metrics such as stop_loss, target, away_wing percentage etc., to see how they impact the output. The optimisation of these parameters can be a future project to take on as well.


