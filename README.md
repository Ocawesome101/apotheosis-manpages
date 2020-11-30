# manpages

This repository contains manual pages for the Apotheosis operating system for OpenComputers.

### manual page format

The manual pages use very simple formatting, provided by the coreutils' `fmt` utility:

 - `\\` is ignored
 - `\cN` inserts VT100 color code `30 + N`
 - `\CN` inserts VT100 color code `40 + N`
 - `\bN` inserts VT100 color code `90 + N`
 - `\BN` inserts VT100 color code `100 + N`
 - `\t` inserts 8 spaces
