# Word-Counting-In-A-File

With the rise of the Rust programming language and the adoption of it by Microsoft and Linux OS, I have decided to give Rust a try. Therefore I will try to learn Rust by creating a small project.

The idea of this project is to a program that will take a file tokenize each word and output the word frequency.

This project was inspired by "https://www.youtube.com/watch?v=n-S9DBwPGTo", who did a similar thing but In C.

Objectives and reasons:
Create a function that will be able to open and read from a file. (To understand the I/O of Rust).
Create a function that will tokenize each word from the file.
Create a function that will calculate the frequency of each word in the file. (The idea of this is to get used to manipulating arrays, hash tables.., etc, using loops and conditions).
Create a function that calculates the percentage of each word.
Output all the information to the user.

Now those are the initial requirements after I have the program and it is fully tested I would like to update it with the following features.

Pass the file I want to analyse as an argument. (By doing this I will be able to understand how to pass arguments to the program).
Change the program architecture to a client-server where the client sends the file and the server analyses the files and sends back the data. (By doing this I will be able to utilise Rust where it shines the most and experience async programming and memory management).
