1-You are working at Toyota Indus Motors and want to assemble a car. Design a flowchart with proper process modules and decision structures to replicate a pipeline production.
![FLOWCHART ](https://github.com/user-attachments/assets/c99ab768-5795-4240-ba7d-f92d1a01348f)

2-Find the maximum number in any of the three variables.

Start
print"Input Three Distinct Numbers"
Input n1
Input n2
Input n3
IF(n1>n2) AND (n1>n3) Then
Print n1,"is the largest"
ELSE IF(n2>n1) AND (n2>n3) Then
Print n2,"is the largest"
ELSE IF(n3>n1) AND (n3>n2) Then
Print n3,"is the largest"
ELSE IF(n1=n2) and (n1>n3){

3-Take three variables as input and add them without using the + operator/

Start
Print"Enter number 1"
Input n1
Print"Enter number 2"
Input n2
Print"Enter number 3"
Input n3
Set c to n1-(-n2)-(-n3)
print c
End

4-Create a small calculator which only does ‘+’ or ‘-‘OperaƟons. (Hint: Take three variable inputs with one being used for the operator)

Start
Print"Enter number 1"
Input n1 as integer
Print"Enter number 2"
Input n2 as integer
Print"Enter the operator"
Input c //as character 'where c represents operator'
if(c = +){
print n1+n2
}
else if(c = -){
print n1-n2
}
End

5-Implement an algorithm for determining if an Nth is a divisor of an n Number (i.e. 2 is a divisor of 6). If so, determine if it’s an even number or odd number as well.

Ask user to input n
Ask user to input N
if(n%N==0), then display "Yes it is a divisor" and go to step 5
else display"No, It is not a divisor"
if(N%2==0), then display"N is an even number"
else display "N is an odd number"


6-Implement an algorithm where the user enters a number, and an appropriate month is displayed.

Ask the user for to input any number between 1-12
If number is 1, Set month to january and display month
If number is 2, Set month to february and display month
If number is 3, Set month to march and display month
If number is 4, Set month to april and display month
If number is 5, Set month to may and display month
If number is 6, Set month to june and display month
If number is 7, Set month to july and display month
If number is 8, Set month to august and display month
If number is 9, Set month to september and display month
If number is 10, Set month to october and display month
If number is 11, Set month to november and display month
If number is 12, Set month to december and display month

7-Implement an algorithm for making a simple calculator with all the operators (+,-,*,/,%)

Set o1 for "+"
Set o2 for "-"
Set o3 for "*"
Set o4 for "/"
Ask user for FN   //First Number
Ask user for SN   //Second Number
Display all 4 operators along with their representatives
Ask user to select one represntative in variable a
If user select '+', display FN+SN
If user select '-', display FN-SN
If user select '*', display FN*SN
If user select '/', display FN/SN
