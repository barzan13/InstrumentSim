# InstrumentSim

InstrumentSim is a Windows desktop instrument simulator project.

The long-term vision is to create a visually interactive instrument environment where users can play, record, and eventually edit musical performances.

## Core Vision

The application should eventually support:

- Visual representations of instruments
- Real-time visual feedback while notes are playing
- Recording and playback systems
- MIDI support
- Multiple instrument types
- Audio experimentation and editing
- Keyboard, mouse, MIDI, and controller input

## Planned Development Path

### Phase 1
- Basic Windows application
- Piano-style interface
- Mouse and keyboard note input
- Visual note highlighting
- Basic sound playback

### Phase 2
- MIDI input support
- Improved audio engine
- Instrument modularity
- Better UI and animations

### Phase 3
- Recording system
- Playback timeline
- Session saving/loading

### Phase 4
- Audio editing experimentation
- Effects and processing
- Expanded instrument support

## Recommended Technology

Recommended stack:

- C#
- .NET
- WPF

WPF is a strong starting point because it handles custom visuals well and has a mature Windows ecosystem.

## Repository Structure

```text
InstrumentSim/
├── docs/
├── src/
├── assets/
└── README.md
```

## First Prototype Goal

Create a playable on-screen piano keyboard that:

1. Plays notes
2. Highlights active keys visually
3. Supports mouse and keyboard input
4. Establishes the architecture for future instruments
