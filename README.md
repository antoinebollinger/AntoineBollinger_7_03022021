# Openclassrooms project #7 : create a social network

![alt tag](https://user-images.githubusercontent.com/56133015/111754179-f9f5b200-8897-11eb-8187-ea26d219dd9e.jpg)

## Getting started

Clone each submodule on your local machine and follow the instructions. You can also clone this global repo :

```
git clone --recurse-submodules --remote-submodules https://github.com/antoinebollinger/AntoineBollinger_7_03022021
```

## Backend

Before your start, make sure you have access to a Mysql server. You'll need to create a ```.env``` file a the root of your backend file, with the following:

```
DB_HOST=//your host - if local, localhost
DB_USER=//your username - if local, root
DB_PASSWORD=//your password - if local, empty
DB_DATABASE=//your database - if local, can be groupomania
```

Then you can go: 

```
npm install
node server
```

> For more infos about this API, please read the guidelines file.

## Frontend

Before starting enjoying your frontend, please make sure you created a ```.env``` file at the root, with:

```
VUE_APP_NAME=Groupomania
VUE_APP_API=//your API url - if local, http://localhost:3000
```

This app was developped with Vue.js (https://vuejs.org/). Make sure you have it installed on your machine.

Launch the app with :

```
npm install
npm run serve
```

## Let's go !

Well, that's it! Now you can join us on Groupomania new social network! See you there :)