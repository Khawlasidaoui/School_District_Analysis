# School_District_Analysis

## Overview of the school district analysis

An initial analysis was conducted to assist the school district in summarizing math and reading scores and break them down by grade, spending, school size and type. The school board later notified that the scores for Thomas High School ninth grade showed evidence of academic dishonesty, and requested another analysis to be done on the data without the compromised grades. The results below show how these changes affected the overall analysis. 

## Results

#### 1. Impact on district summary

The school district summary only showed a slight decrease (less than 1%) in the average and percent passing for both math and reading.

##### Original district summary

![1](https://user-images.githubusercontent.com/79415699/111093262-d84ea080-850e-11eb-97d7-002e51ce2610.PNG)

##### Updated district summary
![2](https://user-images.githubusercontent.com/79415699/111093288-e7355300-850e-11eb-9681-0b94413bd2b2.PNG)



#### 2. Impact on school summary

Average math score, % passing math and reading, and percent of overall passing went down, while the average reading score showed a slight increase.

##### Original
![4](https://user-images.githubusercontent.com/79415699/111093294-ec929d80-850e-11eb-8e50-c98090f9aaf9.PNG)

##### Updated
![3](https://user-images.githubusercontent.com/79415699/111093318-fa482300-850e-11eb-83b5-5e42ecaf7f2b.PNG)

#### 3. Impact on performance

Even with the 9th graders scores adjustment, Thomas High School remained in the second highest place in terms of overall passing percentage. 

##### Original Performance Ranking
![image](https://user-images.githubusercontent.com/79415699/111093607-c4576e80-850f-11eb-97db-7bfe51fabefc.png)

##### Updated Performance Ranking
![image](https://user-images.githubusercontent.com/79415699/111093662-ddf8b600-850f-11eb-8fdd-c01bb50cacbf.png)

#### 4. Impact on math and reading scores by grade:

Since the ninth graders scores were replaced by NaN in the dataset, the math and reading scores were affected, for math:
![image](https://user-images.githubusercontent.com/79415699/111093888-5bbcc180-8510-11eb-9f2c-76b723ea489c.png)
for reading:
![image](https://user-images.githubusercontent.com/79415699/111093921-71ca8200-8510-11eb-8f27-78cdf6b5015e.png)

#### 5. Impact on scores by school spending: 

The bin of $630-$644 was affected by Thomas High School slightly with the average math score going down, the average reading score going up, and the percent passing math, reading, and overall going down.
##### Original
![image](https://user-images.githubusercontent.com/79415699/111094112-e6052580-8510-11eb-88b9-0d10154f3c5e.png)

##### Updated
![image](https://user-images.githubusercontent.com/79415699/111094054-c110b280-8510-11eb-87b4-7de0543a2be0.png)

#### 6. Impact on scores by school size:

The bin of "Medium (1000-2000)" students was affected by Thomas High School slightly with the average math score going down, the average reading score going up, and the percent passing math, reading, and overall going down.

##### Original
![image](https://user-images.githubusercontent.com/79415699/111094233-39777380-8511-11eb-99d4-1c2df8aa61e4.png)

##### Updated
![image](https://user-images.githubusercontent.com/79415699/111094255-485e2600-8511-11eb-9ceb-8b3a8d0cbaef.png)

#### 7. Impact on scores by school type:

The bin of "Charter" schools was affected by Thomas High School slightly with the average math score going down, the average reading score going up, and the percent passing math, reading, and overall going down.

##### Original
![image](https://user-images.githubusercontent.com/79415699/111094301-69bf1200-8511-11eb-9fa9-e79a3373cca3.png)

##### Updated
![image](https://user-images.githubusercontent.com/79415699/111094327-73e11080-8511-11eb-8804-1af824a439f9.png)

## Summary
After adjusting the original dataset and replacing Thomas High School ninth graders' scores with NaNs, we can say the following:

* It was not straighforward to make a direct comparison between schools in the district that year, since math and reading grades were directly affected. 
* Thomas High School's ranking remaing at second best in the district despite the major change in grade reporting, which shows that it has a good level. 

