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























# Result:
 Include your result here
