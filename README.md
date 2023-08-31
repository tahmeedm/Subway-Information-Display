# SubwayDisplay

![Subway_Information_Display](https://github.com/tahmeedm/Subway-Information-Display/assets/113798776/39f3656c-84f8-4846-8a75-5338889ff7e2)

This information display is the easiest way to access live news and weather in any city!

## Key Features
1. The login screen prompts the user for a 'City Code' from openweathermap.org for live weather in that city & a keyword which can be any word and the news will display news related to that keyword.
   
![logingui](https://github.com/tahmeedm/Subway-Information-Display/assets/113798776/7a1a4051-0992-4d9d-be1b-bfbe8fa6bf1e)

3. Once the "login" button is pressed, there are three generated GUI sections: Advertisements(top left), Weather(top right) &  News(bottom).

4. The weather section parses the HTML file of openweathermap.org using regular expressions & synchronizes the weather icons to the city's live weather. (Ex. snowy days display a snowflake, cloudy days show sun with clouds, etc.):

![carbon](https://github.com/tahmeedm/Subway-Information-Display/assets/113798776/e6347897-04e4-45d0-8529-fa43fd2b0f64)

4. The news section utilies the newscatcher.com API which provides live news based on a keyword. It scrolls through the screen continously.


## How to Use
1. Java JDK 17 needs to be installed to run the program.
2. Simply input a city code from openweathermap.org/city. (Ex. 5913490 for Calgary, Alberta), & input a keyword for news.
3. Click login!
