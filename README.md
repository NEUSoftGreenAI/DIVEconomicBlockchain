# Experiment Codes for the paper
## *Basic Information*

 - Title: A Dual Incentive Value-based Paradigm for Improving the Business Market Profitability in Blockchain Token Economy;
 - Authors: Chaopeng Guo, Pengyi Zhang, Bangyao Lin, Jie Song*
 - E-mails: [guochaopeng@swc.neu.edu.cn](mailto:guochaopeng@swc.neu.edu.cn), [20185152@stu.neu.edu.cn](mailto:20185152@stu.neu.edu.cn),  
[2071292@stu.neu.edu.cn](mailto:2071292@stu.neu.edu.cn), [songjie@mail.neu.edu.cn](mailto:songjie@mail.neu.edu.cn)
## *Experiment Environment*
Language: Python
Version: 3.8
Software: Jupyter Notebook
## *Guidelines*
Three parts in the code:
 - Function definition between r and level.
 - Basic functions in the experiments.
 - Codes of seven test cases.
## Function definition between r and level.
It is the first part of codes with "***The relationship between r and level***" title. This part implements the calculation of Equation 6.
## Basic functions in the experiments
It is the second part of codes with "*Basic Functions*" title. This part defines seven functions in the experiment. Before the introduction of functions, the parameters should be firstly explained as follows.(All the repeated parameters in different functions have the same meanings).
 - ***a***: The same as the ***d%*** in the paper;
 - ***b*** : The same as the ***rp%*** in the paper;
 - ***Z*** : The ***Z-score*** of the value of the Equation 16 in the normal distribution;
 - ***expected***: The expectation customers of a membership merchant;
 - ***D***: The variance which is defined in the **Assumption** part of ***Section 5.1*** in the paper;
 - ***real*** : The real number of the membership merchant;
 - ***level***: The membeship merchant's level (1,2,3,4,5).
 
Then, the functions are explained as follows:
 - ***cal_ab(a,b)***: Calculate the value of the Equation 16 in the paper.
 - ***cal_profit(a,b,Z,expected,D,real)***: Calculate the profit of each membership merchant.  *,   
 - ***cal_union(a,b,Z,expected,D,real)***: Calculate the repurchase price for per membership merchant of the alliance. 
 - ***cal_D(a,b,Z,expected,real)***: Calculate the value of ***D***.
 - ***cal_league_price(expected)***: Calculate the profit of a membership merchant and the alliance including the membership fee.
 - ***cal_mv(a,expected,real)***: Calculate the profit of a merchant in the MV scenario which is defined in ***Section 5.1***.
 - ***cal_AQE(a,level)***: Calculate the profit of a merchant in the AQEscenario which is defined in ***Section 5.1***.
## Codes of seven test cases
Besides the mentioned parts, the rest parts of codes are experiments. We have titled each part from Test case 1 to Test Case 7. Each part we have made detailed experiment and graphic. Researchers can use these codes for reference or further studies.
