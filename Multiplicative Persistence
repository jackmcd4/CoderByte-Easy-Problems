/*Using the JavaScript language, have the function MultiplicativePersistence(num)
take the num parameter being passed which will always be a positive integer and
return its multiplicative persistence which is the number of times you must multiply 
the digits in num until you reach a single digit. For example:
if num is 39 then your program should return 3 because 3 * 9 = 27 then 2 * 7 = 14 
and finally 1 * 4 = 4 and you stop at 4. */

function MultiplicativePersistence(num) { 
var count=0;
  var hold=1;
  var arr =num.toString();
  var arr2=arr.split("");
  if(arr.length==1){
    return count;
  }
  while(arr2.length!==1){
    for(var i=0; i<arr2.length; i++){
      hold*=parseInt(arr2[i]);
    }
    count++;
    arr=hold.toString();
    arr2=arr.split("");
    hold=1;
  }
  return count;
         
}
   
