Download Link: https://assignmentchef.com/product/solved-c-programming-language-project-3
<br>
<strong>Part 1. </strong>Write a complete program implementing a simple calculator program. The calculator should have the usual binary operators: addition (+), substraction (-), multiplication (*), division (/), power (**) and modulo (%). The users of the program enter the operation they want to carry out in prefix notation.For example, the following input<sub>          </sub>

<sub>               </sub>+ 10 2

adds 10 and 2 returning 12. If the operator has only one argument, it takes the result of the previous operation as the first argument. If there is no previous operation (e.g., at the very beginning), 0 will be used.<sub>       </sub>

An example run of the program follows:

+ 10 2

12

** 8 2

64 / 2

32 *

10

320 %

10 0













+ 10

10

– 8

<sub>               </sub>2

You are additionally asked to define and use a function called <strong>doit.</strong> This function accepts three arguments: a function to represent the desired operator and two integer inputs. You are not allowed to apply the operator directly. This will require you to define at least 7 functions in your code and also <sub> </sub><strong>menu function</strong> . Example use of doit function is given below:

<sub>          </sub>int  add(number1,  number2); <sub>    </sub>int sub(number1,  number2);

…

<sub> </sub>doit (add, first_number, second  number); doit (sub, first_number, second_number);




<strong>Part 2. </strong>Write a program that takes three arrays. The size of the first array should be 10 and it has to include homework grades. The size of the second array should be 10 and it has to include lab grades. The size of the third array should be 2 and it represents midterm and final grades. The grades will be taken from the user and will be assigned to the each cell of the arrays. Firstly you should calculate the average of the lab and homework grades, seperately. Then you should calculate the weighted average all of grades. To calculate the weighted average, you should take 10% of the average homework grade, 20%of the average lab grade, 30% of the midterm grade and %40 of the final grade. You should use these functions;




Page <strong>1</strong> of <strong>3 </strong>

int take_grades(int [] );<sub>         </sub> int take_exam_grades(int[]);              double calculate_homework<sub>             </sub>(int[]); double calculate_lab(int[]);<sub>   </sub>

double calculate_all(int ,int[],int);







<strong>Part 3. </strong>In this part , you should take height of the shape from user. For example user enters the height number x, will press * character twice. Then should add 4 times and 6 times until the number of * will be (x-1)2. A triangle must be created from the combination of stars, triangle should be surrounded by the shape of / , characters. After the first triangle formed by expanding towards the bottom, the second triangle should be narrowing towards the bottom. Shapes must be look like that;







<strong>Output Example: </strong>







Page <strong>2</strong> of <strong>3 </strong>













Page <strong>3</strong> of <strong>3 </strong>