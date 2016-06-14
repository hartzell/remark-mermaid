This repo contains an example of a problem that I have combining
[remark] and [mermaid]; text in notes in sequence diagrams does not
seem to be taken into account when the diagram is drawn if the diagram
is not on the slide currently being displayed.

The file *bad.jpg* in this repository shows what it looks like when
it's wrong.

If you redraw the slide, then *that slide* is correct, but other
slides are still screwy.

The file *good.jpg* in this repository shows what it looks like when
it's right.

If you clone the repository and open *talk.html* you should see an
example of the problem.


[remark]: https://github.com/gnab/remark
[mermaid]: https://github.com/knsv/mermaid
