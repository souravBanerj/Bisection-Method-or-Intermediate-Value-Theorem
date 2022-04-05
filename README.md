# Bisection-Method-or-Intermediate-Value-Theorem
Suppose f is a continuous function defined on the interval [a, b], with f (a) and f (b)
of opposite sign. The Intermediate Value Theorem implies that a number p exists in (a, b)
with f ( p) = 0. Although the procedure will work when there is more than one root in the
interval (a, b), we assume for simplicity that the root in this interval is unique. The method
calls for a repeated halving (or bisecting) of subintervals of [a, b] and, at each step, locating
the half containing p.
To begin, set a1 = a and b1 = b, and let p1 be the midpoint of [a, b]; that is,
p1 = a1 +
b1 − a1
2 = a1 + b1
2 .
• If f ( p1) = 0, then p = p1, and we are done.
• If f ( p1) = 0, then f ( p1) has the same sign as either f (a1) or f (b1).
• If f ( p1) and f (a1) have the same sign, p ∈ ( p1, b1). Set a2 = p1 and b2 = b1.
• If f ( p1) and f (a1) have opposite signs, p ∈ (a1, p1). Set a2 = a1 and b2 = p1.
