Evernote URI Handler
====================

A simple custom URI handler for Evernote.

= Installation =

1. [Download][]
2. Unzip
3. Put the .app somewhere (/Applications/Utilities is as good a place as any)
4. Launch it once, to register it as the handler for x-evernote:// URIs

= URIs =

At the moment the only thing you can do is trigger a search. Search URIs are in
the form `x-evernote://search?query={query}`. If you've already downloaded the
.app and run it once, you can [click here][test search] to trigger a search. It
should launch Evernote, open a collection window and search for "OS X".

Searching in Evernote is actually pretty powerful. Check out their docs for
details.

= Why? =

I've recently switched from [LaunchBar][] to [Alfred][]. Reading through some
Alfred tips and tricks, someone suggested adding a custom search for searching
in the Spotify app via its `spotify://` URI handler. I wanted a similar custom
search for Evernote, but it doesn't have a URI handler. AppleScript to the
rescue.

Of course, you can use this script for LaunchBar, too. It just never occurred to
me to use a local app's custom URI handler that way until the Spotify
suggestion. It's really handy!

Here's what my custom Evernote search looks like in Alfred:

![Alfred Config](tree/master/images/alfred.jpg)

[Download]: http://github/rfletcher/Evernote-URI-Handler/zipball/master
[Alfred]: http://alfredapp.com
[LaunchBar]: http://www.obdev.at/products/launchbar/
[test search]: x-evernote://search?query=%22OS%20X%22
