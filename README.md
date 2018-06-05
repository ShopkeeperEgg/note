# note

 ## 正则表达式esec匹配方法
 function tokenize(TOKEN_REGEX, str) {
   let result = [];
   let match;
   while (match = TOKEN_REGEX.exec(str)) {
     result.push(match[1]);
   }
   return result;
  }
 

