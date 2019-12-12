# React-Stuff
React-Stuff with versioning


#### umi for ReactJS Application
$ yarn create umi my-app

Select the boilerplate type: Select Ant Design Pro
❯ ant-design-pro

Which language do you want to use? Select language you use
❯ TypeScript
 JavaScript

$ cd my-app
$ yarn
$ yarn start # open browser and visit http://localhost:8000

>>v1\my-app>yarn global add umi


Removed
//"deploy": "npm run site && npm run gh-pages",
Added
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
"homepage": "http://kambleaa007.github.io/React-Stuff",

