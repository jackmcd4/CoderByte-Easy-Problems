/*Using the JavaScript language, have the function LetterChanges(str) 
take the str parameter being passed and modify it using the following algorithm. 
Replace every letter in the string with the letter following it in the alphabet (ie. c becomes d, z becomes a).
Then capitalize every vowel in this new string (a, e, i, o, u) and finally return this modified string. */

function LetterChanges(str) { 
var re = /[a-zA-Z]/;
var arr =[];
var hold =[];
var hold2 =[];
var vow = /[aeiou]/;  
for(var i=0; i<str.length; i++){
  if(str.charAt(i).match(re)){
      arr.push((str.charCodeAt(i)+1));
  }
  else{
      arr.push((str.charCodeAt(i)));
  }
}
for(var i=0; i<arr.length; i++){
    hold.push(String.fromCharCode(arr[i]));
}
hold = hold.join("");
  for(var i=0; i<hold.length; i++){
        if(hold.charAt(i).match(vow)){
            hold2.push(hold.charAt(i).toUpperCase());
         }
    else{
        hold2.push(hold.charAt(i));
    }
  }
  
hold2 = hold2.join("")
return hold2;
}
