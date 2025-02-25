# Bedrock
Limitador de mundos para minetest editado por josegamestest "joseanastacio"

Bedrock for [Minetest](https://www.minetest.net/), a free and open source infinite
world block sandbox game.

[**Forum topic**](https://forum.minetest.net/viewtopic.php?f=11&t=9231)

## Installation

### Download the mod

To install Bedrock, clone this Git repository into your Minetest's `mods/`
directory:

```
git clone https://github.com/Calinou/bedrock.git
```

You can also
[download a ZIP archive](https://github.com/Calinou/bedrock/archive/master.zip)
of Bedrock. If you do so, you will need to extract the archive, then rename
the resulting folder from `bedrock-master` to `bedrock` – this is
**absolutely** necessary to do, else, it won't work!

### Enable the mod

Once you have installed Bedrock, you need to enable it in Minetest.
The procedure is as follows:

#### Using the client's main menu

This is the easiest way to enable Bedrock when playing in singleplayer
(or on a server hosted from a client).

1. Start Minetest and switch to the **Local Game** tab.
2. Select the world you want to enable Bedrock in.
3. Click **Configure**, then enable `bedrock` by double-clicking it
   (or ticking the **Enabled** checkbox).
4. Save the changes, then start a game on the world you enabled Bedrock on.
5. Bedrock should now be running on your world.

#### Using a text editor

This is the recommended way to enable the mod on a server without using a GUI.

1. Make sure Minetest is not currently running (else, it will overwrite
   the changes when exiting).
2. Open the world's `world.mt` file using a text editor.
3. Add the following line at the end of the file:

```
load_mod_bedrock = true
```

If the line is already present in the file, then replace `false` with `true` on that line.

4. Save the file, then start a game on the world you enabled Bedrock on.
5. Bedrock should now be running on your world.

## Version compatibility

Bedrock is currently primarily tested with Minetest 0.4.16.
It may or may not work with newer or older versions. Issues arising in older
versions than 0.4.16 will generally not be fixed.

## License

Copyright © 2011-2017 Hugo Locurcio and contributors

- Bedrock code is licensed under the zlib license, see
  [`LICENSE.md`](LICENSE.md) for details.
- Unless otherwise specified, Bedrock textures are licensed under
  [CC BY-SA 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/).
