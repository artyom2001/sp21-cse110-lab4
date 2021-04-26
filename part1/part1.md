# Answers for Part 1 of Lab #4
## Part 1a
1. 20
2. 20
3. 20
4. Error because the result is not defined outside the scope of the if statement
5. Error because result is a constant value
6. Error because result is a constant value
   
## Part 1b
1. 3 because the for loop counts one more than the size of the prices array
2. 150 because the last discounted price in the array is 300*0.5
3. 150 because the rounded price of the last discounted price is the same
4. [50, 100, 150] because each price in the array is discounted by half.
5. Error because i is not defined outside the for loop
6. Error because discountedPrice is not defined outside the for loop
7. 150 because finalPrice's scope is the entire function
8. [50, 100, 150] because each price in the array is discounted by half.
9. Error because i is not defined outside the for loop
10. 3 because it is the length of the prices array, which also doesnt change
11. [50, 100, 150] because each price in the array is discounted by half.

12. <ol type="A">
    <li>student&#46;name;</li>
    <li>student['Grad Year'];</li>
    <li>student.greeting();</li>
    <li>student['Favorite Teacher'].name;</li>
    <li>student.courseLoad[0];</li>
    </ol>

13. <ol type="A">
    <li>'32', because 2 maps to the string '2', so it is concatenated</li>
    <li>1, because '3' is converted to an integer and then subtracted</li>
    <li>3, because null is equal to 0 as an integer</li>
    <li>'3null', because null will become 'null' as a string and concatenated</li>
    <li>4, because true is equal to 1 as an integer</li>
    <li>0, because both false and null are equal to 0 as integers</li>
    <li>'3undefined', because undefined will become a stirng and concatenated</li> 
    <li>NaN, because undefined is converted to NaN as an integer when subtracted</li>
    </ol> 

14. <ol type="A">
    <li>true, because the '2' is converted to an integer</li>
    <li>false, because it is a string comparison between the first two characters</li>
    <li>true, the '2' is converted to an intger, so they are equal</li>
    <li>false, because two different types: string and integer</li>
    <li>false, because true is converted to a 1, and 1!=2</li>
    <li>true, because both are boolean values which are true</li>
    </ol> 

15. The == checks for equality but can't differentiate types because of type conversion, while === can
16. [Q16](/part1/part1b-question16.js)
17. The result after caling modifyArray([1,2,3], doSomething) will be [2,4,6] because the callback function doubles every element in the passed array and adds it into the resulting array.
18. [Q18](/part1/part1b-question18.js)
19. 1, 4, 3, 2