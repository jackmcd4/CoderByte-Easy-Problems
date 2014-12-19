/*Using the JavaScript language, have the function ABCheck(str)
take the str parameter being passed and return the string true if the characters
a and b are separated by exactly 3 places anywhere in the string at least once (ie. "lane borrowed"
would result in true because there is exactly three characters between a and b).
Otherwise return the string false. */

function ABCheck(str) { 
   var check=0; 
 for(var i=0; i<str.length; i++){
   if(str.charAt(i).toUpperCase() == "A"){
      if(str.charAt(i-4).toUpperCase() == "B" || str.charAt(i+4).toUpperCase() =="B"){
        check=check+1;
      }
   }
   if(str.charAt(i).toUpperCase() == "B"){
      if(str.charAt(i-4).toUpperCase() =="A" || str.charAt(i+4).toUpperCase() =="B"){
       check=check+1;
      }
   }
 }        
  if(check>0){
    return true;
  }
  else{
    return false;
  }
 }
