# Tutorial

## Arrays
Arrays are essentially storage spaces that can be filled with as much data as one would like. Variables, unlike arrays, can only contain one piece of data. Now there are some caveats. For instance, an array is syntactically created using one data type, just like variables. Yet, an array grants ease of access and far more capabilities when considering large/vast amounts of data compared to a variable(single storage space/value). 

## Examples
```golang
// An array named favNums filled with 3 integers
var favNums[3] int

// Insert data into the array
// The first storage space will be assigned the value of 1.
favNums[0] = 1
// The second storage space will be assigned the value of 2.
favNums[1] = 2
// The third and final storage space will be assigned the value of 3.
favNums[2] = 3

```
An alternative syntax to the creation of arrays in golang is:
```golang
varFavNums := [4] int
// Insert data into the array
// The first storage space will be assigned the value of 50.
favNums[0] = 50
// The second storage space will be assigned the value of 900.
favNums[1] = 900
// The third and final storage space will be assigned the value of 150.
favNums[2] = 150
// The fourth and final storage space will be assigned the value of 150.
favNums[3] = 150

```
In order to access members of an array, reference the storage space's address or number you used to create it. 
```golang
  fmt.Println(favNums[0])
```
## Exercise
Create two arrays, one a string array, the other a int array.
Assign the string array three storage spaces which contain any three strings you would like to insert. 
Assign the int array three storage spaces which contain the values 1, 2, and 3.
Finally, print the last items of each array.

## Tutorial Code
```golang
package main

import "fmt"

func main() {
  var strings(3) string
  var numbers(3) int
  
  strings[0] = "Hello world!"
  strings[1] = "Hello world!"
  strings[2] = "Hello world!"
  
  numbers[0] = 1
  numbers[1] = 2
  numbers[2] = 3
  
  
}
```
## Solution
