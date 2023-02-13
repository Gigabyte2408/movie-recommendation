# movie-recommendation
A script that manually loads in data about various movies, stores them as nodes in a LinkedList, and uses user input to recommend and traverse the data.
Created 9 dictionaries manually to store 4 movies for each of 9 genres. Each movie has the title of the movie, a description, a rating, and a cast.
Used a LinkedList to connect each movie in a genre. Then used a hashmap to store all the linkedlists. Rather than using a hashing function, simply used the name of the genre as a way to access the linked lists.
The program is built to allow for many more movies in the dictionaries. 
It functions off user input where the user inputs 1 or more letters based on the preferred genre, and sees recommendations based on that.

Potential Future Improvements:
Add beautiful soup functionality to allow for easy storing and locating of movie info from the internet.
