# CarryClocks

At New Year's midnight,
the toys come alive, and miracles happen.
Why is this only at 24:00:00 December 31,
and not during our afternoon tea on a
random Friday?
Can we penetrate into the mystical nature of the miracle?
The answer is, of course,
the overflow and simultaneous carry in all digits.

In 1997, an IBM supercomputer called Deep Blue
defeated Garry Kasparov in a chess tournament.
How can a machine consisting of nothing but
AND and OR gates do this?
How do computers "think" at all?
How does a boolean logic circuit
calculate a simple arithmetic sum such as "3+4"?
The answer is, of course, carying between digits.

Can we explain all this -- carrying and its significance --
to an eight-year-old?
Can we teach them to count
and do simple addition/multiplication
in different number-system bases at that age?
show to them the mysticism of Mathematics
(and in particular, of _integers modulo m_)?
The answer is: yes, if one has a Dynabook.

The `MagicClockMorph` in this package
represents a single-hand clock.
The number of hours per day
(aka the base of the number system)
can be anything.
When `MagicClock>>#hourBase`
returns 12, the clock resembles the familiar clock on the wall.
10 gives the familiar decimal numbers, 2 the binary.
Time can advance either manually (pusing the "+1" button)
or automatically with periodicity set in
`ClocksGame>>#ms`.
Having several of these morphs, they can be connected together
to carry from one to the next.
`ClocksGame` provides an example; try `ClocksGame new openInWorld`
to start experimenting.
