# Ex04 Places Around Me
## Date: 22/03/24

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
~~~
<html>
    <head>
        <title align="center">THIRUVANNAMALAI</title>
    </head>
    <body>
        <h1 align ="center">THIRUVANNAMALAI</h1>
        <h2 align ="center">PREETHI.B [212221220040]</h2>
    </body>
</html>

<img src="Screenshot 2024-03-21 141746.png" width="1500" height="550" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="Kilnathur" title="Kilnathur" href="Kilnathur.html" coords="377,203" shape="rect">
    <area target="_self" alt="Arunachaleswarar" title="Arunachaleswarar" href="Arunachaleswarar.html" coords="200,218" shape="poly">
    <area target="_self" alt="Reliance" title="Reliance" href="Reliance.html" coords="380,89,NaN" shape="circle">
    <area target="_self" alt="KuberaLingam" title="KuberaLingam" href="Kubera.html" coords="173,40" shape="rect">
    <area target="_self" alt="Nassipatti" title="Nassipatti" href="Nassipatti.html" coords="339,523,NaN" shape="circle">
</map>

<html>
<body bgcolor="pink">
    <head>
        <h1 align="center"> Thiruvannamalai</h1>
        <h2 align="center"> Arunachaleswarar Temple</h2>
    </head>
<p align="center" spacing="center">Built in the traditional Dravidian style of architecture, the temple is believed to be the eighth-largest Hindu temple in the world. The temple complex houses many halls and the most popular one is the thousand-pillared hall, which was constructed during the Vijayanagar period (1336-1646).</p>
</body>
</html>

<html>
<body bgcolor="blue">
    <head>
        <h1 align="center">Thiruvannamalai</h1>
        <h2 align="center"> Kilnathur</h2>
    </head>

<p align ="center">Kilnathur is a village located in the Thiruvannamalai district of Tamil Nadu, India. Thiruvannamalai is known for its famous Arunachaleswarar Temple, one of the largest temple complexes in India dedicated to the Hindu god Shiva. Kilnathur, like many villages in the district, likely has its own local economy and culture, but I don't have specific information about it. If you're looking for details about Kilnathur, you might want to explore local resources or news outlets for more information.</p>
</body>
</html>

<html>
<body bgcolor="cyan">
    <head>
        <h1 align="center">Thiruvannamalai</h1>
        <h2 align="center"> Kubera Lingam</h2>
    </head>

<p align="center">The Kubera Lingam is a sacred lingam (an abstract representation of the Hindu deity Shiva) located in the Arunachaleswarar Temple in Thiruvannamalai, Tamil Nadu, India. It is believed to be associated with the Hindu god Kubera, who is considered the god of wealth and prosperity in Hindu mythology. Devotees visit the Arunachaleswarar Temple to offer prayers and seek blessings from the Kubera Lingam for wealth and prosperity in their lives. T</p>
</body>
</html>

<html>
<body bgcolor="peach">
    <head>
        <h1 align="center"> Thiruvannamalai</h1>
        <h2 align="center"> Nassipatti</h2>
    </head>
<p align="center">Nassipatti is a small village located in the Thiruvannamalai district of Tamil Nadu, India. Like many villages in the region, it likely has its own local economy primarily based on agriculture and small-scale industries. Thiruvannamalai district is known for its spiritual significance due to the presence of the Arunachaleswarar Temple, which attracts pilgrims from across the country. However, I don't have specific information about Nassipatti itself. If you're looking for more details about Nassipatti, local resources or news outlets in the region might have more information.</p>
</body>
</html>

<html>
<body bgcolor="orange">
    <head>
        <h1 align="center">Thiruvannamalai</h1>
        <h2 align="center"> Reliance</h2>
    </head>
<p align="center">Reliance Industries, led by Mukesh Ambani, is one of India's largest conglomerates with interests in various sectors including petrochemicals, refining, oil & gas exploration, telecommunications, and retail. As of my last update, I don't have specific information about Reliance's presence in Thiruvannamalai, but it's possible they have operations or investments in the region given their extensive nationwide presence.</p>
</body>
</html>
~~~
## OUTPUT
![alt text](<Screenshot 2024-03-22 133928.png>)
![alt text](<Screenshot 2024-03-22 134303.png>)
![alt text](<Screenshot 2024-03-22 134523.png>)
![alt text](<Screenshot 2024-03-22 134655.png>)
![alt text](<Screenshot 2024-03-22 134855.png>)
![alt text](<Screenshot 2024-03-22 135008.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
