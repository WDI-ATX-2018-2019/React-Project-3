# Project 3: React-Express-API

# ![GA Logo](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 

### Overview

While your last project taught you how to get started with writing a fullstack application in JavaScript using Express, Mongoose, and Node, this project will have you building another full stack application, but this time with a React front-end.

You will build an app with three major components:

1. An API of your own design, built using Node, Express, and Mongoose, that serves JSON.
2. Front-end React code that updates the UI and makes requests to your API back end.
3. Consume a third party API (google maps, weather, spotify, government data, instagram, news, stocks, etc... possibilities are bascially endless). [Here's a bunch of cool APIs.](https://github.com/TonnyL/Awesome_APIs)

---

### Requirements

> ### *In case you were thinking about it, do not use REDUX for this project*

#### Planning Requirements/ Proposals
  - Clearly defined user stories for your MVP
  - Wireframes
  - Readme in your front-end repo including links to the above and a description of what your project is, why you chose to make it/what problem it olves, technologies used, installation requirements, the contributors, etc.
  - Readme in your back-end repo describing your API endpoints and how to use them (look at other API references for guidance). 

#### Back-End (API) Requirements
  - Node, Express, and some type of database (MongoDB) with at least 1 model. No associations are required. 
  - Must have Create, Read, Update, and Destroy functionality.

#### Front-End Requirements
  - React front end that consumes your backend API.
  - It must communicate with the back end API RESTfully to Create, Read, Update, and Destroy resources, using fetch.

#### Overall Requirements
  - Your app (either the front end or the back end) must consume at least one third Party API.

#### Deployment
  - Your API must be deployed to Heroku and your front-end must be deployed to Heroku or Surge.
  - We recommend Surge as using it to deploy is [very easy](https://daveceddia.com/deploy-create-react-app-surge/)

    > You MUST deploy your back-end and front-end separately. This assignment is to make a front end and separate back end using totally decoupled architecture. This will make it far easier to debug your deployed applications and manage your deployments. One way to get yourself in trouble in this project would be to attempt to follow a tutorial for MERN stack that is NOT decoupled. Do not do this.
    
---

##### Auth and React Router 

- You're not required to do authentication or React Router

### App Organization

You should build your application in completely separate repositories, one for your React front-end and another for your Node-Express-Mongoose API.

---

### Process

* **Keep user stories small** and well-defined. Remember: user stories focus on what a user *needs*, not what development tasks need accomplishing.
* **Write pseudocode** before you write actual code. Thinking through the logic first helps.
* **Don't hesitate** to write throwaway code to solve short-term problems.
* **Read the docs** for whatever technologies / frameworks / APIs you plan to use. (See ["RTFM"](https://en.wikipedia.org/wiki/RTFM))
* **Use Git Branches** 


---

### Code

* **Keep your code DRY** and build your API RESTful.
* **Be consistent** with your code style. (Pick single or double quotes, either put a space between `) {` or don't).
* **Commit early; commit often.** Don't be afraid to break something because you can always go back in time to a previous version (so long as you're committing often).
* **Name things appropriately.  Comment as necessary.** Do your naming conventions make sense? Would another developer be able to look at your app and understand what everything is? (See ["self-documenting"](https://en.wikipedia.org/wiki/Self-documenting)).  Even if it's obvious, comments can help to explain the intent -- the what and why.  This allows the next developer (which could even be you in a few months) to understand the purpose and decide what can be adjusted to achieve the same goal.
* **Ensure it is well-formatted.** Are you indenting consistently? Can we find the start and end of every div, curly brace, etc?  Organizing the hierarchy is key to understanding.

---

### Project Ideas

For this project, work with your team to build a creative product that you actually think someone will want to use.

If you're struggling to come up with your own project ideas, checkout [r/startup_ideas](https://www.reddit.com/r/Startup_Ideas/) on reddit or [requestforstartup.co](https://requestforstartup.co/).


---

### Bonuses

You should only attempt these bonuses if and only if you've satisfied project requirements.

#### Write some routes that use query parameters in your api (e.g. `/cats?color="red"`...figure out how that works

#### Implement pagination in your API (you could do this with query parameters or URL parameters)

### Easier

#### Use semantic-ui to style your app. 

#### JSON web tokens (JWT) for authentication

### Harder

#### OAUTH [oauth module](https://github.com/jaredhanson/oauth2orize)

#### Use [react-strap](https://reactstrap.github.io/) to style your app

#### Create cool animations 

#### Authenticate with Firebase


