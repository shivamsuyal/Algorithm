# Find The Hacker Twins

# The Story Goes Something Like This... 
You are one of the best programmer Of CPU (not the computer's cpu but CPU as Crime Petrol Unit)...

And have been assigned an important task ie. to find the crazy hacker twins. 

The twins have been robbing the banks for past few months and till now no one is able to catch them but today something gonna change.... 

You have received an intel that the twins are in M-City, and to pin point their exact location you have been given access to a satellite near M-City. 
You accepted your task and started working on it. After few minutes you completed your ultimate facial recognition program and uploaded it to the satellite and launched it and now you wait.

(M-City is a big country with an exception that in its population no one have twins, to be more clear if the hacker twins are there than they will be the only twins in the whole big country) 

After 10 minutes the satellite has scaned all the people of M-City and now was sending the data back to you, but the hacker twins knew your plan so, that hacked the satellite and destroyed it completely.

But luckily you managed to recover a little piece of data that contains 50,000 ids of people and you have a strong gut feeling that it also contains the twins facial data. Now let cross your finger and hope for the best. 🤞

# Format Of Data
The data will look like this...

17,32,38,49,50,6

27,3,66,1,0,55

37,29,0,29,37,24

55,0,66,1,3,27

The facial recognition software work something like this:

1. Scans a person 
2. Generate a unique set of 6 random numbers (The sets are unique ie. If one person have this 1,2,3,4,5,6 then this set can't be given to another person ie. the other person can't have 1,2,3,4,5,6 or 1,2,6,4,5,3 or 5,2,3,4,1,6 or in any other sequence untill they are twins )
3. If it encounters twins the it provide them same numbers but with different sequence ie. If Twin1 have 1,2,3,4,5,6 the Twin2 won't have the same sequence of set but something like this 1,4,3,2,6,5 etc.
4. When scan is completed it sends the data to the user.

# Objective
[1] Scan the recovered data file and find the twins id 

(For finding the Id of a person just look for their indexes ie.)

     Unique​_set         Index  Id  Person

    17,32,38,49,50,6    0      0   person1

    27,3,66,1,0,55      1      1   person2

    37,29,0,29,37,24    2      2   person3

    55,0,66,1,3,27      3      3   person4

    and so on....


[2] With the help of id find their location co-ordinates with the help of location file.

[3] Your program computation should be less than 20 seconds because the twins know that you are comming for them and they are ready to flee from the city.
