12. 
    a. student.name;
    b. student['Grad Year'];
    c. student.greeting();
    d. student['Favorite Teacher'].name;
    e. student.courseLoad[0];

13. 
    a. '32',  integers 2 been converted to string '2'
    b. 1, string '3' is converted to numbers
    c. 3, null is converted to number and the value is 0
    d. '3null', null is converted to string and is equal to 'null'
    e. 4, true is converted to number and is equal to 1
    f. 0, both false and null are converted to number and are both equal to 0
    g. '3undefined', undefined is converted to string 'undefined'
    h. NaN, conversion failed for undefined

14. 
    a. true, string '2' is converted to number 2
    b. false, string comparison compare the first character of both strings and '2' > '1' so it is false
    c. true, string '2' is converted to number 2
    d. false, 2 and '2' are different types, it returns false without an attempt to convert them. 
    e. false, true is converted to number 1
    f. true, boolean of a nonzero number is true

15. === checks the equality without type conversion and == check the equality with type conversion

16. part2-question16.js

17. [2, 4, 6], since function is one of the data types, the function doSomething can be passed around like any other variable. Inside the modifyArray, the for loop will iterate 3 times since the array length is equal to 3. Each time the for loop iterate, it will take the original array value and pass it to doSomething function and it will double the value then return and push to the new array. 

18. part2-question18.js

19. 1 
    4 
    3
    2