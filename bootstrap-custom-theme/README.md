## Pre-requisite
NodeJS should be installed on your system

In this project we are going to customize the Bootstrap and spacially its theme
https://getbootstrap.com/docs/5.1/customize/overview/

To do this we will be using Gulp
https://gulpjs.com/

## Gulp CLI has to be installed on your system
```
npm install --global gulp-cli
```

# Steps Followed to Create The Project:
----------------------------------------

### This steps are mostly done by following below link
https://tailwindcss.com/docs/guides/create-react-app

Step 1: Create a empty nodejs project
```
npm init -y
```

Step 2: Install required dev dependencies by executing below command:
```
npm install -D browser-sync gulp gulp-sass sass
```

Step 3: Install Latest Bootstrap dependency
```
npm install bootstrap
```

Step 4: Create Gulp Config file. The file is present here : ./gulpfile.js
(Notice the input path and output paths configured in the file in line no 7 and 9 respectively)

Step 5: Create a bootstrap.scss file inside app/scss/bootstrap.scss

Step 6: Create a styles.css file inside app/css/styles.css and add below content
```
@import url(./bootstrap.css);
```

Step 7: Create a index.html in the project root directory and add below in the header
```
<link rel="Stylesheet" href="./css/styles.css" />
```

Step 8: Start the application through command prompt
```
gulp
```

# Steps to use this Project

Step 1: After cloing the project, do install the project dependencies
```
npm install
```

Step 2: Start the application through command prompt
```
gulp
```

