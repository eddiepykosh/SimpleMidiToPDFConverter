# SimpleMidiToPDFConverter
A Simple Midi to PDF Converter with a easy GUI

Needs the "LilyPond" folder in the same directory in order to function. 7z download covers that

Currently very poorly converts .MID/MIDI to PDF through LilyPond

Logic is as follows .MID/MIDI ---> .ly using midi2ly script, then .ly ---> .pdf using LilyPond.exe 

Does not do a good job on anything that is not STRICTLY Computer generated (ie work from the Python library "MIDIFile" comes out pretty good)


Download: https://github.com/eddiepykosh/SimpleMidiToPDFConverter/raw/master/Alpha%20v1.7z

Probably will crash because of missing Python libraries but god if I know what those libraries are.  (If you install LilyPond or already have LilyPond installed you'll probably be fine)


TODO abandon LilyPond

LilyPond Download - http://lilypond.org/download.html
