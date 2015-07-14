# startermod_basic
A most basic starter mod to get you going!

Instructions for use: Download the mod. Unzip to your stonehearth mods directory, as a peer to stonehearth.smod and radiant.smod. 

The mod adds two new objects to the world, and a new recipe to the carpenter, so that you can see at least one of the objects in the world. 

Before digging into the mod files, start up a game of Stonehearth and make a carpenter. You should see a "Sample Recipe" in his recipe list under the "furniture" category. The Sample Recipe creates a decorative object you can then place in the world. 

startermod_basic also adds a "Sample Object" to the world. This object is so basic that it has almost no use in the game. In order to even see it (as it does not participate in any recipes), you must also download the debugtools mod (https://github.com/stonehearth/debugtools) and install it into the mods folder, again as a peer to stonehearth.smod and radiant.smod. (Make sure the folder is named debugtools, not debugtools_master). Debugtools will put a few icons in the upper right corner of your stonehearth game when you next open it. To see startermod_basic's Sample Object, click the stamp icon/tool, and type: 

startermod_basic:sample_object

Press <enter> and then click somewhere on the ground of the game. Debugtool's clone stamper tool should put a Sample Object into the world. 

Now that you've seen what the startermod_basic adds to the game, you are now ready to use this mod to add your own objects to Stonehearth. 

The simplest way is to replace the sample object's model file (startermod_basic/entities/sample_object/sample_object.qb) with your own model. (To create a stonehearth model, you want a voxel editing program, like Qubicle Constructor, by Minddesk that can save things in the .qb file format. There are other modeling programs out there; experiment to find one you like.)

Once you've named your new object sample_object.qb and copied it into the folder over the existing sample_object.qb file, you can use debugtool clone stamper to see the object in the world as described above. 

You can also do this with the decorative object that the carpenter makes, so that the carpenter will make your decorative object, instead of the default one. 

You can also add additional objects to the mod, by copying the example of sample_object and the decorative object. Try these exercises: 

- create a brand new object in the game, and use the debugtools stamper to put both it AND the sample_object down into the world
- give your carpenter an additional recipe, that will enable him to create your object

