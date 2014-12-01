plexmediaserver_ynh
=============

PlexMediaServer for Yunohost.

## Description
Plex organizes video, music and photos from personal media libraries and streams them to smart TVs, streaming boxes and mobile devices. It is a media player system and software suite consisting of many player applications for 10-foot user interfaces and an associated media server that organizes personal media stored on local devices. It is available for Mac OS X, Linux, and Microsoft Windows.[1] Plex also offers streaming apps for Roku and Chromecast.[2] Integrated Plex Channels provide users with access to a growing number of online content providers such as YouTube, Vimeo, TEDTalks, and CNN among others.[3] Plex also provides integration for cloud services[4] including Dropbox, Box, Google Drive, Copy and Bitcasa.[5]

Plex's front-end media player, Plex Home Theater (formerly Plex Media Center[6]), allows the user to manage and play video, photos, music, and podcasts from a local or remote computer running Plex Media Server. In addition, the integrated Plex Online service provides the user with a growing list of community-driven plugins for online content including Hulu, Netflix, and CNN video.[7]

Source: [Wikipedia](http://en.wikipedia.org/wiki/Plex_(software))


## Licensing

Plex Media Server, unlike the open source frontend, is proprietary software.

Source: [Wikipedia](http://en.wikipedia.org/wiki/Plex_(software))

## Instructions for install

- Use **Install software** option from admin panel
- Find textbox tagged as **Install from github**
- Copy and paste: https://github.com/Novakin/plexmediaserver_ynh 


## Domain configuration

Choose one of your domain or subdomain, but **do not modify the path variable**. 

&nbsp;&nbsp;
<img src='http://img4.hostingpics.net/pics/519450pmsyunohostlocal.png'>


## Plex Configuration

First of all you need to configure plex so you will be able to access your librairies from outside

- Access your server via its local ip : http://YOURIP:32400/web/index.html
- Go to settings (top-right corner icon) > Server tab 
- Click on show advanced
- Go to connect and use your plex account credentials
- Once you are connected make sure your server is mapped to port 32400 

