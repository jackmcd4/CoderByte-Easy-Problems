/*There is definitely a better, simpler way to do this, needs major editing.
The issue I ran into was if the lowest or greatest had repeated numbers.*/

/*Using the JavaScript language, have the function SecondGreatLow(arr)
take the array of numbers stored in arr and return the second lowest and second greatest numbers, 
respectively, separated by a space. For example: if arr contains [7, 7, 12, 98, 106] the output should be 12 98.
The array will not be empty and will contain at least 2 numbers. It can get tricky if there's just two numbers! */

function SecondGreatLow(arr) { 

  if(arr.length ===2){
    var fin2 = arr.join(" ");
    return fin2;
  }
  var newArr = [];
  var low = Math.min.apply(Math, arr);
  var high = Math.max.apply(Math, arr);
  var whereH= arr.indexOf(high);
  var remove1 = arr.splice(whereH,1);
  var whereL= arr.indexOf(low);
  var remove2 = arr.splice(whereL,1);
  var newLow = Math.min.apply(Math, arr);
    newArr.push(newLow);
  var newHigh = Math.max.apply(Math, arr);
    newArr.push(newHigh);

  var fin = newArr.join(" ");

  return fin;
    
}
