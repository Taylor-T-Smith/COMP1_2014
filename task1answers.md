#Task 1 Answers

##Question 3 answers

1. Which function is responsible for getting the name from the user?
	GetPlayerName() 
2. How will you ensure that the user is asked for the name repeatedly?
	Iterate with a while loop until the variable is assigned to something
3. What additional variable will you need and what will its datatype be?
	valid and its data type will be Boolean 

##Pseudo Code for Question 3

FUNCTION GetPlayerName()
	OUTPUT('') 
	valid: Boolean
	valid ← False
	WHILE NOT valid DO
		PlayerName: String
		PlayerName ← INPUT
		IF PlayerName = None
			OUTPUT('You must enter something for your name')
		ELSE
			valid ← TRUE
			END IF
	OUTPUT('')
	RETURN PlayerName

## Question 3b

1. UpdateRecentScores()

##Task 5 questions

1.Datetime module needs to be imported
2.DisplayRecentScores(), UpdateRecentScores(), TRecentScore(), ResetRecentScore()
3.use string.strftime('%d/%m/%y')

## Additional Questions

##Variable Roles

Question 1
1. Fixed Value - a variable which was set and never changes
2. Stepper - a variable that increments every time a part of a program is called
3. Most Recent Holder - holds the latest value encountered 
4. Most Wanted Holder - stores the most appropriate value encountered 
5. Gatherer - a variable that accumulates the effects of other values
6. Transformation - stores a value as a result from a calculation
7. follower - a variable that gets its new value from an old value from different data
8. Temporary - holds a value for a short time only 

Question 2
1. NoOfSwaps = 1000
2. Count
3. LastCard.Rank
4. NextCard = TCard()
5.
6. higher = IsNextCardHigher(LastCard, NextCard) or FoundSpace = False
7. LastCard = TCard() 
8. SwapSpace = TCarsd() 


## Functions and Parameters

1. Passing by value creates a copy of the variable and only the copied variable changes meaning the original stays the same. Passing by reference also creates a copy but the original variable is changed.
2. value - Score
	Reference - ThisCard

		