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
