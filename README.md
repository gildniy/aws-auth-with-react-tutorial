# How to set up AWS auth service with React
Just to begin with, AWS authentication can be achived by using amplify cognito service, and this tutorial demonstrate how to achieve this in a React Application.

**Step 1: Set up amplify**

We are supposing to have npm installed in our machine and git bash, Cmder or any other command line tool.

The first thing to do is to install **amplify-cli** globally which will help us to configure the project and connect it to the aws account.

This is achieved by opening the command line and run `npm i -g amplify-cli`

![image - amplify-cli](https://drive.google.com/open?id=1EqAB5mNRTmBo5qHUipPZW0hdQYbeM5XM)

**Step 2: Create a new React project**

For creating a react project we have to install a react cli by running `npm install -g cli-react`

![image - react-cli](https://drive.google.com/open?id=1t9oh1sVBqCNQY0BIOCPGlg_IVLBwmk9R)

And create a new React app `npx create-react-app amplify-auth-react`

![image - react-new-app](https://drive.google.com/open?id=1nDQFVKD2zl2Nxv7d_MCzrRXJn8gUck5M)

With new React app in place, we are able to view it in the browser by running 
`npm start` from the app directory and a beautiful landing page is visible from the url: `http://localhost:3000`

![image - react-opened-in-browser](https://drive.google.com/open?id=1pr53b9oGVnoi42JPdlgyialrD6mCGGc_)

**Step 3: Initilize amplify**

After creating a new React project we are ready to start a initialize amplify in our project, and we can do this by running `amplify init` in the root directory of our application.

![image - amplify-init-1](https://drive.google.com/open?id=1bt47ISncoOldsTeUsT1GjGz7AF41wMtj)

![image - amplify-init-2](https://drive.google.com/open?id=1RnmmKEakDponKajx8M1VxivbutlqQpE8)

![image - aws-account-verify](https://drive.google.com/open?id=1sXAw2NVfHvLJQuzKWsazWPt_q56-CTFx)

![image - aws-account-verify 2](https://drive.google.com/open?id=1IA-e3PObIdQpeTEOIoZeb_ZB-u43P6g2)

![image - aws-account-verify 3](https://drive.google.com/open?id=1rMFMhnjR_Zc1zXJetFDBRRTAA5qRsRAF)

![image - aws-account-verify 4](https://drive.google.com/open?id=1KzgQ-dQPqIpMa6WczPu5pzDRvYGH5Sg-)

![image - aws-account-verify 5](https://drive.google.com/open?id=1dQGP5aP7bvQfd-1O3-suceMEXsGvh-hV)

![image - aws-account-verify 6](https://drive.google.com/open?id=17znf9IiAMKPbpJbqhRDtbHTai9mIH9sL)

![image - aws-account-verify 7](https://drive.google.com/open?id=1a6rVL_QedYsxgRPcrYIDC7IOy9K4Joln)

![image - aws-account-verify 8](https://drive.google.com/open?id=1K_QAXCW6rsOdiKFJwAesU6PNHjYWGeVe)

![image - aws-account-verify 9](https://drive.google.com/open?id=1E8I48gMZi_GhqoQPXLBAj4oWZYJviRTd)

![image - aws-account-verify 10](https://drive.google.com/open?id=1ohlhs1hR7gYLr9WfOgkcKGstiCtrwxX0)
