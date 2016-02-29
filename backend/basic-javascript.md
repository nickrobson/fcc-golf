### Comment Your Code
```js
/*abcde*///abcde
```

### Declare Javascript Variables
```js
var myName;
```

### Storing Values with the Equal Operator
```js
var a,b=2;a=7;b=a;
```

### Initializing Variables with the Equal Operator
```js
var a=9;
```

### Understanding Uninitialized Variables
```js
var a=5,b=10,c="I am a";a+=1;b+=5;c+=" String!";
```

### Understanding Case Sensitivity in Variables
```js
var studlyCapVar;var properCamelCase;var titleCaseOver;titleCaseOver=9000;studlyCapVar=10;properCamelCase="A String";
```

### Add Two Numbers with JavaScript
```js
var sum=+20;
```

### Subtract One Number from Another with JavaScript
```js
var difference=12-0;
```

### Multiply Two Numbers with JavaScript
```js
var product=1*80;
```

### Divide One Number by Another with JavaScript
```js
var quotient=2/1;
```

### Increment a Number with Javascript
```js
var myVar = 87;myVar++;
```

### Decrement a Number with Javascript
```js
var myVar = 11;myVar--;
```

### Create Decimal Numbers with JavaScript
```js
var myDecimal=.1;
```

### Multiply Two Decimals with JavaScript
```js
var product=2.5*2;
```

### Divide one Decimal by Another with JavaScript
```js
var quotient=2.2/1;
```

### Finding a Remainder in Javascript
```js
var remainder=2%3;
```

### Assignment with Plus Equals
```js
var a = 3;var b = 17;var c = 12;a+=12;b+=9;c+=7;
```

### Assignment with Minus Equals
```js
var a = 11;var b = 9;var c = 3;a-=6;b-=15;c-=1;
```

### Assignment with Times Equals
```js
var a = 5;var b = 12;var c = 4.6;a*=5;b*=3;c*=10;
```

### Assignment with Divided Equals
```js
var a = 48;var b = 108;var c = 33;a/=12;b/=4;c/=11;
```

### Convert Celsius to Fahrenheit
```js
var convert=c=>c*9/5+32;
```

### Declare String Variables
```js
var myFirstName='a';var myLastName='b';
```

### Escaping Literal Quotes in Strings
```js
var myStr="I am a \"double quoted\" string inside \"double quotes\"";
```

### Quoting Strings with Single Quotes
```js
var myStr='<a href="http://www.example.com" target="_blank">Link</a>';
```

### Escape Sequences in Strings
```js
var myStr='\\ \t \t \r \n';
```

### Concatenating Strings with Plus Operator 
```js
var ourStr='I come first. '+'I come second.';
var myStr='This is the start. '+'This is the end.';
```

### Concatenating Strings with the Plus Equals Operator
```js
var ourStr="I come first. ";ourStr+="I come second.";var myStr='';myStr+='This is the first sentence. This is the second sentence.';
```

### Constructing Strings with Variables
```js
var ourName = "Free Code Camp";var ourStr = "Hello, our name is " + ourName + ", how are you?";var myName='abc';var myStr='a'+myName+'c';
```

### Appending Variables to Strings
```js
var anAdjective = "awesome!";var ourStr = "Free Code Camp is ";ourStr += anAdjective;var someAdjective='abc';var myStr = "Learning to code is ";myStr+=someAdjective;
```

### Find the Length of a String
```js
var firstName = "Ada";firstNameLength = firstName.length;var lastNameLength = 0;var lastName = "Lovelace";lastNameLength=lastName.length;
```

### Use Bracket Notation to Find the First Character in a String
```js
firstLetterOfLastName=lastName[0];
```

### Understand String Immutability
```js
var myStr = "Jello World";myStr='Hello World';
```

### Use Bracket Notation to Find the Nth Character in a String
```js
var lastName="Lovelace";var thirdLetterOfLastName=lastName[2];
```

### Use Bracket Notation to Find the Last Character in a String
```js
var firstName="Ada";var lastLetterOfFirstName=firstName[firstName.length - 1];var lastName="Lovelace";var lastLetterOfLastName=lastName[lastName.length-1];
```

### Use Bracket Notation to Find the NthtoLast Character in a String
```js
var firstName="Ada";var thirdToLastLetterOfFirstName=firstName[firstName.length-3];var lastName="Lovelace";var secondToLastLetterOfLastName=lastName[lastName.length-2];
```

### Word Blanks
```js
var wordBlanks=(a,b,c,d)=>[a,b,c,d].join(' ');
```

### Store Multiple Values in one Variable using JavaScript Arrays
```js
var myArray=['',0];
```

### Nest one Array within Another Array
```js
var myArray=[[]];
```

### Access Array Data with Indexes
```js
var myData=myArray[0];
```

### Modify Array Data With Indexes
```js
myArray[0]=3;
```

### Access MultiDimensional Arrays With Indexes
```js
var myData = myArray[2][1];
```

### Manipulate Arrays With push
```js
myArray.push(['dog',3]);
```

### Manipulate Arrays With pop
```js
var removedFromMyArray=myArray.pop();
```

### Manipulate Arrays With shift
```js
var removedFromMyArray=myArray.shift();
```

### Manipulate Arrays with unshift
```js
myArray.unshift(['Paul',35]);
```

### Shopping List
```js
var myList=[['',0],['',1],['',2],['',3],['',4]];
```

### Write Reusable JavaScript with Functions
```js
var myFunction=()=>console.log('Hi World');myFunction();
```

### Passing Values to Functions with Arguments 
```js
var myFunction=(a,b)=>console.log(a+b);myFunction(0,0);
```

### Global Scope and Functions
```js
var myGlobal=10,fun1=()=>oopsGlobal=5;
```

### Global vs Local Scope in Functions
```js
var outerWear="sweater";
```

### Return a Value from a Function with Return
```js
var timesFive=n=>n*5;
```

### Assignment with a Returned Value
```js
processed = process(7);
```

### Stand in Line
```js
var queue=(a,b)=>a.push(b)&&a.shift();
```

### Understanding Boolean Values
```js
return !0;
```

### Use Conditional Logic with If Statements
```js
var myFunction=a=>'That was '+a;
```

### Comparison with the Equality Operator
```js
var myTest=v=>(v==12?'':Not ')+'Equal';
```

### Comparison with the Strict Equality Operator
```js
var myTest=v=>(v===7?'':Not ')+'Equal';
```

### Comparison with the Inequality Operator
```js
var myTest=v=>(v!=99?'':Not ')+'Equal';
```

### Comparison with the Strict Inequality Operator
```js
var myTest=v=>(v!==17?'':Not ')+'Equal';
```

### Comparison with the Greater Than Operator
```js
var myTest=v=>v>100?'Over 100':(v>10?'Over 10':'10 or under')
```

### Comparison with the Greater Than Or Equal To Operator
```js
var myTest=v=>v>19?'20 or Over':(v>9?'10 or Over':'9 or under')
```

### Comparison with the Less Than Operator
```js
var myTest=v=>v<25?'Under 25':(v<55?'Under 55':'55 or Over')
```

### Comparison with the Less Than Operator
```js
var myTest=v=>v<13?'Smaller Than or Equal to 12':(v<25?'Smaller Than or Equal to 24':'25 or More')
```

### Comparisons with the Logical And Operator 
```js
var myTest=v=>v<=50&&v>=25?"Yes":"No";
```

### Comparisons with the Logical Or Operator
```js
var myTest=v=>v<10||v>20?"Outside":"Inside";
```

### Introducing Else Statements
```js
var myTest=v=>v>5?"Bigger than 5":"5 or Smaller";
```

### Introducing Else If Statements
```js
var myTest=v=>val<11?val<5?"Smaller than 5":"Between 5 and 10":"Greater than 10";
```

### Chaining If Else Statements
```js
var myTest=n=>n<20?n<15?n<10?n<5?'Tiny':'Small':'Medium':'Large':'Huge';
```

### Golf Code
```js
function golfScore(par, strokes) {
  if      (strokes == 1)     return 'Hole-in-one!';
  else if (strokes <= par-2) return 'Eagle';
  else if (strokes == par-1) return 'Birdie';
  else if (strokes == par)   return 'Par';
  else if (strokes == par+1) return 'Bogey';
  else if (strokes == par+2) return 'Double Bogey';
  else                       return 'Go Home!';
}
```

### Selecting from many options with Switch Statements
```js
var myTest=v=>{1:'alpha',2:'beta',3:'gamma',4:'delta'}[v];
```

### Adding a default option in Switch statements
```js
answer={a:'apple',b:'bird',c:'cat'}[v]||'stuff';
```

### Multiple Identical Options in Switch Statements
```js
var myTest=v=>v>3?v>6?'High':'Mid':'Low';
```

### Returning Boolean Values from Functions
```js
var isLess=(a,b)=>a<b;
```

### Return Early Pattern for Functions
```js
if(a<0||b<0)return undefined;
```

### Build JavaScript Objects
```js
var myDog={name:'',legs:4,tails:9,friends:[]};
```

### Accessing Objects Properties with the Dot Operator
```js
var hatValue=testObj.hat;
var shirtValue=testObj.shirt;
```








