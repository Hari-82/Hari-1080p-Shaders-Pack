# Hari-1080p-Shaders-Pack

Shaders presets pack for retroarch and 1080p display based on [guest r shaders for retroarch](https://forums.libretro.com/t/new-crt-shader-from-guest-crt-guest-advanced-updates/25444) 


[Libretro Forum post](https://forums.libretro.com/t/haris-1080p-shaders-presets-screenshots/43734)


As per title, those are the shaders presets that I currently use, I use them on a 24", 1080p desktop monitor that I keep fairly close to me (50/70 cm), with few [simple overlays](https://forums.libretro.com/t/overlays-and-integer-scaling/43557) to fill up the screen.

**Those presets are made to be used on a 1080p native resolution monitor.** 

This “use case” can be very narrow but maybe it can still be useful to someone! if you are playing on a native 1080p desktop monitor (or tv?) maybe this can help or maybe can be a starting point for your own presets!




**Integer scaling** is highly recommended with most of my presets: 

> Settings -> Video -> Scaling -> Integer Scaling -> ON

The reason to use Integer scaling is due to unwanted moire effect that un-even scanlines can produce when Integer Scaling is turned off. Also, without Integer scaling, pixels lose their original ratio (square) and can be deformed, generating, sometimes, weird effects. 


If brightness is too much/too low try to increase/decrease Post Brightness, this is not the proper way to do it but its a simple way to adjust it, you can find it in:

`Quick Menu -> Shaders -> Shader Parameters ->` scroll to the very bottom (or just wrap around and go up : )

if you feel that the game-screen is too small for you try to turn on overscale:

> Settings -> Video -> Scaling -> Integer Scale Overscale -> ON
 
I personally do not use much the overscale option but in some situation can be a good way to fill up the screen.

Those presets do not aim to replicate any particular analog TV set/monitor/connection, they are just tailored to my taste and most important to my 1080p monitor.

All the shader's presets in this pack are basically revolving around only 2 main presets: one for  **guest's advance** and one for **guest's ntsc shaders**. This will make the process of updating/refining/modifing very easy. 

_________________________________________


To install:

 Simply extract the “hari” folder and place it anywhere in your Retroarch main folder, but for easy of use I suggest to place it either in shaders_slang or in the main shader's directory.

Retroarch_main_folder/shaders/hari/

or 

Retroarch_main_folder/shaders/shaders_slang/hari/

--------------------Important--------------------

you need to have the latest guest.r's shaders installed: Main Menu -> Online Updater -> Update Slang Shaders.

--------------------Important--------------------

_________________________________________

Comments and suggestions at [Libretro Forum post](https://forums.libretro.com/t/haris-1080p-shaders-presets-screenshots/43734)

Shaders used:

    Guest's Advance [crt-guest-advanced.slangp]
    Guest's NTSC [crt-guest-advanced-ntsc.slangp]
    Hyllian' CRT [crt-hyllian.slangp]
    Grade [grade.slangp]
    Scale fx + aa [scalefx+rAA+aa-fast.slangp]
    XBR LVL2 [xbr-lv2.slangp]
    XBRZ 4X Linear [4xbrz-linear.slangp]
    smaa linear [smaa+linear.slangp]


Special Thanks to guest.r and his [wonderful work](https://forums.libretro.com/t/new-crt-shader-from-guest-crt-guest-advanced-updates/25444) and to all the libretro’s shader community!
