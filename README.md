
# JATE - Just Another Text Editor

## Description

JATE is a progressive web application that allows users to create, edit, and save text documents right in their browser. It uses IndexedDB and service workers to provide an offline experience similar to a native application.

## Features

- **Installable** - Add JATE to your homescreen for quick, easy access.
- **Offline Capabilities** - Continue working even without an internet connection.
- **Auto Save** - Never lose your work, JATE saves as you type.
- **Customizable** - Personalize JATE by changing themes/fonts.

## Installation

If you wish to run JATE locally, clone the GitHub repository and run the following commands:

```shell
npm install
npm run build
```

This will install the required packages and build the client-side code.

## Usage

To use JATE, simply visit the deployed site [here](https://github.com/liq543). You can immediately start typing to create a new document.

Give JATE a name by clicking "Untitled Document" in the navbar. You can also open existing documents from the File menu.

JATE will automatically save your work as you type. If you close the browser window, your document will be there next time you open JATE.

For the full native app experience, install JATE to your home screen. Here's how:

### On Android

1. Open JATE in Chrome.
2. Tap the menu button in the top right.
3. Select "Add to Home Screen".
4. Click "Add".

### On iPhone

1. Open JATE in Safari.
2. Tap the Share button at the bottom.
3. Scroll down and tap "Add to Home Screen".
4. Click "Add" in the popup.

Now you can open and use JATE just like any other app on your device!

## Technical Details

JATE is built using:

- JavaScript
- HTML/CSS
- Webpack bundling
- Service workers
- IndexedDB browser storage
- Express.js on Node.js

The frontend code can be found in the client folder, while the backend Express server is located in server.js.

The application is deployed on Heroku.

## Contributing

Please do not contribute to this project or make any pull requests. 

## Credit

UT Austin Coding Bootcamp for starter code.

## License

This project is open source and available under the MIT License. See LICENSE for details.

## Contact

Please refrain from reaching out with questions or feedback.

**GitHub**: [liq543](https://github.com/liq543)
