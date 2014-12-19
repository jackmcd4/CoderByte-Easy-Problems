/*Using the JavaScript language, have the function LetterCapitalize(str) 
take the str parameter being passed and capitalize the first letter of each word.
Words will be separated by only one space. */


function LetterCapitalize(str) { 
var re = /[a-zA-Z]/;
  var arr = [];
  arr.push(str.charAt(0).toUpperCase());
  for(var i=1; i<str.length; i++){
      if(str.charAt(i).match(re)){
         arr.push(str.charAt(i));
     }
      else{
         arr.push(str.charAt(i) + str.charAt(i+1).toUpperCase());
         i=i+1;
      }
  }
  arr = arr.join("");
  return arr;
}
