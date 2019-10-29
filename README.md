# FizzBuzz
# Write a program that prints the numbers from 1 to 100 and for multiples of '3' print "Fizz" instead of the number and for the multiples of '5' print "Buzz", for multiples of 3 and 5 write Fizz Buzz.

int max = 100;
for (loop = 1; loop <= max; loop++){

 if (number % 3 == 0) {
            if (number % 5 == 0) {
                System.out.print("FizzBuzz);
            } else {
                System.out.print("Fizz");
            }
        } else if (number % 5 == 0) {
            System.out.print("Buzz);
        }
        System.out.print(loop + ",");
    }
}
