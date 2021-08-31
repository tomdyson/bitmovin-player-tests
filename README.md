# Bitmovin player tests

Set open CORS policy on the VTT file, e.g. with

`s3cmd setcors cors.xml s3://tom/share/waste-land.vtt`

Use
[chromecast.link](https://chromecast.link#title=Sideloaded+subtitle+test&content=https://s3.eu-west-2.amazonaws.com/tom.roh.video.output/10655/manifest.mpd&subtitles=https://tom.s3.amazonaws.com/share/waste-land.vtt)
for testing Chromecast support.

Pages are built on Netlify, at https://bitmovin-player-tests.tomd.org
