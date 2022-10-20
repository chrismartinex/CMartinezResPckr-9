# CMartinezResPckr-9
//As the final assignemt in this long saga of mini Challenges, I was able to create program that allows the user to select from threes different Categories, of food and the system
//will hand pick the best 10 restaurant options per category, and if not we can shuffle them all together so the program can pick what's best for the user. 

Peer Review: Griffin Parker

This program works well. It allows the user to select from multiple different styles of restaurants and randomly selects a restaurant for them. I like the aesthetic design of the program, but I think that the way that the program loops could use a little work. You have to type "N" to end the program, which is different than what the program tells the user. I would change the switch case to "END" instead of "N" and use UserInput.ToUpper() to make sure whatever the user types in is changed to all capital letters
