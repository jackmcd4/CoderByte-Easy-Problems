/*Using the JavaScript language, have the function Palindrome(str)
take the str parameter being passed and return the string true if the parameter is a palindrome,
(the string is the same forward as it is backward) otherwise return the string false. 
For example: "racecar" is also "racecar" backwards. Punctuation and numbers will not be part of the string. */

function Palindrome(str) { 
    var re = /[a-zA-Z]/;
    var arr=[];
  for(var i=0; i<str.length; i++){
    if(str[i].match(re)){
      arr.push(str[i]);
    }
  }
    arr = arr.join("");
    var str2 = arr;
    arr = arr.split("").reverse().join("");
  if(arr==str2){
    return true;
  }
  else{
    return false;
  }
  }
