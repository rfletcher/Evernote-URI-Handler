Evernote URI Handler
====================

A simple custom URI handler for [Evernote][] on Mac OS X.

Installation
------------

1. [Download][]
2. Unzip
3. Put the .app somewhere (/Applications/Utilities is as good a place as any)
4. Launch it once, to register it as the handler for `x-evernote://` URIs

URIs
----

At the moment the only thing you can do is trigger a search. Search URIs are in
the form `x-evernote://search?query={query}`. Once you finish the installation
steps above, you can try opening `x-evernote://search?query=test` in your
browser to trigger a search. It should launch Evernote, open a collection window
and search for "test".

Your search can include any of the advanced Evernote search operators, which are
actually pretty powerful. Check out the [Evernote search docs][] for details.

Why?
---

I've recently switched from [LaunchBar][] to [Alfred][]. Reading through some
[Alfred tips and tricks][], someone suggested adding a custom search for searching
in the Spotify app via its `spotify://` URI handler. I wanted a similar custom
search for Evernote, but it doesn't have a URI handler. AppleScript to the
rescue.

Of course, you could also use this script along with LaunchBar, Quicksilver,
etc. It just never occurred to me to use a local app's custom URI handler that
way until the Spotify suggestion. It's really handy!

Here's what my custom Evernote search looks like in Alfred:

![Alfred Config](https://raw.githubusercontent.com/rfletcher/Evernote-URI-Handler/master/images/alfred.png)


[Download]: Evernote-URI-Handler/zipball/master
[Alfred]: http://alfredapp.com
[Alfred tips and tricks]: http://alfredtips.tumblr.com/
[Evernote]: http://evernote.com
[Evernote search docs]: http://www.evernote.com/about/kb/article/advanced-search
[LaunchBar]: http://www.obdev.at/products/launchbar/
