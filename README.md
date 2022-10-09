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
let hungerLevel = 7;
if (hungerLevel >= 7) {
  console.log("Time to eat");
} else {
  console.log("Time to wait");
}
```

  </details>
  <!-- End of Geater than or Equal to -->
  <!-- Is Equal to -->
  <details>
      <summary>5) Is equal to</summary>

`===`

```javascript
let hungerLevel = 7;
if (hungerLevel === 7) {
  console.log("Time to eat");
} else {
  console.log("Time to wait");
}
```

  </details>
  <!-- End of Is Equal to -->
  <!-- Is NOT Equal to -->
  <details>
      <summary>6) Is NOT equal to</summary>

`!==`

```javascript
let hungerLevel = 7;
if (hungerLevel !== 7) {
  console.log("Time to eat");
} else {
  console.log("Time to wait");
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
if (stopLight === "green" && pedestrians === 0) {
  console.log("Go!");
} else {
  console.log("Stop");
}
```

```javascript
let stopLight = "red";
let pedestrians = 0;
if (stopLight === "green" && pedestrians === 0) {
  console.log("Go!");
} else {
  console.log("Stop");
}
```

```javascript
let mood = "sleepy";
let triednessLevel = 5;
if (mood === "sleepy" && triednessLevel === 8) {
  console.log("Time to Sleep");
} else {
  console.log("Not bed time yet");
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
if (stopLight === "green" && pedestrians === 0) {
  console.log("Go!");
} else {
  console.log("Stop");
}
```

```javascript
let stopLight = "red";
let pedestrians = 0;
if (stopLight === "green" && pedestrians === 0) {
  console.log("Go!");
} else {
  console.log("Stop");
}
```

```javascript
let stopLight = "red";
let pedestrians = 1;
if (stopLight === "green" && pedestrians === 0) {
  console.log("Go!");
} else {
  console.log("Stop");
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
if (!excited) {
  console.log("I am excited");
} else {
  console.log("I am not excited");
}
```

```javascript
let mood = "sleepy";
let triednessLevel = 5;
if (!(mood === "sleepy" && triednessLevel === 8)) {
  console.log("Time to Sleep");
} else {
  console.log("Not bed time yet");
}
```

  </details>
  <!-- End of NOT Operator -->
</details>
  <!-- End of Comparison Operators -->
  <!-- Truthy and Falsy -->
<details>
  <summary>Truthy and Falsy</summary><br>

- when let `string`

```javascript
let myValue = "value";
if (myValue) {
  console.log(myValue);
} else {
  console.log("The variable is not initialize");
}
```

- when let `Number` ` 0`

```javascript
let myValue = 0;
if (myValue) {
  console.log(myValue);
} else {
  console.log("The variable is not initialize");
}
```

- when let `Empty String` `''`

```javascript
let myValue = "";
if (myValue) {
  console.log(myValue);
} else {
  console.log("The variable is not initialize");
}
```

- when let `Number` `1`

```javascript
let myValue = 1;
if (myValue) {
  console.log(myValue);
} else {
  console.log("The variable is not initialize");
}
```

- when let `null`

```javascript
let myValue = null;
if (myValue) {
  console.log(myValue);
} else {
  console.log("The variable is not initialize");
}
```

```javascript
let username = "Bod";
let defaultName;
if (username) {
  defaultName = username;
} else {
  defaultName = "Strange";
}
console.log(defaultName);
```

```javascript
let username;
let defaultName;
if (username) {
  defaultName = username;
} else {
  defaultName = "Strange";
}
console.log(defaultName);
```

- `short-circuit evaluation`

```javascript
let username;
let defaultName = username || "Stringer";
console.log(defaultName);
```

```javascript
let username = "Bod";
let defaultName = username || "Stringer";
console.log(defaultName);
```

### Exercise:

```javascript
let tool;
let writingTool = tool || "Pen";
console.log(`The is ${writingTool} mightier than the sword`);
```

```javascript
let tool = "Marker";
let writingTool = tool || "Pen";
console.log(`The is ${writingTool} mightier than the sword`);
```

</details>
<!-- End of Truthy an Falsy -->
<!-- Ternary Operator -->
<details>
  <summary>Ternary Operator</summary>

- `If...Else Statement Operator `

```javascript
let isNightTime = true;
  isNightTime?console.log('Turn on the lights!');
  :console.log('Turn off the lights!');
```

### To Converted `Tarnary` Operator

- when let `true`

```javascript
let isNightTime = true;
  isNightTime?console.log('Turn on the lights!');
  :console.log('Turn off the lights!');
```

- when let `false`

```javascript
let isNightTime = false;
  isNightTime?console.log('Turn on the lights!');
  :console.log('Turn off the lights!');
```

### Exercise:

- `If...Else Statement Operator `

```javascript
let temp = 40;
if (temp < 35) {
  console.log("It is hot");
} else {
  console.log("it is OK");
}
```

#### To Converted `Tarnary` Operator

```javascript
temp < 35 ? console.log("It is hot") : console.log("It is OK");
```

</details>
<!-- End of Tarnary Operator -->
<!-- Else If Statment -->
<details>
  <summary>Else If</summary>

```javascript
let stopLight = "yellow";
if (stopLight === "red") {
  console.log("Stop!");
} else if (stopLight === "yellow") {
  console.log("slow down!");
} else if (stopLight === "green") {
  console.log("Go!");
} else {
  console.log("Caution, unlock");
}
```

</details>
<!-- The switch keyword -->
<details>
  <summary>The switch keyword</summary>

```javascript
let groceryItem = "Alo";

switch (groceryItem) {
  case "Tomato":
    console.log("Tomatos are $0.49");
    break;
  case "Alo":
    console.log("Alos are $2.35");
    break;
  case "Potato Chipe":
    console.log("Potatos are $0.40");
    break;
  default:
    console.log("Invalid item");
    break;
}
```

</details>
<!-- End of The switch keyword -->
