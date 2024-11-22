# Ex04 Places Around Me
## Date:19/11/2024 

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
near.html

<html>
    
    <body>
        <h1 style="text-align: center; font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">My city Avadi</h1>
        <h2 style="color: chocolate; font-style: italic; text-align: center;">K Barathraj(24001402)</h2>
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="green park" title="green park" href="park.html" coords="468,377,645,448" shape="rect">
    <area target="" alt="cdce" title="cdce" href="cdce.html" coords="137,469,218,468,295,467,316,487,302,507,262,507,210,508,169,499,151,491" shape="poly">
    <area target="" alt="box academy" title="box academy" href="box.html" coords="1092,694,80" shape="circle">
    <area target="" alt="zudio" title="zudio" href="zudio.html" coords="360,39,572,76" shape="rect">
    <area target="" alt="remy cinemas " title="remy cinemas " href="remy.html" coords="618,91,735,90,770,90,752,124,768,119,731,119,685,119,644,120,605,115" shape="poly">
</map>
    
    </body>
</html>

park.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="white">
       
        <h3 align="center">
        <font color="green" style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;"><b>Paruthipattu Park</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Paruthipattu Lake, also known as Avadi Lake, is a lake in Chennai, Tamil Nadu, India. It is located in the Avadi locality of Chennai. It is the second eco-park in the city after Chetput Lake.
            <br>
            <br>
            The lake is fed by surplus water from the unpolluted stretch of the Cooum River. The lake serves as a source for groundwater recharge in the neighbouring areas, such as Adhiparasakthi Nagar and Govardhanagiri. The average depth is 12 feet
            <br>
            <br>
            The eco-park surrounding the lake consists of a 3-km-long walking track, children's play area, refreshment block, a central plaza for public gathering, a boat deck with three landing areas, a couple of islands for nesting birds, an open-air theatre, an administration office building, and vehicle parking lot.
        </font>
        </p>

    </body>
</html>

cdce.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="violet">
        
        <h3 align="center">
        <font color="red" style="font-family: cursive;"><b>CDCE Automation</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify" style="font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; font-size: large;" >
            CDCE Automation was established in the year 2013 as a partnership owned organization. We are dedicated towards supplying best quality products and customized solutions to our clients, with a view to render them utmost satisfaction. Furthermore, we have started our business as a manufacturer and supplier of a wide assortment of Auto Tightening Machine, Key Checking Machine, Leak Test Equipment, Sub Assembly Station, Industrial Conveyor and many others. Our products are developed using advanced technology and high quality raw material, which have improved their efficiency and make highly demanded in the market.
            <br>
            <br>
            We procure raw material from the most trustworthy and reliable industrial vendors, whom we have chosen after conducting thorough market research and on the basis of their domain experience, prompt delivery schedule, financial stability and quality of the material. Moreover, with the incorporation of advanced production techniques, our company is successful in coming up with innovative range into the market.
        </p>
    </body>
</html>

remy.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body style="background-color: rgb(255, 251, 0);">
        
        <h3 align="center">
        <font color="black" style="color: rgb(228, 25, 235); font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;"><b>Remy Cinemas</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font size="5" style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
            Behold the mesmerizing transformation of our cinema theater facade! Through cutting-edge technology and the artistry of image sampler laser cutting, we've immortalized iconic actors' faces, creating a dynamic and visually striking entrance. Step into a world where the silver screen comes alive not only on film but also in the very architecture that surrounds it. Our design merges innovation with cinematic grandeur, promising a captivating experience before the curtain even rises
        </p>
    </body>
</html>

box.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body style="background-color: magenta;">
        
        <h3 align="center">
        <font color="black" style="color: aquamarine " style="font-style: italic;"><b>Box Bong Academy</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="italic" size="5">
            The Box Bong Sports Academy Chennai, nestled in the heart of the country, stands as a beacon of excellence in the world of boxing. Founded with the vision to nurture talent and foster the spirit of this noble sport, the academy has quickly risen to prominence, becoming one of the most sought-after destinations for aspiring boxers. At its core, the academy is driven by a passion for the sweet science of boxing and a commitment to the holistic development of its trainees 
        </font>
        </p>
    </body>
</html>

zudio.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body style="background-color: chartreuse;">
        
        <h3 align="center">
        <font color="black" style="color: bisque; font-family: cursive;"><b>Zudio</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font size="5" style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
            Find the best clothing stores nearby you. Explore the wide range of collections for mens, womens & kids in Westside store near you. Shop from more than 150+ stores in India.
            <br>
            <br>
            Tata 's Zudio was launched in 2016, and  by the end of 2023  its revenues were estimated to be in excess of 4,000 crore, reported Rediff earlier this month.   
        </font>
        </p>
    </body>
</html>

```

## OUTPUT
![alt text](<vijay/Screenshot (12).png>)
![alt text](<vijay/Screenshot (18).png>)
![alt text](<vijay/Screenshot (14).png>)
![alt text](<vijay/Screenshot (15).png>)
![alt text](<vijay/Screenshot (16).png>)
![alt text](<vijay/Screenshot (17).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
