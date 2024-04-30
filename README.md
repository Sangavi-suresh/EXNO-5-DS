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

Simple two lines:

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[1,4,1]
plt.plot(x1,y1, label="line 1", color="maroon", linewidth=2)

x2=[1,2,3]
y2=[4,1,4]
plt.plot(x2,y2, label="line 2", color="black", linewidth=2)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on the same graph")
plt.legend()

```

![image](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/34660ea9-f6d2-4f0b-a049-5039cd7ff7de)

Customization of plots:

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='grey', linestyle='dashed', linewidth=3, marker='o', markerfacecolor='maroon',markersize=10)

plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')

plt.title("Customization of Plots")
```

![image](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/feeb5429-c7c5-4f82-aa91-6e994af2cb63)

Implementation using Matplotlib:

```

yield_orange=[0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_orange, color='sienna', linewidth=3)

```

![326153353-0e5e95df-fbc5-4932-ac5a-9d0473167431](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/fe20633a-53c4-4490-ab4f-add23db7ddd1)


```
years= [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples=[0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples, color='chocolate', linewidth=3)

```

![326153371-97d24b81-513d-4e88-8db5-7b3ba45ad3be](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/6d673b4d-8230-45aa-96ec-4c1e166cdcfc)

```
years = range(2000, 2012) 
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]
oranges = [0.962, 0.941, 0.930, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896, ] 
 
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)'); 


plt.plot(years, apples)
plt.plot(years, oranges)

plt.xlabel( 'Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Kanto")
plt.legend(['Apples', 'Oranges'])

```

![326153387-40620a05-10f9-46c4-b1ef-fec22a2f44ce](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/6f4a0536-1643-43ce-9522-1fcf0cd86fb8)

```

plt.figure(figsize=(12, 6))
plt.plot(years, oranges, marker='o')
plt.title("vield of Oranges (tons per hectare)")

```

![326153417-7240f811-daee-4a9a-acb0-b7921fcecc67](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/a12957c3-5ae7-455c-b633-e057f33b2c52)

```

plt.plot(years, apples, marker='o')
plt.plot(years, oranges, marker="x")
plt.xlabel('Year') 
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Kanto")
plt.legend([ 'Apples', 'Oranges'])

```

![326153441-1c1c071b-b001-407c-8f1f-d3a673443d18](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/40a7e97c-1010-4cc7-a0dd-38f1262f9dfd)

Scatter Plot:

```

import matplotlib.pyplot as plt
x_values = [0,1,2,3,4,5]
y_values = [0,1,4,9,16,25]
plt.scatter(x_values, y_values,s=30, color="blue") 
plt.show()

```

![326153462-376aa83f-e208-4672-994f-7101d575fa80](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/3a629e8b-1df7-41a4-9b09-5355554df716)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)

```

![326153490-3c1770fb-7d88-4ed7-a150-55be14618969](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/ccf61672-684a-462e-ac85-f648c36f1288)

![326153499-bef711a9-ddd6-49ff-bb17-26f3d080a123](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/b40b1586-13cf-4d10-8c47-3453a6adff85)

```

plt.scatter(x,y,c="r")
plt.xlabel( 'X axis')
plt.ylabel('Y axis')
plt.title( 'Graph in 2D')
plt.savefig('Test.png')

```

![326153509-d582fdcc-f2f3-4503-bec8-81d05dfa8581](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/4e9a1673-0d76-40ab-9a91-166ea45be6a4)


![326153520-7a01f98b-1e1f-47a5-a04e-c0720e308590](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/ecd6c8f6-baa5-4491-b72c-9316a3a8e1b7)

```
plt.plot(x,y, 'g*',linestyle='dashed' ,linewidth=2, markersize=12)
plt.xlabel( 'X axis') 
plt.ylabel( 'Y axis')
plt.title('2d Diagram') 

```

![326153537-c778f1eb-9e6d-4d85-aa87-dc115db5e1bb](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/66da38f6-6ad5-4060-82ef-6d372d513cde)


![326153543-1d0a16e4-1402-4725-9696-a66465327143](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/5ec7575f-1752-4b3b-a808-4eaf1c2bcf2f)

```

x = np.arange(0, 4 * np.pi, 0.1) 
y= np.sin(x)
plt.title('sine wave form')
plt.plot(x, y)
plt.show()

```

![326153555-ecd74a1b-8eeb-44b4-a592-ea20184e73c1](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/37ecfe8b-5fa8-42c2-b2ff-0d0c1d125c92)

Area Chart:

```

import matplotlib.pyplot as pit
import numpy as np
x=[1,2,3,4,5]
y1=[10, 12, 14, 16, 18]
y2=[5,7,9, 11, 13]
y3=[2,4,6,8,10]
pit.fill_between(x, y1, color='maroon')
plt.fill_between(x, y2, color='orange') 
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()

```

![326153570-2237fffd-023e-465f-a62c-2553fbf81f5c](https://github.com/Sangavi-suresh/EXNO-5-DS/assets/118541861/544d75bd-75f3-40ff-9442-0ccbd1b0f0c4)

import matplotlib.pyplot as pit
import numpy as np
x=[1,2,3,4,5]
y1=[10, 12, 14, 16, 18]
y2=[5,7,9, 11, 13]
y3=[2,4,6,8,10]
pit.fill_between(x, y1, color='maroon')
plt.fill_between(x, y2, color='orange') 
plt.plot(x, y1, color='red')
plt.plot(x, y2, c












# Result:
 Include your result here
