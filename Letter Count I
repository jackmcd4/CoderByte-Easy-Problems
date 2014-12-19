//Forwarning, this one is incomplete, it still doesn't alway get the correct output and so is a work in progress

/*Using the JavaScript language, have the function LetterCountI(str)
take the str parameter being passed and return the first word with the greatest number of repeated letters.
For example: "Today, is the greatest day ever!" should return greatest because it has 2 e's (and 2 t's)
and it comes before ever which also has 2 e's. If there are no words with repeating letters return -1.
Words will be separated by spaces. */


function LetterCountI(str) { 
  var arr = str.split(" ");
  var great=0;
  var word =undefined;
  var count=1;
  for(var i=0; i<arr.length; i++){
    for(var j=0; j<str.length; j++){
      if(arr[i][i]==arr[i][j]){
        count++;
      }
    }
    if(count>great){
      great = count;
      word = arr[i]; 
    }
    count =0;
  }
  if(great==1){
    return -1;
  }
  return word;
}
