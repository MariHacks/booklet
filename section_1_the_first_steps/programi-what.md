# Programi-What?

## Programming <a id="programming"></a>

> **Programming:** provide \(a computer or other machine\) with coded instructions for the automatic performance of a particular task.

Seems simple enough yet programming is incredibly important and most importantly ~~nerds~~ everyone agree that it is cool. Coding can be separated into a couple categories and languages – our booklet covers the main ones.

To code, you will use a coding language – not english, but something that the computer will understand. In this language, you will tell the computer exactly what you want it to do, and unlike a dog, the computer will always listen. Want to make a program that plays “Never Gonna Give You Up” by Rick Astley at random times throughout the day? Terrible taste but you can definitely do it!

## Algorithms

Moving on from memed songs, let’s learn about algorithms. An algorithm is a function that is effective for a specific goal. You can think of an algorithm as a function that takes some input, and processes that input to produce some sort of output.

Let’s say you wanted to guess my favourite number. I don’t know of any function in programming called `FavNum()` so we’ll have to write our own algorithm to solve it. For simplicity sake, let’s assume my number is between 0 and 100. And since I am a busy person, we want to minimize the number of questions that I have to answer.

One way to get my number, is to simply go through all the numbers from 0 to 100 and ask me if that’s my number. Unfortunately, I don’t have all day, and let’s just say I would not be very happy if you had to ask me all those questions.

What you might want to do instead is ask me if my number is bigger than or smaller than 50 \(i.e. the halfway point\). If I answer that it is bigger, then we’re down to numbers 51-100, and if I answer that it is smaller, then we’re down to 0-49. Either way, we cut the eligible amount of numbers in half! Now, we simply have to ask me once again if my number is bigger or smaller than the midpoint of the range and after a couple iterations, we will find out my favourite number! Or you could have simply asked me for my favourite number… it’s 73! This is an example of how a function can use a more _efficient_ algorithm.

The algorithm of repeatedly cutting a list of numbers in half to find a value is called binary search. There are many other cool ones that you can learn about [here](https://www.khanacademy.org/computing/computer-science/algorithms). Algorithms are useful for solving a wide range of problems. A good grasp of algorithms can come in handy if you run into an interesting problem, but is not necessary if you're just starting off.

