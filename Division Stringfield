//This is also a work in progress, it only works up to a point and I need more sig figs.

/*Using the JavaScript language, have the function DivisionStringified(num1,num2)
take both parameters being passed, divide num1 by num2, and return the result as a 
string with properly formatted commas. If an answer is only 3 digits long, return the number with no commas
(ie. 2 / 3 should output "1"). For example: if num1 is 123456789 and num2 is 10000 the output should be "12,345". */ 

function DivisionStringified(num1,num2) { 
var div = num1/num2;
 var n = div.toString();
 var hold;
  if(n.length>3){
    for(var i=n.length-3; i>0; i-=3){
     var hold = n.slice(0,i) + "," + n.slice(i, i+3); 
    }
  n = hold;
  }
  
  return n;
      

  
