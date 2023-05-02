# Turbonomic Performance Dashboard in Envizi.

This blog describes about the Turbonomic Performance Dashboard available in Envizi.

Turbonomic Performance Dashboard in Envizi allows the Sustainability Manager to view and compare  the energy and emissions performance of the data centers and assess the performance of deploying Turbonomic Resource Optimization technology.

The dashboard helps to view the following information.
- Host Energy Consumption by Data Center
- Host Emissions by Data Center
- Density of VM to Host by Data Center
- Intensity of Energy to Host by Data Center


## 1. Dashboard Home

The dashboard shows the entire organizations Host energy and emission details. 

<img src="images/image-11.png">

#### Left Panel

The left side panel shows the following for the entire organization.

- `Host Energy` of Current Year (985.8K), Previous Year (1.0M) and variation (-5.2%)
- `Carbon Emissions`  of Current Year (315.3), Previous Year (342.5) and variation (-7.9%)
- `Average Active hosts` (32) and `Average Active VMs` (509)

So there is a reduction in Host energy consumption and Carbon Emissions  this year compared to previous year.

#### Center Panel

The center panel shows data centers marked in the map.

#### Right Panel

The right side panel shows the list of data centers ordered based on Host energy consumption.


### 1.1 Host Energy Consumption by Data Center

1. Click on any of the `data center` in the Map.

The left side panel is updated with data center specific data.

Now the panel contains the below values.

- `Host Energy` of Current Year (171.8K), Previous Year (243.8K) and variation (-29.5%)
- `Carbon Emissions` of Current Year (39.7), Previous Year (51.1) and variation (-22.3%)
- `Average Active hosts` (47) and `Average Active VMs` (961)

The right side panel also highlights the selected data center.

<img src="images/image-12.png">

2. Mouseover  on the `data center` in the map shows the `Host energy Consumption` graph comparing with the previous year.

The graph shows that `energy consumptions` are less than last year.

<img src="images/image-13.png">

### 1.2 Host Emissions by Data Center

1. Click on the `Emissions` tab in the Center panel.

It refreshes the page with the Emissions details. There is no change to the left panel as it is already showing emission details.

<img src="images/image-14.png">

2. Mouseover on the `data center` in the map shows the `Emissions graph` comparing with the previous year.

The graph shows that emissions are less than last year.

<img src="images/image-15.png">

### 1.3 VM:Host Density by Data Center

It shows `VM and Host density` in the Data center. When more VMs are provisioned in a Host then it would be a effective utilization of the resources. Turbonomic helps to identify the scattered VMs and take appropriate actions.

1. Click on the `VM:Host` tab in the Center panel.

It refreshes the page with the VM:Host details.

2. Mouseover on the data center in the map shows the `VM:Host` density comparing with the previous year.

The graph shows that VM:Host density is higher than last year.

<img src="images/image-16.png">


### 1.4 Energy:Host Intensity by Data Center

It shows `Energy and Host Intensity` in the Data center. When more VMs are provisioned in a Host then it would be a effective utilization of the resources. The energy per host would be also hight. 

1. Click on the `Energy:Host` tab in the Center panel.

It refreshes the page with the Energy:Host details.

2. Mouseover on the data center in the map shows the Energy:Host Intensity comparing with the previous year.

The graph shows that Energy:Host Intensity is higher than last year.

<img src="images/image-17.png">



## 2. Data Center Summary

Lets look at the data center summary report.

1. Click on any of the data center in the right panel.

2. Click on `Drillthrough on selected data center` button.

<img src="images/image-18.png">

It shows the `Data Center Summary` page.

<img src="images/image-19.png">

#### Left Panel

The left side panel shows the following info related to the selected data center.

- Name of the Data center
- Location Id
- Country
- `Host Energy` of Current Year (50.56K), Previous Year (50.56K) and variation (-0.01%)
- `Carbon Emissions` of Current Year (19.70), Previous Year (22.21) and variation (-11.29%)
- Month on Month Host emissions graph.

So there is a reduction in Host energy consumption and Carbon Emissions this year compared to previous year.

#### Center Panel

The top of the Center Panel shows `VM:Host Density vs Host Energy Consumption` graph.

The bottom of the Center Panel shows `No. of Active Hosts vs No. of Active VMs` graph.

### 2.1 VM:Host Density vs Host Energy Consumption

1. Click on any of the month in the left panel.

The center panel get refreshed.

<img src="images/image-20.png">

2. Mouseover the in the `No. of Active Hosts vs No. of Active VMs` section of the graph. It shows 
- The `Active Hosts` of the month is `21`
- The `Active VMs` of the month is `345`

3. Mouseover the in the `VM:Host Density vs Host Energy Consumption` section of the graph. It shows
- The `Host Energy` of the month is `4294.02`
- The `VM Density` of the month is `16.41`

<img src="images/image-21.png">

### 2.2 Energy:Host Intensity vs Host Energy Consumption

1. Click on the `Energy:Host` tab in the Center panel.

It refreshes the page with the Energy:Host details.

2. Click on any of the month in the left panel.

The center panel get refreshed.

<img src="images/image-22.png">

3. Mouseover the in the `Energy:Host Intensity vs Host Energy Consumption` section of the graph. It shows
- The `Host Energy` of the month is `4294.02`
- The `VM Host Density` of the month is `16.41`

<img src="images/image-23.png">

## 3. Reporting Period 

You can change the report period to show the data between the selected dates.

<img src="images/image-24.png">



## Appendix

Reference to the related content.

#### Integrating Turbo with Envizi via AppConnect for Green IT data

This blog explains about the step-by-step instructions to pull green IT data from Turbonomic into Envizi via App Connect.

https://community.ibm.com/community/user/envirintel/blogs/jeya-gandhi-rajan-m1/2023/03/23/integrating-turbo-with-envizi-via-appconnect


#envizi
#Sustainability
#turbonomic
#dashboard

#ESG Data and Environmental Intelligence
#sustainability-highlights-home