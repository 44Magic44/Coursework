# 16/10/2018
I had a problem with making the script work where the object would dissapear once the player came into contact it, turns out i need to first
attach a rigid body to the object before it can actually be detected for the triggers.

# 23/10/2018
Game objects were missing. I quickly remade it but ran into a problem where it was not working. I thought that just having the name Player was enough but the object only works if you TAG it so that the script can read it properly.

# 01/11/2018
During assignment 2 i ran into a problem with instantiating a prefab, i forgot to actually place the prefab into the inspector, everything worked fine after that.
