*/Using the JavaScript language, have the function LongestWord(sen)
take the sen parameter being passed and return the largest word in the string. 
If there are two or more words that are the same length,
return the first word from the string with that length. 
Ignore punctuation and assume sen will not be empty. */

function LongestWord(sen) { 
  var re=/[^a-zA-Z0-9\s]/
  for(var i=0; i<sen.length; i++){
    if(sen[i].match(re)){
      sen = sen.replace(sen[i], "");
    }
    if(sen[i] == "!"){//see description for explanation
      sen = sen.replace(sen[i], " ");
    }
  }
    var arr = [];
    arr = sen.split(" ");
    var hold =[];
  for(var i=0; i<arr.length; i++){
     hold[i] = arr[i].length;
  }
    var max = Math.max.apply(Math, hold);
  for(var i=0; i<arr.length; i++){
    if(max == arr[i].length){
        return arr[i];
    }
  }
  
}
