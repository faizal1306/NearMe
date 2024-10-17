# Ex04 Places Around Me
## Date: 17/10/2024

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
## map.html
```
<html>
    <head>
        <title>
            CUDDALORE
        </title>
    </head>
    <body>
        <h1 align="center">CUDDALORE(OVIYA N)</h1>
        <center>
            <img src="imagemap.png" usemap="#mapnew">
            <map name="mapnew">
                <area target="" alt="Silver_Beach" title="Silver_Beach" href="Silver_Beach.html" coords="616,99,775,142" shape="rect">
                <area target="" alt="Panruti" title="Panruti" href="Panruti.html" coords="263,71,61" shape="circle">
                <area target="" alt="Neyveli" title="Neyveli" href="Neyveli.html" coords="63,481,107,457,179,485,167,521,60,524" shape="poly">
                <area target="" alt="Cuddalore_Port" title="Cuddalore_Port" href="Cuddalore_Port.html" coords="589,179,41" shape="circle">
                <area target="" alt="Vadalur" title="Vadalur" href="Vadalur.html" coords="256,405,326,436,289,488,204,473,183,422" shape="poly">
            </map>
        </center>
    </body>
</html>
```
## Silver_Beach.html
```
<html>
    <head>
        <title>
            Silver_Beach
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">SILVER_BEACH</h1>
        <p>
            The 57 km long beach is <strong>one among the longest in Asia and the second-longest in the Coromandel Coast</strong>. The historical importance of Silver Beach is reflected through Fort St. David, one of the three significant forts constructed by the British Empire, which is located there. While the Pallavas and Medieval Cholas were in power, <strong>Cuddalore was an important town.</strong>

The waves on the beach are mild, making it ideal for swimming. The crabs on the shore are to be avoided, though. The sunrise on the beach is a must-have experience for every beach lover. You can see a few beach resorts close to the shore.  Although primarily a fishing port, the town today has had a number of chemical and pharmaceutical industries since SIPCOT was established.

        </p>
        <center>
            <img src="https://i.ytimg.com/vi/epKW6NxHCOw/maxresdefault.jpg" width="600" height="300">
        </center>
    </body>
</html>
```
## Cuddalore_Port.html
```
<html>
    <head>
        <title>
            Cuddalore_Port
        </title>
        <style>
            h1{
                font-size: xx-large;
                color: #de1212;
            }
            p{
                font-size: medium;
            }
            
        </style>
    </head>
    <body>
        <h1 align="center">CUDDALORE_PORT</h1>
        <p>
            <strong>Cuddalore Port </strong>is an open (anchorage) port located on the <strong>eastern coast of Tamil Nadu</strong>, at the confluence of the <strong> Uppanar (or Paravanar) rivers in the Bay of Bengal</strong>. Ships anchor offshore, and cargo is transferred through small boats or barges between the ships and the shore. The anchorage takes place 0.5 nautical miles offshore in depths of 8-10 meters. This port handles small vessels (or inland vessels), and under the Sagarmala/Inland Waterways project of the Union Ministry of Shipping, it is being developed into a full-fledged port with the extension of breakwaters, construction of cargo berths, and dredging of the channel. This development is supported by a grant from the Union Ministry of Shipping.
        </p>
        <center>
            <img src="https://tnmaritime.tn.gov.in/media/banners/slider4.jpg" 
        </center>
    </body>
</html>
```
## Panruti.html
```
<html>
    <head>
        <title>
            Panruti
        </title>
        <style>
            h1{
                font-size: xx-large;
                color: green;
            }
            p{
                font-size:large;
            }
            body{
                background-color: ivory;
            }
           
        </style>
      
    </head>
    <body>
        <h1 align="center">PANRUTI</h1>
        <p>
            Panruti is <strong>famous</strong> for  <strong>jackfruits and cashew nuts</strong>. The <strong>jackfruit grown here is exported worldwide and is very sweet</strong>. It is a business capital of Cuddalore district. Kananchavadi one of the villages in panruti taluk, famous for palm juice. It has been a great commercial area for more than 200 years. The name Panruti came from the Tamil words "Pann" and "Urutti" meaning "composing song and music", as the place is where many saints and great religious singers such as nayanmars and vainavas sung. A 150-year-old government school was built here by the British East India Company and a <strong>more-than-1000-year-old temple Veerattaneswarar temple is nearby in Thiruvathigai</strong>.
        </p>
        <img align="left"  src="https://www.nurserytoday.co.in/wp-content/uploads/2022/07/JF-Feature.jpg" width="700" height="500">
        <img align="right" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3zJ9TECEBDxWpLaLumJQ_gi-UiDIKhtE_Mw&s" width="700" height="500">
    </body>
</html>
```
## Neyveli.html
```
<html>
    <head>
        <title>
            Neyveli
        </title>
        <style>
            h1{
                font-size: xx-large;
            }
            p{
                font-size: large;
                color: black;
            }
            body{
                background-color: palegoldenrod;
            }
        
        </style>
    </head>
    <body>
        <h1 align="center">NEYVELI</h1>
        <p>
            <span style="font-size: 200%;">Neyveli – A Man-made Township  </span> <strong>    One of the best-planned townships in India</strong>, Neyveli is a small, compact city in the Cuddalore region of Tamil Nadu. Around 1935, it was discovered that copious amounts of the mineral lignite was available just a few feet below the surface of this region.In 1935, the presence of black particles was discovered by <strong>Jambulinga Mudaliar</strong>. The analysis led to the discovery of <strong>lignite</strong> reserves beneath the areas in and around Neyveli village. The Neyveli Lignite Corporation was formed as a corporate Body in 1956 by the <strong>Government of India</strong>. The mining of lignite started in 1962. The <strong>first thermal power station </strong>was commissioned in 1962 with assistance from the <strong>U.S.S.R. </strong>. NLC India Limited has been adjudged as the fastest growing Public Sector Enterprise (Navratna category) by the Hindustan Times group based on a Study/survey by Price Waterhouse Cooper under the Navratna category



        </p>
        
        <img align="left" src="https://iticampus.co.in/wp-content/uploads/2024/03/IMG_20240320_081719.webp" width="800" height="500">
        <img align="right" src="https://png.pngtree.com/background/20240420/original/pngtree-coal-mine-method-mining-engineering-coal-mine-photo-picture-image_8581357.jpg" width="600" height="500">
        
    </body>
</html>
```
## Vadalur.html
```
<html>
    <head>
        <title>
            Vadalur
        </title>
        <style>
            h1{
                font-size: xx-large;
                color: chocolate;
            }
            p{
                font-size: large;
            }
            body{
                background-color: cornsilk;
            }
        </style>
    </head>
    <body>
        <h1 align="center">VADALUR</h1>
        <p>
            <strong>Sri Arutprakasa Ramalinga Vallalar </strong>emerged from Tamil Nadu to educate people on religion, and to be inclusive of other faiths. He taught people to have tolerance, stay united, and taught communities to live in harmony. He inclusively defined spirituality and worked towards one world and united souls.<strong>Sathya Gnana Sabai (lit=Hall of True Knowledge resp. Hall of Wisdom:translit=Cattiya ñāṉa capai)</strong> is a temple constructed on 25 January 1872 by <strong>the saint Sri Raamalinga Swaamigal</strong> also known as<strong> Vallalaar </strong>in the town of<strong> Vadalur</strong> in Cuddalore district,Tamil Nadu, India. It is an octagonal structure; the sanctum sanctorum of this temple is concealed from the main hall by seven curtains which are parted only on the Thai Poosam day.All the four towers of the Chidambaram Nataraajar temple are visible from the sabha.




        </p>
        <center>
        <img src="https://thumbs.dreamstime.com/b/vadalur-vallalar-temple-architecture-vadalur-india-pink-buildings-vadalur-vallalar-temple-timings-architecture-history-vadalur-210850163.jpg" width="700" height="500">
    </center>
    </body>
</html>
```


## OUTPUT
## map.html
![image](https://github.com/user-attachments/assets/5c075ed7-d49d-4588-9195-074526bf2f1d)
## Silver_Beach.html
![image](https://github.com/user-attachments/assets/4610a27d-0695-4bcc-ac9e-9d8732298a3d)
## Cuddalore_Port.html
![image](https://github.com/user-attachments/assets/2d146bcb-873e-40db-8a52-9993ba366436)
## Panruti.html
![image](https://github.com/user-attachments/assets/22a9787d-c4d8-48b8-8009-79a2c09d9c51)
## Neyveli.html
![image](https://github.com/user-attachments/assets/aa429204-530b-4e77-ba9b-bea2c3b550c0)
## Vadalur.html
![image](https://github.com/user-attachments/assets/0e1cc334-0c42-4378-aaf3-fcb4a0ab9aac)
## RESULT
The program for implementing image maps using HTML is executed successfully.
