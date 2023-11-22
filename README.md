# Ex-06 Places Around Me
## Name: S.R.Bhuvanesh
## Reference Number: 23013380
## Aim:
To develop a website to display details about the places around my house.

## Design Steps:
### Step 1
Create a Django Admin Interface.

### Step 2
Download your city map from Google.
### Step 3
Using ```<map>```tag name the map.
### Step 4
Create clickable regions in the image using ```<area>```tag.
### Step 5
Write HTML programs for all the regions identified.

## Code:
### map.html
~~~
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Kanyakumari</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Bhuvaneh S R(23013380)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,50" href="hotel.html" title="KFC">
<area shape="circle" coords="680,400,80" href="clothes_shop.html" title="Pothys retail shop">
<area shape="circle" coords="1260,540,65" href="salon.html" title="Naturals salon">
<area shape="rect" coords="970,160,1100,220" href="temple.html" title="Nagaraja Temple">
</map>
</center>
</body>
</html>
~~~
### home.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="red"><b>Kanyakumari</b></font>
        </h1>
        <h3 align="center">
            <font color="green"><b>Nagercoil</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Nagercoil is a centre for a range of economic activities in the small but densely-populated Kanyakumari District. Economic activities in around the city include tourism, wind energy, IT services, marine fish production and exports, rubber and cloves plantations, agro-crops, floral production, manufacture of fishnets, rubber products among other activities.
            </font>
        </p>
    </body>
</html> 
~~~
### hotel.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="orange"><b>Nagercoil</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>KFC</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                KFC, a subsidiary of Yum! Brands, Inc. (NYSE: YUM.), is a global quick service restaurant brand with a rich, decades-long history of success and innovation. It all started with one cook, Colonel Harland Sanders, who created a finger lickin' good recipe more than 75 years ago, a list of secret herbs and spices scratched out on the back of the door to his kitchen. 
            </font>
        </p>
    </body>
</html>
~~~
### clothes_shop.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="orange"><b>Nagercoil</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Pothys Retail Shop</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Pothys is a chain of textile showrooms in South India. Originally they exclusively sold silk sarees, but today all types of garments are sold. The flagship store in Chennai is called Pothys' Palace.
                Pothys (stylised as POTHYS) was established in 1923 by K. V. Pothy Moopanar under the name Pothy Moopanar to sell cotton sarees and dhotis woven on his own loom. K.V. Pothy Moopanar born in Srivilliputhur belongs to a heritage family of Weavers.
            </font>
        </p>
    </body>
</html>
~~~
### salon.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="black"><b>Nagercoil</b></font>
        </h1>
        <h3 align="center">
            <font color="brown"><b>Naturals Salon</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Naturals was conceived with the idea of the modern Indian. Founded by K. Veena, whose knowledge of the international beauty industry pioneered a new era in the hair and beauty care industry in India, Naturals has made a path-breaking change in the way the beauty industry has been perceived. 

So in the early 2000s, she made that dream a reality by setting up her first salon in Chennai. It took her only a while to understand the market potential and the ever-increasing demand for professional grooming.
            </font>
        </p>
    </body>
</html>
~~~
### temple.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
            <font color="blue"><b>Nagercoil</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Nagaraja Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Nagaraja Temple is an early large temple found in the city of Nagercoil (Nagarkōyil) near the southern tip of Tamil Nadu, India. Its dating is uncertain but likely pre-12th-century. The main sanctum is dedicated to the Nagaraja – the king of serpents. Padmanabham (1985), Heritage Of The Tamils Temple Arts, Editors: SV Subramanian and G Rajendran, International Institute of Tamil Studies, Since the 17th-century, new Hindu shrines have been added to the temple complex attracting devotees of Krishna (Vishnu), as well as Shaiva and Shakti Hindus.[1] The original iconography of the Tirthankaras and Padmavati Devi have and continue to remain a part of the sacred pantheon close to the temple's main sanctum.
            </font>
        </p>
    </body>
</html>
~~~
## Output:
![map png](https://github.com/Bhuvanesh-Suresh/Ex-04-webTech_imagemap/assets/145742661/1809011c-f415-4492-b7a4-9d71648c3f0d)
![home](https://github.com/Bhuvanesh-Suresh/Ex-04-webTech_imagemap/assets/145742661/50a373bd-fee2-4124-b25e-d2c287765fad)
![hotel](https://github.com/Bhuvanesh-Suresh/Ex-04-webTech_imagemap/assets/145742661/d0843b4b-0c19-4cdd-bbd2-8a9dd7d18962)
![clothes_shop](https://github.com/Bhuvanesh-Suresh/Ex-04-webTech_imagemap/assets/145742661/bad93ad3-0d1a-4221-adc7-af98046c6580)
![salon](https://github.com/Bhuvanesh-Suresh/Ex-04-webTech_imagemap/assets/145742661/54d20947-bdbc-436f-9ff4-5260ea048630)
![temple](https://github.com/Bhuvanesh-Suresh/Ex-04-webTech_imagemap/assets/145742661/892b16ee-3ed7-48ed-8316-f19d4ad680a0)


## Result:
Thus, the program for implementing image maps using HTML is successfully executed.
