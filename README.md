Download Link: https://assignmentchef.com/product/solved-cities-connections-and-distances-and-load-txt-file
<br>
<p class="ui header product-top-header" title="Cities, Connections and Distances, and load.txt file Solution">In Section 9.3 of the textbook, the vertices were 7 cites. The edges represented the connections between one city and another. The weights represented the distance in miles between the two cites connected by an edge.

You choose the cities and connections. Include enough cities and connections that I will be able to meaningful test your program.

Make the distances between the cities realistic. You can use Google Maps and round off the distance.

These vertices, edges and weights should be stored in a text file named load.txt, which you will turn in with your assignment. When your program starts, it will use the load.txt file to load the vertices, edges and weights into your program.

Readme.txt file

Document in a readme.txt file (which you will turn in with your assignment) the cities and connections you choose, and the distances assigned to each connection. When describing connections, separately list direct connections from through connections.

A direct connection means you can fly from the departure city to the destination city without having to first fly through another city. For this type of connection, you list the departure city, the destination city, and the distance between the two cities.

A through connection means you can fly from the departure city to the destination city, but you first have to first fly to at least one another city. For this type of connection, you list the departure city, the destination city, each city between the departure city and the destination city which is part of the connection, and the total distance between the departure city and the destination city.

I need this information to efficiently test your program. Therefore, I will deduct points for this requirement not being met.

Project Startup

As mentioned above, when your program starts, it will use the load.txt file to load the vertices, edges and weights into your graph. The program then will display a menu, and prompt the user to enter a choice:

1. Choose departure city

2. Exit

You may assume the user enters 1 or 2. No input validation is required.

If the user chooses 2. Exit, then the program ends.

Program lists Departure Cities, and user chooses

If the user choose 1. Choose departure city, then the program lists the cities. The cities don’t have to be listed in any particular order. However, an ascending letter or number should be to the left of each city so the user can use that letter or number to choose a city. For example:

1. Chicago

2. Denver

3. Atlanta

(and so on)

Choose city:

or

A. Chicago

B. Denver

C. Atlanta

(and so on)

Choose city:

You may assume the user enters a valid number or letter; no input validation is required.

Program lists Destination Cities, and user chooses

Once a user chooses a city, then the program displays “Destination cites” followed by all of the cities except the departure city. Again, the cities don’t have to be listed in any particular order, but an ascending letter or number should be to the left of each city so the user can use that letter or number to choose a city.

You again may assume the user enters a valid number or letter; no input validation is required.

If no connection

Once the user chooses a destination city, if there is no direct or through connection between the departure and destination cities, then the program will output:

No connection between [name of departure city] and [name of destination city]

Press any key to return to menu.

After the user presses the any key (we’ll assume the user has an any key on their keyboard :-), then the menu which displayed at the program startup (1. Choose departure city 2. Exit) will re-display and the program will continue as stated above.

If connection, direct connection?

If there is some connection between the departure and destination cities … the next issue is whether there is a direct connection between the departure and destination cities.

If there is no direct connection between the departure and destination cities (in other words, only a through connection), then the program will output:

No direction connection between [name of departure city] and [name of destination city]

Then the program will output the information in the next section (If connection, through connection?).

If there is a direct connection between the departure and destination cities (there presumably only would be one), then the program will output:

Direct connection between [name of departure city] and [name of destination city]

Then the program will output the information in the next section (If connection, through connection?).

If connection, through connection?

If there is no through connection between the departure and destination cities (in other words, only a direct connection), then the program will output:

No through connection between [name of departure city] and [name of destination city]

Press any key to return to menu [after which the menu displayed at program startup is re-displayed]

If there is at least one through connection between the departure and destination cities, then the program will output all through connections (there may be more than one) in ascending order of distance, listing the intermediate cities, as follows:

Through connection between [name of departure city] and [name of destination city] via [list name or names of cities in between] – [number of miles] miles

After this listing, the program prompts the user to “Press any key to return to menu”, after which the menu displayed at program startup is re-displayed.

<span class="kksr-muted">Rate this product</span>