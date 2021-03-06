#Description of assignment


Describe at least 2 ways of transferring files from a remote server to a local machine.
What are revision control systems? Why are they useful?
What is the difference between redirecting and piping? Describe each.
What is make, and how is it useful?
Describe, in detail, the syntax of a make file.
Give a find command that will run the file command on every regular file (not directories!) within the current filesystem subtree.
The Sieve of Eratosthenes identifies all prime numbers up to a given number n as follows:

Write down the numbers 1, 2, 3, ..., n. We will eliminate composites by marking them. Initially all numbers are unmarked.
Mark the number 1 as special (it is neither prime nor composite).
Set k=1. Until k exceeds or equals the square root of n do:
Find the first number in the list greater than k that has not been identified as composite. (The very first number so found is 2.) Call it m. Mark the numbers
2m, 3m, 4m, ...
as composite. (Thus in the first run we mark all even numbers greater than 2. In the second run we mark all multiples of 3 greater than 3.)

m is a prime number. Put it on your list.
Set k=m and repeat.
Put the remaining unmarked numbers in the sequence on your list of prime numbers.
Write a C function which returns the number of primes less than a given value, as well as the values of all the primes. It might be worth writing this in a way that can be easily used later...

You will be implementing the following items in python, as a single python script with multiple functions. You must have a main function. There should be a way to select between them:
Write a python script that creates the following directories for a given term and course:
assignments
examples
exams
lecture_notes
submissions
Also create a symbolic link to /usr/local/classes/eecs/<term>/<class>/public_html called 'website', and a link to /usr/local/classes/eecs/<term>/<class>/handin called 'handin'.

It is your responsibility to ensure that you don't attempt to create a directory that already exists. Make use of the os, sys, and getopt modules, with both short and long form options for term and course.

Find the greatest product of five consecutive digits in the 1000-digit number.
	  73167176531330624919225119674426574742355349194934
	  96983520312774506326239578318016984801869478851843
	  85861560789112949495459501737958331952853208805511
	  12540698747158523863050715693290963295227443043557
	  66896648950445244523161731856403098711121722383113
	  62229893423380308135336276614282806444486645238749
	  30358907296290491560440772390713810515859307960866
	  70172427121883998797908792274921901699720888093776
	  65727333001053367881220235421809751254540594752243
	  52584907711670556013604839586446706324415722155397
	  53697817977846174064955149290862569321978468622482
	  83972241375657056057490261407972968652414535100474
	  82166370484403199890008895243450658541227588666881
	  16427171479924442928230863465674813919123162824586
	  17866458359124566529476545682848912883142607690042
	  24219022671055626321111109370544217506941658960408
	  07198403850962455444362981230987879927244284909188
	  84580156166097919133875499200524063689912560717606
	  05886116467109405077541002256983155200055935729725
	  71636269561882670428252483600823257530420752963450
	
Bonus points if you can do it in a function of fewer than 3 lines.
Using names.txt, a 46K text file containing over five-thousand first names, begin by sorting it into alphabetical order. Then working out the alphabetical value for each name, multiply this value by its alphabetical position in the list to obtain a name score. For example, when the list is sorted into alphabetical order, COLIN, which is worth 3 + 15 + 12 + 9 + 14 = 53, is the 938th name in the list. So, COLIN would obtain a score of 938 × 53 = 49714. What is the total of all the name scores in the file? See the posted examples for how to work with a file. For this, A = 1, B = 2, etc.
The nth term of the sequence of triangle numbers is given by, tn = ½ n (n+1); so the first ten triangle numbers are:
1, 3, 6, 10, 15, 21, 28, 36, 45, 55, ...
By converting each letter in a word to a number corresponding to its alphabetical position and adding these values we form a word value. For example, the word value for SKY is 19 + 11 + 25 = 55 = t10. If the word value is a triangle number then we shall call the word a triangle word. Using words.txt, a 16K text file containing nearly two-thousand common English words, how many are triangle words?
