# week-3-Project
int[] ages = {3, 9, 23, 64, 2, 8, 28, 93};
int lengthOfArr = ages.length;
 		int difference = Math.abs(ages[lengthOfArr - lengthOfArr] - ages[lengthOfArr - 1]);
         System.out.println("Difference of first and last element in ages[] = " + difference);
         int[] newAges = new int[ages.length];
         System.arraycopy(ages,  0, newAges, 0, ages.length);
         lengthOfArr = newAges.length;
 		newAges[lengthOfArr - 1] = 100;
 		difference = Math.abs(newAges[lengthOfArr - lengthOfArr] - newAges[lengthOfArr - 1]);
         System.out.println("Difference of first and last element in newAges[] = " + difference);
         int sum = 0;
 		for (int i = 0; i < newAges.length; i++) {
 			sum += newAges[i];