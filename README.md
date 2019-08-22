# MidiRouterTool
Software MIDI router from input/output devices and MIDI ports on PC. Main purpose is Arduino MIDI synth development

The tool is a modification of JUCE Example "MIDI Demo", where MIDI messages, from all selected inputs are forwarded to the selected outputs.
Also, it repeats the last note hit on the keyboard - in cycles and lengths specified with sliders on botton.

With this tool I became able to upload a new firmware build (from Visual Studio Arduino extension) on arduino board, without disconnecting MIDI controler and my Arduino Pro Micro based synth.

# There is really no such tool on :)
After hours of searching and testing all possible MIDI tools available, 
I found no solution needed to streamline development of the synth.
The closest candidate was http://projectgus.github.io/hairless-midiserial/, but it couldn't forward MIDI messages (despite it looks like it should).



