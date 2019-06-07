# es-theme-minimal

**Words from the author**

> This theme is an attempt at making EmulationStation look more like a game system.

> Modern Game Systems (PS4, Xbox One, Switch, etc.) deliver a very specific experience compared to a computer. You turn it on, see a simple boot screen, and are in the menu in seconds. You know what you are getting in to. It's made abundantly clear that this is a video game machine. The games are front and center, and everything is wrapped up in a clean, minimal, interface...

> That is what I believe sets a game system apart from the Raspberry Pi. Sure, the interface is fast, and somewhat nice looking. But it doesn't feel like a video game system. This is where the Minimal theme steps in.

**This theme was made by lilbud / https://github.com/lilbud/es-theme-minimal**

---

# Abilities

This theme is super sleak and you can set VRAM to 40MB on a Raspberry system. \
So this is the sleakest theme as far as I know. \
\
This theme is highly customizable, you can change from **three** amazing layout by altering `theme.xml`\
Version 1 gets the original theme setting back as it was released 2017 as version 2 gets a modernized layout in game listing. This one is setted to default. You can always add new backgrounds to the theme by altering the `bg.png` file. \
\
You can get rid off the "blurry" looking overlay by altering the overlay color inside the version assets, by removing the color code line.
```
		<image name="background" extra="true">
			<size>1 1</size>
			<pos>0 0</pos>
			<origin>0 0</origin>
			<path>./../assets/bg.png</path>
			<zIndex>0</zIndex>
			<color>10667f</color>
		</image>
```

# Changes

2019/06/05

Added background image from Minimal v1 to `_extras` \
Enabled help system, this is can be disabled/enabled into ES now

2019/06/06

Added picture for Screenshots (BATOCERA/RECALBOX), own creation \
Added picture for ZX81, GX68000 and recolored Virtual Boy and Odyssey2 (=VIDEOPAC) \
Added picture for prboom (thx norbert79 from devianart for the B/W UAC graphics)

2019/06/07

Added background from theme version 1.0 as default (the hexagons)
Reencoded some files that were named as PNG but were JPG files

# Preview

Get in touch with the original theme author in [this thread via RetroPie Forum](https://retropie.org.uk/forum/topic/12435/)


![](https://i.imgur.com/5UR5yTF.png)

