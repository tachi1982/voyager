#VOY∀GER

This project is solving the __Adopt a Spacecraft: Voyager 1 challenge__.

The main purpose of our project is to know the Solar System, using a kind of "RPG" game based on a web application. Our web app. makes use of Voyager's data. The Voyager spacecraft is the only artifact that is about to reach the outer edge of the heliosphere. The Voyager has provided us unprecedented opportunities to know the outer Solar System. In our app., people can learn the planets in the Solar System through a story involved in a virtual Voyager. The story is as follows:  A boy lives on an imaginary "habitable" planet outside our system. One day, a virtual Voyager visits this planet all the way from the Solar System. The boy first knows the existence of other (habitable) planets from the "Voyager", in which "AI" is installed. Then he decides to leave for and explore other planets with the "Voyager" in order to seek for other peoples. Although sometimes, he faces on some troubles and difficulties, he can get over them with the help of the "Voyager". During the voyage across the Solar System, he can know what each planet is like.

Then, let's enjoy our story with us. "Bon Voyage !"


#How to Test backend API

1. You have to prepare a MYSQL + PHP + Web server somewhere.

2. Make "pvoyager" database on your MYSQL server and run dbResources/pvoyager.sql.
ex.) mysql -u &lt;username&gt; -p pvoyager < dbResources/pvoyager.sql

3. Put dbResources/api.php and dbResouces/config.php on your Web server.

4. Open above config.php and write your configuration for your MYSQL server.

5. Open dbResources/apitest.html and rewrite "api.php" to the location of your api.php.

6. Open dbResources/apitest.html on your browser.

note) HTML/js/pvoyager.js also has a hardcoding URL for the api.
