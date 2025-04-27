# Ex04 Places Around Me
## Date: 27/04/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places Around Me</title>
</head>
<body style="background-color: beige;">
    <header>
        <h1 style="background-color: rgb(74, 255, 183);text-align: center;">Places around Me</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\Screenshot 2025-04-27 175901.png" title="map places"  usemap="#places-map"  width="1500px" height=""890px >
        <map name="places-map">
            <area shape="rect" coords="685,118,760,195"  href="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\stadium.html" title="stadium" />
            <area shape="rect" coords="147,288,237,355"  href="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\temple.html" title="temple" />
            <area shape="rect" coords="553,117,603,164"  href="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\mall.html" title="mall" />
            <area shape="rect" coords="1216,531,1353,601"  href="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\beach.html" title="beach" />
            <area shape="rect" coords="781,216,832,273"  href="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\school.html" title="School" />
            <area shape="rect" coords="1225,482,1294,532"  href="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\college.html" title="college" />
        </map>
    </main>
</body>
</html>

temple.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places in Cuddalore</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: rgb(221, 244, 139);">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: rgb(203, 106, 84);text-align: center;"> PADALEESWARAR TEMPLE</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\OneDrive\Documents\temple.jpg" title="TEMPLE"  usemap="#places-map" class="centreImage"  >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/F6SG5YmSMFvexUxm6" title="TEMPLE" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">Pataleeswarar Temple (பாடலீஸ்வரர் கோயில்) is a Hindu shrine dedicated to Shiva in the town of Thirupathiripuliyur, Cuddalore. It was constructed during the Pallava and Medieval Chola periods.The temple is close to the place where the Gadilam river takes a southward bend, and then proceeds east to join the sea. It is believed that at the time when Appar came to worship at this temple, the river’s course was quite different. To enable the saint to worship without hindrance, Siva changed the course of the river.  </p>
    
</body>
</html>

mall.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places in Cuddalore</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: rgb(224, 224, 189);">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: rgb(128, 233, 173);text-align: center;">V SQUARE MALL</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\V20SQUARE20MALL (1).jpg" title="V SQUARE MALL"  usemap="#places-map" class="centreImage" width="700px" height="450px" >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/Wr5Gs42X1TGn733F7" title="V SQUARE MALL" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">A mall, or shopping mall, is a large, enclosed building containing multiple retail stores, often with a central walkway or atrium. Malls are typically designed to provide a convenient and comfortable shopping experience for consumers. They offer a variety of goods and services, from clothing and electronics to food and entertainment, all under one roof. </p>
    
</body>
</html>

stadium.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places in Cuddalore</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: rgb(255, 94, 209);">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: rgb(255, 255, 255);text-align: center;">ANNA STADIUM</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\OneDrive\Documents\stadium.jpeg" title="ANNA STADIUM"  usemap="#places-map" class="centreImage" width="700px" height="450px" >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/Wr5Gs42X1TGn733F7" title="ANNA STADIUM" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">Anna Stadium in Manjakkuppam, Cuddalore is dedicated to ensuring the best experience for every customer. The center offers a variety of services to cater to your needs, including: Amenities: Wheel Chair Accessible Entrance And Exit, Wheel Chair Accessible In Car Parking.</p>
    
</body>
</html>

school.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places in Cuddalore</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: rgb(221, 147, 194);
        }
        h1{
            text-decoration-color:white; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(207, 77, 77); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">SCHOOL</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\school.jpeg" title="College"  usemap="#places-map" class="centreImage" width="400px" height="250px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/7SmwfZxQLpHuNL4u7" title=" CK School" />
        </map>
    </main>
    <h1></h1>
    <a style="color: black; font-size: xx-large;" href="https://ckschool.in/" title="Visit CK">     CK School of Practical Knowledge Matriculation Higher Secondary School </a> 
    <p style="color: black;"> The CK School is established in 1974, The CK School stands as a beacon of educational eminence in Cuddalore. Our school has earned a formidable reputation for nourishing young minds and promoting holistic development. Its prosperous history, distinguished alumni, and commitment to academic rigour make it an esteemed institution in Cuddalore. With a stretched-out campus boasting state-of-the-art facilities and a vibrant student community. The school upholds a tradition of excellence and innovation.</p>
    <p> As a nursery of leadership and intellectual curiosity, it continues to mould generations' futures, showing its enduring impact on education.The School also offers a plethora of activities in sports, pkip and academics. On the academic front, the school also offers a multitude of curriculums, which fundamentally challenge the students, and allow them to explore themselves. The legacy continues ....</p>
    <br>
    <br>

college.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places in Cuddalore</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: azure;
        }
        h1{
            text-decoration-color: black; font-style: italic;
        }
        a,p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
        }
        p{
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(32, 4, 78); height: 80px;">
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande'; color: white;">COLLEGE</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\OneDrive\Pictures\Screenshots\Screenshot 2025-04-27 183353.png" title="College"  usemap="#places-map" class="centreImage" width="400px" height="250px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/fy68TGfLtpC5x4Gd7" title="Arts College" />
        </map>
    </main>
    
    <h1></h1>
    <a><b>Periyar College of Arts and Science</b></a> 
    <p style="color: black;">Periyar Arts College in Cuddalore is a government-funded, general degree college offering a range of arts, commerce, and science courses. Established in 1964, it's located in Devanampattinam, a village near the East Coast Road and 200km south of Chennai. The college is named after social reformer Thanthai Periyar E.V. Ramasamy. </p>
    <p> The college has evolved to offer a wide range of courses, including those in Tamil, English, History, Economics, Physics, Chemistry, Botany, Zoology, Computer Science, Microbiology, and Political Science. </p>
    <br>
    <br>

beach.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places in Cuddalore</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: rgb(165, 254, 255);">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: rgb(111, 128, 255);text-align: center;">SILVER BEACH</h1>
    </header>
    <main>
        <img src="C:\Users\MAHALAKSHMI B\NearMe\map\mapapp\static\beach.jpg" title="SILVER BEACH"  usemap="#places-map" class="centreImage"  >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/F6SG5YmSMFvexUxm6" title="SILVER BEACH" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">Silver Beach in Cuddalore is a 57 km long stretch of sand on the Coromandel Coast, one of the longest in Asia and the second-longest in Tamil Nadu. Located 2 km from Cuddalore town, it's known for its serene atmosphere and is a popular spot for beach lovers and water sports enthusiasts. Situated on the southeast coast of India, 2 km from Cuddalore town.The beach is known for its clean water, a spacious walking area, and the absence of a large crowd. It's a good place for spending time with family and friends, strolling, and enjoying the sea. Silver Beach is also home to Fort St. David, a historically significant fort built by the British Empire. To the south of the beach, the South Cuddalore Bay area appears as if it is a separate island, and to the west, a river flows into dense mangrove forests.   </p>
    
</body>
</html>
```

## OUTPUT

![screenshot 1](https://github.com/user-attachments/assets/b0bd75f8-f0fc-40ea-a958-7b5dbe45c2ec)

![Screenshot 2](https://github.com/user-attachments/assets/85d12e34-be33-42bc-8188-04a02cf2ad9d)

![Screenshot 3](https://github.com/user-attachments/assets/ed649236-6b3a-4b68-b9dd-8f29546da008)

![screenshot 4](https://github.com/user-attachments/assets/11c03a0b-99b8-4f99-a355-eebae3b70ac2)

![Screenshot 5](https://github.com/user-attachments/assets/5d3abdc8-0631-4c20-9958-6a3c5c56e2d6)

![Screenshot 6](https://github.com/user-attachments/assets/3f5f307d-11ca-49fe-b362-69fbe04cf7bc)

![Screenshot 7](https://github.com/user-attachments/assets/39f17c92-ebf9-4afa-bdd6-b9612de1bb2d)

## RESULT
The program for implementing image maps using HTML is executed successfully.
