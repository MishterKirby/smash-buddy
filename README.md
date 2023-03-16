# Super Smash Bros. Ultimate Training Buddy

A fork of a fork of a fork of a fork, modified to act as player 2 doing random moves in Super Smash Bros. Ultimate so I can train more effectively.

See previous projects for some more detailed information / setup process.

---

LUFA has been included as a submodule, so cloning the repo like this will put LUFA in the right directory:

```
git clone --recursive https://github.com/MishterKirby/smash-buddy.git
```

Now you should be ready to compile. Run `make` in the root directory, then flash the resulting `Joystick.hex` onto your Arduino.

#### Thanks

Thanks to https://github.com/kidGodzilla/woff-grinder for making me stumble upon this project in the first place

Thanks to https://github.com/bertrandom/snowball-thrower for the updated information which modifies the original script to throw snowballs in Zelda. This C Source is much easier to start from, and has a nice object interface for creating new command sequences.

Thanks to Shiny Quagsire for his [Splatoon post printer](https://github.com/shinyquagsire23/Switch-Fightstick) and progmem for his [original discovery](https://github.com/progmem/Switch-Fightstick).

Thanks to [exsilium](https://github.com/bertrandom/snowball-thrower/pull/1) for improving the command structure, optimizing the waiting times, and handling the failure scenarios. It can now run indefinitely!
