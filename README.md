# bitbrawler

![main](./main.png)


```sh
ripec -l raylib -l m -l X11 -o bitbrawler main.rp
./bitbrawler
```

robot combat arena where each robot is written in Ripe and compiled before match.

i'll be tiny Ripe programs fight in a simulation

- raylib for the ui and arena
- comic neue for the ui and iosevka for code
- editor and simulation side by side
- robot decision logic with fire(), move(), tick(), etc
- bots compiled through the qbe backend
- c abi between the arena and bots
- fixed tick simulation
- ticket budget and process sandbox
- switching between bots
- recompile and hot reload


plans

- static mockup
- responsiveness / basic buttons
- editable text buffer (most of my problems)
- save file / invoke ripec
- fixed tick arena + robots
- ripe bot abi
- bot switch / recompile
- isolate / ticket accounting

the hard part is going to come with the editors. i need to start
thiking about owned mutable text

- strings
- growable arrows
- alloc
- utf8 index
- modules
- files
- child processesgit reset HEAD / pipe
- diagnostic
the list goes on...
