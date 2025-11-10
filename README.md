# Ex04 Places Around Me
## Date: 10/11/2025

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
## Map.html


<!DOCTYPE html>
<html>
<head>
  <title>Places Around Guduvanchery</title>
  <style>
    body {
      font-family: Arial;
      background: #f8f8f8;
      text-align: center;
    }
    h1 {
      background: #4a8254;
      color: white;
      padding: 10px;
    }
    img {
      border: 2px solid #333;
      width: 1200px;
      height: 600px;
    }
  </style>
</head>
<body>
  <h1>Nearby Places Around Guduvanchery</h1>
  <h2>HARISH 212224230085</h2>
<img src="C:\Users\admin\web\NearMe\mapphoto.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="Vandalur" title="Vandalur" href="vandalur.html" coords="602,5,876,127" shape="rect">
    <area target="_self" alt="Zoho" title="Zoho" href="zoho.html" coords="371,551,247,469" shape="rect">
    <area target="_self" alt="ACSmahal" title="ACSmahal" href="acsmahal.html" coords="668,558,537,497" shape="rect">
    <area target="_self" alt="Ramanujar" title="Ramanujar" href="ramanujar.html" coords="955,147,1079,231" shape="rect">
</map>
</body>
</html>

## vandalur.html

<!DOCTYPE html>
<html>
<head>
  <title>Vandalur Zoo</title>
  <style>
    body {
      font-family: Arial;
      background-color: #dcedc8;
      text-align: center;
      padding: 20px;
    }
    img {
      width: 400px;
      border-radius: 10px;
    }
    a {
      text-decoration: none;
      color: #2e7d32;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Arignar Anna Zoological Park, Vandalur</h1>
  <img src="c:\Users\admin\OneDrive\Desktop\Fundamentals of web application\TNIE_import_2020_11_10_original_Annazoo_EPS_.avif" alt="Vandalur Zoo">
  <p>
    The Arignar Anna Zoological Park, commonly known as Vandalur Zoo, is one of the largest zoos in South Asia.
    It is home to hundreds of species including lions, tigers, elephants, reptiles, and birds.
  </p>
  <p>
    🕒 Timings: 9:00 AM – 5:00 PM (Closed on Tuesdays) <br>
    📍 Location: Vandalur, Chennai – 48
  </p>
  <a href="map.html">⬅ Back to Map</a>
</body>
</html>

## ramanujar.html

<!DOCTYPE html>
<html>
<head>
  <title>Sri Ramanujar Engineering College</title>
  <style>
    body {
      font-family: Arial;
      background-color: #f3e5f5;
      text-align: center;
      padding: 20px;
    }
    img {
      width: 400px;
      border-radius: 10px;
    }
    a {
      text-decoration: none;
      color: #6a1b9a;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Sri Ramanujar Engineering College</h1>
  <img src="C:\Users\admin\web\NearMe\sri-ramanujar-engineering-college-chennai-3tzfmaqsth.avif" alt="Sri Ramanujar Engineering College">
  <p>
    Sri Ramanujar Engineering College, located in Vandalur, is affiliated to Anna University.
    It offers various undergraduate and postgraduate programs in engineering and technology.
  </p>
  <p>
    🎓 Courses Offered: CSE, ECE, MECH, CIVIL, IT <br>
    📍 Location: Kolapakkam, near Vandalur-Kelambakkam Road
  </p>
  <a href="map.html">⬅ Back to Map</a>
</body>
</html>

## acsmahal.html

<!DOCTYPE html>
<html>
<head>
  <title>ACS & NPC Mahal</title>
  <style>
    body {
      font-family: Arial;
      background-color: #fff3e0;
      text-align: center;
      padding: 20px;
    }
    img {
      width: 400px;
      border-radius: 10px;
    }
    a {
      text-decoration: none;
      color: #e65100;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>ACS & NPC Mahal, Guduvanchery</h1>
  <img src="C:\Users\admin\web\NearMe\images (1).jpeg" alt="ACS & NPC Mahal">
  <p>
    ACS & NPC Mahal is a popular wedding and event venue near Guduvanchery.  
    The spacious hall and modern facilities make it ideal for large family functions and celebrations.
  </p>
  <p>
    🕒 Timings: Available for events 24/7 <br>
    📍 Location: Near Nanmangalam Lake, Guduvanchery
  </p>
  <a href="map.html">⬅ Back to Map</a>
</body>
</html>

## Output
![alt text](<Screenshot 2025-11-10 101402.png>)
![alt text](<Screenshot 2025-11-10 101525.png>)
![alt text](<Screenshot 2025-11-10 101820.png>)
![alt text](sri-ramanujar-engineering-college-chennai-3tzfmaqsth.avif)
## RESULT
The program for implementing image maps using HTML is executed successfully.
