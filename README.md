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
map.html

<html>
    <head>
        <title>
            sample page
        </title>
    </head>
    <body>
        <h1 
            align="center">
            PANRUTI
        </h1>
         <h1 align="center">
            RITHIKA S (25015482)

         </h1><img src="MY MAP.png" usemap="#image-map">
      
          

<map name="image-map">
    <area target="" alt="SRI RANGANATHAR TEMPLE" title="SRI RANGANATHAR TEMPLE" href="temple.html" coords="1767,530,1889,602" shape="rect">
    <area target="" alt="GANDHI PARK" title="GANDHI PARK" href="park.html" coords="635,196,595,220,605,248,685,248,690,213" shape="poly">
    <area target="" alt="SHRI VEERATTANESWAR KOVIL" title="SHRI VEERATTANESWAR KOVIL" href="holy place.html" coords="1269,679,80" shape="circle">
    <area target="" alt="SRI SOMANATHA SWAMI TEMPLE" title="SRI SOMANATHA SWAMI TEMPLE" href="house of god.html" coords="466,39,581,104" shape="rect">
    <area target="" alt="SHREI DHANVANTRI TEMPLE" title="" href="house of prayer.html" coords="425,188,378,226,405,246,442,253,493,231,473,205" shape="poly">
    <area target="" alt="ALEEF GARDEN RESTAURANT" title="ALEEF GARDEN RESTAURANT" href="hotel.html" coords="667,558,99" shape="circle"
</map>



    </body>
</html>


hotel.html


<html>
    <head>
        <title>
            NATIVE
        </title>
    </head>
    <body bgcolor="red">

        <h1 align="center">
            <font color="maroon">
                <b>PANRUTI</b>
            </font>
        </h1>
        <h2 align="'center">
            <font color="black">

            <b>ALEEF GARDEN RESTAURANT</b>
            </font>
        </h2>
        <hr size="4" color="cyan">
        <pre align="justify">
            <font face="Georgia" size="4"></font>


Aleef Garden Restaurant offers a delightful culinary experience in Panruti, 
combining traditional South Indian flavors with diverse international dishes in 
a welcoming setting.

1. Location and Ambiance

        Aleef Garden Restaurant is situated at 198, Link Road, Panruti, Cuddalore,
Tamil Nadu 607106                                                                                    

    
 . The restaurant features an exotic and inviting atmosphere that appeals to 
 families, friends, and casual diners alike 
. Guests can enjoy both indoor and rooftop dining options, offering a relaxed 
environment suitable for a variety of occasions 

2. Cuisine and Specialty Dishes
      
         The restaurant serves a wide range of dishes, including South Indian, 
Indian, Arabian, and Chinese cuisines 
. Popular dishes include chicken biryani, tandoori chicken, fried chicken, prawn 
thoukku, and Chettinad-style chicken
 . Both vegetarian and non-vegetarian options are available, with recipes passed 
 down through generations and adapted for contemporary tastes 


3. Customer Experience and Service
        
            Aleef Garden Restaurant is known for its courteous and helpful staff, 
providing attentive service that enhances the dining experience 
Restaurant Guru
. With a Google rating of 4.2 out of 5 based on visitor reviews, many guests 
appreciate the quality of food and the efficient service 
Restaurant Guru
. Online delivery through platforms like Zomato makes it convenient for patrons 
to enjoy the restaurant’s offerings from home 



 </pre>
 <img src="aleef.png" usemap="#image-map">
 <map name="image-map"></map>
 </body>
 </html>

house of prayer.html

<html>
    <head>
        <title>
            NATIVE
        </title>
    </head>
    <body bgcolor="brown">

        <h1 align="center">
            <font color="pink">
                <b>PANRUTI</b>
            </font>
        </h1>
        <h2 align="'center">
            <font color="white">

            <b>SHREI DHANVANTRI TEMPLE</b>
            </font>
        </h2>
        <hr size="4" color="orange">
        <pre align="justify">
            <font face="Georgia" size="4"></font>

            The Shree Dhavantri Temple, dedicated to Lord Dhanvantari, is a 
revered place embodying Ayurveda's principles and offers compelling insights 
into health, spirituality, and culture.

1. Historical Significance

        The Shree Dhavantri Temple, associated with Lord Dhanvantari, the 
deity of Ayurveda and health, holds a significant place in the healing traditions of India. Lord Dhanvantari is celebrated as an incarnation of Lord Vishnu, credited with imparting the knowledge of Ayurveda to humanity. The temple marks 
the location where devotees seek blessings for recovery from ailments and hope 
for overall health and wellness This connection emphasizes the temple's role as a spiritual and medical 
center for many practitioners of Ayurveda and traditional healing.

2. Architectural Features

        The temple features traditional South Indian temple architecture, 
characterized by a majestic 'Rajagopuram' (gateway tower), decorated with intricate carvings that symbolize the divine and healing aspects of 
Lord Dhanvantari. The sanctum sanctorum houses a revered idol of Dhanvantari, depicted holding a pot of 'amrita' (nectar of immortality), which symbolizes 
health and healing  The design often incorporates motifs of lotus flowers and medicinal plants, 
reinforcing its association with Ayurveda and its holistic healing philosophies.


3. Rituals and Offerings
Daily rituals at the temple include special poojas dedicated to LordDhanvantari, incorporating traditional chanting and offerings of ayurvedic 
'prasad' (sacramental food). Notably, during festivals like Dhanteras (Dhanvantari Jayanti), large gatherings attract devotees who participate in special ceremonies seeking wellness and prosperity . The temple is known for its unique offerings, such as 'Mukkudi'—a 
sacred prasadam believed to have healing properties, exemplifying the temple's commitment to health 

4. Festivals Celebrated
       The temple witnesses vibrant festivals, notably Dhanvantari Jayanti, which 
celebrates the birth of Lord Dhanvantari and emphasizes the importance of Ayurveda in contemporary society. This festival includes processions, 
special prayers, and community gatherings, further enhancing a sense of 
unity among devotees 

. Additionally, the temple also hosts various cultural activities linking health and spirituality, encouraging a holistic approach to well-being among visitors.
The Shree Dhavantri Temple not only serves as a place of worship but also standsas a beacon of Ayurvedic wisdom, attracting individuals seeking both spiritual and physical healing.


</pre>

<img src="shri dhanvandhri temple.png" usemap="#image-map">
</body>
</html>


house of god.html

<html>
    <head>
        <title>
            NATIVE
        </title>
    </head>
    <body bgcolor="pink">

        <h1 align="center">
            <font color="purple">
                <b>PANRUTI</b>
            </font>
        </h1>
        <h2 align="'center">
            <font color="white">

            <b>SRI SOMANATHA SWAMI TEMPLE</b>
            </font>
        </h2>
        <hr size="4" color="white">
        <pre align="justify">
            <font face="Georgia" size="4"></font>

1. Location and Access

         Sri Somanatha Swami Temple is situated on Ponnusamy Street, Thorapadi, 
Panruti, Tamil Nadu (607106). It is approximately 1.09 kilometers from Panruti 
Railway Station, making it easily accessible by rail. The temple serves as a 
spiritual center for devotees from Panruti and surrounding areas.

2. Deity and Worship

      The temple is devoted to Sri Somanatha Swami (Lord Shiva). Devotees 
worship the deity for spiritual benefits, believed to fulfill wishes and 
provide relief from sins. Regular poojas and rituals take place, and the 
temple maintains specified darshan timings for open worship, encouraging daily 
devotional practices.


3. Temple Architecture and Features
       
        While specific historical construction details in Panruti are limited, 
the temple is noted as a traditional Shaivite shrine with typical South Indian 
temple architecture. Features include a sanctum for the main deity, small 
subsidiary shrines, and spaces for conducting rituals. The sacred environment 
reflects centuries of devotion in the region.

4. Visitor Experience and Reviews

     The temple has an average rating of 4.2 out of 5 stars based on multiple 
visitor reviews, highlighting its spiritual ambiance. Visitors appreciate the 
serene atmosphere, spiritual significance, and proximity to local amenities. 
The temple plays an integral role in maintaining religious and cultural traditions
 in Panruti.

 </pre>

 <img src="Sri somanatha swami temple.png" usemap="#image-map">
 </body>
 </html>


 holy place.html


 <html>
    <head>
        <title>
            NATIVE
        </title>
    </head>
    <body bgcolor="pink">

        <h1 align="center">
            <font color="'white">
                <b>PANRUTI</b>
            </font>
        </h1>
        <h2 align="'center">
            <font color="yellow">

            <b>SHRI VEERATTANESWAR KOVIL</b>
            </font>
        </h2>
        <hr size="4" color="cyan">
        <pre align="justify">
            <font face="Georgia" size="4"></font>

Shri Veerattaneswar Kovil, Panruti

Shri Veerattaneswar Kovil, located in the serene village of Thiruvathigai near
 Panruti, Tamil Nadu, is a revered Hindu temple dedicated to Lord Shiva. Known 
 for its spiritual significance and architectural beauty, this temple holds a 
 special place in the hearts of devotees.

Deity and Significance:
   
       Lord Shiva is worshipped here as Veerattaneswarar, symbolizing his
fierce form. The temple is associated with the legend of Lord Shiva destroying 
the demon Tripurasura, representing the triumph of good over evil. His consort, 
Goddess Parvati, is worshipped as Thiripurasundari, embodying grace and compassion.

Architectural Marvel: 

      The temple showcases stunning Dravidian architecture, with intricately 
carved pillars, majestic gopurams (towering gateways), and a serene 
ambiance that invites devotees to immerse themselves in prayer and 
meditation.

Spiritual Beliefs: 

       It is believed that visiting this temple helps devotees overcome 
arrogance, karmic burdens, and illusions, leading them toward spiritual 
liberation. The temple is also said to grant blessings akin to visiting 
Lord Shiva's celestial abode, Kailash.

Location and Accessibility: 

       Situated just 2 kilometers east of Panruti town, the temple is easily 
accessible and attracts visitors from across Tamil Nadu and beyond.
This sacred site is not just a place of worship but also a testament to 
Tamil Nadu's rich cultural and spiritual heritage. A visit to Shri Veerattaneswar 
Kovil offers a profound sense of peace and divine connection.
   
     </pre>
     <img src="sri veerataneshwara temple.png" usemap="#image-map">



park.html

<html>
    <head>
        <title>
            NATIVE
        </title>
    </head>
    <body bgcolor="purple">

        <h1 align="center">
            <font color="'white">
                <b>PANRUTI</b>
            </font>
        </h1>
        <h2 align="'center">
            <font color="yellow">

            <b>GANDHI PARK</b>
            </font>
        </h2>
        <hr size="4" color="orange">
        <pre align="justify">
            <font face="Georgia" size="4"></font>
1. History and Significance
         
       Gandhi Park is dedicated to the memory of Mahatma Gandhi, celebrating his 
contributions to India's independence and ideals of peace. One of its central 
attractions is a five-foot-tall statue of Gandhi near the Four-Road junction in 
Panruti, crafted from an amalgamation of five precious metals, 
including approximately 40 kg of gold, making it not only symbolic but also valuable.
The park serves as a cultural and historical landmark, reflecting the town’s
 admiration for the Father of the Nation.


2. Attractions and Features

     The park offers a variety of facilities for visitors seeking relaxation and 
outdoor activities. It features well-maintained gardens, open green spaces, 
walking and jogging trails, and seating arrangements for families. The area 
also includes designated spots for yoga, meditation, and children's play areas, 
making it an ideal destination for people of all ages 
The combination of greenery and the historical statue creates a tranquil ambiance 
for reflection and recreation.


3. Visiting Experience and Tips

       The best time to visit is early morning or late evening when the weather is
pleasant, particularly during October to March 
. Visitors are advised to wear comfortable shoes for walking, carry water, and
 respect the park rules without plucking flowers or damaging the greenery. 
 The park is accessible by car, bus, or train, with parking and local 
 transportation options available to reach the site easily 
. These practical tips ensure a smooth and enjoyable experience in the park.


4. Nearby Attractions and Tourism

        Located in Panruti, a town known for cashews and jackfruit, 
the park is close to other attractions such as the Panruti Market, Periyar Park, 
and local temples
 . Visitors can combine a trip to Gandhi Park with cultural experiences, 
 shopping for regional produce, or exploring historical and spiritual landmarks 
 nearby, making it a perfect stop in a broader Panruti tour.
In summary, Gandhi Park in Panruti blends history, culture, and natural beauty, 
providing a peaceful environment for relaxation, learning, and family activities. 
It is a must-visit destination for both locals and tourists seeking inspiration and 
tranquility in Tamil Nadu
</pre>
<img src="gandhi park.png" usemap="#image-map">
</body>
</html>


temple.html


<html>
    <head>
        <title>
            NATIVE
        </title>
    </head>
    <body bgcolor="blue">

        <h1 align="center">
            <font color="'black">
                <b>PANRUTI</b>
            </font>
        </h1>
        <h2 align="'center">
            <font color="pink">

            <b>SRI RANGANATHAR TEMPLE</b>
            </font>
        </h2>
        <hr size="4" color="red">
        <pre align="justify">
            <font face="Georgia" size="4"></font>


1. History
The Sri Ranganathar Temple was constructed by the ruler of Thiru Vathigaland draws inspiration from the iconic 
Srirangam Ranganathaswamy Temple.
Positioned between the Kedilam and Pennai rivers, the temple reflect
a rich lineage associated with Vaishnavite traditions. Historically,
it has served as a center for spiritual gatherings, religious education,and 

devotional practices, establishing itself as a focal point of faithfor local communities. The temple’s foundation highlightsthe 
ruler’s 
commitment to devotion and cultural patronage, emphasizing Lord Ranganathar’s prominence in the region.
2. Architecture and Deities
The temple features a classical Dravidian style, with the sanctum housing
Lord Ranganathar in the Sayana Kolam (reclining) posture on Adisesha.
Alongside the main deity, consorts Sridevi Thayar and Bhoodevi Thayar reside in
the same sanctum, while a separate sannidhi is dedicated to Goddess RanganayakiThayar. The layout is designed to create a peaceful ambience, 
enhanced by its riverside location, reflecting both spiritual serenity and traditional temple aesthetics, with intricate carvings and ornamental
 details admired by devotees
 and tourists alike.
3. Rituals and Festivals
The temple maintains a vibrant schedule of daily pujas and annual festivals, 
including Brahmotsavam, Masi Teppa, and Vaikunta Ekadasi. Devotees participate in
these ceremonies to seek divine blessings for prosperity, health, and overall wellbeing. The traditional dress code and ritualistic practices are strictly
followed, emphasizing devotion, discipline, and adherence to Vaishnavite customs. The temple attracts a significant number of pilgrims, particularly during
 the peak months from September to March, when festivals are celebrated with grandeur.
4. Cultural Significance and Accessibility
As a cultural landmark, the temple plays a pivotal role in preserving Vaishnavite 
traditions, fostering community cohesion, and supporting spiritual education in 
Panruti. Strategically located near the Panruti bus stand and railway station, it 
is easily accessible to both local visitors and pilgrims from other regions. 
The integration of scenic rivers, age-old traditions, and active religious life 
makes the temple an essential destination for devotees seeking spiritual solace 
and a deeper connection with Tamil Nadu’s cultural heritage.

        </pre>
 </h1><img src="sri ranganatha swami temple.png" usemap="#image-map">

    </body>
</html>

```

## OUTPUT


![alt text](<jabilie/mapapp/static/Screenshot (31).png>)


![alt text](<jabilie/mapapp/static/Screenshot (32).png>)

![alt text](<jabilie/mapapp/static/Screenshot (33).png>)

![alt text](<jabilie/mapapp/static/Screenshot (34).png>)
![alt text](<jabilie/mapapp/static/Screenshot (35).png>)


![alt text](<jabilie/mapapp/static/Screenshot (36).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
