<h2>This is an Electron application that allows you to record your screen. It uses the desktopCapturer module from Electron to capture the screen, and the MediaRecorder API to record the video.</h2>

<h3>Getting Started</h3>
To get started, clone the repository and install the dependencies:
<br/>

<code>cd screen-recorderv1
npm install</code>

<br/>

<h3>Then, run the application:</h3>

<code>npm start</code>
Using the Application
<br/>
<br/>
Once the application is running, you can click the "Start" button to begin recording your screen. The video will be recorded until you click the "Stop" button. The video will then be saved to your computer in WebM format.

The application also allows you to choose a specific window or screen to record. To do this, click the "Choose a Video Source" button and select the desired window or screen from the menu.

<h3>Building the Application</h3>
To build the application for distribution, run the following command:

<code>npm run make</code>
<br/>
This will create an out directory containing the built application for your platform.
