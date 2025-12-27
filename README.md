# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
<body bgcolor="cyan">
    <h1 align="center">
        <font color="red"><b>Marina Beach</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>SANTHANALAKSHMI</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#MyCity" width="1500" height="600">
        
        <map name="MyCity">
            <area shape="rect" coords="450,450,500,500" href="home.html" title="College">
            <area shape="rect" coords="370,50,500,190" href="temple.html" title="Paneri Amman">
            <area title="Thiruvallur Statue" href="statue.html" coords="570,450,700,500" shape="rect">
            </map>
    </center>
</body>
</html>

statue.html

<html>
<head>
<title>Thiravallur Statue</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>Marina Beach</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thiravallur Statue</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Thiruvalluvar Statue at Marina Beach, Chennai, is a cultural landmark dedicated to the great Tamil poet and philosopher Thiruvalluvar, the author of the Thirukkural. Located along the Marina seafront, the statue symbolizes Tamil ethics, wisdom, and moral values, attracting visitors, students, and tourists alike. It stands as a reminder of Tamil Nadu’s rich literary heritage and the timeless relevance of Thiruvalluvar’s teachings on virtue, wealth, and love.
</p>
</body>
</html>

temple.html

<html>
<head>
<title>Paneri Amman</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Marina Beach</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Paneri Amman - Hindu Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Paneri Amman Temple, is a revered local shrine dedicated to Goddess Amman, worshipped as a protector and provider of strength and well-being. Deeply rooted in the cultural and spiritual life of the surrounding community, the temple is known for its simple architecture, daily rituals, and vibrant celebrations during festivals such as Aadi and Navaratri. It serves as an important place of devotion for residents, reflecting the rich tradition of Amman worship in Tamil Nadu.
</p>
</body>
</html>

home.html

<html>
<head>
<title>University Of Madras</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Marina Beach</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>University Of Madras - A Prestigious College</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The University of Madras, established in 1857, is one of the oldest and most prestigious universities in India. Located in Chennai, Tamil Nadu, it has played a vital role in shaping higher education and intellectual thought in the country. The university is known for its strong academic traditions, historic Marina Campus, and notable alumni who have contributed significantly to fields such as science, literature, politics, and law. With a legacy spanning more than a century and a half, the University of Madras continues to be a center of learning, research, and cultural heritage.
</p>
</body>
</html>
```
# OUTPUT
<img width="1063" height="591" alt="Marina_Beach_SANTHANALAKSHMI_clean" src="https://github.com/user-attachments/assets/7704eb76-4540-4972-812c-a4533f9ea975" />
<img width="1033" height="582" alt="image" src="https://github.com/user-attachments/assets/12706a5f-f755-4069-95fe-25a51f187133" />
<img width="1041" height="584" alt="image" src="https://github.com/user-attachments/assets/1abb4c78-4502-4295-b790-19d851354e1f" />
<img width="1039" height="587" alt="image" src="https://github.com/user-attachments/assets/6c41aafa-557f-4579-9d3d-9495bac23c03" />


# RESULT
The program for implementing image maps using HTML is executed successfully.
