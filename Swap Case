/*Using the JavaScript language, have the function SwapCase(str) take the str parameter and swap the case of each character.
For example: if str is "Hello World" the output should be hELLO wORLD. Let numbers and symbols stay the way they are. */

function SwapCase(str) { 
var re1 = /[A-Z]/g;
  var re2 = /[a-z]/g;
 var hold = [];
  for(var i=0; i<str.length; i++){
    if(str.charAt(i).match(re1)){
   hold.push(str.charAt(i).toLowerCase());
    
    }
   else if(str.charAt(i).match(re2)){
   hold.push(str.charAt(i).toUpperCase());
  
   }
    else if(str.charAt(i) !== re1 || str.charAt(i) !== re2){
      hold.push(str.charAt(i));
    }
  }
    var hold2 = hold.join("");
return hold2;
  
}
