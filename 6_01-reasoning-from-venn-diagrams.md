#6.1 Reasoning from Venn Diagrams or thruth tables alone

|P  |Q  |P Spoog Q|
|--- |--- |----    |
|T  |T  |T        |
|T  |F  |T        |
|F  |T  |F        |
|F  |F  |T        |

###Ex.1 
John is riding his bike SPooG Jill is walking to the park.
Jill is walking to the park.
Therefore, John is riding his bicycle.

- 1. P SPooG Q
- 2. Q
- C. P

The arg. is valid.

###Ex.2
John is riding his bike SPooG ( Jill is walking to the park or Frank is sick )
Frank is not sick
John is not riding his bicycle.
Therefore, Jill is walking to the park.

- 1. P SPooG (Q V T)
- 2. ~T
- 3. ~P
- C. Q

|P | ~P | Q| T | ~T  |Q V T | P SPoog (Q V T) |       |
|---|---  |---|---|---   |---    |---              |---    |
|T |F   |T |T  | F   |T     |T                |       |
|T |F   |T |F  | T   |T     |T                |       |
|T |F   |F |T  | F   |T     |T                |       |
|T |F   |F |F  | T   |F     |T                |       |
|F |T   |T |T  | F   |T     |F                |       |
|F |T   |T |F  | T   |T     |F                |       |
|F |T   |F |T  | F   |T     |F                |       |
|F |T   |F |F  | T   |F     |T                |Q is false, while ~P, ~Q and P SPoog (Q V T) are all True       |


