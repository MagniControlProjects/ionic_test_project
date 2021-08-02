# ionic_test_project
Example project for learning about ionic deployment framework and setting up a basic project.

What is Ionic
Single code base (HTML+JS+CSS) to output to all platforms, ( IOs, Electron, Android, Progressive Web App (PWA, Looks and feels native, but isn't) .
PWA is a serves applications feels like a native app through a web browser. Optomized to work offline, be reliable: fast, and engagin. Tap into device features such as location or camera.
The Ionic platform 
Ionic ->  Bucket of Web components -> platform agnostic and automatically adjusting items which can be dumped into a product. Web elements can be written by me. (HTML).
Capacitor component processing
Capacitor -> Takes Application and wraps it into a native mobile app. (Container)
(Capacitor is a more up to date Cordova like solution, but isn't).

Ionic CLI (+Angular CLI)
Project management and build workflow. (Command Line interface).
Creation
Live-reload
bundling
optimization
Ionic Cloud Services - Such as cloud compilation.

Can be used with React, or rawJavaScript.


Notes: Need to heavily capture the machine requirements and consider spinning virtual machine environments for these.

Project Model
Note: Ionic components are written in stencil. 

What is Angular
Angular is simply a JavaScript single page application framework. 
Single page applications, highly reactive JavaScript driven web apps. Web apps are re-rendered single page applications, but looks like multiple pages. After initial download much of the information is client side processing. Single page apps have better State/Data management of different page entities may become tricky. High speed dynamic re-rendering. Does not feel like a web browser.
Note: there is not a hard linked dependency between using a front end framework and ionic framework. However the presentation needs to be considered for use in multiple apps. the frameworks come with good design practices through matter of their creation process.

Getting Started
https://ionicframework.com/getting-started
This getting started sections explains how to:
Install the framework, which depends on node.js and npm (node package manager) of suitable version.
Create a default app (which may seem complicated if not used to react or angular) 
Run the app as a Progressive web app. i.e. Server the application code via network port on the workstation to allow a web browser to query the code and run the application locally.
There is a larger further step not covered by getting started which is managing the deployment and packaging of product into native containers, now this is achieved using 

Install Dependencies
node.js (npm (node package manager), is defacto standard for web application packages) Under the hood, these all require node.js.
npm install -g @ionic/cli
// Basically use node package manager to install @ionic/cli (command line interface package) globally.

Create New Project
ionic start
This will create a new project in the current directory, It will prompt you for project default information.
Blank is the most boring but simplest.
