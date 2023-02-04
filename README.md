# URL Shortner Web Applicaiton <img align="left" alt="lemon Technology" width="90px" style="padding-right:10px;" src="https://user-images.githubusercontent.com/99763066/216785724-05efc1ce-0de9-4e69-bf03-9709c133f940.png" />


##

## Project Setup 

> Clone the Project . Execute npm install on the same path of your root directory of the downloaded Project.

> Create a .env file in the root directory and add the following enviroment variable .

```javascript
PORT = 3000
```

## Running Screen Shot of Project 



![Screenshot 2023-02-04 164147](https://user-images.githubusercontent.com/99763066/216785455-5d98dc89-70ad-41ad-baf6-d02f5aff020c.jpg)




## How Working is Done - 

> Dependencies we used to make project work .
```json
"dependencies": {
    "dotenv": "^16.0.3",    //dotenv it helps to create the enviroment variable
    "ejs": "^3.1.8",        //EJS simply stands for Embedded Javascript, let us generate HTML with plain javascript
    "express": "^4.18.2",   // Lets us create a web application framework. 
    "mongoose": "^6.9.0",   // It is ODM for for MongoDB
    "nodemon": "^2.0.20",   // let's server run automatically after every changes we done in server files.
    "shortid": "^2.2.16"    // Package to generate the shortId for our longId.
    }
```

## FOLDERS ARCHITECTURE

> `config` folder let us hide the Confidentail data using dotenv.

> `models` folder let create our database schema and database.

> `src` folder consist of our server file.

> `view` fodler consist of our .ejs file for frontend UI and styling .
