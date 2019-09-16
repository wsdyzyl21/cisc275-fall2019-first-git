# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?

1.ArrayList dogs
2.new dog "Fido" 4 legs
3.new dog "Fido" 3 legs
4. new dog "Alfie" 4 legs
5.new Animals


3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
1.new Comparator<Animals>()
2.public int compare(Animals a, Animals b){
	 return a.getLegs() - b.getLegs();
}