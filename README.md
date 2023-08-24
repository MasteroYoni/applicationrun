# React-template
After your initial project generation has completed, you can view your app on PCF by going to your PCF URL. Log in to https://login.sys.pp01.edc1.cf.ford.com/login, select the space and look for the app you deployed. The route(URL) will be will be listed in the last column next to your app name.

# First Time Setup
## Github
1. To take advantage of the project template Dev Central Station has provided, you will need Git. Git can be found [here](https://git-scm.com/downloads).
2. In your Github repo, locate the project you just created:

    a. Click the green button in the upper right corner that says "Clone or Download".

    b. Copy the link provided, it should look something like ```git@github.ford.com:RepoOrgName/Generated project name.git```. For help setting up your authentication to GitHub for the first time, please follow the directions found [here](https://github.ford.com/DevEnablement/pcfdev-guides/blob/master/git/GitConfiguration.md)

3. On your computer, open a terminal window and type ````git clone```` and the paste the link you copied above all in one line - this will clone your repo locally
4. Open your favorite IDE and navigate to the Github folder you just downloaded and open it. For help pushing your code to your Github repo or to PCF, scroll to the "Commit and push your code" section below

## Proxy Setup with Intellij
1. While using Intellij, go to preferences
2. Navigate to "system settings"->Http proxy
3. Select the "Manual proxy configuration" radio button and then the "HTTP" radio button
4. Under "Host name" type `internet.ford.com` and select port `83`
5. Under the "no proxy for" heading, use `*.ford.com, localhost, 127.0.0.1`
## Proxy Setup with Intellij Terminal (Mac)
1. Check to see if any proxy settings are already present by clicking on "Terminal" at the bottom
2. Type `env | grep -i proxy` to see if environment variables are set
3. You will want to add the proxy config by typing the following commands:

    a. `export http_proxy=http://internet.ford.com:83`

    b. `export https_proxy=http://internet.ford.com:83`

    c. `export no_proxy="ford.com,localhost,127.0.0.1"`

    d. `export HTTP_PROXY=http://internet.ford.com:83`

    e. `export HTTPS_PROXY=http://internet.ford.com:83`

    f. `export NO_PROXY="ford.com,localhost,127.0.0.1"`

## Proxy Setup with Intellij Terminal (Windows)
1. Check to see if any proxy settings are already present by clicking on "Terminal" at the bottom
2. Type `SET | findstr proxy` to see if any proxy environment variables are set
3. You will want to add the proxy config by typing the following commands:

    a. `set http_proxy=http://internet.ford.com:83`

    b. `set https_proxy=http://internet.ford.com:83`

    c. `set no_proxy="ford.com,localhost,127.0.0.1"`

    d. `set HTTP_PROXY=http://internet.ford.com:83`

    e. `set HTTPS_PROXY=http://internet.ford.com:83`

    f. `set NO_PROXY="*.ford.com,localhost,127.0.0.1"`

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# Contact Us
Need to notify us of a bug, have issues, new feature request or simply want to brag? Join the /d/c/s Community Channels!
- [Dev/Central/Station Slack](https://app.slack.com/client/T5V3ZFCD6/C9L83E6DQ)
- [Dev/Central/Station Webex Teams](https://www.webexteams.ford.com/space?r=fz8y)
