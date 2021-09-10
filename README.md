# Walmart-Scraper
This app is used to track the Walmart products stock and prices. </br> 

## Features

- Data from Walmart Website. 
- Login/Signup option available. You can also add different users and view all of them under users section.
- Changing password facility available. 
- Add new Product by pasting the link of the product from Walmart Website.
- Search Product by entering product SKU
- Track In-Stock, Out-Stock, Price Changed under Walmart section.



## DashBoard Interface 
![Dashboard](https://user-images.githubusercontent.com/47499505/121127812-f98e0700-c847-11eb-9fb9-49c5b988735c.png)

## Stack Used
- <b>Front End</b> : HTML5, CSS3, EJS - Embedded JavaScript templates.
- <b>Back End</b> : Node.js, Express.js, MongoDB.
- <b>NPM Packages</b> : Express, Mongoose, Async, Body-parser, Cheerio, Connect-flash, Crypto, Dotenv, Ejs, Express-session, Method-override, Nodemailer, Passport, Passport-local, Passport-local-mongoose, Path, Puppeteer

## Getting Started

- Clone the repository

```bash
https://github.com/jatin9909/Walmart-Scraper.git
```

> Create `config.env` file and add credentials (see `config.env` for reference).

- First install node modules listed above:

```
npm install <package-name>
```

- Run MongoDB using
```
mongod
```

- Run app.js using
```
node app.js
``` 
or 
```
nodemon
``` 
(you need to install it seperatley using npm install nodemon)


- Open local host in your machine
```
localhost:3000
```

### Note
Item will be shown Out of stock if the item is not sold by Walmart directly and In stock if Item is directly sold by Walmart. 
