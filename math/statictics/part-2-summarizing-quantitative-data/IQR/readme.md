# Interquartile Range (IQR)
Interquartile range is the amount of spread in the middle 50% of a dataset.

In other words, it is the distance between the first quartile Q<sub>1</sub> and the third quartile Q<sub>3</sub>.
## IQR = Q<sub>3</sub> - Q<sub>1</sub>

Here's how to find the IQR:
#### *Step 1:* 
Put the data in order from least to greatest.
#### *Step 2:*
Find the median. If the number of data points is odd, the median is the middle data point.   
If the number of data points is even, the median is the average of the middle two data points.
#### *Step 3:*
Find the first quartile Q<sub>1</sub>. The first quartile is the median of the data points to the left of the median in the ordered list.
#### *Step 4:*
Find the third quartile Q<sub>3</sub>. The third quartile is the median of the data points to the right of the median in the ordered list.
#### *Step 5:*
Calculate IQR by subtracting Q<sub>3</sub> - Q<sub>1</sub>

## Example
Essays in Ms. Fenchel's class are scored on a 6
point scale.
### Find the IQR of these scores:
1, 3, 3, 3, 4, 4, 4, 6, 6
#### *Step1:*
The data is already in order.
#### *Step 2:*
There are 9 scores, so the median is the middle score.
1, 3, 3, 3, `4`, 4, 4, 6, 6  
The median is 4.
#### *Step 3:*
Find Q<sub>1</sub>, which is the median of the data to the left of the median.  
There is an even number of data points to the left of the median, so we need the average of the middle two data points.  
1, `3`, `3`, 3  
Q<sub>1</sub> = (3 + 3) / 2 = 3  
The first quartile is 3.  
#### *Step 4:*
Find Q<sub>3</sub>, which is the median of the data to the right of the median.  
There is an even number of data points to the right of the median, so we need the average of the middle two data points.  
4, `4`, `6`, 6  
Q<sub>3</sub> = (4 + 6) / 2 = 5  
The third quartile is 5.
#### *Step 5:*
Calculate the IQR.  
IQR = Q<sub>3</sub> - Q<sub>1</sub> = 5 - 3 = 2
### The IQR is 2 points.
