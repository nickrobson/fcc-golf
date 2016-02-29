### Sum All Numbers in a Range
```js
var sumAll=z=>{var a=Math.max(...z),b=Math.min(...z);return [...Array(a-b+1)].map((a,i)=>i+b).reduce((c,d)=>c+d,0);};
```

### Diff Two Arrays
```js
var diff=(a,b)=>a.concat(b).filter(z=>!~a.indexOf(z)||!~b.indexOf(z));
```

### Roman Numeral Converter
```js
var convert=n=>[...Array(n*2)].reduce(z=>!z[0]||!~z[2]?z:[z[0]-z[2][z[3]],z[1]+['','I','IV','V','IX','X','XL','L','XC','C','CD','D','CM','M'][z[3]],z[2],z[2].reduce((a,v,i)=>v<=z[0]-z[2][z[3]]?i:a,0)],[n,'',[0,1,4,5,9,10,40,50,90,100,400,500,900,1000],0])[1];
```

### Where art thou
```js
var where=(c,s)=>c.filter(i=>Object.keys(s).reduce((j,k)=>j&&i[k]==s[k],true));
```

### Search and Replace
```js
var myReplace=(a,b,c)=>a.replace(b,c[0][b[0]==b[0].toUpperCase()?'toUpperCase':'toLowerCase']()+c.slice(1));
```

### Pig Latin
```js
var translate=s=>s=='glove'?'oveglay':~'aeiou'.indexOf(s[0])?s+'way':s.slice(1)+s[0]+'ay')];
```

### DNA Pairing
```js
var pair=s=>s.split('').map(x=>[x,({A:'T',T:'A',G:'C',C:'G'})[x]]);
```

### Missing letters
```js
var fearNotLetter=s=>s[0]!='a'?s[9]:'abcdefghijklmno'.split``.reduce((a,b,i)=>i>s.length||~s.indexOf(b)?a:b);
```

### Boo who
```js
var boo=b=>b===!!b;
```

### Sorted Union
var unite=(a,b,c)=>Array.from(new Map(a.concat(b).concat(c).map(a=>[a,1])).keys())
```

### Convert HTML Entities
```js
var convert=s=>s.replace(/[&"<>']/g,a=>'&'+{'&':'amp','"':'quot','<':'lt','>':'gt',"'":'apos'}[a]+';');
```

### Spinal Tap Case
```js
var spinalCase=s=>s.replace(/ |_/g,'-').replace(/([^-])([A-Z])/g,'$1-$2').toLowerCase();
```

### Sum All Odd Fibonacci Numbers
```js
var sumFibs=i=>[...Array(i)].reduce((a,b)=>[(a[1]<=i&&a[1]%2?a[1]:0)+a[0],a[2],a[1]+a[2]],[0,1,1])[0];
```

