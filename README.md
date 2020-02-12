## Here is my informative readme

Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR 
(pull request). Is there other keywords that can accomplish the same thing?

**Answer: Fix and Close**

Q2: Do you have to create a new PR EVERYTIME you want to close an issue,
or is it possible to close multiple issues within a single PR? If so, 
how?

**Answer: chain them like Close #1, Close #2 ..**

Q3: Provide an example of using map that is different from the one I have done.
Your example must use map both as a named function declaration and with an
anonymous function. 



ex anonymous):

	 doubledArray = [1,2,3,4].map(function (element){
	 	return element * 2;
	 });

	// doubledArray now hold [2,4,6,8]


ex2 named):
	 
	myfunc(element){
		return element + 1;
		}

	incrementOne = [1,2,3].map(myfunc)

	//incrementOne holds [2,3,4]
	

     



Within comments, explain exactly what map is doing. Finally, why is the
"transformation function" we discussed in class sometimes referred to 
as a callback function. 


