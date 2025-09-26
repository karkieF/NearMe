# Ex04 Places Around Me
## Date: 26/09/25

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
<html>
<head>
<title>Map of Madurai</title>
</head>
<body>
    <h2 align="center"> KARKIE F (25016839)</h2>
    <h1 align="center">MADURAI</h1>
    <center>
<img src="Screenshot 2025-09-20 141908.png" usemap="#image-map" alt="centered image" width="900" height="800">
     </center>
<map name="image-map">
    <area target="" alt="Meenakshi Amman Temple" title="Meenakshi Amman Temple" href="temple.html" coords="537,404,120" shape="circle">
    <area target="" alt="Famos Jigarthanda" title="Famous Jigarthanda" href="famous.html" coords="765,436,847,532" shape="rect">
    <area target="" alt="Madurai junction" title="Madurai junction" href="junction.html" coords="105,439,86" shape="circle">
    <area target="" alt="Meenakshi Bazaar" title="Meenakshi Bazaar" href="bazaar.html" coords="209,193,134,165,254,132,269,212,230,256,180,252,150,218,135,190,132,164,161,126,208,117,236,119,254,132,254,132" shape="poly">
    <area target="" alt="Thirumalai Nayakkar Mahal" title="Thirumalai Nayakkar Mahal" href="mahal.html" coords="818,626,719,580,767,574,810,575,861,575,892,594,907,608,919,635,904,658,860,663,817,663,785,668,748,665,726,649,714,630,719,579" shape="poly">
</map>
</body>
</html>

mahal.html
<html>
<head>

</head>

<body bgcolor="pink" align="center">
    <h1 align="center">THIRUMALAI NAYAKKAR MAHAL</h1>
        <img src="c:\Users\karki\OneDrive\Pictures\Screenshots\Screenshot 2025-09-26 221047.png" alt="Thirumalai nayakkar mahal" width="600">
        <p>
           The Thirumalai Nayakkar Mahal is a 17th-century palace located in Madurai, Tamil Nadu, India. It was built by King Thirumalai Nayakkar, who ruled Madurai from 1623 to 1655. The palace is known for its stunning architecture, which blends Dravidian and Islamic styles.
           The palace is a two-story structure with a large courtyard in the center. The walls are adorned with intricate stucco work, and the ceilings are decorated with beautiful frescoes. The palace also features several grand halls, including the audience hall, which was used by the king to meet with his subjects. 
           Today, the Thirumalai Nayakkar Mahal is a popular tourist attraction and a symbol of Madurai's rich cultural heritage. Visitors can explore the palace and learn about its history and architecture. The palace also hosts cultural events and performances, making it a vibrant part of the city's cultural scene.
           Thirumalai Nayakkar Mahal is renowned for its "majestic Indo-Saracenic architecture", blending Dravidian and Islamic styles into a grand 17th-century palace in Madurai.
           The palace features a "sprawling courtyard", intricate stucco work, and beautifully frescoed ceilings, showcasing the artistic excellence of the Nayak period.                                                                                                                                                     
       </p>
</body>
</html>

bazaar.html
<html>
<head>

</head>
<body bgcolor="brown">
    <h1 align="center">MEENAKSHI BAZAAR</h1>
    <p>
        <img src="static/bazaar.jpg" alt="Meenakshi Bazzar" width="60">

        The Meenakshi Bazaar is a bustling marketplace located near the Meenakshi Amman Temple in Madurai, Tamil Nadu, India. It is known for its vibrant atmosphere and a wide variety of goods, including textiles, jewelry, handicrafts, and local PR.
        The Meenakshi Bazaar is a vibrant marketplace that offers a unique shopping experience. Visitors can find a wide range of products, from traditional handicrafts to modern fashion items. The bazaar is also a great place to sample local street food and immerse oneself in the lively atmosphere of Madurai.
        The bazaar is a must-visit destination for anyone looking to experience the rich culture and heritage of Madurai. With its bustling stalls and friendly vendors, it provides a glimpse into the daily life of the locals and the vibrant traditions of the region.  
    </p>
</body>
</html>

junction.html
<html>
<head>

</head>
<body bgcolor="silver">
    <h1 align="center">MADURAI JUNCTION</h1>
        <img src="static/junction.jpg" alt="Madurai junction" width="600">
        <p>
                  The Madurai Junction is a major railway station located in Madurai, Tamil Nadu, India. It serves as a key transportation hub for the region, connecting various cities and towns through an extensive rail network.
            The station is equipped with modern amenities, including waiting rooms, ticket counters, and food stalls. It handles a significant volume of passenger traffic and plays a crucial role in the daily commute of thousands of people.
            Today, the Madurai Junction is a vital part of the city's infrastructure and a key gateway for travelers. It is well-connected to major cities in Tamil Nadu and beyond, making it an essential hub for both local and long-distance trains.
            Madurai Junction is a bustling railway hub in Tamil Nadu, India, connecting the city to major destinations with its extensive rail network and modern amenities.                                                                                                                                   
       </p>                                                                                                                                                
</body>
</html>

famous.html
<html>
<head>

</head>
<body bgcolor="sky blue">
    <h1 align="center">MADURAI FAMOUS JIGARTHANDA</h1>
    <p>
        <img src="static/jigarthanda.jpg" alt="Madurai Famous Jigarthanda" width="600">

            Jigarthanda is a famous cold beverage that originated in Madurai, Tamil Nadu, India. It is a delicious and refreshing drink made with a combination of milk, sugar, and a special ingredient called "nannari" syrup, which is derived from the roots of the Indian sarsaparilla plant.
            Jigarthanda is a must-try beverage for anyone visiting Madurai. It is widely available at local eateries and street vendors throughout the city. The drink is typically served chilled, making it a perfect refreshment on a hot day.                
    </p>   
</body>
</html>

temple.html
<html>
<head>

</head>
<body bgcolor="green">
    <h1 align="center">MEENAKSHI AMMAN TEMPLE</h1>
    <p>
        <img src="static/temple.jpg" alt="Meenakshi Amman Temple" width="600">

            The Meenakshi Amman Temple is a historic Hindu temple located in the city of Madurai, Tamil Nadu, India. It is dedicated to Goddess Meenakshi, a form of Parvati, and her consort, Lord Sundareswarar, a form of Shiva. The temple is renowned for its stunning Dravidian architecture, intricate carvings, and vibrant sculptures.
        The temple complex is vast, covering an area of about 14 acres, and consists of several gopurams (gateway towers), mandapams (halls), and shrines. The tallest gopuram, known as the South Tower, stands at a height of 170 feet and is adorned with thousands of colorful sculptures depicting various deities, mythological figures, and scenes from Hindu epics. The temple's main sanctum houses the idols of Meenakshi and Sundareswarar, which are made of black stone and are richly decorated with gold and precious stones.
        The Meenakshi Amman Temple is not only a place of worship but also a significant cultural and historical landmark. It attracts millions of devotees and tourists from around the world each year. The temple hosts several festivals, with the most famous being the Meenakshi Thirukalyanam, which celebrates the divine marriage of Meenakshi and Sundareswarar. This grand event features elaborate rituals, processions, and cultural performances, drawing large crowds of devotees and visitors.
        The Meenakshi Amman Temple is a magnificent example of South Indian temple architecture and a testament to the rich cultural heritage of Tamil Nadu. It continues to be a vibrant center of religious and cultural activities, preserving ancient traditions while welcoming modern-day devotees and tourists alike.
    </p>

    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (11).png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (12).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
