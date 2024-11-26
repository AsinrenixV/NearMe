# Ex04 Places Around Me
## Date: 26/11/2024

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
        <title>My City</title>
    </head>
<body>
    <h1 align="center">
        <font color="red"><b>Thrissur</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Asin Renix V (24900126)</b></font>
    </h3> 
    <center>
        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Bellijem Homes Resort" title="Bellijem Homes Resort" href="Resort.html" coords="497,449,747,521" shape="rect">
    <area target="" alt="Thrissur Zoo &amp; Museum" title="Thrissur Zoo &amp; Museum" href="Zoo.html" coords="993,266,1294,362" shape="rect">
    <area target="" alt="Hotel Niya Regency" title="Hotel Niya Regency" href="Hotel.html" coords="302,524,104" shape="circle">
    <area target="" alt="Vellanikara" title="Vellanikara" href="Temple.html" coords="1662,139,101" shape="circle">
    <area target="" alt="Sobha city Mall" title="Sobha city Mall" href="Mall.html" coords="487,11,707,105" shape="rect">
</map>
    </center>
</body>

hotel.html

</html>
<html>
    <body bgcolor="lightgreen">
        <font><h1 align="center">Hotel Niya Regency </h1> </font>
        <font align="center" size="5"><p><br>
            A jewel in the crown of Thrissur , a world of endless privileges and timeless elegance awaits you at Niya Regency. Niya Regency a solitary owned property, comprising highly talented and experienced Individuals who are all passionate about what they do. A place where you enjoy some enlightened moments while basking in the glory of our land.

            Niya Regency offers unmatched services and facilities from succulent dining to themed lounges for social events and activities for all ages and is an ideal setting for great weddings. For first class service, business, sumptuous dining and more, Niya Regency Promises to always exceed your expectations and assure satisfaction and convenience to our dear customers.
            
            From succulent dine in our Fisherman's hub, using fresh blue catch with delectable flavors of Kerala merging fusion technology, pooled with an enriched multi cuisine spot on, to themed lounges.
        </p></font>
    </body>
</html>

mall.html

<html>
    <body bgcolor="lightgray">
        <font>
            <h1 align="center">Sobha City Mall</h1>
        </font>
        <font align="center" size="5"><p><br>
            Sobha City Mall is a shopping mall in Sobha City, Puzhakkal, Thrissur City, Kerala, India. The Mall opened on 17 December 2015.[1][2] It is built on 4.7 acres (1.9 ha) land and covers an area of 450,000 square feet (42,000 m2).The mall is centrally air-conditioned and has a six screen multiplex by INOX Leisure Limited. It offers a luxury business hotel, office space, restaurants, food courts and a 600 car parking facility.
        </p></font>
    </body>
</html>

resort.html

<html>
    <body bgcolor="lightpink">
        <font><h1 align="center">Belljem Homes Resort</h1> </font>
        <font align="center" size="5"><p><br>
            On your next trip to Kerala, consider our charming Belljem Homes Your own private resort. Stationed in a tranquil housing colony in the Thrissur locality of Poothole, our home is easily accessible by either car or auto and comes equipped with ample parking space. While you are there, our spacious well-maintained villa will surely satisfy you.

            Our home comes fully furnished and well equipped with up-to-date kitchenware. We know the importance of family and friends and the commodious living area at our home should provide the perfect plot for your get-togethers. We appreciate privacy and our restful home within a real neighborhood should give you the ability to live life at your pace and soak in the local rhythm.
            We highly recommend our area for the proximity it offers to important points within the city. Additionally, we advise exploring Shoba Mall for its extensive upscale restaurant scene. We welcome food from vendors and restaurants to our home. Please confirm the availability of home delivery through online ordering platforms. Under the multiple listings below on this all-encompassing website, you can now pick the most suitable home for you. Make your home in ours. We look forward to your stay.
        </p></font>
    </body>
</html>

temple.html

<html>
    <body bgcolor="lightblue">
        <font><h1 align="center">Vellanikara </h1> </font>
        <font align="center" size="5"><p><br>
            Trikkur Mahadeva Temple is a rock-cut cave temple in Trikkur village in Thrissur District in Kerala believed to have been built in the 7th or 8th century. Being a cave temple, Buddhist and Jain monks used the site to meditate alongside the Hindu monks. It is a protected monument under the Department of Archaeology, Govt of Kerala since 1966. The temple and its premises are now owned by Paliyam Trust which is managed by Kshetra Samrakshana Samiti (Temple Protection Committee).The main deity of this temple is Lord Shiva a.k.a. Mahadeva, as the name suggests. It is believed that the huge Shivalinga here was consecrated by Lord Agni. Thus, it is believed that Lord Agni always worships Lord Shiva, and he accompanies him. Due to this belief, the idol is not carried outside for processions on rainy days.

            The temple is located on the top of the hillock inside a 30 feet long and 12 feet broad natural cave. The huge Shiva Linga is at the southern end of the cave, just above this there is a waterhole that never dries even in the hottest days during summers. The Shiva Linga faces the east, but the door of the Garbhagriha is faced towards North. The Linga is in the center, fixed on to a rectangular pedestal. There is an evergreen pond on the top of the rock. Since 1966, the temple is a protected monument under the Department of Archaeology.
        </p></font>
    </body>
</html>

zoo.html

<html>
    <body bgcolor="cyan">
        <font><h1 align="center">Thrissur Zoo & Museum</h1></font>
        <font align="center" size="5"><p><br>
            Thrissur Zoo or State Museum & Zoo, Thrissur (formerly the Trichur Zoo) is a 13.5-acre (5.5 ha) zoo that opened in 1885 in a small area called Chembukkavu, in the heart of Thrissur City, Kerala, India. It is one of the oldest zoos in the country and is home to a wide variety of animals, reptiles, and birds. The zoo compound includes a natural history museum and an art museum that showcase the social and cultural heritage of the region. The Thrissur Zoo is 2 kilometres (1.2 mi) from the Thrissur City center and is open from 10:00 AM till 5:15 PM, except on Mondays. Being one of the two Zoological Parks in the state of Kerala, it sees many visitors on a regularly. Still and video cameras are allowed in the park for a small fee.
        </p></font>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
