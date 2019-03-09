# Burger

## Overview
- A burger logger with MySQL, Node, Express, Handlebars and ORM. Following the MVC design pattern and using Node and MySQL to query and route data in the app, and Handlebars to generate HTML.
   
## Live Site
- https://eat-da-burger-edb.herokuapp.com/

![Delicious Burger](DeliciousBurgers.png)

## Description
- Eat-Da-Burger is a restaurant logging app that lets users input the names of burgers they'd like to eat.
- Whenever a user submits a burger's name, the app will add the burger to the Wanna Try list.
- When the user clicks the like button, the burger will move to the left side of the page.
- When the user clicks the dislike button, the burger will move to the right side of the page.
- If a burger is added to the like list or dislike list, user can delete the burger from the list by clicking the trash icon next to the burger.
- Once the user deletes the burger name, user will have to add the name again to the list to see the same burger's name on the Wanna Try list.



## Directory Structure
```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger_theme.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

## Technologies Used

- Node.js
- Express.js
- Express Handlebars
- MySQL
- ORM 


