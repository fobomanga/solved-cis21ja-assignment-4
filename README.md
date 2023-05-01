Download Link: https://assignmentchef.com/product/solved-cis21ja-assignment-4
<br>
Write a program that calculates the sum of N integers in a sequence.

<strong>Background</strong>An integer sequence has <em>N</em> integers, with a starting value <em>a</em>, and a constant difference <em>d</em> between 2 integers.For example: the sequence    3, 9, 15, 21              has N = 4, a = 3, d = 6and the sequence    1, 2, 3, 4, 5, 6, 7     has N = 7, a = 1, d = 1

The sum <em>S </em>of all <em>N</em> integers is calculated as:  <em>S = N(2a + (N-1)d) / </em>2

<strong> </strong>

<strong>Details</strong>

<ol>

 <li>Prompt the user for the <em>N</em>, <em>a</em>, and <em>d</em> values, in that order.</li>

</ol>

<ul>

 <li>The prompt should explain clearly what you expect from the user. For example, the prompt should not be simply “<em>d</em> “.  See sample output below.</li>

 <li>You can expect that the user will give you N, <em>a</em>, and <em>d</em> values that are between 1 and 100, so there’s no error checking needed.</li>

 <li>Given that 100 is the max value of all input, use the <em><u>appropriate data type</u></em> and the <em><u>register size</u></em> that can store the maximum output value, but not use the largest possible data size.2pts of the lab is for using the correct data type / size.</li>

</ul>




<ol start="2">

 <li>Calculate the sum, using the given formula.Be efficient with your code for the calculation. Refer to the class notes for suggestions.</li>

</ol>

1pt of the lab is for coding efficiency.




<ol start="3">

 <li>Print the values of <em>N</em>, <em>a</em>, <em>d</em>, and sum on one line of output. See sample output.The output line should be a separate line, so don’t forget the newline character at the end of the line.4. Do not declare and use any memory variable, except for text strings.The text strings for the prompts and the output text can be defined in the .data section, but all user input and calculation results should be in registers. This requirement is to encourage everyone to be on a ‘first name basis’ with the registers.</li>

</ol>

2 pts of the lab is for not using memory variables to store numeric data.




<ol start="5">

 <li>Documentation</li>

</ol>

<ul>

 <li>To get credit for the lab, don’t forget your name at the top.</li>

 <li>Use comments to explain logical blocks of code.</li>

 <li>It is also visually helpful to add a blank line between logical blocks.</li>

</ul>

<strong></strong>



<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Test</strong>Run multiple test cases: at least one with a small N and large a and d values, and another one with a large N and small a and d values.




Sample program output:Enter the number of integers: 90Enter the start integer: 3Enter the difference between integers: 1N = 90, a = 3, d = 1, sum = 4275