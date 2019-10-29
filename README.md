# FizzBuzz
# Write a program that prints the numbers from 1 to 100 and for multiples of '3' print "Fizz" instead of the number and for the multiples of '5' print "Buzz", for multiples of 3 and 5 write Fizz Buzz.

		int max = 100;
		for(int num = 1; num <=max; num++) {
			
			if (num % 15 == 0) {
				System.out.print("FizzBuzz" + ",");
			} else if (num %5 == 0) {
				System.out.print("Fizz" + ",");
			} else if (num %3== 0) {
				System.out.print("Buzz" + ",");
			} else {
				System.out.print(num + ",");

	}
}

}
}
