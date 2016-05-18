# RSS Feed Reader and Jasmine Test Suite project

## Project Overview

This project is an exercise in using [Jasmine](http://jasmine.github.io/) to test the main features of a web based application. The project consists of an RSS feed web application and a set of test suites.

## Implementation

This application was developed by [Udacity](http://udacity.com) and provided as an exercise in the Frontend Web Development course. The objective is to extend the test suites provided in **jasmine/spec/feedreader.js** to more comprehensively test the functionality of the feed reader application.

### Scripts

**js/app.js** - Main feed reader application. Makes use of [jQuery](http://jquery.com), [handlebars](http://handlebarsjs.com/) and the **Udacity RSStoJSON Feed Reader** API to present a list of feeds that the user can select from.<br>
**jasmine/spec/feedreader.js** - A set of test suites written using [Jasmine](http://jasmine.github.io/). The tests are run when the page is loaded and the results are presented at the bottom of the displayed page.

### Libraries

**[Jasmine](http://jasmine.github.io/) 2.1.2** - Behavior-driven development framework for testing JavaScript code.<br>
**[jQuery](http://jquery.com) 2.1.1** - Fast, small and feature-rich JavaScript library used to make DOM manipulation and AJAX easier.<br>
**[handlebars](http://handlebarsjs.com/) 2.0.0** - Provides easy HTML semantic template functionality.

### APIs

**Udacity RSStoJSON Feed Reader** - This replaces the deprecated Google Feed Reader API that was used in the initial development of the app by Udacity.

## Installation

This is a single-page web application. Copying the contents of the project directory to a web server will complete installation.

The active site can be viewed [here](http://ritchmct.github.io/frontend-nanodegree-feedreader/)
