# FitLit: Turing FE Module 2
### Nicole Gooden
### Kathryn Jackson


## Abstract

This project requires creating an activity tracker user interface using given data. This application presents the logged data on a dashboard, allowing users to view their activity, sleep, and hydration data. Users can also see their achievements and how their performance compares to that of their friends.

Test driven development was used to drive the implementation of our code, ensuring that the data presented for each day is accurate. The day can be changed using the calendar element on the dashboard.

**The learning goals include:**
* Follow the specification below to make a working application
* Implement ES6 classes that communicate to each other as needed
* Write modular, reusable code that follows SRP (Single Responsibility Principle)
* Implement a robust testing suite using TDD
* Use object and array prototype methods to perform data manipulation
* Display information on the page while maintaining ability to test class properties and methods
* Create a data dashboard that is easy to use and displays information in a clear way


## Preview of Working Application
![](https://media.giphy.com/media/S9iRAKiz7vDaOY2oAF/giphy.gif)
![](https://media.giphy.com/media/humYba0LTMiBNQbCrl/giphy.gif)


## Installation
1. In your terminal, [choose the directory](https://www.git-tower.com/learn/git/ebook/en/command-line/appendix/command-line-101#:~:text=To%20change%20this%20current%20working,%24%20cd%20..) that you would like to store this repository in.

2. Clone this repo.
```
git@github.com:nicolegooden/fitlit-kj-ng.git
```

3. Once you have cloned this repo onto your local device, go into the newly installed directory and install the library dependencies. To do this, run:
```
npm install
```
4. While still in the new directory, deploy the application by running:
```
open src/index.html
```


## Usage and Accessibility
After starting this project, we attended a class session on accessibility. We chose to do further research on ways that we could change our project to make it more accessible within our given timeframe. [One source](http://dyslexiahelp.umich.edu/sites/default/files/good_fonts_for_dyslexia_study.pdf) that we found explained that font style and line height make the page more readable for people with learning disabilities such as dyslexia. For this reason, we changed our font to _Verdana_ and increased our line height by 50%. Another change we made was to change our `div` elements to `section` elements. By using semantic HTML, our application is now more accessible to people using screen-reading software.

Our dashboard is separated into five main sections. The header contains our welcome message and calendar element. The user card displays the current user's personal information. All fitness data can be found in the hydration, sleep, and activity widgets, including weekly data and achievements.

### User Card

The **user card** displays the user's:
* ID
* Name
* Address
* Email
* Stride Length

### My Hydration

The **hydration widget** displays:
* How many ounces the user has consumed today
* How many ounces the user has displayed each day over the course of the last week

### My Sleep

The **sleep widget** displays:
* How many hours the user slept last night
* The quality of the user's sleep from last night
* The user's hours slept and quality of sleep for each night over the course of the last week

### My Activity
The **activity widget**  displays:
* The user's step count for today
* How many miles the user walked today
* The user's step count, how many flights of stairs were climbed, and active minutes for each day over the course of the last week

## Next Steps
* Display our weekly data with graphs
* Use Lighthouse in dev tools to check accessibility
* Display names of friends rather than just their ID
* Add a widget to compare user's data to their friends' data
* Refactor some of our longer methods in `scripts.js`

## Our GitHub Accounts
[Nicole Gooden](https://github.com/nicolegooden)
[Kathryn Jackson](https://github.com/kathrynljackson)
