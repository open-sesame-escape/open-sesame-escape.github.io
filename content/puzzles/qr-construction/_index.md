---
title: "Qr Construction"
date: 2023-03-19T20:40:39-06:00
weight: 500
thumbnail: "blank.png"
summary: "Put together a QR code to get the next clue."
---

In a home DIY escape room, you can leverage the [internet] by directing
players to content on their mobile devices using [QR codes]. As a reminder,
a QR code when scanned with a mobile device's camera can direct bring up a
particular URL. There are plenty of free services to create a QR code from
any URL you choose,

A QR code can be posted on just about any object, and sometimes QR codes
can be parts of items in the room. But alternately, you can make the
building of QR codes part of the puzzles.

The basic idea of these puzzles is to provide parts of a QR code that have
to be put together in some way. Essentially, these puzzles break apart or
otherwise mangle a QR code, and the players have to put it back together.
Before we talk about how to mangle QR codes, it is helpful to be familiar
with what changes will not break a QR code and which will. This is
important as the design of a QR code construction puzzle involves breaking
the QR code and having the player fix it.


### Changes you can make to QR codes

QR codes are designed to be quite resilient to change. Because they are
designed to be scanned from a camera, they are readable in
the face of noise and misalignment. Thus, it is possible to rotate the QR
code or even flip it upside-down and it will still work.

{{< example-image src="qr-code-rotate.png" >}}

Not surprisingly, the QR code can be sheared in the same way that might
happen if the camera is not held perfectly straight.

{{< example-image src="qr-code-perspective.png" >}}

Surprisingly, QR codes can be mirrored and will still work.

{{< example-image src="qr-code-mirror.png" >}}

There is redundancy in a QR code's data, and they still can be read when
certain parts are covered up. In particular, the center part of the QR code
is redundant, and it is common to place a logo there.

{{< example-image src="qr-code-center-image.png" >}}'

It is also possible to blend a QR code with another image as long as there
is enough contrast between the 2 colors of the QR code. This can be
particularly helpful for QR construction puzzles as it gives hints to users
on the proper orientation of the image pieces.

{{< example-image src="qr-code-background-image.png" >}}


### Changes that break QR codes

As resilient as QR codes are, once you break off a big enough piece, it
will no longer be readable. When making a QR construction puzzle, you want
to force the players to put together all of the pieces before it can be
scanned.

When you look at a QR code, you will see "eyes" in three of the corners as
well as a smaller alignment eye in the fourth corner. QR scanners use these
elements to register the position of the code, and removing any of them
will make the code unreadable.

{{< example-image src="qr-code-no-alignment.png" >}}

An interesting vulnerability of QR codes is that the matrix of squares has
to be precise. In the following example, the left image splits the two
halves of the code by a small amount. The right image shifts the two halves
a little bit vertically. Despite the changes being very small, they render
the codes inoperable. This means once you separate the QR into pieces, it
needs to be possible to align them again precisely.

{{< example-image src="qr-code-split.png" >}}


### Puzzles

With that in mind, here are some puzzles based on putting together QR code
pieces.



[internet]: /equipment/internet
[QR codes]: /equipment/internet/#qr-codes
