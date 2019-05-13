# Coding challenge 

The coding challenge is divided in 3 parts.
* 2 Javascript algorithm exercises.
* 1 React exercise.

Please upload your code on your git platform (github, bitbucket, etc) in a repository.
Create one folder per exercise.

After you've finished, you can share the repository URL with your contact (prefered) or, if you made it on a private repository, just send a .zip containing the source code.

## Javascript Exercise 1 : The Warm Up

https://www.hackerrank.com/challenges/maximum-element/problem

## Javascript Exercise 2 : The Thor Challenge

Let A be an array with n integers (positive and negative). 
Let m be an integer.

What is the maximum sum value, modulo m, out of each consecutive sub-array ?

Example :

```
A = [ 1, 2, -3 ]
m = 2

The possible consecutive sub-array are :
[1], [2], [-3], [1, 2], [2, -3], [1, 2, -3]
Attention : [1, -3] is not a consecutive sub-array

The sum of each number inside each subarray is : 1, 2, -3, 3, -1, 0

So if we apply modulo 2 for each sum : 1, 0, -1, 1, -1, 0
Therefore, the maximum sum value modulo 2 out of each consecutive sub-array is 1.
```

## React Challenge : The TO-DO List

For this challenge, you are supposed to build a complete **to-do list**, persisted on user's machine.
Complementary libraries are permited provided that we are able to check how you code using React (and optionally Redux). To speed up your development, you are allowed to bootstrap or grab simple components from existing libraries of your choice (ex: Material-UI). Also, please use create-react-app to give you a functional dev/build environment.

You are free to design it the way you want. Don't invest too much on a beautiful visual because in real life you will use and contribute to an existing library of shared components.

You will have to be able to explain your final solution in detail. 

### Requirements 
* Assign priority on a TO-DO item and provide possibility to sort them by priority.
* Set a due time. Set a visual indicator stating if the time is near or has passed.
* Your solution has to work on latest Chrome version.

### Optional

According to the time you have left, you could add some extra features. Please note that this list is completely optional, we can 100% base our assessment on the requirements above. However if you decide to add a feature, we will take into account that adding an extra feature increases the complexity of the challenge.

Suggered features :
* Optimistic updates.
* Authentication.
* Unit and/or E2E tests.
* Firebase integration, link Firebase Realtime Database to your frontend store.
* Anything else that comes to your mind.

For this challenge, please include a README explaining how to run your solution (and potentially which feature(s) you decided to add).

## Review Criteria 

We pay special attention to :
* Coding skills : Readability, clean code, maintability, efficiency...  threat this project as if another team would continue working on it after your assignment.
* Architecture skills : Code organization, modularity, namings, interaction between components and containers.
* Best practices.

If we like what we see, we'll invite you to present and explain your solution :)

Happy Coding !

![alt text](https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif)
