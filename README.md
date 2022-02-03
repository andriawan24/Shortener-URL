# Shortener-URL
Build my own shortener link using Node JS, if you want to try you can go to [this page](https://shortener.andriawan24.xyz/)

### Routes
* ```/shorten``` use POST method<br />Create unique short URL to redirected to the real link
* ```/:url``` use GET method<br />Replace the ```:url``` with your short link generated before

### Library
* body-parser
* ejs
* express
* mongoose
* shortid
* valid-url
