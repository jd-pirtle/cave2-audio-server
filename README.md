##cave2-audio-server##


###This is an audio server for the CAVE2 Hybrid Reality Environment at the [Electronic Visualization Lab](http://www.evl.uic.edu/index.php "Electronic Visualization Lab").###

The goal of this work-in-progress is to provide CAVE2 developers with a simple way to trigger, place and update sounds in virtual space.  The server is implemented in Supercollider, and works in concert with a  [C++ API](https://github.com/uic-evl/omicron/wiki/SoundAPIReference "c++ API") developed by Arthur Nishimoto.  

The C++ API preps and sends simple OSC messages to Supercollider (e.g. play, stop).  The audio server should work with any process capable of sending OSC messages.
