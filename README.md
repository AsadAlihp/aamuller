<h3>Getting Started</h3>
Create React Native App is the easiest way to start building a new React Native application. It allows you to start a project without installing or configuring any tools to build native code - no Xcode or Android Studio installation required.
<h3>Setting up DayBack</h3>
To Start building Download Dayback project and extrat it, after extration go to DayBack directory via CLI. e.g: `cd DayBack`<br />
Assuming that you have <a href="https://nodejs.org/en/download/current/">Node</a> installed, you can use npm to install the create-react-native-app command line utility:<br/>
`npm install -g create-react-native-app`
<br />
<h3>For Testing/Debugging</h3>
Move into the DayBack directory and run this command.
`npm run` <br />
This will start a development server for you, and print a QR code in your terminal. Scan the QR code using Expo(<a href="https://play.google.com/store/apps/details?id=host.exp.exponent">android</a>/<a href="https://itunes.apple.com/us/app/expo-client/id982107779?mt=8">iOS</a>) App and Test DayBack on your Device.<br />
<h3>Installing build tool exp</h3>
XDE currently doesn't include an option for building a standalone app, so we'll need exp for this. Run `npm install -g exp` to get it.
If you haven't used exp before, the first thing you'll need to do is login with your Expo account using `exp login`. In case you do not have account on exp then <a href="https://expo.io/signup">sign up</a>.

<h3>Build For Android</h3>
To build android apk file of DayBack run this command  `exp build:android` 
<br />Now you can find installable package link after succesful build.
<h3>Build For iOS</h3>
To build iOS installable file of DayBack run this command `exp build:ios` 
<br /> Now you can find installable package link after succesful build.

