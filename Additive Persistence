/*Using the JavaScript language, have the function AdditivePersistence(num) 
take the num parameter being passed which will always be a positive integer and return 
its additive persistence which is the number of times you must add the digits in num until 
you reach a single digit. For example: if num is 2718 then your program should return 2 
because 2 + 7 + 1 + 8 = 18 and 1 + 8 = 9 and you stop at 9. */


function AdditivePersistence(num) { 
var arr = num.toString();
var count=0;
var hold=0;
  var arr2 = arr.split("");
  if(arr2.length == 1){
    return count;
  }
  while(arr2.length!==1){
  for(var i=0; i<arr2.length; i++){
      hold += parseInt(arr2[i]);
  }
    count = count+1;
   arr = hold.toString();
  arr2 = arr.split("");
  hold =0;
  }
  return count;
}
