/* Using the JavaScript language, have the function MeanMode(arr)
take the array of numbers stored in arr and return 1 if the mode equals the mean,
0 if they don't equal each other (ie. [5, 3, 3, 3, 1] should return 1 because the mode (3) equals the mean (3)).
The array will not be empty, will only contain positive integers, and will not contain more than one mode. */

function MeanMode(arr) { 
var avg=0;
  var count =0;
  for(var i=0; i<arr.length; i++){
    count+=arr[i];
  }
  avg = count/(arr.length);

  var freq={};
  var maxim=0;
  var result;
  for(var a in arr){
    freq[arr[a]]=(freq[arr[a]] || 0) +1;
    if(freq[arr[a]]>maxim){  
    maxim=freq[arr[a]];
      result = arr[a];
    }
  }

  if(avg===result){
    return 1;
  }
  else{
    return 0;
  }
  }
