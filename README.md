Download Link: https://assignmentchef.com/product/solved-data-structures-and-algorithms-info6205-homework-2
<br>
Put all your java, compiled class files and documentation files into a zip file named Homework2.zip and submit it via the drop box on the blackboard before the END of due date. Put your name on all .java files. There will be a short quiz on this homework.




<ol>

 <li>Human use Infix expression and computers use Postfix expression. Consider these</li>

</ol>

Infix expressions:

(1 + 2 * (20 / 5 ))

(1 + 3 + ( ( 4 / 2 ) * ( 8 * 4 ) ))

(4 + 8) * (6 – 5)/((3 – 2) * (2 + 2))




<ol>

 <li>a) Evaluate Infix expression</li>

 <li>i) use two arrays</li>

 <li>ii) use single array</li>

</ol>

iii) discuss the running time of (i) and (ii)

<ol>

 <li>b) Convert Infix expression to Postfix</li>

 <li>c) Evaluate Postfix expression</li>

</ol>




Write Java code for (a,b,c) as described above, compile and run Infix examples.




<ol start="2">

 <li>Consider the following Algorithm to convert Infix expression to Postfix.</li>

</ol>




<ol>

 <li>a) Consider Infix expression example: ( ( A / ( B + C ) ) – D )</li>

 <li>b) Apply Algorithm to Infix example, show step-by-step</li>

 <li>c) Write Java code for the algorithm to convert Infix to Postfix expression</li>

</ol>




Algorithm:

while there are more symbols to read

read the next symbol

case:

operand –&gt;     output it.

’(’     –&gt;     push it on the stack.

’)’     –&gt;     pop operators from the stack to the output

until a ’(’ is popped; do not output either of

the parentheses.

operator –&gt;     pop higher- or equal-precedence operators

from the stack to the output; stop before

popping a lower-precedence operator or

a ’(’. Push the operator on the stack.

end case

end while

pop the remaining operators from the stack to the output

<ol start="3">

 <li>For the LinkedList implementation of Queue example discussed in class, write a TestLinkedListQueue class to test enqueue, dequeue,, isEmpty and other operations as needed with</li>

</ol>

{item1, item2, item3, item4, item5}




<ol start="4">

 <li>Describe the Array Implementation of Queue with the following example. Use ample main() shown below and write the Java code for enqueue and dequeue, and other operations as necessary and manage the head and tail pointers. Test and Print the queue at each operation.</li>

</ol>




<strong>public</strong> <strong>static</strong> <strong>void</strong> main(String a[]){

MyQueue queue = <strong>new</strong> MyQueue(5);

queue.enqueue(4);

queue.dequeue();

queue.enqueue(56);

queue.enqueue(2);

queue.enqueue(67);

queue.dequeue();

queue.dequeue();




5.Write a Iterative method to sumDigits that has one integer parameter and returns the sum of the digits in the integer specified. The method should throw an IllegalArgumentException if the integer specified is negative. Remember, your method should not use iterative loops. For example, if the integer is 26397, then this method should return 27.




<ol start="6">

 <li>Write a recursive method countStringBinarythat has one integer parameter n and returns the number of binary strings of length n that do not have two consecutive 0’s. For example, for n = 4, the number of binary strings of length 4 that do not contain two consecutive 0’s is 8: 1111, 1110, 1101, 1011, 1010, 0111, 0110, 0101</li>

</ol>