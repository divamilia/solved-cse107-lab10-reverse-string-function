Download Link: https://assignmentchef.com/product/solved-cse107-lab10-reverse-string-function
<br>
<ol>

 <li>Write the reverse string() function for the given code below.</li>

</ol>

(Hint: use strlen() function which gives the length of a string.)

<table width="425">

 <tbody>

  <tr>

   <td width="425">#include&lt;stdio.h&gt; #include&lt;string.h&gt; void reverse_string(char str[]);int main(){ char str_arr[100];printf(“Enter a string:”); scanf(“%s”, str_arr); reverse_string(str_arr);printf(“Reversed string is: %s 
”, str_arr);return 0;}</td>

  </tr>

 </tbody>

</table>

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

16

1

<ol start="2">

 <li>Write print line(), print histogram() and len() functions for the given code below. <strong>printline() </strong>: Prints <em>&lt;</em>int num of chars<em>&gt; </em>times <em>&lt;</em>char c<em>&gt; </em>character. <strong>print</strong><strong>histogram() </strong>: Prints a histogram of <em>&lt;</em><strong>int values[]</strong><em>&gt; </em>with <em>&lt;</em><strong>char c</strong><em>&gt; </em>using print print line() and len() functions. <strong>len() </strong>: Returns the length of <em>&lt;</em><strong>int array[]</strong><em>&gt;</em>.</li>

</ol>

<table width="425">

 <tbody>

  <tr>

   <td width="425">#include&lt;stdio.h&gt; void print_line(char c, int num_of_chars); void print_histogram(char c, int vals[]); int len(int arr[]);int main(){ int values[100], val=1, count=0; printf(“Enter positive integer(s), to print anhistogram.
Enter a non-positive integer to stop.

”); do{ printf(“Enter a value:”); scanf(“%d”, &amp;val); values[count] = val; count++; }while(val &gt; 0); print_histogram(’*’, values); return 0;}</td>

  </tr>

 </tbody>

</table>

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

16

17

18

19

20

21

<strong>Sample:</strong>

Enter positive integer(s), to print an histogram. Enter a non-positive integer to stop.

Enter a value: <strong>3</strong>

Enter a value: <strong>5</strong>

Enter a value: <strong>6</strong>

Enter a value: <strong>2 </strong>Enter a value: <strong>-1</strong>

Output: ***

*****

******

**