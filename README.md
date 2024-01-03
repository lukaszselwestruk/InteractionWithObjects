Interaction with various objects Developed with Unreal Engine 5

I. Implemented Mechanics:

Simple interaction mechanic that works on 3 types of cubes and 2 types of spheres:
- Right click - pick up an actor (player can move with the actor held in front of the camera)
- Left click - release
- F - Call the pre-implemented Get function on held actor and print its return value

II. Folder Architecture:

- Core: Blueprints and coding-related materials.
- Art: Graphics for everything except characters.
- Map: Level design and layouts.
- Characters: All assets related to characters.

III. Restrictions and Guidelines:

- Didn't re-parent any of the Blueprint classes.
- Didn't modify the pre-implemented Get functions in any way.
- Used the 3 input events in BP_FirstPersonCharacter to interact with the system and didn't add any other input.
- Assumed that there could have been tens or hundreds of different objects we could have picked up.
- Made sure the system didn't spend resources unnecessarily.

Link to repo SOON
