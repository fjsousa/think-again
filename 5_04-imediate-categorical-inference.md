#5.4 Imediate Categorical Inference

It is an inference with just 1 premise, in which both the premise and the conclusion are of the form A, E, I, O.

- A: All Fs are Gs
- E: No Fs are Gs
- I: Some Fs are Gs
- O: Some Fs are not Gs

F cat - Subject term

G cat - Predicate term

##Conversion

|              |           |    |
|-----              |--------           |-----    |
|All Fs are Gs      |All Gs are Fs      |invalid  |
|No Fs are Gs       |No Gs are Fs       |valid    |
|Some Fs are Gs     |Some Gs are Fs     |valid    |
|Some Fs are not Gs |Some Gs are not Fs |invalid  |

------

Valid Immediate Categorical Inferences:

- All otters are authors -> Trotter the otter is an author.
- All sheep are brown. -> Therefore, Horace the sheep is brown.


