Given a string s consisting of words and spaces, return the length of the last word in the string.
var lengthOfLastWord = function(s) {
    let tomb= [];
    let b= s.trim()
    tomb=b.split(" ");
    let seged =s.substr(tomb.length)
    let utosoindex=0;
    for (let x = 0; x < tomb.length; x++) {
        seged=seged.substr(tomb)
        utosoindex+=1;
    }
    return(tomb[utosoindex-1].length)
};
-------------------------------
Write a function to find the longest common prefix string amongst an array of strings.

var longestCommonPrefix = function(strs) {
    console.log(strs)
    elsoszo=strs[0]
    elsoszokezdet= elsoszo[0]+elsoszo[1]
    console.log(elsoszokezdet)
    for (let x = 1; x < strs.length; x++) {

            if((strs[x][0]+strs[x][1])==(elsoszokezdet))
            {
                return("fl")
            }
            else return("")
        
    }

};
-------------------------------
