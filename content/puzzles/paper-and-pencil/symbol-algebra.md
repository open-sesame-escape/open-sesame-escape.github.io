---
title: "Symbol Algebra"
date: 2022-05-01T17:53:20-06:00
weight: 30
thumbnail: "symbol-algebra.png"
summary: "Make a simple algebra problem with symbols instead of letters."
---

A [symbol substitution] cipher replaces a set of symbols/images/icons with
letters or numbers. But to ad a challenge to the puzzle, don't simply give
the players the lookup. Make them work for it.

Hide a conversion from symbol to number in a simple math problem. This
takes the form of solving algebra, but with pictures instead of letters for
the variables. Here is a simple example.

{{% example %}}
🍗 + 🍗 + 🍗 = 12

🍗 + 🥖 + 🥖 = 20

🥖 - 🍮 = 7

🍮 + 🍗 + 🧀 = 7

🥗 + 🍮 - 🍗 = 0
{{% /example %}}

Note that this problem is straightforward to solve. You don't need a
technique like Gaussian elimination. The system is easily solved from the
top down.

The first line has 3 🍗 equal 12. Thus, 🍗 must be 4. The second line has
🍗 + 🥖 + 🥖 = 20. Thus, 2 🥖 sum to 16, and consequently 🥖 is 8. By the
third line, it is clear that 🍮 must be 1. From there, it is easy to get
that 🧀 is 2, and by the fifth line 🥗 3.

OK. The players have solved the puzzle. Now what? These values are not
useful until coupled with another clue. This could be coupled with any
puzzle that involves listing symbols in a certain order such as grid
lookup. Here is a simple example using a [code-word lookup] with a clue
containing a list of food for a meal.

{{% example %}}
Reception 5 Course Meal

1. Bread Assortment
2. Cheese Platter
3. Salad
4. Roast Chicken
5. Flan
{{% /example %}}

To completely solve this puzzle, the players have to (1) solve the algebra,
(2) notice that the images used for symbols in the math are referenced in
the menu, and (3) list the numbers associated with each food symbol in the
menu's order: 82341.

[symbol substitution]: /puzzles/ciphers/symbol-substitution
[code-word lookup]: /puzzles/hidden-messages/lookup
