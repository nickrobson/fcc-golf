### Declare JavaScript Objects as Variables
```js
var motorBike={wheels:2,engines:1,seats:2};
```

### Construct JavaScript Objects with Functions
```js
var MotorBike=()=>{this.wheels=2,this.engines=1,this.seats=2;};
```

### Make Instances of Objects with a Constructor Function
```js
var myCar=new Car();myCar.nickname='a';
```

### Make Unique Objects by Passing Parameters to our Constructor
```js
var Car=(a,b,c)=>{this.wheels=a;this.seats=b;this.engines=c;},myCar=new Car(1,2,3);
```

### Make Object Properties Private
```js
var Bike=()=>{var gear=1;this.getGear=()=>gear;this.setGear=g=>gear=g;};
```

### Iterate over Arrays with map 
```js
var newArray=oldArray.map(a=>a+3);
```

### Condense arrays with reduce
```js
// singleVal is already defined
singleVal=array.reduce((a,b)=>a+b);
```

### Filter Arrays with filter
```js
var newArray=oldArray.filter(a=>a<=5);
```

### Sort Arrays with sort
```js
array.sort((a,b)=>b-a);
```

### Reverse Arrays with reverse
```js
newArray=array.reverse();
```

### Concatenate Arrays with concat
```js
newArray=oldArray.concat(concatMe);
```

### Split Strings with split
```js
array=string.split(' ');
```

### Join Strings with join
```js
joinedString=joinMe.join(' ');
```