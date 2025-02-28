# p9
Brute force continuous part with limited range.

# Description
We have upper bound 3 to 4 on maximum compressed structure amount as a number.
This can be applied to {+,0,-} set ordinals.
So with them, invariant method can be applied to describe them and count up any of the function we have on some step next as a 19,683 \* 19,683 (because we need output and internal state change, also we don't need to get invariant on each.) functions.
So we brute force them as testing continuity of them all, then we apply the prediction with the most continuous one function.

# Relation to p\[0-8\]
The p\[0-8\] uses internal states awared but before to apply the predictions.
The p9 isn't so because we after to apply the predictions.
However, if there's some discontinuity, we fail even with this p9.

# Tips we need with this p9
We need maximum rank input nor maximum compressed input on this.
Otherwise, we need much more variable dimensions, we easily fails with this predictor.

# We cannot test because the calculation amount is too large for us
We cannot test p9 by ourself because only 1 step prediction estimated to take at least some minutes on our environment because of memory inefficiency (we don't have enough memory on our machines to hold all of possible function lists).

