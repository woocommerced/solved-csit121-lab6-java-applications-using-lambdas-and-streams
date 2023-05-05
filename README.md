Download Link: https://assignmentchef.com/product/solved-csit121-lab6-java-applications-using-lambdas-and-streams
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write Java applications using lambdas and streams.</li>

</ul>

<h1>Question 1</h1>

Write a Java application that declares an array of 20 elements to store the prices of items sold at a grocery store. Initialize the array with 20 prices. Then, using lambda and streams perform the following operations on the array created:

<ol>

 <li>Display all prices sorted in ascending order</li>

 <li>Display the total prices.</li>

 <li>Display the most expensive price, the cheapest price, and the average price.</li>

 <li>Count and display all prices that are above RM100 sorted in ascending order</li>

 <li>Increase all prices to 10% of its original price, sort, and display the new prices.</li>

 <li>Display all prices that are in the range of RM100 and RM500 inclusive.</li>

</ol>

<h1>Question 2</h1>

Declare and implement a class called Invoice with the following fields:

<ul>

 <li>part number (an integer value)</li>

 <li>description (such as hammer, wrench, sugar, flour, etc)</li>

 <li>type (such as hardware, grocery, etc)</li>

 <li>quantity (an integer)</li>

 <li>price (a double value)</li>

</ul>

Implement the following methods for the class Invoice:

<ul>

 <li>a non-default constructor that takes parameters to set all of its fields</li>

 <li>set methods for each of the fields</li>

 <li>get methods to retrieve each of the fields</li>

</ul>

Use the class Invoice above to create an array of Invoice objects. Use the data given in the data.txt file to set the values for each of the objects in the array. Then, perform the following queries on the array of Invoice objects and display the result.

<ol>

 <li>Use lambdas and streams to sort the Invoice objects by description, then display the results.</li>

 <li>Use lambdas and streams to sort the Invoice objects by price, then display the results.</li>

 <li>Use lambdas and streams to display the Invoice objects group by type.</li>

 <li>Use lambdas and streams to map each Invoice to its description and the value of the invoice (quantity * price). Order the results by Invoice value.</li>

 <li>Re-write (d) to select the Invoice values in the range of RM200 to RM500.</li>

</ol>

<h1>Question 3</h1>

Write a recursive method called power(), that takes as parameters two integers x and y such that x is non-zero and returns x<sup>y</sup>.  Use the following recursive definition to calculate x<sup>y</sup>.

If y ≥ 0:

1                           if y = 0

x<sup>y </sup> =                x                            if y = 1

x  ×  x<sup>y-1</sup>                if y ≠ 0




If y &lt; 0: x<sup>y </sup> =         <u>      1      </u> .

x<sup>y</sup>

Write a main method to test your recursive method above.  Let the user enters the value for x and y.  Call the recursive method and display the result.

<strong> </strong>


