podcast-timer
=============

A very simple Java GUI for timing podcasts (generating chapter marks). Released under the MIT license.

Usage
-----

At the moment this really is as simple as it gets:

1. Press the "Start Timer" button as you start recording your podcast.
2. Press the "Enter Chapter" button when a new chapter starts.
3. A dialog will pop up, asking you for a chapter title.
4. Enjoy your chapters!

NOTE: The Podcast timer will substract 5 seconds from each of the chapter time stamps in order to compensate for slowness when entering them.

Chapter format
--------------

The chapter marks follow this format:
<pre>
hh:mm:ss.000 Chapter 1
hh:mm:ss.000 Chapter 2
</pre>
The advantage of this format is that it is understood by http://auphonic.com which I use for podcast postproduction.

Download
--------

You can find a pre-built runnable jar file <a href="https://docs.google.com/file/d/0B9sn6KPUPAjsTWVGTUE3djFtdFk/edit">here</a>. However, this might not be current.
