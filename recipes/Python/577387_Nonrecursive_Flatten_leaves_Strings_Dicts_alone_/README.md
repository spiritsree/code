## Non-recursive Flatten, leaves Strings and Dicts alone, minimal type assumptions, with tests  
Originally published: 2010-09-09 23:58:03  
Last updated: 2010-09-10 00:10:47  
Author: Manuel Garcia  
  
I have written Flatten a few dozen times, and also searched the interwebs - I don't feel good about a heavily recursive function for Python, and some of the "type-sniffing" I saw in some codes seemed fishy - so I coded up this version.  At least this increases the options.