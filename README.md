# CubeBot documentation

### Commands

arguments:

| typed | usage |
| --- | --- |
| argument | required argument |
| [argument] | optional (partial) argument |
| (argument/otherargument) | choose either (partial) argument |

Bouncer+ is a role that can be set with !setrole and !setroleid, using the `bouncerplus` name as role argument. It makes the user a bouncer but grants additional permission to Bouncer+ permissions.

| command | arguments | role | description |
| ----- | ----- | ----- | ----- |
| !setroleid | userid (rolename/roleid) | Co-Host | Set someone's role, also searches existing staff if offline |
| !setrole | (userid/[@]username) (rolename/roleid) | Manager | Set someone's role. Promotes up to Manager |
| !theme | themename | Bouncer+ | Change the room theme. Use no arguments to list themes |
| !skip | | Bouncer | Skip the current song |
| !hangman | (start/stop) | Bouncer | Start/stop a game of hangman |
| !lock | [clear] | Bouncer | "!lock" locks the waitlist, "!lock clear" locks and clears the waitlist |
| !unlock | | Bouncer | Unlock the waitlist |
| !userinfo | (userid/[@]username) | Resident DJ | Get someone's woots and role |
| !roll | [maxnumber] | Everyone | Roll a dice, maxnumber is the max, default is 6 |
| !g | (word/character) | Everyone | Guess either a word or a single character in hangman |
| !help | | Everyone | Link to the commands page |
