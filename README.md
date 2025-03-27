# Threaded-Autocomplete
INSTRUCTIONS
Your assignment is to complete the four TODOs
in this document, starting with the top TODO
and working your way down in order.

Then you must make AT LEAST ONE additional
modification of your choice from the following
list:

OPTIONS:

	---STOP ON EXCLAMATION
	Currently the getTextToPeriod method in 
	ThreadedAutocomplete searches for periods 
	or question marks and gathers all the 
	text from the current Scanner position up 
	to that punctuation and returns it. Modify 
	the method to also stop at exclamation marks.
	You can test it with the word "tiresome" and
	if you see: "tiresome unlucky ghost story!"
	with blanks in the other textareas, then you
	did it correctly.
	Also I find my code in the top half of the getTextToPeriod method to be gross so if you 
	manage to make it more elegant, I'll throw in 
	a couple extra credit points.

	---QUIT TO EXIT
	Currently typing the word "quit" into the
	JTextField causes the threads to exit. Make
	it so that "quit" also closes the GUI.

	---BREAK BETWEEN WORDS
	The wrappedToFit method in 
	ThreadedAutocomplete splits the text every 60
	characters regardless of whether or not the
	split occurs in the middle of a word. Modify
	this method so that words are not split up.

	---MULTIWORD MATCH
	Currently only the last word entered in the 
	text field is used for matching. Modify 
	ThreadedAutocomplete to attempt to match on 
	the entire user input, then if no matches are
	found, attempt to match on the whole input
	minus the first word, then if no matches are
	found, try the whole input minus the first
	two words. And so on until a match is found
	or the user input is exhausted. If you do
	this option I'll throw in 3 bonus points
	because I think it's harder than some of
	the other options.

	---THREE BUTTON OUTPUT
	Add three buttons to the GUI (one for each
	JTextArea) and resize the GUI to display them.
	When the user clicks a button, the current
	JTextField contents, followed by the 
	autocompleted text in the corresponding 
	JTextArea should be written out to file.
	Further clicks continue to APPEND to the file
	rather than overwriting it so that the user
	can create a mashup story from the three
	novels. If you do this option I'll throw in
	5 bonus points because I think it's harder
	than some of the other options.

	---SOMETHING NEW
	Propose your own extension and complete it.
	Your extension must be of comparable 
	difficulty to the other options and must be
	described in detail in a comment at the top of
	Main.java that also tells me, your instructor,
	where to look in the code to see this
	modification.

Note clearly in a comment at the top of
Main.java which modifications you made.

Small amounts of extra credit are available for
additional modifications beyond the required one
(up to 5 points per).
