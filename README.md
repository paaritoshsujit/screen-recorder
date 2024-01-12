<h1>This is an Electron application that allows you to record your screen. It uses the desktopCapturer module from Electron to capture the screen, and the MediaRecorder API to record the video.</h1>

<h3>Getting Started</h3>
To get started, clone the repository and install the dependencies:
<br/>
cd screen-recorderv1
npm install

<br/>
Then, run the application:

npm start
Using the Application
Once the application is running, you can click the "Start" button to begin recording your screen. The video will be recorded until you click the "Stop" button. The video will then be saved to your computer in WebM format.

The application also allows you to choose a specific window or screen to record. To do this, click the "Choose a Video Source" button and select the desired window or screen from the menu.

Building the Application
To build the application for distribution, run the following command:

bash
Copy code
npm run make
This will create a out directory containing the built application for your platform.

Configuration
The following configuration options are available in the forge.config.js file:

packagerConfig.asar: Whether to package the application as an ASAR archive. Default is true.
makers: An array of maker configurations for packaging the application for different platforms.
plugins: An array of plugin configurations for customizing the build process.
The following configuration options are available in the package.json file:

config.forge.packagerConfig: Additional packager configuration options.
config.forge.makers: An array of maker configurations for packaging the application for different platforms.
