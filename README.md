<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/35c3bd68-6f91-4396-9749-6f71564b249d" />### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 20/04/2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
###EMPLOYEE
<img width="1920" height="1200" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/bcc030b6-daa1-4136-a645-fa81788e102f" />

###WEATHER
<img width="1920" height="1200" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/73b44345-aa45-4f23-9c20-c6e7f4de1b24" />

### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
###EMPLOYEE
<img width="1915" height="1199" alt="Screenshot 2026-04-18 140430" src="https://github.com/user-attachments/assets/c1a4a094-232d-4d7f-9bfb-85c8779768f8" />

###WEATHER
<img width="1920" height="1200" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/8d86290e-c384-4dba-99c2-a6cb82b2899f" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
###EMPLOYEE
<img width="1920" height="1200" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/f05b50de-0903-464b-8e59-42f3cc5bd786" />

###WEATHER
<img width="1920" height="1200" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/75eb13d8-8491-4fd2-975e-c4abd1bab2c8" />

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
###EMPLOYEE
<img width="1920" height="1200" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/f14adb93-6cb1-49b2-a687-0174728ab843" />

###WEATHER
<img width="1920" height="1200" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/7fc169b6-0899-4d57-a4d0-2e52aeb5e3c4" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
