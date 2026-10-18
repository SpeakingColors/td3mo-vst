# TD-3-MO: device notes

Source: Behringer TD-3-MO-SR / TD-3-MO-AM Quick Start Guide (PDF in our project files). Only what that guide prints is listed here.

## What the guide confirms

- Analog bass line synthesizer with a "MIDI-controllable VCF and sub-harmonics oscillator" (guide subtitle).
- USB port (item 44): class-compliant USB MIDI, plus MIDI IN and MIDI THRU on DIN. A 3.5 mm patchbay and CV IN exist.
- 13-note keyboard buttons for step entry, TIME MODE and PITCH MODE for pattern editing, Track Write / Track Play / Pattern Play modes.
- Panel controls: tune, cutoff, resonance, envelope mod, decay, accent, soft attack, filter FM, filter tracking, accent sweep, sub osc on/off, muffler (VCA soft clip), volume.

## What the guide does NOT contain

The quick start does not list a CC map, SysEx format or pattern dump format. Before building the controller we need:

1. The CC list for the VCF, sub oscillator and other MIDI-controllable parameters (Behringer MIDI chart or a capture).
2. Whether patterns can be sent and received over SysEx, and the byte layout.
3. USB MIDI port names on Linux.

Nothing is assumed in the meantime.
