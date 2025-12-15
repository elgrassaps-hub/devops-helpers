# Sample application

This is a sample application to visualize dependency between objects. 

Creates Web Ui on 8050 port once ran. 

## Requirements

Python >3.7 is a requirement. 

## Installation

```
pip3 install networkx dash plotly
```

## How to run

```
python3 GraphAnalysis.py obj_dependency_data.csv
```

## How to access

Access Web UI on 8050 port. 


Task 4 screenshot :
![img_3.png](img_3.png)
![img.png](img.png)
![img_1.png](img_1.png)
![img_2.png](img_2.png)

Task 5 screenshot:
![img_8.png](img_8.png)
![img_9.png](img_9.png)

![img_4.png](img_4.png)
![img_5.png](img_5.png)
Bind data vs existing:
![img_6.png](img_6.png)

![img_7.png](img_7.png)

Task 6 screenshot:
![img_10.png](img_10.png)

volume:
![img_11.png](img_11.png)
![img_16.png](img_16.png)
Writer:
![img_12.png](img_12.png)
mounted volume:
![img_18.png](img_18.png)
Reader:
![img_13.png](img_13.png)
mounted volume :
![img_17.png](img_17.png)
Containers:
![img_14.png](img_14.png)
inspect:
![img_15.png](img_15.png)

Task 7 
screenshot:
![img_19.png](img_19.png)
![img_20.png](img_20.png)

Task 8 
screenshot:

https://hub.docker.com/repositories/pskorodz

Multistage is 436 MB comparing to initial 558 MB:
![img_21.png](img_21.png)
![img_22.png](img_22.png)

After: Layers reduced to 20, Vulnerabilities reduced to 23:
![img_26.png](img_26.png)

Before:
22 layers, 95 vulnerabilities
![img_27.png](img_27.png)


app working:
![img_23.png](img_23.png)

Dockerhub pushed
https://hub.docker.com/repository/docker/pskorodz/sample-app-multistage/general
![img_24.png](img_24.png)
![img_25.png](img_25.png)

Alpine version reduced to 312MB:
![img_28.png](img_28.png)
![img_29.png](img_29.png)

![img_30.png](img_30.png)

Issues reduced to 2:
![img_31.png](img_31.png)