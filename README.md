<img width="85" height="32" alt="image" src="https://github.com/user-attachments/assets/17567c9b-0b07-43a9-9f09-8e99ab43bfa2" /># Practice-Questions
Practice Questions _08.08.2026

1. VLOOKUP – Price of Product ID P103
VLOOKUP("P103",A2B3:E7,4,0)
Result: 32000
2 - Using XLOOKUP, find the Stock of Product ID P105.
=xlookup("P105",A7:A12,E7:E12)
Result: 30
3 - Using MATCH, find the position of Product ID P104.
=MATCH("P104",A7:A12,0)
Result: 4
4 - Using INDEX, return the Product Name in the 4th row.
=INDEX(B7:B12,4)
Result: Headphone
5 - Using INDEX + MATCH, find the Category of Product ID P106.

=INDEX(C7:C12,MATCH("P106",A7:A12,0))
Result: Electronics
