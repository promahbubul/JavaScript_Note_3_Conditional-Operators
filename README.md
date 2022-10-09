# JavaScript Conditional Operators

<details>
<summary>If Statements</summary>

```javascript
if (true) {
  console.log("It will be printed");
}
```

```javascript
if (false) {
  console.log("It will be printed");
}
```

```javascript
let sale = true;
if (sale) {
  console.log("Time to  buy");
}
```

```javascript
let sale = true;
sale = false;
if (sale) {
  console.log("Time to  buy");
}
```

</details>
<details>
<summary>If...Else Statements</summary>

```javascript
if (false) {
  console.log("This code with no run");
} else {
  console.log("This code will run");
}
```

```javascript
if (true) {
  console.log("This code with no run");
} else {
  console.log("This code will run");
}
```

```javascript
let sale = true;
sale = false;
if (sale) {
  console.log("Time to buy");
} else {
  console.log("Time to wait");
}
```

</details>

<!-- Comparision Operators -->
<details>
  <summary>Comparison Operators</summary>

  <!-- Less than -->
  <details>
      <summary>1) Less than</summary>

`<`

```javascript
let hungerLevel = 7;
if (hungerLevel < 7) {
  console.log("Time to eat");
} else {
  console.log("Time to wait");
}
```

  </details>
  <!-- End of Less than -->
  <!-- Geater than -->
  <details>
      <summary>2) Geater than</summary>

`>`

```javascript
let hungerLevel = 7;
if (hungerLevel > 7) {
  console.log("Time to eat");
} else {
  console.log("Time to wait");
}
```

  </details>
  <!-- End of Geater than -->
  <!-- Less than or Equal to -->
  <details>
      <summary>3) Less than or equal to</summary>

`<=`

```javascript
let hungerLevel = 7;
if (hungerLevel <= 7) {
  console.log("Time to eat");
} else {
  console.log("Time to wait");
}
```
  </details>
  <!-- End of Less than or Equal to -->
  <!-- Geater than or Equal to -->
  <details>
      <summary>4) Geater than or equal to</summary>

`>=`

```javascript
let hungerLevel = 7
  if(hungerLevel >= 7)  {
  console.log("Time to eat");
  } else {
    console.log("Time to wait")
  }
```
  </details>
  <!-- End of Geater than or Equal to -->
  <!-- Is Equal to -->
  <details>
      <summary>5) Is equal to</summary>

`===`
```javascript
let hungerLevel = 7
  if(hungerLevel === 7)  {
    console.log("Time to eat");
  } else {
    console.log("Time to wait")
  }
```

  </details>
  <!-- End of Is Equal to -->
  <!-- Is NOT Equal to -->
  <details>
      <summary>6) Is NOT equal to</summary>

`!==`
```javascript
let hungerLevel = 7
  if(hungerLevel !== 7)  {
    console.log("Time to eat");
  } else {
    console.log("Time to wait")
  }
```

  </details>
  <!-- End of Is NOT Equal to -->
</details>
 <!--End of Comparison Operators  -->

<!-- Logical Operators -->
<details>
      <summary>Logical Operators</summary>

 **There are `3` Logical Operators.**

`AND` `&&`<br>
`OR` `||`<br>
`NOT` `!`

  <!-- AND Operator -->
  <details>
    <summary>1) AND Operator</summary>

`&&`
```javascript
let stopLight = "green";
let pedestrians = 0;
  if(stopLight === 'green' && pedestrians === 0) {
    console.log('Go!')
  } else {
    console.log('Stop');
  }
```
```javascript
let stopLight = "red";
let pedestrians = 0;
  if(stopLight === 'green' && pedestrians === 0) {
    console.log('Go!')
  } else {
    console.log('Stop');
  }
```
```javascript
let mood = 'sleepy';
let triednessLevel = 5;
  if(mood === 'sleepy' && triednessLevel === 8) {
    console.log('Time to Sleep');
  } else {
    console.log('Not bed time yet');
  }
```
  </details>
  <!-- End of And Operator -->
  <!-- OR Operator -->
  <details>
    <summary>2) OR Operator</summary>

`||`
```javascript
let stopLight = "green";
let pedestrians = 0;
  if(stopLight === 'green' && pedestrians === 0) {
    console.log('Go!')
  } else {
    console.log('Stop');
  }
```
```javascript
let stopLight = "red";
let pedestrians = 0;
  if(stopLight === 'green' && pedestrians === 0) {
    console.log('Go!')
  } else {
    console.log('Stop');
  }
```
```javascript
let stopLight = "red";
let pedestrians = 1;
  if(stopLight === 'green' && pedestrians === 0) {
    console.log('Go!')
  } else {
    console.log('Stop');
  }
```
  </details>
  <!-- End of OR Operator -->
  <!-- NOT Operator -->
  <details>
    <summary>3) NOT Operator</summary>

`!`
```javascript
let excited = true;
  if(!excited) {
    console.log("I am excited");
  } else {
    console.log("I am not excited");
  }
```
```javascript
let mood = 'sleepy';
let triednessLevel = 5;
  if(!(mood === 'sleepy' && triednessLevel === 8)) {
    console.log('Time to Sleep');
  } else {
    console.log('Not bed time yet');
  }
```
  </details>
  <!-- End of NOT Operator -->
</details>
  <!-- End of Comparison Operators -->

      
      

      
    
  
      

      








