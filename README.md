# Hackerrank_Equalizing_The_Array_Working_Test_Case
 The code starts by creating a Scanner object, which is used to read input from the user.
 
 Next, an integer variable n is declared and initialized with the value of scnr.nextInt().
 
 Then an array of integers is created and filled with values taken from the scanner object.
 
 The for loop iterates over each element in the array and assigns it to i using nextInt() before incrementing i by 1.
 
 The code computes the sum of all integers from 0 to n. The code above uses a for loop to iterate through each integer in the array and add it to the sum.
 
 The code starts by creating a new LinkedList list to store already visited numbers in the array.
 
 The code then creates a Map map to map each number in the array to the amount of repetitions.
 
 For loop iterates through all numbers in the array and stores them into an instance variable called i.
 
 The following is what you should say: In this program, we are going to create a linked list that will be used as an index for our array of integers so that we can avoid repetition when adding items into it later on.
 
 We will also create a hashmap which maps each integer from 0-9 onto how many times it has been seen before (the value stored in its corresponding key).
 
 Then, for loops iterate through all numbers from 0-9 and add them into our linked list or hashmap accordingly.
 
 The code creates a list, map and for loop to iterate through all numbers in the array.
 
 The code also creates an integer called i which will be used to store the current iteration number.
 
 The code starts by checking if the list already contains the number.
 
 If it does, then we skip to the next number in the list.
 
 Notice that we check for this BEFORE adding anything to the list, otherwise our answer will always be 1 because of a bug in our code.
 
 Next, we add number to the list for future comparison and then finally add it to the list itself.
 
 The code attempts to add a number to the list, but if the list already contains that number, then we skip to the next number.
 
 The code above will always return 1 because it will always check for whether or not the list contains an array before adding anything to it.
 
 The code is trying to find the value for a key that is already in the map.
 
 If it finds one, it increases the value of the map by 1 and puts it back in.
 
 
 Otherwise, if there isn't one yet, then we add 1 to whatever is in the map for that key and put it back in.
 
 The code is used to add a new value to the map.
 
 The code first checks if the key already exists in the map by using map.get(array[i]) The code then uses int add = map.get(array[i]) + 1; to increase the value for that key by one and put it back into the map.
 
 If there was no match, then we use int add = map.get(array[i]) + 1; to increment that value by one and put it into the map instead of checking for a match on every iteration of this looping statement.
 
 The code iterates through the values of the map.
 
 The key is irrelevant since we only care about the least amount of steps needed to equalize the array.
 
 We don't need to know which value is the most repeated, just how many times it appears in our list.
 
 We are going to return a max value that will be 0 if there are no repetitions and 1 otherwise.
 
 */ for (int i = 0; i < map1.size(); ++i) { //Max is now set as an int variable called max max = Math.min(map1[i], max); //This line sets up a min() function call with two parameters: map1[i] and max } return max; } In this code, we have created a for-each loop that iterates through all of our values in our first map using an integer variable called i .
 
 The for-each loop then assigns each iteration's result into another integer variable called max .
 
 This process continues until either there are no more iterations or when one iteration's result equals another iteration's result (in other words, when they're equal).
 In order to do this, we use Math.min()
 
 The code iterates through the values of the map and returns the least amount of steps needed to equalize the array.
 
 The code does not need to know which value is the most repeated, just the amount of repetitions.

