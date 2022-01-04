# Shortener-URL
Build my own shortener link using Node JS, untuk percobaan secara langsung bisa masuk ke [halaman ini](https://shortener.andriawan24.xyz/)

### Routes
* ```/shorten``` use POST method
Create unique short URL to redirected to the real link
* ```/:url``` use GET method
Replace the ```:url``` with your short link generated before

### Library
* body-parser
* ejs
* express
* mongoose
* shortid
* valid-url
