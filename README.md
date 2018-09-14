# CISC275-Fall2018-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
	1) A dog named Fido with 4 legs
	2) A dog named Fido with 3 legs
	3) A dog named Alfie with 4 legs 
	4) Comparator<Animal>
	5) ArrayList<Dog>

3. Can you spot the comparator constructor call? Where is the class definition for the comparator?

- The Comparator constructor is called by the parenthesis in the line:
> Collections.sort(dogs, new Comparator<Animal>(){

- The class definition for the Comparator is in MyCompare3 class.
