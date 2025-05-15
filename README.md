# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

Dev by : KARTHICK S

Reg no : 212224230114

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
plt.plot(x,y,label='line1')
```

## Output:
![image](https://github.com/user-attachments/assets/ecd91ec2-6972-4cc1-b3e9-6d2ab41f0e9f)

```
x1 = [1,2,3]
y1 = [2,4,1]
x2 = [1,2,3]
y2 = [4,1,3]

plt.plot(x1,y1,label='line1')
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
## Output:
![image](https://github.com/user-attachments/assets/3a8703e7-f321-4662-a029-b89fcaff46f8)
```

import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
## Output:
![image](https://github.com/user-attachments/assets/ddeeb8d3-6aa3-408d-84bd-d4cc3cec9460)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

## Output:
![image](https://github.com/user-attachments/assets/64795dc5-4dec-41b5-8ae3-697944575851)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)

```
## Output:
![image](https://github.com/user-attachments/assets/cc3903d4-f43f-42cf-a1a8-ffb064ba04ca)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);

```
## Output:
![image](https://github.com/user-attachments/assets/b48fadf3-f1e9-4ccb-b616-6d7d42f456cb)

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
## Output:
![image](https://github.com/user-attachments/assets/e4663cf4-ef80-4a39-a928-d3199868b199)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x

```
## Output:
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])

#code:
```
y
```

## Output:

array([11, 12, 13, 14, 15, 16, 17, 18, 19, 20])

#code:
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
## Output:
![image](https://github.com/user-attachments/assets/c51b1c4a-a7ee-4b8b-9e03-240041fd41ae)

```
y=x*x
y
```

## Output:

array([ 0,  1,  4,  9, 16, 25, 36, 49, 64, 81])


#code:
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.legend(['y-values']);
```

## Output:
![image](https://github.com/user-attachments/assets/1643b600-1e53-4f88-9f23-3391c98e8685)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
## Output:

![image](https://github.com/user-attachments/assets/c4f8818a-a63c-4ca9-b71d-f6561bc29fd0)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
## Output:

![image](https://github.com/user-attachments/assets/0ba51560-3eae-4f99-97ce-d503deb6fe6d)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```

## Output:

![image](https://github.com/user-attachments/assets/cc135d6f-5bff-480d-b98a-92585ab5c4df)
```

import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
## Output:

![image](https://github.com/user-attachments/assets/521045fe-d63a-4813-a3d5-3127aca1446b)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```

## Output:

![image](https://github.com/user-attachments/assets/fcde89c6-65d3-4064-a890-f82a7cee92da)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
## Output:

![image](https://github.com/user-attachments/assets/f7ec276b-4660-47e1-b4ea-6484dc3943df)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
## Output:

![image](https://github.com/user-attachments/assets/b4f00772-6e23-41e0-9f08-03b2727060b0)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
## Output:
![image](https://github.com/user-attachments/assets/d1d1b9fc-59b7-43c2-aab1-1929e5c6a9b4)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
## Output:
![image](https://github.com/user-attachments/assets/25e95803-03f8-4ff2-941b-d3f9d53a3509)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
## Output:
![image](https://github.com/user-attachments/assets/4072c08d-f787-4a40-a086-d9f3c25a561c)


# Result:

Data visualization using matplot library was done successfully
