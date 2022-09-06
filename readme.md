# ⚡ Java Script history and basics ⚡

## 🟡 Javascript History

1. JS first name was Mocha (coffee)
2. It was introduced by Netscape Browser.
3. Since, microsoft introduced Internet Explorer with it's own script and different for Netscape so it was difficulty for developers.
4. To Solve this issue, ECMA came.
5. ES6 is different types of versions introduced by ECMA.

## 🟡 Basics

<br>

### 🟠 Data Types

<br>

#### 🔴 Primitve Data Type (Single value)

<br>

1. Number: 7,1.616, 45.22
2. String: Any Characters kept inside double or single quote are called as String. Ex: "shobham" , "2" , "1.235","45%"
3. Boolean: By John Boole Ex: 0 and 1
4. Empty Values: null, undefined

<br>

#### 🔴 Non Primitive Data Type (Multiple values also called Objects)

<br>

1. Array: Collection of values written inside [] and seprated by ',' which can be of same or different data type. Ex: [1,2,3,4,5] , ["Ram","Shyam","Shobham"], [[1,2,3],["Ram","Shyam"] Array Index: Position of elements inside Array is called by Index Ex: [1,2,3,4,"Ram"] Here position of "Ram" is index 4\. Index starts from 0.

  **Note**: Syntax: Set of instructions used to run the program of js.

2. Object: Elements inside {} and in the form of key-value pairs are called Objects.

  Ex: {abc:"LCO"}

<br>
<br>

### 🟠 Variables

Variables are the container that holds the value which might be a number, string, boolean, or anything. Variables are important because, without them, our tasks will be tedious. We have to use our given input again and again to perform the task.

Let's create a variable.

> Step:1 Declaration We will use the let keyword to declare the variable.

```
let yourName;
let yourAge;
```

Currently, they don't have values, they are empty containers. Let's store the value inside them.

> Step:2 Initialize After declaring the variable name, initialize it to give some value.

```
yourName= "Rohan";
yourAge=25;
```

We can declare and initialize the variables together like this.

```
let myName= "Prateek";
let myAge= 25;
```

#### Different ways to declare the variables

> Using var keyword

```
var userName= "Sam";
```

When js came into picture then this keyword was mostly used but due to its confusing nature, let and const came into picture.

> Using let keyword

```
let userAge= 56;
```

You can't redeclare the variable again once declared by let. Try in your console.

```
let userAge= 89;
let userAge= 25;
// Throws error
```

And this is good thing for throwing error to avoid confusion, but in var you can declare as much as you can. That's why always use let and const.

With let, you can update your variable.

```
userAge= 54;
```

Their is also a naming convention to declare the variables. I will suggest you to read [naming convention article](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Variables).

> Using const keyword As per the name, it is used when to want to make something constant.

```
const user; // error
const user= 25; // correct
```

You can not declare and initialize using const seprately, it needs to be done together.

#### Variables Types

1. Numbers You can store intergers, decimals , floating and doubles inside variables.

```
let num1= 25;
let num2= 2.53;
```

2. Strings

Any thing inside double or single quote is called string.

```
let yourName= "Pratyush";
let youAge= "25";
```

3. Boolean It returns true or false.

  ```
  let isNum= 5>2;
  console.log(isNum); // true
  ```

**Note:** To print your variables in console, you can use this sytax in editor. console.log(your variable name);

4. Arrays Arrays in js are the container which stores multiple elements with same or different data type inside [] and these elements are seprated by comma.

  ```
  let array1= [1,2,3,4,5];
  ```

  To access the elements, we use array index which starts from 0.

  ```
  console.log(array1[0]); // 1
  ```

5. Objects

  ```
  let person = {
  name:"Prateek",
  age:25
  }
  ```
