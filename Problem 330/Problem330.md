Good morning! Here's your coding interview problem for today.

This problem was asked by Dropbox.

A Boolean formula can be said to be satisfiable if there is a way to assign
truth values to each variable such that the entire formula evaluates to true.

For example, suppose we have the following formula, where the symbol Â¬ is used
to denote negation:

(Â¬c OR b) AND (b OR c) AND (Â¬b OR c) AND (Â¬c OR Â¬a)

One way to satisfy this formula would be to let a = False, b = True, and c =
True.

This type of formula, with AND statements joining tuples containing exactly one 
OR, is known as 2-CNF.

Given a 2-CNF formula, find a way to assign truth values to satisfy it, or
return False if this is impossible.


