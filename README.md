# BlenderMazeBuilderAddon

Here is a new beta version of the maze builder blender addon tool.

The process is simple :

After installation, just open the panel to the right band of the viewport.

1) set 3D grid resolution
2) select the piece you want to place
3) click spawn button to place the piece at the given position

MAZE CREATION PROCESS:
After placing all the pieces of your project:
1) Connect the piece by selecting vertex or edges, then press F.
2) Merge them all using ctrl+J
3) Create a closed mesh which limits define an entry and an exit
4) Use the bool tool integrated addon to get the maze.

WARNING :

The beta version has issue with the size of the room (which is too big compared to the connector piece)
In a case you mistakenly spawn the wrong piece, don't use ctrl+Z (UNDO). Delete the piece and spawn again with different settings.
Blender may crash using ctrl+Z.


Advice : consider the list as an alphabet to compose with 

More information and tips are coming on the way.

