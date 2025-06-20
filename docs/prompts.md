# Prompts Used

## Cursor

```
Set up a basic HTML/JavaScript project using AnimCubeJS to display a Rubik’s Cube that can be scrambled with a custom scramble. Add buttons to scramble and reset the cube.
```

```
when you press apply scrmable, make it play, too
```

```
Add buttons to apply a T perm (for edges) and a Y perm (for corners) (minus the first F and las F') using standard move notation. When clicked, apply the correct sequence to simulate executing that algorithm on the selected target.
```

```
add a full parity button, like the Y and T perm for the following algo: R U R' F' R U2 R' U2 R' F R U R U2 R' U'
```

```
this is meant to be a blind solver - so - let's add two things:

pressing start hides the cube behind a cover

You can type one letter at a time into a new box that puts that cube in the swap position ready to go into the buffer - next to that a toggle for whether we are in edge or corner mode. The works based on the following:

► Edge setup moves
A: Lw2 D' L2
B: buffer (you can't swap with B)
C: Lw2 D L2
D: no setup moves
E: L Dw' L
F: Dw' L
G: L' Dw' L
H: Dw L'
I: Lw D' L2
J: Dw2 L
K: Lw D L2
L: L'
M: buffer (you can't swap with M)
N: Dw L
O: D2 L' Dw' L
P: Dw' L'
Q: Lw' D L2
R: L
S: Lw' D' L2
T: Dw2 L'
U: D' L2
V: D2 L2
W: D L2
X: L2

► Corner setup moves
A: buffer piece (you can't swap with A)
B: R2
C: F2 D
D: F2
E: buffer piece (you can't swap with E)
F: F' D
G: F'
H: D' R
I: F R'
J: R'
K: F' R'
L: F2 R'
M: F
N: R' F
O: R2 F
P: R F
Q: R D'
R: buffer piece (you can't swap with R)
S: D F'
T: R
U: D
V: no setup moves
W: D'
X: D2

```

```
now do the undo setup for the most recent apply
```
