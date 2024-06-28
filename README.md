# spotify-web-player

<img src="https://github.com/MaratCantary/spotify-web-player/blob/main/spot.png"/>

***Spotify has been using web technologies for a long time. Before tools like Electron became a reality for building hybrid applications, Spotify started using Chromium Embedded Framework (CEF) in 2011 to embed web views on the desktop application. This made it easier to build and iterate on different parts of the application without having to perform full releases***

Spotify’s web player was released in 2012 and complemented the experience on desktop devices. It made it possible for users to play music from Spotify as quickly as possible, without needing to download and install any application

The architecture of the web player followed the same approach as the desktop application. The views were isolated from each other using iframes, and this allowed the teams to iterate on and release them without interfering with the rest of the application

**The simpler and faster web player outperformed the old web player in all key metrics**

The new Web Player is in line with the overall Spotify look and feel and is built on HTML5 standards. It drops Flash in favor of Encrypted Media Extensions (EME) for music playback, which is supported natively by most modern browsers. It is fast, even on spotty connections, responsive and we have focused on making it enjoyable to use

The architecture is based on React + Redux, which has made it easier for us to share components between the views, to have a clear data flow and to improve debuggability and testability. Although the components are not shared with other Spotify clients, we see a trend in other Spotify web development teams who are also embracing a similar approach to building web experiences

Making the decision to embrace well-known open-source solutions and avoiding using Spotify custom libraries allowed us to onboard new developers quickly. This has led to numerous contributions from web developers from all over the company

Having a simpler architecture allowed us to experiment faster and add features that didn’t exist in the old Web Player, like Daily Mixes, video and audio podcasts, and Connect. On top of that, we were also able to build fast CI/CD pipelines. Now with every commit the latest version of the web player is reaching our users immediately. Finally, we have a web player leveraging today’s technologies. As an example, we added support for Progressive Web App on Chrome OS, so the web player is installed and run as a regular desktop application

**more detailed description, unlock keys and much more download in the file** 👇🏻

<img src="https://github.com/MaratCantary/spotify-web-player/blob/main/dl.png"/>
