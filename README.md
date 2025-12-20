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

<map name="image-map" >
    <area target="" alt="" title="Marina Beach" href="Marina.html" coords="1585,462,1779,586" shape="rect">
    <area target="" alt="" title="Express Avenue" href="mall.html" coords="1374,364,1558,469" shape="rect">
    <area target="" alt="" title="Semmozhi poonga" href="park.html" coords="1125,453,1281,598" shape="rect">
</map>
    </center>
</body>
</html>


```

## OUTPUT
![alt text](<myproject/mapapp/static/Screenshot (74).png>)
![alt text](<myproject/mapapp/static/Screenshot (75).png>)
![alt text](<myproject/mapapp/static/Screenshot (76).png>)

<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/d649c4e1-c781-42af-92b0-62addab86968" />

<img width="1920" height="1080" alt="Screenshot (80)" src="https://github.com/user-attachments/assets/820cc746-84fc-41de-99ff-15e0d13f0c6f" />

<img width="1920" height="1080" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/5d4dc455-4e16-4b43-94d2-469199c518d0" />

<img width="1920" height="1080" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/6d7daf50-b6d4-400f-be64-c0fc3d985c6b" />


## RESULT
The program for implementing image maps using HTML is executed successfully.
