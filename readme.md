Ionic Capacitor App to test send and receive push notifications with firebase.

If you want to test this app, you should run the next commands:

1) npm i

2) ionic build

3) ionic cap add android

4) ionic cap copy

5) ionic cap sync

Note that you must connect the app with firebase, to do that, you must create a project, if you have already one, great. If you don't, you must create it and add your app, generate the google-services.json and put it into the android/app folder.
That's it, you should receive the push notifications in background.

Finally you can connect your device and deploy your app with ionic cap run android -l --external
