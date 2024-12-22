java c
Business and Economic Forecasting
EMET3007/6012 
Assignment 1 
•      100 %   = 28 points.
• Maximal 3 students   can   submit   one   solution   of Assignment   1. All   stu-   dents   within a group   receive   the same grade. Both students of   each   group   submit the SAME solution WITH uni-id’s   of   students within   the   group.   Solutions   are   submitted via Wattle(Turniton). The   other   student(s)   sub-   mits his/her uni id and the uni id of students within the group.
•   Name   the   uploaded   ﬁle,   if   possible   as   a   pdf,   in   the   form   of   “your   uni   id-A1”   .
•   Only working within each group   is   allowed.    Please   use wattle   to   build   groups. Try to be precise in your argumentation.
•   If there is an issue   with   uploading   the   ﬁle   on   wattle   please   send   a   copy   to   [email   protected]   and   explain   the   nature   of   the   technical issue.
• Due on   21st   August   2024 WEDNESDAY   6pm   (Week   5)   (GMT+10).   Late assignment will not be accepted.
Form. of Solution
•   coding   in   matlab   is expected; you can   use   parts of   the code   which   is   avail-   able on wattle) however excel is feasible.
•   please provide code (with explanation) in your solution ﬁle so that it can   be easily replicated with   matlab.
• please type your solutions
Solve the following 5 problems.
Problem 1  1+2+2=5 points 
Suppose   X1, . . .   ,   Xn      are iid random variables with mean µ and variance σ2      < ∞ .
(a)      Find the expected value and variance of the sample mean

(b)      Show that

(c)      Show that the sample variance

is   an   unbiased   estimator   of σ2, i.e., E[S2] = σ2   .
Problem 2                                                                                                                                                                               4 points 
Write a MATLAB program to generate data from the trend-cycle model in   Ex-   ample 3 from Week 2 with a quadratic trend component.
mt      = a0   +   a1t +   a2t2, 
and the same cycle component 
ct      = b1cos(ωt) +   b2 sin(ωt).
Plot time path of the model
yt      = mt   +   ct
with   T   = 50, a0    = 0, a1    = 0.5, a2    = 0.1, b1    = 4, b2    = 0, ω = 2π/4 and σ2    = 2.
Note: here is no noise component!
Problem 3  5+1=6 points 
a. Write   a   MATLAB   program   to   generate   data   from   the   following   mean-reverting   process:
yt      = µ + φ(yt   -1   - µ) + et, et      ~ N(0, σ2   ),
fort   =   1,   2, . . .   , T, where the process is initialized with y0      = μ .    Plot one real-   ization   of   the   process   with   T   = 50, μ = 5, φ = 0.8 and σ2    = 2.
b.         What   can   you   say   about   the   parameter φ and   how   is   it   affecting   the   process?
Note: here is a noise component!
Problem 4 代 写EMET3007/6012 Business and Economic Forecasting Assignment 1Matlab
代做程序编程语言                                                                                                         3+3+3+2+1=12 points Suppose we wish to compare the forecast accuracy of two simple methods for   forecasting the Canberra inﬂation rate:   (1) the mean using data up to the most   recent   observation,   and   (2)   a   random-walk   method   that   uses   only   the   most   recent   observation.      The   evaluation   period   is   from   2016   Q3   to   2021   Q4.      For
Table 1: Canberra CPI Inﬂation rate per quarter from ABS
Quarter 
Inﬂation 
Quarter 
Inﬂation 
2014 Q3 
0.4 
2018 Q2 
0.4 
2014 Q4 
0.1 
2018 Q3 
0.6 
2015 Q1 
-0.1 
2018 Q4 
0.7 
2015 Q2 
0.4 
2019 Q1 
0.1 
2015 Q3 
0.2 
2019 Q2 
0.3 
2015 Q4 
0.2 
2019 Q3 
0.7 
2016 Q1 
0.2 
2019 Q4 
0.6 
2016 Q2 
0.2 
2020 Q1 
0.4 
2016 Q3 
0.8 
2020 Q2 
-2.3 
2016 Q4 
0.6 
2020 Q3 
2.3 
2017 Q1 
0.6 
2020 Q4 
0.8 
2017 Q2 
0.0 
2021 Q1 
0.9 
2017 Q3 
0.9 
2021 Q2 
0.8 
2017 Q4 
0.6 
2021 Q3 
1.3 
2018 Q1 
0.8 
2021 Q4 
1.0 
measures of accuracy, we consider MAFE and   MSFE.
a)      Use the two   methods (historical   mean and random   walk) to   produce   one-   step-ahead forecasts for each quarter from 2016 Q3   to   2021   Q4.   For   each   method, graph your forecast against the actual data.
b)      Compute   the   two   measures   of   forecast   accuracy   for   the   two   methods.   Which model performs better according to these measures?
c)    (can be solved without a) and b))Find   one   additional measure   of forecast   accuracy   (online   or elsewhere).   Describe   this   measure, and compare the two   models   under this   new   mea-   sure.
d)    (can be solved without a) and b))A large   portion of the error in   your forecasts   is   coming   from   a   small   num-   ber   of   outlier   datapoints.    Identify   these   datapoints,   and   describe   what   real-world event is driving this anomaly.
e)    (can be solved without a) and b))
Find the actual 2022 Q1 Canberra CPI inﬂation rate from the ABS.   Com-   pare the realisation to your forecast.
Problem 5 4 points 
Prove   the   following   theorem:      Given   a   density   forecast f (yT+hjIT, θ) and   the absolute   loss   function   L(y(ˆ),   y)      =      j   y(ˆ)   -   yj,   the   point   forecast   which   minimises expected loss is the median mT+h.Note:   the median is the unique value mT+h    such that y   T+h   is as equally likely   to   be above mT+h   as   below it. Mathematically, mT+his the unique value which   satisﬁes
Clariﬁcation: The task in this question is to show that to minimise absolute
loss,the modeller should sety(ˆ)T+h      = mT+h.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
