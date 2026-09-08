# Glassprint

A glass Tetris that develops a picture.

A picture (a soft gradient by default, or any photo you drop on the board) is cut
into the 10 x 20 grid of the well. Pieces fall as clear glass. The instant one
lands, colour inks into each of its four cells: the exact patch of the picture at
that coordinate, arriving pale and developing to full colour over a couple of
seconds. Stack, and the picture develops. Clear a row and everything above drops
and re-inks, so the picture reflows and stays whole. Top out, and the glass comes
off: the tiles fuse into one plate, a highlight passes over it, and it is lifted
away for the next picture.

No score, no level, no words. The room is paper. All the colour is on landed glass.

## Run

Open `index.html`. Nothing to install. Zero dependencies, one file.

Arrow keys move and rotate, space drops, hold a direction to walk. `p` pauses,
`r` starts a new picture, `Esc` pauses and releases the keyboard. On touch, swipe
to move, tap to rotate, swipe down to drop.

Drop an image onto the board (or paste one, or use the frame button) and it
becomes the picture. Press the frame button again to go back to gradients. The
tray button saves the current picture as a PNG.

## Design record

`DESIGN.md` is the full record: the mechanic, the material (block spec from Figma
190:493), the motion rules, the bugs found along the way and the trade-offs taken.
