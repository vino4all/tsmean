# Disclaimer

**Note that this project is still in furious development (currently it's pre-alpha) and only a glimpse of it’s full potential is publicly visible today. To get notified when the next major public release is ready, [sign up to the mailing list for releases](http://eepurl.com/cXa2aP). To apply for alpha testing, visit [www.tsmean.com/alpha](http://www.tsmean.com/alpha?utm_source=github&utm_medium=banner&utm_campaign=alpha_testing). To read more about the project, visit [www.tsmean.com](http://www.tsmean.com/?utm_source=github&utm_medium=banner&utm_campaign=project_info).**


<hr>

![tsmean logo](https://s3.eu-central-1.amazonaws.com/bersling/images/tsmean-logo.png)

# Pre-Alpha Release

This is a **starter kit** for webapps **completely written in TypeScript**.

The starter kit is using the following technologies:

- **M**ySQL
- **E**xpressJS
- **A**ngular4
- **N**odeJs

... and that's why it's called tsmean! All of those are modern
technologies and well suited for development
with TypeScript. You get to use TypeScript now
on the client **and** the server! This leads to efficiency
through consistency. Read more about it here: www.tsmean.com.


# Installation

## Prerequisits ##

- node (v6 or v8) & npm (v3 or v5)
- git
- ts-node (`npm install -g ts-node`)
- angular-cli (see https://github.com/angular/angular-cli)


## Install ##
If the prerequisits are met, run:

```
git clone https://github.com/tsmean/tsmean your-project-name
cd your-project-name
cd backend && npm install
cd ../shared && npm install
cd ../frontend && npm install
```

# Backend

First `cd backend`, then:

- to spin up a REST-API server `npm start`. Check it out at http://localhost:4242
- To run the tests `npm test`

# Frontend
First `cd frontend`, then:

- to start the Angular app `npm start`. Check it out on http://localhost:4200
- you can develop all modules independently. For example, `cd src/app/user` and run `ng serve`.
This launches a minimal app only displaying the user module (i.e. without login etc).
You can test all modules using `ng test`.


# Live Demo
https://fir-tsmean.firebaseapp.com/

[![screenshot](https://s3.eu-central-1.amazonaws.com/bersling/images/animals3.gif)](https://fir-tsmean.firebaseapp.com/)


# Homepage
http://www.tsmean.com
