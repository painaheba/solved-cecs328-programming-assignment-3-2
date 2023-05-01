Download Link: https://assignmentchef.com/product/solved-cecs328-programming-assignment-3-2
<br>



<h1>1      Robot Delivery</h1>

A robot is delivering products for a company in a city with a only one-way streets. The robot is required to deliver to at least one household on every street and then return to its original destination for refit and repair. The city charges the robot a small fee per street that it traverses; this fee is charged <em>every time </em>that the robot crosses from one intersection to the next. Fees vary depending on the street, but every street that the robot is allowed to travel on requires a fee of at least 1; any streets that have 0 fee mean that the robot is not allowed to travel there. The robot’s goal is to minimize the total fees that it is charged for delivering all of its products, respecting the constraints.

<h1>2     Input/Output</h1>

The first line of the input file (input.txt) will hold the number <em>n </em>of intersections in the city. What follows will be an <em>n </em>× <em>n </em>adjacency matrix. Any 0 (<em>i,j</em>) entry in the adjacency matrix indicates that you cannot cross from intersection <em>i </em>to intersection <em>j</em>. A nonzero (<em>i,j</em>) entry will represent the fee that it costs to travel from intersection <em>i </em>to intersection <em>j</em>.

The intersections are numbered from 0 to <em>n </em>− 1.

You may choose any cycle of minimum total fee as long as it starts and ends at the same intersection.

Your output will be a sequence of integers from 0 to <em>n</em>−1 with a space after each.

<h1>3     Example</h1>

The input file (input.txt) may look like the following:

5

0 22566 46247 86550 85679

0 0 17214 0 0

1

77002 0 0 31972 0

0 0 0 0 12066

63767 0 0 6302 0

The output file (output.txt) could look like the following (and remember that there will be multiple correct answers for any given input):

0 4 3 4 0 3 4 0 2 3 4 0 1 2 0

2