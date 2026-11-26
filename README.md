# x2gif
shell script to record your x11 display device and convert it to a gif

# install
1.) install ffmpeg 

2.) run shell script

3.) if you want, add it to your path to run it anywhere

# usage
the script accepts 1 argument, the amount of time to record. it accepts the time in seconds or any time format that works with ffmpeg

# issues
this isn't really an issue but by default it records at 1280x720. you have to change this by editing the script in a text editor. this is because, generally, the monitor you use on a computer stays the same size over time, so it's easier to edit the shell script one time rather than type the resolution every time.

# where it works
tested: linux device with x11

probably works: bsd family with x11

probably doesn't work: non x11 systems

definitely doesn't work: windows or macos>10
