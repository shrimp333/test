# Starting whatever this is

I watched a video on youtube and it suggested starting a blog could be helpful towards learning. So I've decided that i will be documenting things that I learn for myself (Tips, Tricks, Assignments, etc.) while not quite going into an actual blog; or this might be exactly what a blog is, I'm not too sure tbh.

## Contents
- [How I got here](#how-i-got-here)
- [What we've done](#what-weve-done-so-far)
    - [C#](#c)
    - [HTML CSS](#html-css)
    - [SQL Databases](#sql-databases)

## How I got here

During VCE I studied IT and Software Development, did okay score wise due to unwillingness towards learning when I was that age but I really enjoyed the programming aspect of the units. After high school I went and did a Diploma in Business with the initial intention to continue on the next year into the degree course. However, after failing and repeating one of the subjects in that course I came to the realisation that I hated business and started wondering why on earth I had chosen to go and study it. After getting my diploma I immediatly, just as I turned 20, joined a cert 4 TAFE course in IT - Programming. So far, 6 weeks in, I have been really enjoying it. We are currently learning C#, HTML, CSS, SQL and how to analyise and design systems and other important software development skills.

## What we've done so far

### C#
When it comes to C# we have essentially gone over almost everything I learnt during VCE. Although this time in C# this time instead of Visual Basic, which has been quite easy as VB and C# are extremely similar languages.

We have gone over:
- Basic Variables, declarations, assigning, datatypes
- Selection, if statements
- Repetition, While loops, For loops
- Arrays and Lists
- Functions

We've had a single assignment so far for this class which has been to create a console app that asks a user to input a number and it will generate a number between 1-6 that many times, essentially creating a program that rolls dice.
```c#

Console.WriteLine("How many Dice would you like to roll?");
numOf = int.Parse(Console.ReadLine());
//inputs how many dice user wants to role and parses it to an integer
Console.WriteLine("Dice Rolled were:");
for (int i = 0; i < numOf; i++)
{
    result = dice.Next(1,6);
    Console.WriteLine(result);
}
//for each of the dice wanted to roll generates a random number between 1 and 6 and prints it
Console.WriteLine("Would you like to roll again? (yes/no)");
if (Console.ReadLine() == "no")
{
    break;
}
//if the user does not want to roll again breaks the loop ending the program, if not loops back to the start.

```

With the output of the code being

![Code output image](./assets/output.png)

### HTML, CSS

Before this course I had hardly ever touched any web development but it's been going well. So far all we've been given is images of web pages that we must recreate using HTML and CSS, we can use javascript and frameworks however. He suggested that we look into bootstrap as it would help but I haven't touched it yet. I've also been reading online and watching some videos that have been saying that learning css fundamentals before using a framework is a good idea as if you have learnt a framework without fundamentals and choose to switch to another framework it will take twice the time to learn the new framework. I have also read that you should just immediatly go into using a framework but I am unsure so I'm just sticking to vanilla css for now.

Our first assignment was extremely easy to do as we only had to create a simple webpage with some minimal styling and dummy text

<img src="./assets/WebProg_Challenge1.png" alt="drawing" width="750"/>

### SQL Databases