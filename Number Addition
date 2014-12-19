//This is almost there, but won't work if the str given looks like this: won80 8 or hat55 7 

/*Using the JavaScript language, have the function NumberSearch(str)
take the str parameter, search for all the numbers in the string, add them together,
then return that final number. For example: if str is "88Hello 3World!"
the output should be 91. You will have to differentiate between single digit
numbers and multiple digit numbers like in the example above.
So "55Hello" and "5Hello 5" should return two different answers. Each string will contain at least one letter or symbol. */

function NumberAddition(str) { 
  var count =0;
  var re = /[0-9]/gi;
  for(var i=0; i<str.length; i++){
    if(str.charAt(i).match(re) && str.charAt(i+1).match(re)){
      var hold = str.slice(i, i+2);
      var hold2 = parseInt(hold);
      count += hold2;
      str = str.slice(i+2,str.length);
    }
    else if(str.charAt(i).match(re)){
      var hold = parseInt(str.charAt(i));
      count += hold;
    }
  }
  return count;
}
