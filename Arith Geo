
function ArithGeo(arr) { 
    var arith=0;
    var geo=0;
  for (var i=0; i<arr.length; i++){
    if(arr[i]/arr[i-1] == arr[i-1]/arr[i-2]){
      geo+=1;
    }
    else if(arr[i]-arr[i-1]==arr[i-1]-arr[i-2]){
      arith+=1;
    }
  }
  if(arr[arr.length-1]/arr[arr.length-2]!==arr[arr.length-2]/arr[arr.length-3]){
      geo=0;
  }
  if(arr[arr.length-1]-arr[arr.length-2]!==arr[arr.length-2]-arr[arr.length-3]){
      arith=0;
  }
if(arr.length>3){
  if(arr[arr.length-2]/arr[arr.length-3]!==arr[arr.length-3]/arr[arr.length-4]){
    geo=0;
  }
  if(arr[arr.length-2]-arr[arr.length-3]!==arr[arr.length-3]-arr[arr.length-4]){
    arith=0;
  }
}
  if(arith>0){
    return "Arithmetic";
  }
  else if(geo>0){
    return "Geometric";
  }
  else{
    return -1
    }

}
