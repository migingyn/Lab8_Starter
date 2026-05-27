# Lab8-Starter
> By: Mikey Nguyen

## How are graceful degradation and service workers related?
Graceful degradation and service workers are related because service workers are what actually make graceful degradation possible on the web. Without them, losing your internet connection means your app just breaks. Service workers sit in the background and intercept network requests, so if you're offline they can pull from the cache instead of hitting the network. The app still works, just with what it already has stored locally rather than fetching everything fresh.

## PWA Image
![pwa image](pwa.png)

[View Page](https://migingyn.github.io/Lab8_Starter/)