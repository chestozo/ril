## Intro
Some time ago I was struggling with a lot of cool articles floating around and not so much time to read them.
Also usually I was stumbling upon those cool articles and all I wanted was to save them for later.  
At that time there was several reader apps — RIL (Read it Later which is now called Pocket) and Instapaper among the most popular. Those inspired me to write my own version of the app so that I could make some changes to better feat my own needs. 

For example I wanted to read some intranet articles and I didn't want to save those on someone elses servers.  
Like this I came up with an idea to have multiple servers: one that was for publicly available articles and another one that would be dedicated to some articles that are available only inside my work intranet.

## Features

And like this it started and became my main pet project that was constantly evolving and where I was adding features from time to time.
Here is a list of the main features (some of them are unique among other analogue apps):
- offline support - sync articles while you are online read anytime later even without internet connection
- random article - this one I find particularly useful when you have some time for reading but you don't know what to read exactly - just press the random article button and surpise youself with some article that once you have found to be interesting
- dark mode support - the app will automatically switch to dark mode with you phone. Still you can toggle light / dark mode manually when you need it
- search for article - search by article title save date or url
- `beta` backup / restore all you app data. This can be usufull when you are switching devices. Another option is to setup the same user on multiple devices wich is also available
- nice font =) yes I know that this is something that is taste dependent but I am really happy with the current font in the app and believe me I was looking for it for a long time!
- `beta` article speach reading mode - this one is in early beta and probably it is too early to use it. I hope to finish it soon!
- slide presentation sites support - like slideshare.net - slides are saved and shown as a sequence of images
- `iframe`s are kept so that you can watch youtubes (internet connection required) straight inside the app
- multiple servers support - by default you are using only one server for any type of article. If you need to setup a private server so that it will be available only to you - please DM me and I will help you to do so 🤝.

Maybe something else but I don't remember it right now 🙄  
Yeah forgot to say that it is free!

## App
So lets start with the app.

First of all it is not a classic app from App Store or Google Store (at least for the moment).  
It is a so called [PWA](https://en.wikipedia.org/wiki/Progressive_web_application) which in short is a website that you can bookmark and add to the home screen of you mobile / tablet device and it should look and feel like you are using a normal app.  

This kind of apps has same benefits like usual website benefits compared to apps:
- you are always using the last version and you don't need to manually update the app
- you pay nothing for it (there is no tricky way of charging you like in-app payments so that you can be sure it is free)

### Install the app
Here I am providing instructions for iOS 13 but it should be similar on Android.

<img src="https://github.com/chestozo/ril/raw/master/p01.png" />

<img src="https://github.com/chestozo/ril/raw/master/qr.png" width="160" />

1. open [https://chestozo.github.io/ril/app/](https://chestozo.github.io/ril/app/) on your mobile device
2. click on Bookmark button
3. proceed by clicking on Add to Home Screen
4. change bookmark lable as you wish and click on done
5. that's it! Bookmark should be on you home screen.
6. finally: open the app and enter your username of choice.  
   NOTE: because for now we are not using password protection you can choose a pretty unique username like `nickname.pLFfR2Im` to not clash with other user names.  
   Swipe right in the app and enter your username (it will be saved automatically):  
   <img src="https://github.com/chestozo/ril/raw/master/p06.png" width="600" />

## Extension
Now lets add some articles.

For this you will need a Chromium based browser like [Google Chrome](https://www.google.com/chrome/) or [Yandex browser](https://browser.yandex.ru/).  
And this [browser extension](https://github.com/chestozo/ril/raw/master/ril-ext.zip).

So here come the second tricky feature of the app: the browser extension is not (yet 🤷‍♂️) published on Chrome webstore. So here are the steps to install the extension:
1. download the [browser extension](https://github.com/chestozo/ril/raw/master/ril-ext.zip)
2. extract it (somewhere where you will less probably delete it like Documents folder for example)
3. now turn hacker mode ON
4. open [chrome://extensions](chrome://extensions) in your browser
5. enable Developer mode and click on Load unpacked button:
   <img src="https://github.com/chestozo/ril/raw/master/p02.png" />
6. choose the dir where you have extracted the extension. This is what you should get:
   <img src="https://github.com/chestozo/ril/raw/master/p03.png" />   
7. setup user name (same as you have used in the app):
   <img src="https://github.com/chestozo/ril/raw/master/p04.png" />
   <img src="https://github.com/chestozo/ril/raw/master/p05.png" />
8. Done

## Using the app
1. Now any time you encounter a medium article / facebook post / twitter thread or any other piece of text that you want to read one day - press the extension button - it will save this page to our server (tab is closed once article is saved).
2. Then go to the app and sync it - articles will be downloaded to your app and will stay there until you read them.  
And that's it!

## Keywords
`reader`, `app`, `offline`, `free`
