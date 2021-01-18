# IAS_21
In this tutorial I will show you a simple way to get the last updated exchange rate at each step of a purchase process. In this first part I will show you how to send to your accounting team the posting related to the purchase cost of products bought around the world, the payment converted with the correct rate.

We have an excel report with a simple list of 150  purchases with the supplier name, the amount of the purchase the currency of the operation; the date of purchase and the payment date.
We will build a python script that will analyse for each single purchase, the accounting posting that has to be done (debit and credit converted with the correct exchange rate),calculate the realised gains or losses on FX every time that we made a payment and finally write back the accounting posting into the excel report, ready to be send to your accounting team.
