# OpenStream Architecture

## Host

Windows gaming PC.

Responsibilities:

- Game discovery
- Game launching
- Desktop/game capture
- Hardware video encoding
- Audio capture
- Input injection
- Session management

## Client

Android tablet.

Responsibilities:

- Device pairing
- Game library
- Hardware video decoding
- Audio playback
- Controller input
- Keyboard/mouse
- Touch controls
- Diagnostics

## Network

Preferred topology:

    Windows PC
         |
    Private network / Meshnet
         |
    Android tablet

## Video

Codec negotiation preference:

    AV1
     |
    HEVC
     |
    H.264

Actual selection depends on hardware and client support.

## UX

OpenStream has its own user interface.

The UI must not expose the legacy Sunshine web interface
or Moonlight interface to the user.
