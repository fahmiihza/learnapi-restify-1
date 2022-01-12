# learnapi-restify-1
Dokumentasi Fahmi dalam belajar membuat Node.JS REST API pake Restify, Mongoose, JWT

1. Membuat file package.json
```
npm init -y
```
2. Install restify, restify-errors (untuk mengatasi error), monggose (untuk MongoDB database) dan mongoose-timestamp 
```
npm i restify restify-errors mongoose mongoose-timestamp
```
3. Install nodemon, dimana berfungsi menjalankan aplikasi yang mana ketika terjadi perubahan code pada aplikasi nodemon akan otomatis melakukan restart terhadap aplikasi yang sedang dijalankan.
```
npm i -D nodemon
```
4. Buka file package.json lalu ubah script pada bagian berikut, dari yang awalnya :
```
"scripts": {
   "test": "echo \"Error: no test specified\" && exit 1"
},
```
Sehingga menjadi seperti berikut
```
"scripts": {
   "start": "node index.js",
   "dev": "nodemon index.js",
},
```
