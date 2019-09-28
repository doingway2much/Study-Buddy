#Suddy Buddy

Project # 2 (Georgia Tech Bootcamp)
Colaborator: Seth Randell, Jesselyn Jackson  and Ryan Sims

We came up with this idea to bring people together that are going through the same thing.  We noticed when working together in Bootcamp we were able to retain more and helped each other grasp the marital better.  This project was quite challenging at first due to the different issues we ran into joining the data from different tables.  This caused us to run into issues with the search for buddy page and that's why it's just static.  Please see the hidden features at the bottom of the page to see what else was done in this project.

Technologies:
* JavaScript
* jQuery
* mySQL
* Node.js
* Handlebars
* Sequelize ORM
* Matirelize

![Project2](https://github.com/doingway2much/Bootstrap-Portfolio/blob/master/assets/img/SB.jpg?raw=true)


#About Us
StudyBuddy was created because we saw how hard it was to find a study buddy especially for those already out of school.
We sought out to create a platform where users can find other buddies to help further their understanding and learning.
In the future, we want StudyBuddy to help connect students of all subjects and include in-house learning content.
StudyBuddy was created using HTML, CSS, Javascript, jQuery, Handlebars, MySQl, Materialize and Node.

Installing and setting up the App:

1) First create an account and choose a few interests to get started!

``` 
git clone https://github.com/rainbojack1/Project-2.git
```

2) Creat a .env file in your main directory

```
touch .env
```

3) Add your mySQL password to the .env file

```
MYSQL_KEY="Your password" (no quotes)
```

4) Install NPM packages no need to install them mauall since we have a package.json file

```
npm insall
```

5) Created the database and add your seed data you may have to add the creatAT and updated at files if you getting an error imorting the seed files.

```
mysq -u root -p
source schema.sql
souce seed.sql
```
7) Once that is done just run the app
```
node server.js
```

*****HIDDEN PAGES*****\

/admin
[![AdminView](https://github.com/doingway2much/Study-Buddy/blob/master/public/img/admin.jpg?raw=true)]

This page lets yous see all of the users but has a delete button so you can delete entries from the database with out writing queries.
