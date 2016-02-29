### Reverse a String
```js
var reverseString=s=>s.split``.reverse().join``;
```

### Factorialize a Number
```js
var factorialize=n=>n<2?1:n*factorialize(n-1);
```

### Check for Palindromes
```js
var palindrome=s=>(s=s.replace(/[^a-z0-9]/gi,'').toLowerCase()).split``.reverse().join``===s;
```

### Find Longest Word in a String
```js
var findLongestWord=s=>Math.max(...s.split` `.map(a=>a.length));
```

### Title Case a Sentence
```js
var titleCase=s=>s.split` `.map(a=>a[0].toUpperCase()+a.substr(1).toLowerCase()).join` `;
```

### Return Largest Numbers in Arrays
```js
var largestOfFour=a=>a.map(a=>Math.max(...a));
```

### Confirm the Ending of a String
```js
var end=(s,t)=>s.endsWith(t);
```

### Repeat a string repeat a string
```js
var repeat=(s,n)=>s.repeat(n>0?n:0);
```

### Truncate a string
```js
var truncate=(s,n)=>n<s.length?s.slice(0,n+(n<3?0:-3))+'...':s;
```

### Chunky Monkey
```js
var chunk=(a,s)=>a.map((b,c)=>c%s?0:a.slice(c,c+s)).filter(a=>a);
```

### Slasher Flick
```js
var slasher=(a,h)=>a.slice(h);
```

### Mutations
```js
var mutation=a=>!a[1].replace(RegExp('['+a[0]+']','ig'),'');
```

### Falsey Bouncer
```js
var bouncer=a=>a.filter(a=>a);
```

### Seek and Destroy
```js
function destroyer(a){return a.filter(a=>Array.from(arguments).indexOf(a)<=0);}
```

### Where do I belong
```js
var where=(a,n)=>a.sort().filter(a=>a<n).length;
```

### Caesars Cipher
```js
var rot13=s=>s.split('').map(a=>a.charCodeAt(0)).map(a=>a>64?((a-65)+13)%26+65:a).map(a=>String.fromCharCode(a)).join('');
```