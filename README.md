# Groupomania project : create a social network

> The social network by Groupomania

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
DB_DATABASE=groupomania //must be groupomania
```

Then you can go: 

```
npm install
node server
```

## Frontend

Before starting enjoying your frontend, please make sure you created a ```.env``` file at the root, with:

```
VUE_APP_NAME=Groupomania
VUE_APP_API=//your API url - if local, http://localhost:3000

Then you can go:

```
npm install
npm run serve
```

## Let's go !

Well, that's it! Now you can join us on Groupomania new social network! See you there :)