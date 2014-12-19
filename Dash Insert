/*Using the JavaScript language, have the function DashInsert(str) insert dashes ('-') between each two odd numbers in str.
For example: if str is 454793 the output should be 4547-9-3. Don't count zero as an odd number. */

function DashInsert(num) { 
var arr = num.toString();
  var arr2 = arr.split("");
  var hold =[];
  for(var i=0; i<arr2.length-1; i++){
    if(arr2[i]%2!==0 && arr2[i+1]%2!==0){
      hold.push(arr2[i]);
      hold.push("-");
      }
    else if(arr2[i]%2!==0 && arr2[i+1]%2==0){
      hold.push(arr2[i]);
    }
    else if(arr2[i]%2==0){
      hold.push(arr2[i]);
    }
  }
  hold.push(arr2[arr2.length-1]);
  var hold2 = hold.join("");
  return hold2;
}
