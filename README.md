<h1 style="text-align:center"><img src="https://i.imgur.com/dHpUAIh.png"></h1>

Music-js is a music visualization program that includes many built-in
customization options for a playlist of music. Provided links to
MP3, Ogg Vorbis, and/or WebM sound files, it can create a real-time
visualization of the music as it plays, using the HTML5 Audio API.

This application supports visualization of external sound files,
enabling this to easily become a plugin for other sites.

Documentation will be added in another update. For now, refer to the
JSON object in ``index.html`` under ``/static`` for a demonstration
of customizable attributes.

To install this server, you need node.js. Once that's installed, run

```
git clone https://github.com/patrickroberts/music-js.git
cd music-js/static/
mkdir media
```

At this point you should add a ``music.mp3`` to the ``media`` folder. After
that, return to the terminal or command prompt and run

```
cd ..
npm install
```

then run ``app.cmd`` (or ``node app.js`` if you prefer commandline or
your OS doesn't support batchfiles) and open <http://localhost:8080>.
