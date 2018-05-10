
Covered call:
--------------------
> S - C

Protective put:
--------------------
> S + P ( = C + Ke^-rt => fiduciary call)

Put-call forward parity
--------------------
> Fe^-rt + p = c + Ke^-rt

Day count and compounding conventions
-------------------
Day count and compounding conventions vary among different financial instruments. There are three variations used in the CFA curriculum:

|     Markets                                                     |Days per year| Compounding         | Calc |
|------|-----|-------------|----------------|
|All LIBOR-based contracts such as FRAs, swaps, caps, floors, etc |360| simple interest               | r * days/360    |
|Equities, bonds, currencies, and stock options                    |365| periodic compound interest    | (1+r)^ days/365|
|Equity indexes                                                     |365|continuous compounding         |e^(r*days/365)  |
