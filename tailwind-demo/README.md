### This steps are mostly done by following below link
https://tailwindcss.com/docs/guides/create-react-app

## Pre-requisite
NodeJS should be installed on your system

## Create React App CLI has to be installed on your system
```
npm install --global create-react-app
```

# Steps Followed to Create The Project:
----------------------------------------

Step 1: Create a React Project
```
npx create-react-app tailwind-demo
cd tailwind-demo
```

Step 2: Install required dependencies by executing below command:
```
npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9
```

Step 3: Create Tailwind Configuration File
```
npx tailwindcss-cli@latest init
```

Step 4: Create Tainwind Base File. This file is present here: src/styles/tailwind.base.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 5: Create a styles.css file inside src/styles/styles.css and add below content
```
@import url(tailwind.css);
```

Step 6: Refer this styles.css in your index.js or App.js
```
import "./styles/tailwind.css";
```

Step 7: Add a new npm script in package.json
```
"tailwind": "npx tailwindcss-cli build -i ./src/styles/tailwind.base.css -c ./tailwind.config.js -o ./src/styles/tailwind.css",
```

Step 8: Update the npm start script in package.json
```
"start": "npm run tailwind && react-scripts start",
```

Step 9: Start the React Application
```
npm start
```

## To use this Project

Step 1: After cloing the project, do install the project dependencies
```
npm install
```

Step 2: Start the React Application
```
npm start
```


# Some related important links
https://tailwindcss.com/
https://play.tailwindcss.com/
https://tailblocks.cc/

https://necolas.github.io/normalize.css/
