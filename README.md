Warhol_Weather
==============
Please read this, it will help answer all your questions.


So, inorder for this to work you need a couple of things:

1.) A Pebble Watch
2.) A Smart Phone (Android or Apple)
3.) A webserver you can toss php files
3a.) If you don't have a webserver maybe a friend does or you could ask someone nicely to use their weather file
4.) A Free account from Forecast IO
4a.) To Create your free account just head to https://developer.forecast.io/ and click register...then COPY YOUR API KEY LISTED THERE.


Now head over to:
https://cloudpebble.net/ide/

Click Import Project (create a free account if you don't have one):

Click Import from Github:

Past my url into there:
https://github.com/nbash/Warhol_Weather

Once that loads click on main.c and scroll to the bottom and change line 307 to point to your weather.php file that is available here

https://github.com/nbash/Warhol_Weather/blob/master/server/weather.php

make sure you edit the weather.php file to change the API_KEY_HERE to your API key from Forecast IO.

now that you have your weather.php file modified and hosted, you have this project imported into cloudpebble, just copile it, hit create short link and go to that link from your phone.
