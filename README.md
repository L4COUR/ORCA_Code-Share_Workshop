# ORCA_Code-Share_Workshop
## Setup
You can download [builds](https://hundredrabbits.itch.io/orca) for **OSX, Windows and Linux**, or if you wish to build it yourself, follow these steps:

- If you have Git, open up your terminal, or command-prompt(CMD).

```
git clone https://github.com/hundredrabbits/Orca.git
cd Orca/desktop/
npm install
npm start
```

or...

Go to their Website https://hundredrabbits.itch.io/orca, and download your corresponding build.

<img src="./media/download.png" alt="download" style="zoom:50%;" />

you can always open up Orca by running the terminal and typing in

```
cd Orca/desktop/
npm install
npm start
```

## What is Orca?

![](./media/Orca_Map.gif)

## How to manuever

- use the arrowkeys to move around the map
- "space-bar" to play or pause Orca
- (cmd/ctrl) + g = help overlay

## Hello World (using Pilot)

![](./media/Orca_Hello-World.gif)

Orca and Pilot can communicate with each other using UDP messages. These are symbolised with ";" in Orca. in this instance i have assigned the UDP-message with 3 parameters.

RED = UDP channels (0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F)

GREEN = Note value (2C = second octave, middle C)

BLUE = Bang! = "*" = Activates the message = micro compiling

- basic operators
- a quick example

## Connect Orca with?

### Free

- Pilot showcase, and same download process
- Zupitor web browser modular synth
- VCV Rack

### Not-free

- Max/MSP
- Ableton/ any DAW
- External Hardware Synths with Midi-inputs

### ways of communicating

- UDP = Pilot...
- MIDI = External Hardware, Ableton, VCV Rack, Zupitor, Max/MSP...
- OSC = Max/MSP...



## Sources

- https://z.musictools.live/
- https://vcvrack.com/
- https://github.com/hundredrabbits/Orca
- https://github.com/hundredrabbits/pilot

