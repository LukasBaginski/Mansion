## Variables:
A:
B: Beginning of current chunk
C: Chunk limit X
D: Chunk limit Y
E:
F:
G:
H: Player height level limit
I: *Reserved for loops*
J: *Reserved for loops*
K: Currently pressed key
L: *Reserved for calculating list positions*
M: *Reserved for current tile in list for rendering*
N:
O:
P: Position of player in the list
Q: Boolean if player is currently rendering / has to be
R: Boolean if world is currently rendering / has to be
S: *Reserved for coming story, see interpretation below*
T: Current tile
U:
V: Previous player X position
W: Previous player Y position
X: Player X position
Y: Player Y position
Z: Player height level

## Lists:
1: Floor 1 (Z=1)
2: Floor 2
3: Floor 3
4: Floor 4
5: *Reserved for NPC positions*
6: *Reserved*
7: *Reserved*
8: *Reserved*
9: *Reserved*

## Misc:
### Tiles:
0: Air
1..: Blocks

### Variable interpretation
#### S
To be seen as a binary value, i.e. 001100101100. 1 bit = Story completed, 0 bit = Story uncompleted.

### List interpretation
#### List 5
Every odd value is the X-position of an NPC, every even position stands for each Y-position.
