# NSSS-Modloader

NOTE: Outdated and unsupported, use the ModLoader port in the NSSS discord instead.

A port and expansion of Risugami's ModLoader for b1.7.3 to Not So Seecret Saturday (https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/2916817-the-not-so-seecret-saturday-mod-for-alpha-1-1-2_01). Note that this will not be compatible with b1.7.3 mods, this is intended for mods made specifically for NSSS.

Currently this is incomplete. Once gets caught up feature wise to b1.7.3 (in terms of methods that are actually relevant to NSSS, the version number will change to v1.0.0 and more API expansions and methods may be added after.

HOW TO CREATE MODS:

1)Decompile NSSS after adding ModLoader to the jar.

2)Create a mod_(insert mod name here) class in the net.minecraft.src package.

3)Start modding! Some useful tutorials for how ModLoader works can be found on The Zyga's channel such as this one: https://www.youtube.com/watch?v=hprGX28zNlQ.

4)Put all of the classes you modified (in their directories) into a folder.

5)Copy or make a file of the same name of your mod_x class and put it in the root of the folder. This is a janky way of getting ModLoader to read the mod_x class in the /net/minecraft/src folder. NOTE: currently this requires the .class extension, in the future this will change.

6)Compress everything inside the folder and name it as you please.

HOW TO INSTALL MODS:

Option A: Add the mod to your .minecraft/NSSSmods folder. NOTE: this will only work if the mod edits no base classes.

Option B: Add the mod to the .jar. Using multimc this means clicking the "add to minecraft.jar" button and selecting the mod. Otherwise, locate the .jar and insert the files into it.
