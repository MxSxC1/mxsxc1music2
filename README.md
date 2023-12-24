# mxsxc1music2
Minecraft Custom Sounds &amp; Music

Music by MxSxC1. Sleet Recorded Live. Only use work with artists permission, and respect copyright.

Drop the folder "mxsxc1_music2" in your resourcepack folder. For example:

C:\Users\[UserName]\AppData\Roaming\.minecraft\resourcepacks\mxsxc1_music2\

I deliberately do not use "music" and instead use "ambient" to save clashes with Minecraft music which I mute...

2 Commands below will work.

/playsound minecraft:mxsxc1_sleet ambient @a ~ ~ ~ 100 1

/playsound minecraft:mxsxc1_whisper ambient @a ~ ~ ~ 100 1

To Use your own sounds:

Put your own files in the folders (or create your own). They MUST be on .ogg format.

Amend the sound.json to match your file.

Example below:

/playsound minecraft:mxsxc1_sleet ambient @a ~ ~ ~ 100 1

Refrers to the following within sounds.json

"mxsxc1_sleet": {"sounds": [{"name": "custom/mxsxc1_sleet","stream": "true"}]},

which refers to file:

\.minecraft\resourcepacks\mxsxc1_music2\assets\minecraft\sounds\custom\mxsxc1_sleet.ogg



