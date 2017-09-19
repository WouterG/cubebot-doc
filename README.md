# CubeBot documentation

### Commands

arguments:

| typed | usage |
| --- | --- |
| argument | required argument |
| [argument] | optional (partial) argument |
| (argument/otherargument) | choose either (partial) argument |

| command | arguments | role | description |
| ----- | ----- | ----- | ----- |
| !setroleid | userid (rolename/roleid) | Host | Set someone's role, also searches existing staff if offline |
| !setrole | (userid/[@]username) (rolename/roleid) | Manager | Set someone's role. Promotes up to Manager |
| !theme | themename | Bouncer | Change the room theme. Use no arguments to list themes |
| !skip | | Bouncer | Skip the current song |
| !hangman | (start/stop) | Bouncer | Start/stop a game of hangman |
| !lock | [clear] | Bouncer | "!lock" locks the waitlist, "!lock clear" locks and clears the waitlist |
| !unlock | | Bouncer | Unlock the waitlist |
| !move | (userid/[@]username) position | Bouncer | Move someone to the position on the waitlist, e.g: `!move @Wouto1997 2` |
| !remove | (userid/[@]username) | Bouncer | Remove the user from the DJ booth/waitlist |
| !userinfo | (userid/[@]username) | Resident DJ | Get someone's woots and role |
| !join | | Resident DJ | force-join the waitlist |
| !roll | [maxnumber] | Everyone | Roll a dice, maxnumber is the max, default is 6 |
| !g | (word/character) | Everyone | Guess either a word or a single character in hangman |
| !help | | Everyone | Link to the commands page |
