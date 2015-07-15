#### Intro

These are quick and dirty firmwares in various stages of completeness. Source code will follow once I tidy up and release the pot library they use.

#### Bounce
Trigger input using RESET CV

Trigger output on OUT

To-do: knobs adjust gravity and bounce, alternative mode where OUT is related to height



#### Drum Machine

Trigger drum 1 using START CV

Trigger drum 2 using RESET CV

Trigger output on OUT

Change drums with pots — STATION = drum 1, START = drum 2

To-do: sort out bass drum sample, add ability to change volume of each drum, add accent on drum 1 with START CV



##### Drum Sequencer

STATION pot = odd divider

START pot = even divider

Trigger output on OUT

To-do: change dividers using CV inputs



#### Sampler

CV/Audio input using STATION

Trigger record using RESET

Trigger play using START

Audio/CV output using OUT

Trim sample using knobs — STATION = offset, START = length

Tips: set STATION pot to 0, START pot to 100% to play full length sample

To-do: reset button to change between one-shot and cycle modes
