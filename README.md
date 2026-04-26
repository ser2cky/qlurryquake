# Qlurry Quake
GLQuake like you remember it. 
---
Are you tired the pixelated glop that these so called "software-rendered" source ports are peddle to the masses? Are you a 59 year old Quake fan from way back when that remembers how things TRULY used to be like? Are you a defiant Quake fan that loves all things "gl_texturemode GL_LINEAR_MIPMAP_NEAREST"? Well, I've got just the fix for you people! I present to you ladies and gentle, QLURRYQUAKE, a fork of QuakeSpasm that's sole purpose is to have CVars that make your Quake experience all the more GLQuake!

# What's new
- r_glemu 1 ( New CVar )
	- This CVar when enabled, replicates GLQuake's model lighting, texture round-downs, and transparent texture edge bleeding. When set to 1 specifically, QlurryQuake will replicate GLQuake 0.92's stretched viewport.
- r_particles 3 ( Modified CVar )
	- Setting this to 3 makes particles use GlQuake's 8x8 particle texture.
- r_shadows 2 ( Modified CVar )
	- Makes QlurryQuake render shadows the GLQuake way instead of the QuakeSpasm way.
- r_oldwater 2 ( Modified CVar & Buggy )
	- Brings back GLQuake's water warping. Gets ugly if you turn on "r_novis".
	
# Planned
- More GLQuake specific quirks if I find some more...
- Fixing water warping for good