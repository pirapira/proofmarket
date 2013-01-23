A Design for Proof Markets
============================

Writing `Agda` or `Coq` is fun, but intellectual pleasure is not enough.  Formal proofs should be rewarded financially.

I propose a design of *proof markets* using the technique of *prediction markets*, where
you can bet for `A` or `not A`.
When someone submits a proof of `A`, all bets on `not A` are distributed among the betters for `A`.

If Alice wants `A` to be proved, she can bet a large amount for `not A`.
Then hopefully Bob proves `A`, bets a small amount on `A`, and gets the large amount from Alice.
So far the story is just about buying and selling proofs.
However, in a prediction market, a third party can speculate.
If Charlie bets for `A` before Bob appears, Charlie gets free money when `A` is proved.

What if the specification of `A` is wrong and actually `not A` can be proved?
In that case, Alice wants to prove `not A` soon to get back her money.
Or, Alice could be malicious enough to invite speculators like Charlie to make mistakes.

The whole picture will be, after all, fun to watch and participate.
