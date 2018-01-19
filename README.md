# MIDIoke
voice to midi

Read the report 'midioke-transforming-human.pdf' for more information or visit the [demo_site](http://liacs.leidenuniv.nl/~s1420062/MIDIoke/home.html)

#### To run MIDIoke you first need to install these packages:
 pyaudio, 
 struct,
 math,
 matplotlib,
 numpy,
 midiutil,
 scipy,
 matplotlib

Then when you run MIDIoke.py you will first be asked for how long you want to run the program. Just enter a number and MIDIoke will run for that many seconds.


You will see a graph while it is running. This graph shows you the detected pitch, the energy and the energy-threshold.
Once the set time has run out the graph will freeze.
If you close the graph your MIDI will be written to the file named: "outPut.mid"
