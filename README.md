imapsync UI
===========

This is a UI for [imapsync](http://imapsync.lamiral.info/)

Main website is hosted by GitHub [here](http://alexandernst.github.io/imapsync_ui)

![Screenshot](https://raw.githubusercontent.com/alexandernst/imapsync_ui/148c7a79641989264c39ebc6a70ed76080d4d25b/imapsync_ui.png)

As you can see, some options are still missing. I have added the basic (and most used) ones.
Please feel free to send me patches if you miss some extra options.

The license is `WTFPL` so you're allowed to do whatever you want with the code. It's provided
as-is, and I'm not responsible for any damage or data loss.

Building
=====

You'll need `Qt 5.x` and `cmake`, or `QtCreator`.
There is nothing special about the code; just open the project and hit the build button.

Using
=====

Place your copy of `imapsync.pl` in the same folder as this project's binary and give execute
permissions to it (`chmod +x imapsync.pl`), then run the UI.