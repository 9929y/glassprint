# Glassprint

A glass Tetris that develops a picture.

A picture (a soft gradient or a small scene by default, or the colours of any
photo you drop on the board) is cut into the 10 x 20 grid of the well. Pieces
fall as clear glass. The instant one lands, colour inks into each of its four
cells: the exact patch of the picture at that coordinate, arriving pale and
developing to full colour over a couple of seconds. Stack, and the picture
develops. Complete a row and that band *sets*: the glass comes off it and its
ten tiles fuse into one strip of the finished print. Nothing is ever taken away.
Top out, and the glass comes off everything: the tiles fuse into one plate, a
highlight passes over it, and it is lifted away for the next picture.

The goal is the picture. A clean row is a clean band of it; the holes you leave
are the holes the print will have. The tray's rim brightens as the well fills,
and that is the only progress indicator. No score, no level, no words. The room
is paper. All the colour is on landed glass.

## Run

Open `index.html`. Nothing to install. Zero dependencies, one file.

Arrow keys move and rotate, space drops, hold a direction to walk. `p` pauses,
`r` starts a new picture (press it twice if there is a picture on the board),
`Esc` pauses and releases the keyboard. On touch, slide to move, tap to rotate,
drag down to lower the piece a cell at a time, flick down to drop it.

Drop an image onto the board (or paste one, or use the frame button) and its
colours become the picture. Press the frame button again to go back to the
built-in pictures. The tray button saves the current picture as a PNG.

## Design record

`DESIGN.md` is the full record: the mechanic, the material (block spec from Figma
190:493), the motion rules, the bugs found along the way and the trade-offs taken.
