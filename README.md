# PureData_projects
This repository consists of all the pure data patches I have worked/working on. Most of them are based on Pure Data-Vanilla.

Project: Mahasynth

Dependencies:
  Pd-Vanilla
  Externals:
    1)Zexy
    2)Cyclone

The patch is a work in progress of an additive synthesizer with additional features to shape the audio. 1 Basic functionality: 
The synthesizer consists of two oscillators that have an option to choose among three wave types (sine, saw and square), each wave has four harmonics, with the fundamental being the loudest and the rest 3 gradually decreasing in volume. Each oscillator gain can be controlled. Additionally each oscillator has a detuning factor and a low pass filter. The signal from the two oscillators is multiplied with an ADSR ramp followed by a final gain controller. 
Subsequently to play the notes a user can either use the keyboard as a MIDI device, or can toggle a random sequencer. The details of each of these controlling sections is given in the following parts of the report.


