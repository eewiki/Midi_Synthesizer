# Midi_Synthesizer
This Pure Data program is a simple midi synthesizer.

# Setup
After Downloading Pure Data and setting up a midi connection, open the file *MidiSynth-main*. Be sure DSP is turned on in Pure Data  and slowly increase the volume on the computer. Volume knobs/sliders on the midi controller will have to be adjusted to begin their control.

# How it works
Each of the four files are a patch. The main patch contains the controls for the synth, the note patch produces each midi note, The adsr patch controls the volume envolope, and the tone patch uses additive synthesis to produce the sound.