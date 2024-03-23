# Ex04 Places Around Me
## Date:22-03-2024 

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
map.html
```
<html>
    <head>
        <title>chennai</title>
    </head>
    <body bgcolor="cyan">
        <h1> CHENNAI CITY</h1>
        <h3>Name: R K Priya Dharshini</h3>
        <h3>Reg no:212223040155</h3>
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="egmore" title="egmore" href="egmore.html" coords="750,636,93" shape="circle">
    <area target="" alt="chennai park" title="chennai park" href="chennaipark.html" coords="1155,554,104" shape="circle">
    <area target="" alt="island grounds" title="island grounds" href="islandgrounds.html" coords="1407,786,72" shape="circle">
    <area target="" alt="bknsuditorium" title="bknsuditorium" href="bknauditorium.html" coords="707,455,91" shape="circle">
    <area target="" alt="chennaifort" title="chennaifort" href="chennaifort.html" coords="1490,418,161" shape="circle">
</map>
    </body>
</html>
```
CHENNAIPARK.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="BLUE">
        <h1 align="center">
        <font color="gold"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="YELLOW"><b>CHENNAIPARK</b></font>
        </h3>
        <hr size="3" color="PINK">
        <p align="justify">
        <font face="Georgia" size="5">
            As of 2019, there are 632 parks in Chennai City, including 142 parks in the north zone, 224 in the central zone, and 266 in the south zone.



        </font>
        </p>
    </body>
</html>
```
chennaifort.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="PINK">
        <h1 align="center">
        <font color="gold"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="GREY"><b>CHENNAI FORT</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            The Fort St. George Museum, nestled in Chennai, is a historical marvel waiting to be explored. Founded in 1644, it stands as a living testament to the British ...




        </font>
        </p>
    </body>
</html>
```
egmore.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="BROWN">
        <h1 align="center">
        <font color="gold"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="PINK"><b>EGMORE</b></font>
        </h3>
        <hr size="3" color="YELLOW">
        <p align="justify">
        <font face="Georgia" size="5">
            Egmore is a neighbourhood of Chennai, India. Situated on the northern banks of the Coovum River, Egmore is an important residential area as well as a ...





        </font>
        </p>
    </body>
</html>
```
islandground.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="GREEN">
        <h1 align="center">
        <font color="gold"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
        <font color="YELLOW"><b>ISLANDGROUND</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            The Island, also called as Island Grounds, is a river island situated on the Cooum River in the northern part of the Indian city of Chennai.






        </font>
        </p>
    </body>
</html>
```
bknauditorium.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="GREAY"><bKNAUDITORIUM</b></font>
        </h3>
        <hr size="3" color="PINK">
        <p align="justify">
        <font face="Georgia" size="5">
            The banquet hall at BKN Auditorium, Periyamet, Chennai is a great option for large social gatherings - engagements, weddings and reception ceremonies.




        </font>
        </p>
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot 2024-03-22 114109.png>) ![alt text](<Screenshot 2024-03-22 114345.png>) ![alt text](<Screenshot 2024-03-22 113732.png>) ![alt text](<Screenshot 2024-03-22 113852.png>) ![alt text](<Screenshot 2024-03-22 113906.png>) ![alt text](<Screenshot 2024-03-22 114030.png>) ![alt text](<Screenshot 2024-03-22 114044.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
