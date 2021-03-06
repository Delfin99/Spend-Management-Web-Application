# EnterpriseAppDev: Spend Management Web Application

## EnterpriseApplicationDevelopment:

### This Enterprise Application Development project is planned to manage spends, providing pie chart in a group

#### This project has features the followings:

  - <b>Responsive mobile-first design and user experience</b>
  
  - <b>CRUD operations with a persistent database</b>
  
  - <b>Authentication with username/password</b>
  
  - <b>Asynchronous data consumption from a REST API</b>
  
#### Technologies

  - <b>Server Side</b>
  
    - Express.js (Web framework)

      - Node.js
    
      - EJS (Embedded JavaScript)
      
      - Bcrypt.js (Password hashing)
      
      - Passport.js (Authentication)
      
      - Chart.js (Pie chart)
      
    - Database
    
      - Mongoose
    
  - <b>Client Side</b>
  
    - HTML
  
    - CSS / Bootstrap
   
    - JavaScript / jQuery
    
    
#### Functionalities

  - <b>Sign Up<b>
    - Create, Read, Update, Delete
  
  - <b>Sign in / Sign out</b>
    - Authentication with username and password
    - Bcrypt with password hash
    
  - <b>Dashboard</b>
    - Table / Chart
      - Create, Read, Update, Delete 
      
  
#### Folders
```
.
├── config (Session Authentication)
│   └── passport.js
├── index.js
├── models (Mongoose Schema)
│   ├── Account.js
│   ├── SequenceID.js
│   └── Table.js
├── node_modules (Packages)
├── package-lock.json
├── package.json
├── public
│   ├── css
│   │   └── style.css
│   └── js
│       ├── javascript.js
│       └── utils.js
├── routes (Router)
│   ├── account.js
│   ├── dashboard.js
│   └── home.js
└── views
    ├── account
    │   ├── profile.ejs
    │   ├── signup.ejs
    │   └── update.ejs
    ├── dashboard
    │   ├── create.ejs
    │   ├── index.ejs
    │   └── update.ejs
    ├── home
    │   ├── index.ejs
    │   └── signin.ejs
    └── main (Header and Navigation bar)
        └── main.ejs
```


#### Development 

##### Run (within the folder where 'index.js' file and 'node_modules' folder are located)
```
> npm install express --save
> node index.js
```
or
```
> npm install express --save
> npm install nodemon -g
> nodemon
```

> http://localhost:8080


###### Note) In case of port number error, just change port number in index.js file
```
// Port Configuration
app.listen(3000, function (){
  console.log('http://localhost:3000');
});
```
> http://localhost:3000



