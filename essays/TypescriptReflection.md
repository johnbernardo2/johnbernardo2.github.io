---
layout: essay
type: essay
title: "My View on Typescript as a New Programmer"
# All dates must be YYYY-MM-DD format!
date: 2024-09-04
published: true
labels:
  - Typescript
---

As I am writing this essay, I can say that I do not have a full opinion on typescript just yet. I have learned javascript just recently and a bit of typescript right after. But what I’ve done so far has seemed enjoyable to me, learning through w3schools.com basic typescript and javascript through freecodecamp.org. I didn’t feel as if I were jumping over hurdles because of my background in java. And I do believe my background in java is still beginner-level, relatively.

I did enjoy seeing a change in syntax, one being about variables.
In java, when you declare a string or number, you use the type first, the name of the variable, and then set it equal to what it is.

Example:
String location = “Honolulu”;
int zipCode = 96822;

Pretty basic, but only because that’s the first language I’ve learned.
In javascript, it’s even simpler where no type is needed, you can just use “let” for both in place of the types in Java.

However, in typescript, you use a colon after the name of the variable and set the type for it equal to its literal, whilst using let or another declaration (eg const, var).

Example:
let location: string = “Honolulu”;
let zipCode: number = 96822;

It is a small change, but it is new to me.

Another thing I found interesting was typescripts implementation of IntelliSense. I’m assuming even in a better environment for javascript, typescript’s use in IntelliSense is more robust. It’s interesting to me because I am used to using an IDE and or code editor with IDE-like features. And for that to be an important note when learning typescript’s background impresses me. Like Java in Mac’s terminal and Vim, there is no IntelliSense or any suggestion-like features for it.

The practice WODs so far are fine to me. I did have to use extra resources for both, but when I understood the code, redoing them became easy and I finished in Rx times for both. This will be a vague explanation for both. First WOD is a Euler problem that asks for all the natural numbers under 1000, that are divisible by 3 or by 5, then the sum of all those numbers

My thought process goes:

Okay, so we need a for loop that goes all the way to 1000, check.

And we already know how to use remainers with %, check.

So we set it up like this:
 i % 3 === 0 || i % 5 === 0
//check

Then finally we need to add those values to the sum until 1000.

Done.

Here is the completed WOD.

function projectEulerOne (): number {
    let sum = 0;
    for (let i = 1; i <1000; i++) {
        if (i % 3 === 0 || i % 5 === 0) {
            sum+= i;
            }
            
        }
        return sum;
    }

I think my programming background must strengthen before I start doing more WODs. But so far I believe athletic software engineering or WODs are good at challenging your thinking.
