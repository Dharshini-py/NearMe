# Ex3 Places Around Me
## Date: 10.12.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NearMe</title>
</head>
<body>
    <h1 align="center">
        <font color="purple">CHENNAI</font>
    </h1>
    <h2 align="center">
        <font color="dark pink"> DHARSHINI V [25010872]</font>
    </h2>
    <center>
    <img src="chennai.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Marina beach" title="Marina beach" href="Marina.html" coords="1571,473,1801,596" shape="rect">
    <area target="" alt="Semmozhi Poonga" title="Semmozhi Poonga" href="park.html" coords="1120,449,1284,604" shape="rect">
    <area target="" alt="Express Avenue" title="Express Avenue" href="mall.html" coords="1359,356,1608,463" shape="rect">
    <area target="" alt="Anna Nagar" title="Anna Nagar" href="annanagar.html" coords="630,34,912,182" shape="rect">
    <area target="" alt="Rohini Silver screens" title="Rohini Silver screens" href="rohini.html" coords="544,190,820,244" shape="rect">
</map>
    </center>
</body>
</html>

```

mall.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="pink">
    <center>
        <br>
<img src="Express-Avnue.jpg" height="300" width="650">
<h1>EXPRESS AVENUE</h1>
    <p>Express Avenue (EA) Mall in Chennai is South India's "destination mall," known for its "shopper-tainment" concept, blending shopping, dining, and entertainment with modern architecture and sustainability, featuring international brands, a large multiplex (Escape Cinemas), a sprawling food court (EA Garden), office spaces, and a hotel, all with extensive parking and an innovative feel. </p>
    </center>
</body>
</html>

```

marina.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="#FFD3AC">
    <center>
        <br>
        <img src="beach.png" height="300" width="500">
        <h1>MARINA BEACH</h1>

    <p>Marina Beach is a natural urban beach in Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from near Fort St. George in the north to Foreshore Estate in the south, a distance of 6.0 km, making it the second longest urban beach in the world, after Cox's Bazar Beach.</p>
    <p>Marina Beach in Chennai is special for being India's longest and the world's second-longest natural urban beach, a 13km stretch along the Bay of Bengal, known for its vibrant atmosphere, iconic landmarks (Lighthouse, statues), sunrise/sunset views, and as a cultural hub for strolling, street food, and public gatherings, though swimming isn't safe due to strong currents.  </p>
    </center>
</body>
</html>

```

park.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="#B3E0DC">
    <center>
        <br>
        <img src="images.jpg" height="300" width="500">
        <br>
        <h1>SEMMOZHI POONGA</h1>
    <p>Semmozhi Poonga is a botanical garden in Chennai set up jointly by the Horticulture and Agricultural Engineering department of the Government of Tamil Nadu</p>
    <p>Nestled in the heart of Chennai, Tamil Nadu, Semmozhi Poonga is a verdant oasis that beautifully captures the essence of nature's splendor amidst an urban landscape. Translating to "Classical Language Park" in Tamil, this botanical garden stands as a tribute to Tamil culture and nature’s unparalleled artistry.</p>
    </center>
</body>
</html>

```

annanagar.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="teal">
    <CENTER>
        <br>
        <img src="annanagar.png" height="400" width="500">
        <br>
        <h1>ANNA NAGAR</h1>
        <p>Anna Nagar in Chennai is famous for being a well-planned, upscale residential area with wide roads, green spaces, and a grid layout, known for its diverse food scene (especially late-night eats), popular landmarks like the Anna Nagar Tower, bakeries, and numerous temples, making it a sought-after place to live and visit for its lifestyle, shopping, and food.</p>
    </CENTER>
</body>
</html>

```
rohini.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rohini Silver Screens</title>
</head>
<body bgcolor="#CF9FFF">
    <center>
        <br>
        <img src="rohini.jpg" height="300" width="500"
        <br>
        <h1>ROHINI SILVER SCREENS</h1>
        <p>Rohini Silver Screens is a renowned, state-of-the-art multiplex in Koyambedu, Chennai, famous as the "Mecca of First-Day First Shows" (FDFS) for Tamil films, offering Dolby Atmos, 4K projection, luxurious seating, and a huge food court, providing a premium cinematic experience with unique fan-centric celebrations and special event hosting for film lovers. </p>
    </center>
    
</body>
</html>

```

        
## OUTPUT

<img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/2b702cb8-2987-45c0-a8f3-be80d599d6e6" />

<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/d649c4e1-c781-42af-92b0-62addab86968" />

<img width="1920" height="1080" alt="Screenshot (80)" src="https://github.com/user-attachments/assets/820cc746-84fc-41de-99ff-15e0d13f0c6f" />

<img width="1920" height="1080" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/5d4dc455-4e16-4b43-94d2-469199c518d0" />

<img width="1920" height="1080" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/6d7daf50-b6d4-400f-be64-c0fc3d985c6b" />


## RESULT
The program for implementing image maps using HTML is executed successfully.
