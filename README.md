# Benford_test_using_tableau
This Project contains a visualization of Benford's Law. 
I have taken stock market data of Adani enterprises for the year 2022 to compare it with Benford's law graph.

## What is Benford's Law?

Benford's law, also known as the first-digit law, is a statistical principle that states that in many naturally occurring datasets, the first digit of a number is more likely to be small than large. Specifically, the law predicts that the digit 1 will appear as the first digit about 30% of the time, while the digit 9 will appear as the first digit less than 5% of the time.

One interesting application of Benford's law is in fraud detection. If a dataset deviates significantly from the expected distribution of first digits, it may be an indication that the data has been manipulated or fabricated. For example, if a company's financial statements show an unusually high proportion of numbers starting with the digit 9, it could be a red flag for fraudulent activity.

### Benford's Law Graph:

![benford](https://user-images.githubusercontent.com/95336274/222050901-1f2d75f0-3267-4de9-bed3-da3386509427.jpeg)

### Graph of the Adani Enterprises compared to Benford's Law:

<img width="1049" alt="Screenshot 2023-02-28 at 1 42 45 AM" src="https://user-images.githubusercontent.com/95336274/222051215-aff35df9-9208-491d-97aa-f17a4e2e749a.png">

The above graph shows the percentage deviation from the Benfod's law. I have taken only two columns from the dataset and those are: the no. of shares and the deliverable quantity. No. of shares refers to the volume of trade on a perticular day and deliverable quantity is the total no. of shares delivered to the investors.

### For Example:

When in the same example you have three players A, B, C
Transaction 1: A buys 100 shares, B sells 100 shares
Volume = 100
Transaction 2 = A sells 70 shares, C buys 70 shares
Volume = 70
Total day transaction = 100 + 70 = 170
A buys 30 shares in delivery (100-70)
B sells 100 shares in delivery and C buys 70 shares in delivery
So A and C buys 100 (30+70) in delivery, B sells 100 shares in delivery

