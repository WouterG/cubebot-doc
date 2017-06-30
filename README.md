# CubeBot documentation

### Commands

arguments:

| typed | usage |
| --- | --- |
| argument | required argument |
| [argument] | optional argument |
| (argument/otherargument) | choose either argument |

| command | arguments | role | description |
| ----- | ----- | ----- | ----- |
| !theme | themename | Manager | Change the room theme. Use no arguments to list themes |
| !setrole | userid (rolename/roleid) | Manager | Set someone's role. Promotes up to Manager |
| !skip | | Bouncer | Skip the current song |
| !hangman | (start/stop) | Bouncer | Start/stop a game of hangman |
| !lock | [clear] | Bouncer | "!lock" locks the waitlist, "!lock clear" locks and clears the waitlist |
| !unlock | | Bouncer | Unlock the waitlist |
| !roll | [maxnumber] | Everyone | Roll a dice, maxnumber is the max, default is 6 |
| !g | (word/character) | Everyone | Guess either a word or a single character in hangman |
| !help | | Everyone | Link to the commands page |
