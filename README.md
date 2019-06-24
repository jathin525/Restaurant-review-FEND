# Mobile Web Specialist Certification Course

* * *

#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Project Rubric

Your project will be evaluated by a Udacity code reviewer according to the [Restaurant Reviews project rubric](https://review.udacity.com/#!/rubrics/1090/view). Please review for detailed project requirements. The rubric should be a resource you refer to periodically to make sure your project meets specifications.

### What do I do from here?

1.  In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    -   In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
    -   Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.

2.  With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3.  Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4.  Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.

## cloning and downloading the project

-   I had gone through all the instructions given by Udacity in the rubric structure from the link <https://github.com/udacity/mws-restaurant-stage-1>
-   then I unzipped the project folder

## steps performed to complete the task

-   To load map I used JavaScript  token from MAPBOX.
-   and I added the links in `index.html`, `restaurant.html` to connect the project with map.

## changes in index.html

-   I added a meta Tag to display website responsive using viewport
-   then I removed height property from `filter-option` and  added padding property for it in `style.css`.
-   and then I checked the accessibility and made changes to get maximum accessibility.
-   and I also checked the color contrast for all the pages and also made some changes in colors so that it makes responsiveness attractive.

## changes made in restaurant.html

-   for the section `restaurant-container`, I made it into two divisions so that it can place a side.
-   In  the `review-container`, added some CSS styles so that it will be displayed attractively .
-   And then I added a meta Tag to display website responsive using viewport.
-   then I initialized service-worker in `index.html` by using <script> tags and given path of service Worker(sw.js).
-   and then I created manifest.json file with few properties .
-   I had manipulated the  code in dbhelper.js to work with any server. committed the URL with port and assigned direct path.

## FOR RUNNING Project

-   I had implemented this code using `python server` ,we can also implement this project using 200 ok server but we need to do some changes in `dbhelper.js`.

    \+and finally thanks for **Udacity team** for giving this great opportunity to learn about front end
