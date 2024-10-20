# Sendalo

Sendalo is a web/mobile interface to an emscripten build of the excellent c2t tool by datajerk. c2t is a really clever program that allows transferring disk images to a running Apple II (among other things).

[Try it online!](https://santandrea.net/sendalo)

## Why do I think this is useful?

The ASCII Express site is fun and a great idea, but it has limited selection.

ADTPro is fantastic! But you need a running modern PC, and some means of bidirectional communication to make it work. Ethernet cards are expensive, serial not readily available and audio mic input jacks are becoming difficult to find on modern laptops. And there is no mobile version.

c2t will work with just a simplex link, so all you need is an audio cable and there you go! But you still need another computer and typing commands in the terminal.

Finally, with this frontend you can unleash the power of c2t directly on your mobile device, with just an audio cable and no PC. Just paste the .dsk image URL from your favorite web archive, or upload your own, and the disk will be streamed over. Also nice on computers if you don’t want to download executables or type commands.

c2t can do a lot more than this, don’t forget to check the official project page on GitHub to learn more.

## Notes on code and licensing

Sendalo is licensed under the MIT License. I don't actually care, but this is something you have to do in 2022.

sendalo.wasm and sendalo.js are simple emscripten builds of vanilla c2t executables and do not constitute modified or derived works. c2t itself is licensed under the New BSD License. Full source code for the software can be found on the author's page.
