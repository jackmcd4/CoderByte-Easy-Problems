//wont work if the word is repeated

/*Using the JavaScript language, have the function ThirdGreatest(strArr)
take the array of strings stored in strArr and return the third largest word within in. 
So for example: if strArr is ["hello", "world", "before", "all"] your output should be world because 
"before" is 6 letters long, and "hello" and "world" are both 5, but the output should be world because it
appeared as the last 5 letter word in the array. If strArr was ["hello", "world", "after", "all"]
the output should be after because the first three words are all 5 letters long, 
so return the last one. The array will have at least three strings and each string will only contain letters. */

function ThirdGreatest(strArr) { 
    var count=[];
    for (var h=0; h<strArr.length; h++){
        count[h]=strArr[h].length;
    }

    for(var i=0; i<2; i++){
    var max1 = Math.max.apply(Math, count);
    for(var j=0; j<count.length; j++){
        if(max1===count[j]){
           count[j]=0;    
        }
    }
    }
    var max3 = Math.max.apply(Math, count);
    for(var i=0; i<strArr.length; i++){
        if(max3===strArr[i].length){
            return strArr[i];
        }
    }
}
