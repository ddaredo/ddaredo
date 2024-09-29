flowchart LR
    A[Generate number] -->|number Generated| B(Get user guess)
    B --> C{Correct Guess}
    C -->|yes| D[Congratulate]
    C -->|NO| E[tell user high/low]
    E-->B
    D--> F(End)

<!---
Textual Description
1. Start: The game begins, initializing variables and setting up the rules.
2. Genarate Random number
3.prompt user for guess.
4. Check guess if the guess matches to the generated random numbers. 
5. if the Guess is correct, the program will end. 
6. if the guess is not correct, tell the value and have another attempt. 
7.end
ddaredo/ddaredo is a ✨ special ✨ repository because its `guessing.md` appears on your GitHub profile.
--->
