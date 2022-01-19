# 4781_CandyStore

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/4781_CandyStore/blob/main/4781_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

Similar to knapsack problem.

The difference is that there is plenty of each candy and it is double type.

Because m is given as double , we should * 100 to make int and + 0.5 before casting to int to erase errors.

After that from the first item, checking if it is possible to have that item and if we can , find (current money - that item's price) + that item's calorie  vs the max calorie until now.

At first , I use malloc because we don't know the length of dp. However, if we do malloc and free, it takes some time to do that so it does not work properly.

After that I use memset to reset the dp.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
