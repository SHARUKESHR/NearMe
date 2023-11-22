# Ex04 Places Around Me
## Date: 20.11.23

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color=""red><b>Dharmapuri</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Sharukesh R (23012910)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="600" width="1400">
            <map name="MyCity">
                <area shape="rect" coords="450,250,700,400" href="dharmapuri.html" title="Dharmapuri">
                <area shape="rect" coords="950,20,1150,180" href="kambainallur.html" title="Kambainallur">
                <area shape="rect" coords="1200,20,1400,180" href="Vannampatty.html" title="Vannampatty">
                <area shape="rect" coords="1100,250,1400,500" href="Morappur.html" title="Morrapur">
                <area shape="rect" coords="300,400,600,700" href="Palayampudur.html" title="Palayampudur">
            </map>
        </center>
    </body>
</html>

Palayampudur.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
<h1 align="center">
<font color="red"><b>Palayampudur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>neighbour village </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Palayampudur is a Village in Nallampalli Block in Dharmapuri District of Tamil Nadu State, India. It is located 16 KM towards South from District head quarters Dharmapuri. 7 KM from Nallampalli. 305 KM from State capital Chennai
</p>
</body>
</html>

Morappur.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>Morrapur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> neighbour village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    It has a total of 43 panchayat villages. It includes the railway station which is an important link between the east of Chennai and west of Salem and Coimbatore, and in Dharmapuri district. Morappur is also famous for the Singara Velan temple. Morappur has a government hospital and good agricultural development.
</p>
</body>
</html>

Vannampatty.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>vannampatty</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>neighbour village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Though the name 'Vannampatti' is denoted for the whole village,it is rightly devided in to two parts by a main path that runs north-south wise and the west half(which is originally called vannampatty) has been merged in to the paraipatty panchayat and the east half has been merged (according to the revenue records, it is called 'vellaimalaipatty)in to the veerakkal panchayat.
</p>
</body>
</html>

kambainallur.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="violet">
<h1 align="center">
<font color="red"><b>kambainallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>neighbour village </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kambainallur has an average literacy rate of 70.69%, lower than the national average of 80.09%: male literacy is 78.28%, and female literacy is 62.77%. In Kambainallur, 13% of the population is under 6 years of age.
</p>
</body>
</html>

dharmapuri.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>dharmapuri</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> my hometown</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Dharmapuri District is one of the major producers of mango in the state, fine quality granite is found in the district. It is also one of the main sericulture belts in the state. Around 30 percent of the district's area is under forest cover. Kaveri enters Tamil Nadu through this district.
</p>
</body>
</html>

```


## OUTPUT


![1](https://github.com/SHARUKESHR/NearMe/assets/144870484/4d042189-73eb-400d-a3e6-4cfb229ef970)










## RESULT
The program for implementing image maps using HTML is executed successfully.
