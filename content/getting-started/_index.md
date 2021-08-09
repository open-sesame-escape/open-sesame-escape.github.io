---
title: "Getting Started"
---

Ready create your own escape room? This page goes over the basics to get
you started.

## Anatomy of an Escape Room

Before we jump into discussing designing the particular elements of an
escape room, let us first consider the overall structure of the design. If
you have participated in an escape room, at any time you were probably
thinking in terms of the things you found and the locks you had to open.
But when designing an escape room, it is helpful to think of the structure
in terms of _rooms_ and _boxes_.

A room is, well, a room. It is a space in which players can roam. It also
contains clues, items, and boxes as well as potential passages to other
rooms and the exit. Boxes are containers that likewise contain clues and
items.

Both rooms and boxes are opened by solving a puzzle that allows them to be
opened (except, of course the room the players start in). From a design
standpoint, rooms and boxes are very similar.

Once the rooms and boxes have been decided on (we will get to how to do
that shortly), the elements can be arranged in a flow diagram that
specifies the order in which players must solve them. Here is an example of
how an escape room might be structured.

{{< mermaid align="center" >}}
graph TB;
  R1[Room 1: Office Space] --> B1(Box 1: Formula) & B2(Box 2: 'Oregano' Stash)
  B1 & B2 --> R2[Room 2: Laboratory]
  R2 --> B3(Box 3: Lab Notes)
  B3 --> B4(Box 4: Secure Email) & B5(Box 5: Weapons)
  B4 & B5 --> E[Exit]
{{< /mermaid >}}

What makes organizing your escape room this way so important is that it
allows you to ensure that the arrangement of items in your escape room is
correct. In particular, your the arrangement of items in your escape room
_must_ follow the following 2 rules.

  1. The puzzle for any box or room must need only items that are
     accessible without the items in that box or room.
  2. It should not be possible to open a box or room before its time.

Of these 2 rules, the first is the most important. If it is broken, the
escape room cannot be solved. In the example above, `Box 1` better not
require an item that is located in `Room 2`. If that is the case, then the
players will never be able to progress because they need `Room 2` to open
`Box 1` but need `Box 1` to open `Room 2`. Avoiding this situation is easy
with the flowchart. Simply ensure that all the items required for the
puzzle of any given box or room are located in an earlier node.

The second rule is a bit less important because voilating it at least
doesn't get the players stuck. Still, you don't really want the players to
be able to open the exit without solving all of the previous puzzles. Also,
the story comprising your escape room might make less sense if things are
opened in the wrong order. And there may be cases where 2 locks need to be
opened in a certain order. You should make sure the second cannot be opened
before the first. This can be verified by making sure that the puzzle for
every box and room requires at least one item from every node pointing
directly to it.

Although the full flowchart is useful, in truth I rarely ever draw out the
whole thing. It is simply too incovenient during the design process when
the structure is constantly shifting. Instead, I usually just write things
out in a linear outline. The outline is a simple ordered list of rooms and
boxes, like this.

{{% example %}}
  * **Room 1**
    * Items
      * Item 1
      * Item 2
  * **Box 1**
    * Puzzle
	  * Do X with item 1
	  * Do Y with item 2
	* Items
	  * Item 3
	  * Item 4
  * ...
{{% /example %}}

An outline like this is easy to edit in a text editor or word processor.
Also, it is easy to veryify rule 1, any box/room needs items only from
accessible boxes/rooms. To verify this, simply search each item in a puzzle
and verify that it occurs earlier in the document. Rule 2, veryifying that
you cannot open a box/room too early, is a bit harder without the
explicit flowchart. But you can once again check where the items that each
puzzle requires are revealed and make sure that at least one of the items
appears in a room or box that should be open first.
