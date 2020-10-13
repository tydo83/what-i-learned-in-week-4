# What I Learned In Week 4

## **Else if in for-loop**

```
function meeting(x){
    for(let i = 0; i < x.length; i++) {
        if(x[i] == 'O') {
            return true;
        }  
        else {
            return false;
        } 
    }    
    return 'None available!';
}
```
This loop doesn't work properly. 

```
function meeting(x){
    for(let i = 0; i < x.length; i++) {
        if(x[i] == 'O') 
            return true;  
    }    
    return 'None available!';
}
```
This loop works correctly. 

---

## **Code Refactoring** 
It is the process of clarifying and simplifying the design of existing code, without changing its behavior.
```
num = num + 1  ==  num +=1  ==  num++
```

---

## **Node command**
> youtube-dl url
* youtube-dl is a command-line program that lets you easily download videos and audio from more than a thousand websites.
> nodemon main.js
* nodemon is a tool that helps develop node. js based applications by automatically restarting the node application when file changes in the directory are detected.

---

## **array method**
> array.push()
* adds new items to the end of an array. 
> array.pop()
* removes the last element from the array.
> array.shift()
* removes the first element from the array.
> array.unshift()
* adds new items to the first of an array. 
> array.slice 
* returns a shallow copy of a portion of an array into a new array object selected from start to end(not included). The original array will not be modified. 
> array.splice (n, m, c) 
*  changes an existing array by removing, adding and/or replacing specified elements from it. The method mutates the array.
> array.reverse
* transposes the elements of the calling array object in place, mutating the array, and returning a reference to the array.
> array.concat
* combine two arrays. 
---
## **Trailing comma**
Trailing commas(sometimes called "final commas") can be useful when adding new elements, parameters, or properties to JavaScript code.

---
## **mapping**
1. Always produce a new array.
2. Has the same number of elements. 
3. Each element has been changed in the same way.

### why mapping is important ?
Since, in programming, you would not want to change the original data. 

### examples of mapping
* different ui elements of a list or posts
* truncated list
* add bonuses
* add or remove last name




