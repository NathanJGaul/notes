# GDScript Motivation
GDScript was born out of the need for a scripting language to handle Godot's unique game development architecture:

 - Godot embeds scripts in nodes. Most languages are not designed with this in mind.
- Godot uses several built-in data types for 2D and 3D math. Script languages do not provide this, and binding them is inefficient.
- Godot uses threads heavily for lifting and initializing data from the net or disk. Script interpreters for common languages are not friendly to this.
- -   Godot already has a memory management model for resources, most script languages provide their own, which results in duplicate effort and bugs.
> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAxNTk4MTIyNF19
-->