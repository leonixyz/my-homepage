# My Homepage

Trydactyl is one of my favourite webextensions, but since Mozilla disallowed
webextensions from being able to set about:* and file://* as homepage, I cannot
use my favourite `about:home` as home/newtab page.

I am aware that Trydactyl developers provide a native messager to circumvent
these problems, but I don't want to use it because it offers too broad 
functionality for my needs. I want just a blank page with a search box.

This repo is just a systemd unit launching `python3 -m http.server` with custom
parameters, and an index.html file to serve.

Then, I set my Firefox homepage and newtab page to http://localhost:49930.

