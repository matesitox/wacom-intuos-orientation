# wacom-intuos-orientation
tiny script to easily adjust wacom intuos tablet orientation for use dual screens.
Useful when you have a laptop on a desk with a screen above it. Vertical orientation more closely, but not exactly, matches the aspect ratio of the combined screen area reducing aspect ratio shock and preserving - somewhat - the usefulness of your muscle memory.

Works on ubuntu 16.04.02 desktop with Wacom Intuos Creative tablet.

## usage

`$ tablet horizontal` sets the orientation to default
`$ tablet vertical` sets the orientation to vertical

## sources

http://linuxwacom.sourceforge.net/wiki/index.php/Rotation

## improvements

- auto detect number of screens
- auto detect relative screen position
- auto detect screen resolution
- adjust input transformation matrix to preserve scale mapping of input movements
