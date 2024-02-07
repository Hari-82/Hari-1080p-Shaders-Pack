# Hari-1080p-Shaders-Pack

Shaders presets pack for retroarch and 1080p display based on [guest r shaders for retroarch](https://forums.libretro.com/t/new-crt-shader-from-guest-crt-guest-advanced-updates/25444) 


[Libretro Forum post](https://forums.libretro.com/t/haris-1080p-shaders-presets-screenshots/43734)


As per title, those are the shaders presets that I currently use, I use them on a 24", 1080p desktop monitor that I keep fairly close to me (50/70 cm), with few [simple overlays](https://forums.libretro.com/t/overlays-and-integer-scaling/43557) to fill up the screen.

**Those presets are made to be used on a 1080p native resolution monitor.** 

This “use case” can be very narrow but maybe it can still be useful to someone! if you are playing on a native 1080p desktop monitor (or tv?) maybe this can help or maybe can be a starting point for your own presets!




**Integer scaling** is highly recommended with most (see below) of my presets: 

> Settings -> Video -> Scaling -> Integer Scaling -> ON

The reason to use Integer scaling is due to unwanted moire effect that un-even scanlines can produce when Integer Scaling is turned off. Also, without Integer scaling, pixels lose their original ratio (square) and can be deformed generating, sometimes, weird effects. 

I personally do not use much the overscale option but in some situation can be a good way to fill up the screen.

If brightness is too much/too low try to increase/decrease Post Brightness, this is not the proper way to do it but its a simple way to adjust it, you can find it in:

`Quick Menu -> Shaders -> Shader Parameters ->` scroll to the very bottom (or just wrap around and go up : )

if you feel that the game-screen is too small for you try to turn on overscale:

> Settings -> Video -> Scaling -> Integer Scale Overscale -> ON
 
I personally do not use much the overscale option but in some situation can be a good way to fill up the screen.

Those presets do not aim to replicate any particular analog TV set/monitor/connection, they are just tailored to my taste and most important to my 1080p monitor.

All the shader's presets in this pack are basically revolving around only 2 main presets: one for  **guest's advance** and one for **guest's ntsc shaders**. This will make the process of updating/refining/modifing very easy. 

Those presets are based on mask 9 and its properties tied to 1080p native resolution display ( [more info here](https://forums.libretro.com/t/new-crt-shader-from-guest-crt-guest-advanced-updates/25444/4149?u=hari-82)), this means that to have those presets do what they are supposed to do they have to be used on a native 1080p monitor. Also, screenshots do not tell whole story as there is a difference on how the look (zoomed in) and how they actually look on the real display.

screenshot - monitor photo

![screenshot vs monitor](https://github.com/Hari-82/Hari-1080p-Shaders-Pack/assets/59340968/c0d1b569-07df-4c2f-9704-db7b87c845d0)


My presets are divided in different folders:


**0 - Quick Selection**  (Highly recommended to use with Integer Scaling)

This is Just a collection of 5 different looks for easy and quick selection

**1 - Standard** (Highly recommended to use with Integer Scaling)

This are based on Guest’s Advanced shader, they are divided by mask type and can be used with any “standard” 8-16 bit system and also for non-upscaled gen. 5, no “composite transparency” effect. Generally sharp and tidy.

**2 - NTSC** (Highly recommended to use with Integer Scaling)

This are based on Guest’s NTSC shader, again, they are divided by mask type. They do have the “composite transparency” effect (sonic waterfalls). Generally Less sharp then the previous folder and more “grungy”, still very usable in any 8-16 bit systems and also for non-upscaled gen. 5 and recommended for Mega Drive/ Genesis (love them with C64)!

**3 - Edge Smoothing** (Highly recommended to use with Integer Scaling)

Those have some level of edge smoothing effects, they are very sharp and clear but still use scanlines and a mask for a crt effect. Nice with late 90s early 2000s Snk and Capcom fighting games, but can be used in any 8, 16 and 32 bit system. 

Note: presets from `/3 - Edge Smoothing/Slot Mask/No scanlines/` can be used in any situation and also for non-integer scaled content. 

**4 - Tate** (No need for Integer Scaling)

This, as the name suggest, is for Vertical arcade games and can be used with no integer scaling: most games will do fine (80s - early 90s) with the first preset but in more recent one a little moire can appear, in that case I suggest to use other options in this folder.

**5 - Upscaled Internal Resolution** (No need for Integer Scaling)

Those presets are meant to be used with PS1, N64, Dreamcast and Naomi with upscaled internal resolution: there is a mask but no scanlines. I’m very happy with the result with those and they are my presets of choice to play generation 5 3D games. give it a shot!

Note: The 2 presets in the main folder are generic and can be used with any upscaled content, I also include some alternatives for some specific systems if you want a different look. 

**9 - Extra**

   **1 - Megabezel**

This are 3 presets adapted for the [Megabezel project](https://forums.libretro.com/t/mega-bezel-reflection-shader-feedback-and-updates/25512/6723), as per usual with Megabezel: Integer scaling **must be** turned OFF and aspect ratio set to Full.

> Settings -> Video -> Scaling -> Integer Scaling -> OFF
> 
> Settings -> Video -> Scaling -> Integer Scale Overscale -> OFF
> 
> Settings -> Video -> Scaling -> Aspect Ratio -> FULL

   **2 - Systems**

currenty empty, WIP.

   **3 - Heavy Dedithering**

this are 2 presets that are meant to be used with games that use some heavy dithering patterns (ie. videos in Flasback for Sega Mega-CD). 


base: this is a service folder.


_________________________________________


To install:

 Simply extract the “hari” folder and place it anywhere in your Retroarch main folder, but for easy of use I suggest to place it either in shaders_slang or in the main shader's directory.

Retroarch_main_folder/shaders/hari/

or 

Retroarch_main_folder/shaders/shaders_slang/hari/

_________________________________________

Comments and suggestions at [Libretro Forum post](https://forums.libretro.com/t/haris-1080p-shaders-presets-screenshots/43734)

Shaders used:

    Guest's Advance [crt-guest-advanced.slangp]
    Guest's NTSC [crt-guest-advanced-ntsc.slangp]
    Grade [grade.slangp]
    Scale fx + aa [scalefx+rAA+aa-fast.slangp]
    XBR LVL2 [xbr-lv2.slangp]
    XBRZ 4X Linear [4xbrz-linear.slangp]
    smaa linear [smaa+linear.slangp]
    Ps1 boxblur [ps1-dedither-boxblur.slangp]
    Megabezel gdv [MBZ__3__STD__GDV.slangp]
    Megabezel gdv NTSC [MBZ__1__ADV__GDV-NTSC.slangp]


Special Thanks to guest.r and his [wonderful work](https://forums.libretro.com/t/new-crt-shader-from-guest-crt-guest-advanced-updates/25444) and to all the libretro’s shader community!
