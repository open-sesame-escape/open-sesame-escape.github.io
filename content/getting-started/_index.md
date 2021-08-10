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

## The Plot

Right now you might be thinking, _Plot? I want to make escape rooms, not
write stories. We're already 3 pages into this stupid web site and we're
still talking about things like plot._

I admit that on the first time I set out to make an escape room, I didn't
give much credence to the story. But what I found is that the story is
important for a couple of reasons. First, the story provides purpose for
the players. It is what elevates the game above a simple puzzle book.

Second, constructing the story early helps with the overall design of the
escape room. The plot points of the story form the aforementioned rooms and
boxes that structure the room. I'm constantly surprised how, once I come up
with the basic plot structure, how quickly the rest of the escape room
comes together. Simply having an idea of what each room and box will mean
helps come up with creative ideas.

That's not to say that the design of the escape room should be a linear
process. After outlining the basics of the plot, I find it most useful to
bounce back and forth from puzzle design to plot refinement and back. The
plot points can provide inspiration for clever puzzle designs. And the
design of puzzles can provide interesting refinements for the plot.

## The Puzzles

Yes. Finally. The puzzles. The best part of any escape room.

The puzzles can be pretty much anything. And, of course, you'll find lots
of suggestions on the [puzzles] pages here. But, remember as you
design puzzles that you are not creating the same variety of puzzles that
you might find in, say, a book of crossword or sudoku puzzles. So, here are
some features of the best escape room puzzles.

  * **Lateral Thinking** The best escape room puzzles are solved with a bit
    of lateral thinking. The puzzles comprise a collection of items and
    clues that on face value have no particular significance. But when
    looked at differently or put together in the right way, a secret
    meaning is revealed.
  * **Shortness** The mechanics of the puzzle should not take a long time
    to complete. Players might take a long time to figure out to solve a
    hard puzzle, but once they achieve that "ah-ha" moment, the answer to
    the puzzle should be quick and self evident.
  * **Uniqueness** Each puzzle in the escape room should be unique. In
    fact, none of the players should have ever seen any of the puzzles or
    anything like them.

When starting the puzzle design for your escape room, it is good to start
by browsing [puzzle suggestions][puzzles] from this page and others while
keeping these features in mind. You can also get inspiration from any
commercial escape rooms that you have done. As you think about potential
puzzles, it is a good idea to keep a list of potential ideas, even if you
do not yet have an idea where you will use it. You never know when
inspiration will hit, and it is good to jot down ideas as they come before
they are forgotten.


[puzzles]: /puzzles
