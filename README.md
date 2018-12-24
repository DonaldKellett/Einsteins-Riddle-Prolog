# Einsteins-Riddle-Prolog

Einstein's Riddle (aka Zebra Puzzle) formulated as a (SWI-)Prolog program.  As stated by the [Wikipedia entry of the Zebra Puzzle](https://en.wikipedia.org/wiki/Zebra_Puzzle), many versions of it exist - the one formulated here is the one appearing in Life International magazine on 17/12/1962 (more details in the Wikipedia entry).

This program (`Einstein's Riddle.pl`) is merely one of many possible ways to represent said puzzle as a (SWI-)Prolog program and may not be the "best" representation (in terms of readability, efficiency, etc.).  Furthermore, this is definitely not the first time someone translated said puzzle into a Prolog program (many similar answers can be found on StackOverflow) so I do not claim any form of ownership over said Prolog program - feel free to use/modify/redistribute it as you see fit!

The program has been tested using an official SWI-Prolog interpreter (more details at https://www.swi-prolog.org/); however, it is not guaranteed to work under other Prolog implementations (e.g. GNU Prolog) as certain built-in predicates have been used that *may* (or may not) be specific to the SWI-Prolog implementation.

For readability, `Einstein's Riddle.pl` contains comments per line explaining what each Prolog statement corresponds to in the original puzzle.  As stated in the comments of the program, when you try to solve the puzzle by posing the query `solve(WhoDrinksWater, WhoOwnsTheZebra).`, exactly one solution set should be produced which is `WhoDrinksWater = norwegian, WhoOwnsTheZebra = japanese.`.
