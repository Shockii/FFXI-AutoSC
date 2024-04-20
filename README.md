AutoSC is not a tool I created and all rights reserved for the oringal creater. I left AutoSC intact in its entierty but just adjust some things.

I found that AutoSC, when enabling the 'Open new SC' function, only allowed for 1 value of tp to be set. So it would open with a weapon skill but if someone else opened, I was left waiting for AutoSC to kick in after the skill chain, as it wanted to open skill chains, and wouldn't fire during someone elses.

I added another value for tp, opentp, to allow for you to set two tp values. One that is used by the 'Open new SC' function, while allowing for a value for tp to still function with normal skill chains started by others.

In an example, I would set the min value for tp to use for others, 'tp' to 1200, and when anyone started a skill chain, if I have a value of 1200 or greater, it would use a weapon skill for the chain.
While, I would set my 'opentp' to 2500, so that if for some reason I had a ton of tp and had not utilized it during a skill chain, that it would fire off a selected skill for the opener.

This requires you to enable 'Open new SC' as well as set a  default skill to use for the opener.

* opentp <number> - minimum TP to use a set opener skill, set with the <ws name> command
* ws <ws name> - Will set the WS to use for opening a SC and the _open_ option is toggled on.
* open - Toggle whether or not the set WS should be used to open fresh SCs when no SC effect is already present.

With these three values set, you can fire off solo skill chains and join in on others.
