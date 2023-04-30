Download Link: https://assignmentchef.com/product/solved-cs271-assignment-2
<br>
Write a program to calculate Fibonacci numbers.

<ul>

 <li>Display the program title and programmer’s name. Then get the user’s name, and greet the user.</li>

 <li>Prompt the user to enter the number of Fibonacci terms to be displayed. Advise the user to enter an integer in the range [1 .. 46].</li>

 <li>Get and validate the user input (<em>n</em>).</li>

 <li>Calculate and display all of the Fibonacci numbers up to and including the <em>n</em><u><sup>th</sup></u> The results should be displayed 5 terms per line with at least 5 spaces between terms.</li>

 <li>Display a parting message that includes the user’s name, and terminate the program.</li>

</ul>

<strong> </strong>

<strong>Requirements: </strong>

<ul>

 <li>The programmer’s name and the user’s name must appear in the output.</li>

 <li>The loop that implements data validation must be implemented as a post-test loop.</li>

 <li>The loop that calculates the Fibonacci terms must be implemented using the MASM <em>loop</em></li>

 <li>The <em>main</em> procedure must be modularized into at least the following <u>sections</u> (procedures are not required this time):

  <ol>

   <li>introduction</li>

   <li>userInstructions</li>

   <li>getUserData</li>

   <li>displayFibs</li>

   <li>farewell</li>

  </ol></li>

 <li>Recursive solutions are not acceptable for this assignment. This one is about iteration. 6)    The upper limit should be defined and used as a <u>constant</u>.</li>

 <li>The usual requirements regarding documentation, readability, user-friendliness, etc., apply.</li>

 <li>Submit your text code file (.<em>asm</em>) to Canvas by the due date.</li>

</ul>

<strong> </strong>

<strong>Notes: </strong>

<ul>

 <li>It is not necessary to store the Fibonacci numbers in an array. The terms may be displayed as they are generated.</li>

 <li>The second-order Fibonacci sequence is defined as:

  <ol>

   <li>The first two terms are both 1.</li>

   <li>All other terms are calculated as the sum of the two previous terms.</li>

   <li>The reason for restricting <em>n</em> to [1 .. 46] is that the 47<sup>th</sup> Fibonacci number is too big for <em>DWORD</em> data type.</li>

  </ol></li>

</ul>

<strong> </strong>

<strong>Example</strong> (see next page)

<h1>page 1 of 2</h1>




<strong>Example</strong> (user input in <strong><em>italics</em></strong>):

Fibonacci Numbers

Programmed by Leonardo Pisano




What’s your name? <strong><em>Paul</em></strong>

Hello, Paul

Enter the number of Fibonacci terms to be displayed Give the number as an integer in the range [1 .. 46].




How many Fibonacci terms do you want? <strong><em>50 </em></strong>Out of range.  Enter a number in [1 .. 46]

How many Fibonacci terms do you want? <strong><em>14 </em></strong>




1     1     2     3     5

8     13     21     34     55

89     144     233     377




Results certified by Leonardo Pisano.

Goodbye, Paul.







<strong>Extra-credit options </strong>(original definition must be fulfilled):

<ol>

 <li>Display the numbers in aligned columns.</li>

 <li>Do something incredible.</li>

</ol>




To ensure you receive credit for any extra credit options you did, you must add one print statement to your program output PER EXTRA CREDIT which describes the extra credit you chose to work on. You will not receive extra credit points unless you do this. The statement must be formatted as follows…