---
title: "Directional Lock Alternative"
date: 2025-01-01T14:38:12-07:00
weight: 11
thumbnail: "blank.png"
summary: ""
hidden: true
---

{{< figure src="../locks/directional-lock.jpg" class="image-right" >}}

At one time Masterlock produced a padlock that allowed you to set a combination
as a sequence of directions, and the device was unlocked by pushing this
sequence of directions on a knob. This type of lock was commonly used in escape
rooms and enabled many clever puzzles. Several puzzles on this site require the
entry of a sequence of directions.

Unfortunately, Masterlock has discontinued the production of these locks, and no
other brand has yet to produce their own. You may still be able to find one of
these locks, but as time goes by they will become more rare and expensive.

If you would like to include a puzzle to find a sequence of directions and
cannot get one of these padlocks, here is an alternative. This approach sets up
a web page where players can enter directions, just like they could for a
directional padlock. The web page will then provide a code that players can
enter into a traditional padlock. To set this up, click the link below.

## [Web Directional Lock]

Here's how this tool would be used. The above link is used to create a table
like this.

{{< example-image src="directional-start.png" >}}

This page is displayed on a mobile device or other computer. You can have the
page preloaded on a device accessible in the room, or provide a [QR] code for
players to load on their own device.

{{< example-image src="directional-phone.jpg" >}}

As players are solving the puzzle, they press the direction buttons. After
entering the sequence, they press the `Submit` button.

{{< example-image src="directional-submitted.png" >}}

When the sequence is submitted, a code is provided. The players can enter this
code into a traditional numeric padlock. In the previous example, the player
entered the sequence down-right-up-right-up-left and received the code `5572`.
If they entered the correct sequence of directions, the code will open the lock.

The above images show the default behavior to provide a random-ish but
consistent code. The above link to the [web directional lock] provides several
options to adjust the page for your needs.

[Web Directional Lock]: https://www.open-sesame.xyz/directional-lock/
[QR]: /puzzles/qr-construction/
