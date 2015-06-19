[TOC]
# PACmon 2.2 Manual
>This manual uses the [Markdown](http://daringfireball.net/projects/markdown/) syntax.


##REVISION HISTORY
head1 | head2
------|-------
hello | foo
hi    | bar

---
## 1. Overview

### 1.1  What is PACmon
>PACmon (Power Acquisition Control and Monitoring) is a hardward and software solution which measures information of power feature of developemnt board of Exynose base and provides developers and testers with a web-based monitoring and profiling tool. 

### 1.2 Channels
>PACmon has eight low voltage channels, two high voltage chnanels and four temperature channels.

Channel Type| The Number of Channels
------------------------|--------------
            Low         |             2
            High        |             8
            Temperature |             4

---
### 1.3 What PACmon measures
>PACmon measures voltage, current and power through each low and high channels and temperature through temperature channels.



---
### 1.4 What PACmon Shows with Measured Data.

### 1.4.1 Realtime

#### 1.4.1.1 Line Graphs
>During measurement Pacmon shows line graphs for power and one temperature updated on a realtime basis which shows how values have changed as time has passes.

#### 1.4.1.2 Column Graphs
>Also, PACmon displays realtime current, voltage, power values for each channels through column graphs as column graphs.

___

### 1.4.2 After measurement
>After measuring PACmon analyzes the measured data and provides many useful information.

#### 1.4.2.1 Timeline Graphs
s
#### 1.4.2.2 Column Charts for Average Current, Voltage and Power
a
#### 1.4.2.3 Table for Average Current, Voltage and Power
a

#### 1.4.1.3 Table for Average, Minimum and Maximum Temperature
>PACmon displays average values for temperature data measured during measurement duration for each channel respectively.

#### 1.4.1.4 Column Charts for proportions of each state in CPUs, GPUs and Devices.
>PACmon displays column charts for proportions of Each State for CPUs, GPUs and Devices. 

#### 1.4.1.5 CPU idles.
a

#### 1.4.1.4 Power Percentage Pie Graph
>PACmon displays differently for two cases; when high voltage channels are measured and when only low voltage channels are measured.
when only low voltage channels are measured it shows its power proportion to its total sum of powers. 
When high voltage channels are measured, it shows power proportion of each channel to the power of eighth channel.


---


        

 
## 2. BASIC OPERATION
### 2.1 PC Setting
> To run PACmon server and connect to it via web browser, you need to 

#### 2.1.1 proxy setting


#### 2.1.2 RNDIS setting

### 2.2 Connection to PACmon server through Web Browser

### 2.3 Settings

![Figure 1.1](http://55.vs.woobi.co.kr/settings.PNG)
#### 2.3.1 ADC Sampling Frequency (Hz)
>You can set ADC sampling frequency. This value is connected to PACmon DB and used to determine sampling freqency in Kernel.

#### 2.3.2 Test Duration (sec)
>This is the time duration during which measurement proceeds.


#### 2.3.3 Use High Voltage/Current

> You can determin whether to use high voltage channels ( channel 8 and 9 ). If you check the checkbox then high voltage channels will be measured as long as low voltage channels.

#### 2.3.4 Shunt, Amp and Names in Voltage Channel Table
> You can set shunt resitance, amplification and name for each voltage channel. These values must corresponde to the real values on the PACmon board. shunt resistance and amplification values will be used in analysis process. 

> When you are using channel 4 for display then you can set the channel's name, for exmaple, "disp". These names will be used only in display.

### 2.4 Profiling Settings

### 2.5 Time Sync



### 2.6 Measuring
a


### 2.5 Analysis Result



---
## 3. ADDITIONAL FEATURE

---
## 4. S/W UPGRADE
```{.python}
def sum(a, b):
    return a+ b

def bbb():
    return 3
    
    
```

