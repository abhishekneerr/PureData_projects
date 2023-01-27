# PureData_projects
This repository consists of all the pure data patches I have worked/working on. Most of them are based on Pure Data-Vanilla.

### 1) Project: Mahasynth

#### Dependencies:
  Pd-Vanilla
  Externals:
    1)Zexy
    2)Cyclone

The patch is a work in progress of an additive synthesizer with additional features to shape the audio. 1 Basic functionality: 
The synthesizer consists of two oscillators that have an option to choose among three wave types (sine, saw and square), each wave has four harmonics, with the fundamental being the loudest and the rest 3 gradually decreasing in volume. Each oscillator gain can be controlled. Additionally each oscillator has a detuning factor and a low pass filter. The signal from the two oscillators is multiplied with an ADSR ramp followed by a final gain controller. 
Subsequently to play the notes a user can either use the keyboard as a MIDI device, or can toggle a random sequencer. The details of each of these controlling sections is given in the following parts of the report.

### 2) Granular + Ambient Synth

#### Dependencies:
 Pd-Vanilla
  Externals:
    1)Zexy
    2)Cyclone
    3)freeverb~
    
The abstractions and the audio files have to be in the same folder.
    
The patch has 3 major elements, a granular synthesizer, an ambient section and a drum section. The user can play an ambient pad melody generated using a random sequencer as well as soft drums, on top of which granular synthesized vocals can be played. 
The core of the patch is the granular synthesizer. Shown in the gray section of the main patch. The granular synthesizer consists of a grain abstraction shown in figure below. As well as some controlling elements to control the grain playback, randomly or precisely as the user likes. In parallel to the granular synth, there is a Pad and Melody section shown in the yellow area which triggers an ambient pad and a melody on top of that. Moreover, at the right of the patch, in green canvas, there are drum controls that help you play basic drum elements with other elements of the patch. Additionally there are basic controls and scopes to visualize the final output and control the functionality of the patch.

Patch in action: https://youtu.be/A9mo9o0KzYg
  

