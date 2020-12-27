# house-navigation-VR

This is a web based virtual reality app aimed at demonstrating the applications of React360. 

You will need [Node.js](https://nodejs.org/en/) installed on your system. Once you have that, install [react-360-cli](https://github.com/facebookarchive/react-360) by running the follwing command in your terminal:

```
npm i -g react-360-cli
```
*The "-g" flag install this command line interface globally on your system.*

Once you have this repository cloned/forked, navigate to its directory and run the following command to run this application:

```
npm start
```

This will launch the localhost server on port 8081. You can view the application by navigating to http://localhost:8081/index.html on your favorite browser.



If you receive the following error:

```
error: bundling failed: Error: `fsevents` unavailable (this watcher can only be used on Darwin)
```

run `brew install watchman` and then `npm start` again. 

## Support for mobile

Installing [webVR polyfill](https://github.com/immersive-web/webvr-polyfill) will enable stereoscopic rendering of VR into our mobile phones. You can install it by running the following command in the project directory:

```
npm install --save webvr-polyfill
```
