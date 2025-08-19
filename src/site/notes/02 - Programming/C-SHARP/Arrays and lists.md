---
{"dg-publish":true,"permalink":"/02-programming/c-sharp/arrays-and-lists/"}
---

# Arrays
Arrays are used to store multiple values of the same [[02 - Programming/C-SHARP/Variables\|type]].

The positions in the array are fixed and marked by numbers, starting from 0.

```cpp
// the simplest way to make an array
int[] numberArray = {56, 123, 12};

// the most explicit way to make an array
int[] numberArray = new int[] {56, 123, 12};

// a method to create an empty array
int[] numberArray = new int[5]; // 5 = number of elements
```
Before running, we need to actually initialise the array by giving it a size or some content.

## Checking the size
```cpp
int[] numberArray = new int[5];

// this will print out “5”
Console.WriteLine(numberArray.Length);
```
## Reading the contents
To read the content of an array, we call the array and in the brackets we put the position of the number we want to grab.
```cpp
int[] numberArray = new int[] {22, 52, 524, 7, 87};

// this will print out “22”
Console.WriteLine(numberArray[0]);
```

We can also find the index of a number in an array using this function:
```cpp
int[] numberArray = new int[] {481, 73, 87}

// this will print out “1”
Console.WriteLine(System.Array.IndexOf(numberArray, 73));
```

# Lists
Lists are similar to arrays, but have some more helpful features, such as adding or removing elements.

```cpp
// we CANNOT initialise a list like this
List<int> numbersList = {52, 23, 757};

// this is the most xplicit option
List<int> numbersList = new List<int> {52, 23, 757};

// this is an empty initialisation of a list
List<int> numbersList = new List<int>();
```

## Checking the size
```cpp
List<int> numbersList = new List<int>();

Console.WriteLine(numbersList.Count);
```
## Reading the contents
```cpp
List<int> numbersList = new List<int>(12, 45);

// this will print out “12”
Console.WriteLine(numbersList[0]);
```
## Adding and removing elements
```cpp
List<int> numbersList = new List<int>();

// this will add the number 12 to the list
numbersList.Add(12);

// this will remove the number 12 from the list
numbersList.Remove(12);

// this will add the number 12 at the position 3
numbersList.Insert(12, 3);

// this will remove the number at the position 1
numbersList.RemoveAt(1);
```

## Checking for content
We can check if a list contains a certain number using this function:
```cpp
List<int> numbersList = new List<int>(13, 134, 83);

// this will print out true
Console.WriteLine(numbersList.Contains(134));
```

We can get the index from the list of a particular number using this method:
```cpp
List<int> numbersArray = new List<int>(35, 183, 46);

// this will print out “2”
Console.WriteLine(numbersList.IndexOf(46));
```