# Mini project — Interactive DJ System with Pure Data and OSC Controller
## Description
This project consists of developing an interactive DJ system built in Pure Data (PD) and remotely controlled through the OSC Controller app, which uses the Open Sound Control (OSC) protocol to send data from a mobile device.

The system allows users to mix audio tracks, apply real-time sound effects, and manipulate sonic parameters (volume, crossfader, delay, reverb, filter, etc.), emulating the behavior of a physical DJ console.
It integrates tactile controls from the phone (sliders, buttons, and 3D touch zones) to create a smooth and performative experience.

## Objective

Design an interactive environment that enables:

Control of two audio tracks (Deck A and Deck B) from a mobile interface.

Real-time sound effect processing (delay, reverb, filter, kill switch, one-shot effects).

Continuous (volume, mix, pitch) and discrete (on/off, triggers) control.

Use of Pure Data as the sound processing engine and OSC Controller as the wireless control interface.

## Implementation

Software used:

Pure Data — audio processing and modular system design.

OSC Controller — tactile interface for sending OSC messages over Wi-Fi.

System structure:

Main patch: connects all modules and manages global signal flow.

Deck A / Deck B: playback modules with independent volume and pitch control.

Crossfader: blends both decks.

MasterVol: overall volume output.

FX Modules:

Delay: adjustable echo with feedback control.

Reverb: ambient effect with depth parameter.

Filter: low-pass filter controlled via sliders or 3D touch.

Kill switch: temporary sound cut.

One-Shot FX: short synthesized effects created directly in PD (horn, snare, crash, riser).

## Video

[Video](https://www.youtube.com/watch?v=TU_VIDEO_ID)
