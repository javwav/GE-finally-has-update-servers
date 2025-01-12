## Graphics Enhancement 2.2
- Fixed and improved "Subsurface Scattering Fix". Now it will also show properly when using resolution scaling and will not require a stage reset after changing the display or the internal resolution.
- Fixed CyberSpace boost motion blur being too low in 3D.
- Slightly tweaked reflections.
- Increased terrain blend draw distance and detail maps draw distance. No performance hit, not a big visual difference either.
- Fixed an error with the "Enable changes in Cyberspace" description.

## Graphics Enhancement 2.1
- "Force 2D Motion Blur" now works in cyberspace as well (thanks to angryzor)
- Fixed rain enhancements applying when custom atmospheres are enabled (those have their own)
- Made "decrease grass fade out distance" start slightly further away and finish way further to make big patches of grass less annoying
- Decreased reflection artifacts slightly
- Slightly tweaked shadowmap cascade layout
- Removed the NeedleFxSceneData library from all the code files and added it in a separate file to decrease file size and hopefully improve stability
- Added stronger filtering with Full Resolution AO
- Attempt number 1 to fix the subsurface scattering code glitch

## Graphics Enhancement 2.0
- Big ass update
