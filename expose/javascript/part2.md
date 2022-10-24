1. 3 will be printed to the console, because the for loop will run for three iterations and on each iteration it increments i since var has scope for the
entire function
2. 150 will be printed to the console because on the last iteration it will be
300 * 0.5 which is 150 thus 150 will be the last value set to discountedPrice and since var has scope for the entire function 150 will be printed out
3. 150 will be printed to the console because on the final iteration 150 will be the value of discountedPrice and multiplying and dividing by 100 will ive you the same result and since math.round roudns to the nearest integer it will do nothing to 15000 because it is already an integer and dividing it by 100 will return back 150. since finalPrice is a var it is accessable throughout the entire function
4. [50,100,150] this is because on every iteration the finalPrice is being pushed into the discounted array thus after the loop is done it will have all the finalprices and since discounted array is a var it is accessable throughout the entire function thus the array full of all the finalPrices is returned
5. The code returns an error because i is a let variable and it is defined in the for loop which has its own scope where variables in the scope cannnot be accessed outside of the for loops scope which in this case is the function. Thus on line 12, i is not defined so it returns an error 
6. The code returns an error because the discountedPrice is a let variable and its scope is only within the for loop and line 13 is outside of the for loop thus discountedPrice on line 13 is undefined because line 13 is outside of the scope of the for loop
7. 150 will be printed to the console because the finalPrice variable is a let variable defined in the scope of the function thus finalPrice is accesable within the scope of the for loop and is reassigned a new value every iteration and after the last iteration it is assigned the value 150 and on line 14 when it is called again it is accessable because finalPrice scope is within the function and it's value is 150 
8. [50,100,150] gets printed to the console because discounted is a let variable defined in the scope of teh function thus like finalPrice it isd accessable within the scope of the for loop and anywhere within the function as well. Thus within the for loop its gets add all teh finalPrices every iteration then gets returned outside of the for loop which is the resulting array of all the finalPrices
9. The code returns an error because i is a let variable and it is defined in the for loop which has its own scope where variables in the scope cannnot be accessed outside of the for loops scope which in this case is the function. Thus on line 12, i is not defined so it returns an error 
10. 3 because the length of prices is 3 and length is defined within the scope of the function thus it can be called anywhere within the function
11. [50,100,150] gets printed to the console because discounted is a const variable that is defined within the scope of the function thus it is accessable within the function and within the for loop and it is not being reassigned in the for loop, the array is simply updating with new values,a new array is not being assigned, thus when it is called again on line 14 to be returned it has all the discountedPrice values within it
12a) student.name
12b)student['Grad Year']
12c)student.greeting()
12d)student['Favorite teacher'].name
12e)student.courseLoad[0]
13a)'32' because JS maps the int to its string represnetation then contenates it with the string 2 giving a 32
13b)1 because a string conversion occurs when the minus is present and the '3' is converted to an int and the operaion follows, 3-2 = 1
13c)3 because the null gets converted to int 0 giving 3 + 0 which is 3
13d)'3null' because the null gets converted to a string then gets concatenated with the string 3
13e) 4 because the true boolean gets converted to the int 1 giving 1 + 3 which is 4
13f)0 because false and null both get converted to int 0 giving 0 + 0 which is 0
13g)'3undefined' because undefined gets converted to a string then is concatenated with 3 giving '3undefined'
13f)NaN because undefined gets converted to NaN thus leaving '3' - NaN which is not possible giving the result NaN
14a)true because 2 gets converted to an int and 2 is greater than 1
14b)false because it compares the very first character in the string in this case was '1' and '2' and '2' > '1' thus it returns false since
it wss '2' < '1'
14c)true because because the string '2' gets converted to an int 2 and 2 is equal to 2 thus it returns true
14d)false because the it is a string being compared to an int and they are different type so the strict equality check returns false
14e)false because a boolean is not equal to an int
14d)true because the boolean function converts the int to an boolean and thus both things being compared are booleans thus it returns true
15) The difference between the two operators is the == is equality test with type conversion and whereas === checks without different type conversion thus it checks if the two things are the same type
16)
for (const property in object) {
  if(property[0] == 'r' || object[property] % 2 != 0){
  	console.log(object[property]);
  };
}

17)
