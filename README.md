lengthOfArr = ages.length;
 		difference = Math.abs(ages[lengthOfArr - lengthOfArr] - ages[lengthOfArr - 1]);
         console.log ("Difference of first and last element in ages[] = " + difference);
          //newAges.push = new [ages.length];
          ages.push(100) 
          difference2 = Math.abs(ages[lengthOfArr - lengthOfArr] - ages[lengthOfArr - 1]);
          console.log ("Difference2 of first and last element in ages[] = " + difference2);
//          //System.arraycopy(ages,  0, newAges, 0, ages.length);
  lengthOfArr = newAges.length;
 		newAges[lengthOfArr - 1] = 100;
 		difference = Math.abs(newAges[lengthOfArr - lengthOfArr] - newAges[lengthOfArr - 1]);
         console.log ("Difference of first and last element in newAges[] = " + difference);
        let sum = 0;
 		for (let i = 0; i < newAges.length; i++) {
 			sum += newAges[i];
 		}
 		let average = sum / lengthOfArr;
 		console.log("The average age in newAges[] = " + average ); 
