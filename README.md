#### Intro

These are quick and dirty firmwares in various stages of completeness. Source code will follow once I tidy up and release the pot library they use.

#### Bounce
Trigger input using RESET CV

Trigger output on OUT

Control gravity and bounce with station and start pots — start with them somewhere in the middle

Switch between trigger and CV out with the reset button

To-do: play with state of ball when triggered- relate to current environment



#### Drum Machine

Trigger drum 1 using START CV

Trigger drum 2 using RESET CV

Audio output on OUT

Change drums with pots — STATION = drum 1, START = drum 2

To-do: sort out bass drum sample, add ability to change volume of each drum, add accent on drum 1 with START CV



##### Drum Sequencer

STATION pot = odd divider

START pot = even divider

Trigger output on OUT

To-do: change dividers using CV inputs



#### CV/Audio Sampler

CV/Audio input using STATION

Gate record using RESET (records for length of gate)

Trigger play using START

Audio/CV output using OUT

Trim sample using knobs — STATION = offset, START = length

Tips: set STATION pot to 0, START pot to 100% to play full length sample. If you're using audio then you need to play about with attenuating and offseting the signal using something like an MI Shades module as the CV inputs on Radio Music are only 0-3v

To-do: reset button to change between one-shot and cycle modes


#### Clock Multiplier

Clock input using RESET

Clock multiplier using STATION POT

CV control of multiplier using STATION CV

Trigger output using OUT

Tips: Station pot controls multiplier from 1 to 32; Station CV control adds to this 0 to 32. LEDs show current multiplication in binary.
