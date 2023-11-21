# Ex-06 Places Around Me
## Name: P.Loknaath
## Reference Number: 23004546
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
            <font color="red"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>P Loknaath (23004546)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="#MyCity">
                <area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
                <area shape="circle" coords="570,230,50" href="school.html" title="Narayana CBSE School">
                <area shape="circle" coords="680,400,80" href="hall.html" title="Soundrapandian Party Hall">
                <area shape="circle" coords="1260,540,65" href="gym.html" title="Shredded Gym Society">
                <area shape="circle" coords="970,160,1100,220" href="temple.html" title="Varahi Amman Temple">
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
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="red"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Madhanandhapuram</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Madanandhapuram is a small locality in Kunnattur Taluk in the Chennai district of Tamil Nadu. Pallavaram railway station and Chromepet railway station are the nearby railway stations to Madanandapuram. Madhanandapuram bus stop, Cycle Stand bus stop, Moulivakkam bus stop, and St Mary's School bus stop are the nearby bus stops in this locality. Chennai Bypass road, Madha Nagar Main road, Mugalivakkam Main road, Wireless Station road, Ramasamy Nagar Main road, and Kundrathur Main road are well-connected roads and also the highways are well-developed. Saveetha School Of Engineering, The Psbb Millennium School, and Sivanthi Matric School are the nearby schools and colleges situated in Madanandapuram. Annai Hospital, Yasotha hypnosis academy, and Hriday Hospital are the nearby hospital's medical centers situated in this locality. 
            </font>
        </p>
    </body>
</html>
~~~
### school.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="black"><b>Madhanandhapuram</b></font>
        </h1>
        <h3 align="center">
            <font color="brown"><b>Narayana CBSE School</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Narayana Group of Schools Madhanandapuram is an all-inclusive educational institution that provides a complete learning experience for its students. From early childhood education to senior secondary, we offer a wide range of programmes and services that help students develop their academic, social, and emotional skills.
            </font>
        </p>
    </body>
</html>
~~~
### gym.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="orange"><b>Madhanandhapuram</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Shredded Gym Society</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Shredded Society Fitness Studio in Chennai is one of the leading businesses in the Dance Classes. Also known for Gyms, Dance Classes, Yoga
Classes, Women Gyms, Fitness Centres, Weight Loss Centres, Unisex Gyms, Men Gyms and much more. Find Address, Contact Number, Reviews &
Ratings, Photos, Maps of Shredded Society Fitness Studio, Chennai.
            </font>
        </p>
    </body>
</html>
~~~
### hall.html
~~~
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
            <font color="blue"><b>Madhanandhapuram</b></font>
        </h1>
        <h3 align="center">
            <font color="magenta"><b>Soundrapandian Party Hall</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Soundrapandian Kalyana Mandapam is a wedding venue in Chennai. They make certain that all of their customers are satisfied with the services provided at this location. They offer a variety
of wedding packages that include a variety of services, such as multi-event space, guest accommodation, prefabricated decor, multi-cuisine in-house catering, and so on, all of which can be
customised to fit your budget and needs. It is an ideal location for your grand and regal event. Whether you're planning an intimate reception or a large Indian wedding reception, their team
of professionals is ready to make your day unforgettable.
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
    <body bgcolor="orange">
        <h1 align="center">
            <font color="red"><b>Madhanandhapuram</b></font>
        </h1>
        <h3 align="center">
            <font color="green"><b>Varahi Amman Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p alig="justify">
            <font face="Georgia" size="5">
                Varahi Amman kovil is a hindu temple located in Chennai, Tamil Nadu. The average rating of this place is 4.50 out of 5 stars based on 69 reviews. The street address of this place is PHASE-1, 5th St, nearby Jaimaruthi kalyana mandapam, Annai velankanni nagar, Madhanandapuram, Chennai, Tamil Nadu 600125, India. It is about 0.86 kilometers away from the Ramapuram railway station.
            </font>
        </p>
    </body>
</html>
~~~
## Output:
![map](https://github.com/Loknaath-sec/Ex-04-webTech_imagemap/assets/145742558/9f9165b5-7919-4255-95cd-244da01e00cf)
![home](https://github.com/Loknaath-sec/Ex-04-webTech_imagemap/assets/145742558/ec46d4ad-de66-4559-9b1d-ce9422778991)
![school](https://github.com/Loknaath-sec/Ex-04-webTech_imagemap/assets/145742558/040c6c6f-b181-40a9-9001-fa3e2e050355)
![gym](https://github.com/Loknaath-sec/Ex-04-webTech_imagemap/assets/145742558/9d5a91ec-c40a-4242-b9a8-c4dbe2a7dee1)
![hall](https://github.com/Loknaath-sec/Ex-04-webTech_imagemap/assets/145742558/9cdc022f-156b-4f5f-8f39-c94b3314f3cf)
![temple](https://github.com/Loknaath-sec/Ex-04-webTech_imagemap/assets/145742558/e97401bd-d774-419a-8f79-4cb1fbd42777)


## Result:
Thus, the program for implementing image maps using HTML is successfully executed.
