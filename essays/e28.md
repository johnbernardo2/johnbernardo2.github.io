---
layout: essay
type: essay
title: "My thoughts on ESLint"
# All dates must be YYYY-MM-DD format!
date: 2016-02-06
published: true
labels:
  - Engineering
---


## Introduction - What is ESLint?

ESLint is a linting extension for javascript and typescript. In a way, it’s a coding correctional tool. The way it works is that you’ll first have to configure and implement certain files, then invoke “npm install” into the terminal to install it.  Assuming you make errors in your code, ESlint will provide you corrections on said code. Similar to intellisense, but not exactly. It is to improve the quality of your code up to the coding standards.


## Initial thoughts on ESLint

Personally I liked ESLint, especially in the first optional assignment when we were already given a code to correct. Not that I hate creating my own code, but it was a laid back experience for the corrections to already be there. Kind of like buying a lego set and using the instructions. Working piece by piece in correcting the code. I do believe it is useful or at least a starting point for those who are learning javascript or typescript. It’s not exactly like intellisense because ESLints focus is on quality, style, and practices for standards.


## Conclusion - Current thoughts on ESLint

While I do like ESLint, it’s not something I’ll give someone a 10/10 reccomendation as I am still new to javascript and typescript relatively. As I am mostly neutral in topics I am not proficient in. The inital five files implementation is pretty simplistic. But I’m not sure if I would want to keep having to rename and download the files differently. Unless, you can just copy it the first time, then keep copying it when you need to use it. Then I am wrong.

This is what I mean:

```
sample.eslintrc.js, rename it to .eslintrc.js.  //Right click, rename, find file
sample.eslintignore, rename it to .eslintignore. //auto downloaded when clicked, but have to rename in VSCode
sample.gitignore, rename it to .gitignore.  //auto downloaded when clicked, but have to rename in VSCode
sample.package.json, rename it to package.json.  //Right click, rename, find file
sample.tsconfig.json, rename it to tsconfig.json.  //Right click, rename, find file
```
It could possibly be a hassle to someone.

Another problem I could see is that if the code is too large and you are doing manual corrections. It’s possible that a certain style, like Airbnb Typescript Style, could be too strict on the code, extending the time for completion.

Overall, ESlint is fine to use. But if there is some other popular standard outthere, eg eslint with prettier, I will reccomend that.

