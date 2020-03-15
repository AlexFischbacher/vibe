# vibe, the enhanced osu! editor
vibe is a beatmap editor for the [osu!](https://osu.ppy.sh/home) rhythm game, written with C and SDL2. vibe aims to improve the experience of osu! editing by reducing the amount of repetitive actions, implementing specific features through the Guile Scheme extension system, and allowing mappers to collaborate in real-time.

## Features
 - **A library to store patterns and sliders.** Never again need to redraw the same wave slider over and over again. Simply save a pattern or a slider to the library, and paste it wherever or whenever you need. Patterns saved with the library are context-sensitive, and will not place bad simply due to changing bpm throughout maps!
 - **An alternative keyboard-centric and vi-inspired editing experience.** vibe has the ability to be turned into a vi-like editor, with modes, motions, and operators. The efficiency of using this setup is definitely worth learning, but is not enabled by default to support those that transfer from the original osu! editor.
 - **An extreme improvement of osu!catch mapping.** Vibe is a fully functional osu!catch editor, meaning testing maps is no longer necessary to map Catch the Beat.
 - **Bookmark labels.** vibe has support for bookmark labels in the form of comments parsed from .osu files to allow mappers to logically organize a map and quickly go between sections of a map.
 - **Faster dilation and rotation of objects and patterns.** Inspired by photo editors, vibe makes it very easy to quickly turn or scale things.
 - **In-editor modding.** You should never need to leave the editor to suggest changes to a map.
 - **Improved hitsounding and timing.** Copy complex timing between difficulties with an improved object resnap, and allow for keybinds that select patterns of object rhythm to allow for insanely fast hitsounding.
 - **Jury, the map checker.** Jury is an advanced osu! map checker that can check and automatically refactor objects that break the ranking criteria. Jury will have multiple front-ends, including a web version, a standalone Qt application, and the implementation for vibe.
 - **Live, collaborative mapping.** Passing .osu files between collaborators is tedious and inefficient. With live editing, vibe gives mappers the power to work together and allows mentors to demonstrate concepts to mentees in real time.
 - **Plugins made with Guile Scheme.** As vibe is created with the power of C, Guile Scheme is leveraged to allow user-created plugins. *Please note: community-made plugins have the potential to be dangerous. A list of approved extensions is located at the wiki. Never download untrusted software to your computer, as you run the risk of installing malcious code. You have been warned.*
 - **Reverse distance snap.** Repairing a pattern that uses distance snap? Simply swap the distance snap mode and restrict movement to an area around the object that comes after the object you are placing!
 - **Support for custom snapping.** Avoid needing to change BPM to use snaps like 1/5 or 1/7 for peculiar songs.

## Install
Unfortunately, vibe is unable to be downlaoded at this time. I am working on this as my main project for spring break, and as such will likely have a release somewhere in the future. When a release is made, you will be able go to the releases section and download prebuilt binaries or go to your respective Linux distribution's package manager and install from there. I plan on pushing to the AUR at the very least.
