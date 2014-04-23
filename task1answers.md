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

1.
2.

## Functions and Parameters

1. Passing by value creates a copy of the variable and only the copied variable changes meaning the original stays the same. Passing by reference also creates a copy but the original variable is changed.
2. 

		