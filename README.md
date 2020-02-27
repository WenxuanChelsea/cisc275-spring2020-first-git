# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?

"Fido, 4"
"Fido, 3"
"Alfie, 4"
Animal a
Animal b

3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?

In the Collections.sort method, which is passed as the second argument.
	 Collections.sort(dogs, new Comparator<Animal>() {
			@Override
			public int compare(Animal a, Animal b){
			    return a.getLegs() - b.getLegs();
			}
		});


