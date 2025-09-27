# Ex04 Places Around Me
## Date: 27.09.2025

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
<!DOCTYPE html>
<html>

<head>

<title>My City</title>

</head>

<body>

<h1 align="center">

<font color="red"><b>Pondicherry</b></font>

</h1>

<h3 align="center">

<font color="blue"><b> Amsavaradhan M (25011322)</b></font>

</h3>

<center>

<img src="map.png" usemap="#My City">

<map name="My City">
    <area target="" alt="puducherry" title="puducherry" href="puducherry.html" coords="1071,349,1268,440" shape="rect">
    <area target="" alt="oussudu lake" title="oussudu lake" href="oussudulake.html" coords="614,337,788,415" shape="rect">
    <area target="" alt="white town" title="white town" href="whitetown.html" coords="1312,446,1472,515" shape="rect">
    <area target="" alt="serenity beach" title="serenity beach" href="serenitybeach.html" coords="1324,53,1518,136" shape="rect">
    <area target="" alt="pondy marina" title="pondy marina" href="pondymarina.html" coords="1195,603,1371,679" shape="rect">
</map>
</center>
</body>
</html>

puducherry.html

<html>

<head>

<title>My City</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Pondicherry</b></font>

</h1>

<h3 align="center">

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Pondicherry, officially known as Puducherry,is the capital and most populous city of the Union Territory of Puducherry in India. The city is in the Puducherry district on the southeast coast of India and is surrounded by the Bay of Bengal to the east and the state of Tamil Nadu, with which it shares most of its culture, heritage, and language.
</p>

</body>

</html>

oussudulake.htmml

<html>

<head>

<title>My City</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Oussudu Lake</b></font>

</h1>

<h3 align="center">

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Ousteri Lake (Oussudu) is one of the biggest lakes around Pondicherry. Its more than a century old man-made water body and is  recognized as one of the important wetlands of Asia by the International Union for Conservation of Nature and Natural Resources (IUCN). It is a major supplier of fresh water to the region. It is open to tourists for boat rides and bird watching. During winters this lake becomes dwelling for over 2000 migratory bird species. PTDC operates a boat club at the lake. They offer 30min rides on the 20-seater boats they have which allow visitors to enjoy the cool breeze and the scenery. If lucky, one can also sight some rare birds found in this region.
   
</p>

</body>

</html>

serenitybeach.html

<html>

<head>

<title>My City</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Serenity Beach</b></font>

</h1>

<h3 align="center">

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Serenity Beach, located just north of Pondicherry town, offers a peaceful coastal retreat for travelers seeking quiet charm, natural beauty, and a unique cultural blend of Tamil and French influences. Far removed from the commercial buzz of Promenade or Rock Beach, Serenity Beach lives up to its name with golden sands, gentle surf, and an atmosphere that invites relaxation and reflection.
   
</p>

</body>

</html>

whitetown.html

<html>

<head>

<title>My City</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>White Town</b></font>

</h1>

<h3 align="center">

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    White Town, or the French Quarter of Puducherry, is a historical neighborhood famous for its well-preserved French colonial architecture, characterized by yellow houses, cobblestone streets, and charming bougainvillea-lined pathways. This picturesque area offers a unique blend of French and Indian cultures, with historic buildings now housing boutique hotels, art galleries, and cafes serving French-inspired cuisine. Visitors can enjoy heritage walks, explore beaches like Promenade Beach, and experience the relaxed atmosphere of the "French Riviera of the East".
   
</p>

</body>

</html>

pondymarina.html

<html>

<head>

<title>My City</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>Pondy Marina</b></font>

</h1>

<h3 align="center">

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
   The Pondy Marina is not a beach per se but rather a very alive and vibrant  that brings together spectacular ocean views, thrilling activities, and a foodie heaven. One can easily imagine taking a stroll on the velvety, soft sands, relishing the taste of justprepared seafood right by the shoreline or taking in the glorious view of the sun sinking gradually beneath the horizon with the soothing gentle waves washing over their feet.There is certainly an undeniable charm that describes the marina, and such charm is intricately intertwined with its remarkable versatility, making it quite an attractive destination for an array of visitors.
</p>

</body>

</html>
```

## OUTPUT
![alt text](../pondicherry.png)
![alt text](<../oosudu lake.png>)
![alt text](<../serenity beach.png>)
![alt text](<../white town.png>)
![alt text](<../pondy marina.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
