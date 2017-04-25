# school_donations

## Overview

### What is it?
This is my stream two project for the Code Institute's full stack developer course. 
The "school donations dashboard" displays a host of visual chart representations based on school donations made in the U.S. 
The user can interact with each of them to filter information based on State, resources ,subjects and more, the figures and charts then recalibrate in realtime.
There is also a tutorial/tour feature for any user still not sure exactly how to use or understand each dashboard item.

### How does it work?
The app is built to retrieve data from a **Mongo** (NoSQL) database, compiled with data from a **CSV** file, the data is then rendered into stunning, interactive chart visualizations with the use of **D3**.

## Technologies

- [Flask](http://flask.pocoo.org)
  - **Flask** is a Python microframework used to build this app, not unlike angularJS it provides url routing, among other features.
- [D3](https://d3js.org)
  - **D3**, a javascript library that uses **HTML**, **SVG** & **CSS** to create the visual representations of data obtained from the mongo database.
- [Intro.js](http://introjs.com)
  - **Intro.js**, another javascript based, open source project that implements a step by step tutorial guide that is applied to each individual data visualization.

## Project requirements/ guidlines

- Create project using Flask framework
- Use of D3js and Introjs
- Utilize bootstrap to create an effective and responsive layout.
- Create at least one more data visualization.
- Deploy source to GitHub repository.
- Deploy database-**mongodb** and host live site on **Heroku**.

## Live site
You can visit the live site at: https://safe-ravine-65278.herokuapp.com

