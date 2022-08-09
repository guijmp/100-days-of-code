# 100 Days Of Code - Log

## Day 0: June 3, 2022

**Today's Progress:** Preparing for the 100 days challenge:
    - Learned some hotkeys in VS Code
    - Started the VIM tutorial and did it until lesson 3.3
    - Created a Twitter and Instagram account.

**Thoughts:**

I do not have a CS degree, so there is a lot of background knowledge that I lack. However, I am excited to be starting this challenge.

## Day 1: June 4, 2022

**Progress:** Started debugging the calculator program

**Thoughts:** I took way too much time to refresh my memory on what the program is doing and figuring out the cause of some errors. Of course this is all explained in the book but I am trying to follow along with as little help as possible.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/c75c1f671ad221d9fdb425ef1e4e1891554b4e3f)


## Day 2: June 4, 2022

**Progress:** Cleaned up the code and restructured, started introducing feature of keep calculator running even after an error is displayed.

**Thoughts:** I kept checking the book to make sure I got the exercise right. Following along by coding definitely makes me understand the issues that he raises along the way. I am feeling good about my progress, today's lesson: When whithin handling error exception, check for functions that could raise another error, becasue this would be caught by any external error handler.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/2243f161e9ead92d7cc938128f88a9aa497d3c3c))


## Day 3: June 5, 2022

**Progress:** Finalized treatment of errors in multiple statements. Now calculator does not close when an error is found, it refreshes its state to receive next input. Found out a strange behaviour when multiple operators are used eg. 1+++2;

**Thoughts:** I was quite concentrated today, but I got stuck because I didn't realize that I was compiling to a file with a slighlty different name, so I was running the same file over and over again and wondering why my changes were not working haha.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/3c86931391e135a087e6c81340f88e74f72ada11))


## Day 4: June 6, 2022

**Progress:** Started implementation of a new feature to the calculator: user defined variables.

**Thoughts:** The use of Tokens to allow for a stram with different types was very enlightning. I managed to spend some time reading and going through the book implementation but also started implementing it by myself without checking the book. I am happy with today's progress.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/compare/main...FeatureWork))


## Day 5: June 8, 2022

**Progress:** Finished writing changes to introduce the new feature, but now compiler is having trouble with the constructors that I used.

**Thoughts:** Today I did not check the Book, so I am cureious to see how I fared once I deal with the compilation errors. I am happy with today's progress

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/98a3c880da1be5dc60e84d85836969f106e801c2)


## Day 6: June 9, 2022

**Progress:** Setting variables inside main function seems to be working but user defined variables needs debugging.

**Thoughts:** I was a bit tired today so I wasn't very productive. Git bash stoped running excutable file so got stuck with that for a while.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/6680d0647392b9dfe4ef909019ac5463bf291429)


## Day 7: June 10, 2022

**Progress:** Put some cout statements in critical parts to try to debugg the code.

**Thoughts:** I was not paying a lot of attention today and I haven't managed to figure out why the code is not working. On the other hand, the current behaviour is very strange so I am really curious as to what is happening.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/d1db3c1b56c6427919a8d13d7c435064e2a93772)


## Day 8: June 11, 2022

**Progress:** Found out reason for odd behaviour was just good functioning of the program. It seems to be working now, but needs further testing

**Thoughts:** I was getting confuseed because I wasn't mentally following the program from the beggining. Pro tip: when in doubt, start from the beggining!

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/d539534d76e29aa4b2b406b75262baa67c3f06c2)


## Day 9: June 12, 2022

**Progress:** Removed unecessary cout statements. Tested calculator with weird inputs. Implemented a function for the sqrt.

**Thoughts:** Although today was a crazy day (coming back from a camping trip!) I am very happy that I sat down and still managed to be productive with the code today.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/7c669987f0e742506a95812e4407cabe504c86d1)


## Day 10: June 13, 2022

**Progress:** Implemented function for power, modified quit and let keyworkds.

**Thoughts:** Today was also good progress, but I am getting a bit tired of this calculator project, as it is dragging for a bit. Luckily, only a few last modifications are sugested at the end of chpt. 7 so hopefully I will be done with this calculator in one week.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/7443941ed3c8dec19e2d54bda798aa10e1ec4305)


## Day 11: June 14, 2022

**Progress:** Variable names can now contain underscores, started adding assignment feature to change values of stored variables.

**Thoughts:** Today was good progress, I was very focused and the hour went by quickly. I think I am very close to getting the assignment of variables right, so it should be straight forward to do that tomorrow.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/54e8c558233f42fec836f58ae30af6922029bf65)


## Day 12: June 15, 2022

**Progress:** Understood a key part of why assignment was not working. This was due to using range based for loops without reference. Fixed it and now assignment is working. Started introducing constant variables.

**Thoughts:** Today was very productive, I learnt the difference between using for loops with and without reference. 

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/12083f54912865361fae51afda820c7582f092c7)


## Day 13: June 16, 2022

**Progress:** Introduced small improvements in the code, making it more consistent (fron cin >> ch; to cin.get(ch);)

**Thoughts:** Started with 0 motivation to code, ended up coding more than 1h, although still quite irritable today. Overall was still an Okay progress.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/cff6870f2ef11c2ffe51b4afe848e5187e833d0e)


## Day 14: June 17, 2022

**Progress:** Introduced comment that explains Grammar, realized that pow and sqrt functions were at the wrong level of Grammar. COrrected it. Changed layout of code for better readability

**Thoughts:** Got stuck trying to figure out a way of taking assignment operation outside Primary level of Grammar. Main issue is that token stream cannot store two Tokens at a time so reading 2 Tokens in advance is not available. Decided to stick to current Grammar, because it is indeed working as intended. I think it will be best to mode Definition under the Primary level as well, to keep consistency.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/cf2e3d88d2738f8de15c06c7f0bf5cbee9decc47)


## Day 15: June 17, 2022

**Progress:** Put definititions of variables at the Primary level. Need to do final change to make calculator accept only ints

**Thoughts:** Todya was okay, nothing special. My progress is very slow, as in two weeks I got over one chapter of the book.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/99365a5548e42367e17d0a5c4d2df3b932b92fa5)


## Day 16: June 17, 2022

**Progress:** Today I finally moved on to chapter 8. Read about half of it, and it was very enlightning in explaining the different ways of passing arguments in functions

**Thoughts:** I did not code today, I just read the book, so I guess that is against the rules. However, I do think I am actually learning when I have these few days of just reading, so I can be better prepared for the coding implemntation, so I am going to count it towards the challenge.

**Link to Work:** None :(


## Day 17: June 20, 2022

**Progress:** Finished reading chapter 8, started the simple Drill. Got stuck with an issue due to Linkage of files.

**Thoughts:** I really was not feeling it today, I spent the whole hour quite irritated. Also have not managed any progress.

**Link to Work:** None :(


## Day 18 and 19: June 21 and 22, 2022

**Progress:** Participated in the Bright Network Internship experience, coded a path finding algorithm in Python

**Thoughts:** I thoughrouly enjoyed coming up with the algorithm myself, I am happy with the result

**Link to Work:** *To be added*


## Day 20: June 23, 2022

**Progress:** Did the drill of CHapter 8 on passing variable by value, reference or const reference.

**Thoughts:** I spent way too much time figuring out that in order to link two cpp files they both need to be specified on the compiler

**Link to Work:** [Drills](https://github.com/guijmp/Drills)



## Day 21: June 24, 2022

**Progress:** Edited Calculator program to use header files and avoid global variables - pass variables by reference

**Thoughts:** Today was okay, not too productive, but not too bad either. Happy with the state of the calculator program.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/42b6a5b222ba351d87764eb01b5fd199daaaa2ee)


## Day 22: June 25, 2022

**Progress:** Did some exercises from chapter 8. Highlight was a function to reverse a vector using only the reference to that vector. Loved the simplicity and elegance of my solution.

**Thoughts:** Today was actually quite productive, and ended on a great note with my solution for reversing a vector by reference.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/089299b349d8f95ab484bc1f3be1de8b9b237399)


## Day 23: June 26, 2022

**Progress:** Did some more exercises from chapter 8. Did some function that simulates the behaviour of zip in python()

**Thoughts:** Today I was focused as well, so I would say that it was productive. Only managed to get through 2 exercises but oh well.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/38fa1be1229ef363a10f7d33248f4c7674918074)


## Day 24: June 27, 2022

**Progress:** Did one more exercise at the end of chapter that utilised struct. Great way to return several values from function!

**Thoughts:** Today I was again focused, mainly because I did this hour in the morning.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/68644b24f24b245de266f9c359a1a0d6af7ecb1c)


## Day 25: June 28, 2022

**Progress:** Finished exercises from chapter 8, started chapter 9.

**Thoughts:** I was really tired today and generally not feeling it. Still, some progress is better than none.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/c9daf12886ceae37edc1ec08ae84344791fce979)


## Day 26: June 29, 2022

**Progress:** Finished reading chapter 9, but did no coding.

**Thoughts:** I was so not in the mood + really tired, so ended up just reading the chapter

**Link to Work:** None


## Day 27: June 30, 2022

**Progress:** Started Drill for the Date class.

**Thoughts:** Today went okay, I managed to write the bones of the date class and start getting used to writing robust code for the users

**Link to Work:** [Date](https://github.com/guijmp/Date/commit/e7b3aef3e0f50234abff9fa09594f6f60aeae90a)



## Day 28: July 1, 2022

**Progress:** Finished Drill for date class

**Thoughts:** I did some progress today as well, mainly on trying out overloading operators and const member functions.

**Link to Work:** [Date](https://github.com/guijmp/Date/commit/876bef4980eca616d4c6ddde6ff166dc2a5e16b6)


## Day 29: July 2, 2022

**Progress:** Started chapter 9 exercises, class for pairs of names and ages

**Thoughts:** I was a bit sleepy, but managed to get into it halfway through.

**Link to Work:** [Drills](https://github.com/guijmp/Drills)


## Day 30: July 3, 2022

**Progress:** Started exercise for books in library

**Thoughts:** Today was fine, not much learning.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/de8a0c4546cc628fa2670f16e72fcda1aacd35fb)


## Day 31: July 4, 2022

**Progress:** Wrote an equivalent function of Python's split()

**Thoughts:** Today started with a fowl mood, but coding actually improved it.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/dbd221d08987c54a52f45030e3de62c30320f1c9)


## Day 32: July 5, 2022

**Progress:** Added a Patron class.

**Thoughts:** Today I was also not feeling it, but it was okay.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/a85ee43fa44464bba085ecf2dcb857fa23666f99)


## Day 33: July 6, 2022

**Progress:** Seperated project into different files. Added overarching Library class.

**Thoughts:** Today I was really into it yeah.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/47cf6d8f966ad11da7aecfbcd49d3a21c51a734e)



## Day 34: July 7, 2022

**Progress:** Almost finished writing all functions, so far so good.

**Thoughts:** Today was also quite productive.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/07c5da464fb3cc3bf9a5362d4f57e9920be31b01)



## Day 35: July 8, 2022

**Progress:** Finished writing functions, still requires debugging.

**Thoughts:** The beginning of today was absolutely excruciating, because I was tired due to a poor night of sleep. Somehow I managed to get through the whole hour.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/b97c652d3a7b57a0bc6f7f2b0f80e2fd8ebd10de)


## Day 36: July 9, 2022

**Progress:** Finished Library project, working to a satisfactory degree. Started writing simple class for operations with rational numbers

**Thoughts:** Today was again incredibly difficult to start, I could not fathom how I would get through the hour. However, it got much better once I got into the flow of things.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/78868c405fcec8a383f0ced0504a9267de36aaec)


## Day 37: July 10, 2022

**Progress:** Did some small progress on hte Rational class

**Thoughts:** Today was very unproductive, I barely touched the code. Found an online example of a properly implemented Rational class and was surprised by its elegance and simplicity. There is still a lot that I do not know, so I might try to implement this example as a way of learning.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/1e9166805577addeb05aa762165e8f159f2007dc)


## Day 38: July 11, 2022

**Progress:** Did very little progress on the Rational class.

**Thoughts:** Today was actually one of the least productive days thus far, I had a very demanding day at work and I am curretnly mentally exhausted so I couldnt properly focus on the code today.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/1e9166805577addeb05aa762165e8f159f2007dc)



## Day 39: July 12, 2022

**Progress:** Started reading chapter 10 on I/O.

**Thoughts:** Today was the third horrible consecutive day. I did not manage to get into flow and actaully had to take a 10 min nap because I got so exhausted half way through.

**Link to Work:** None unfortunately


## Day 40: July 13, 2022

**Progress:** Started simple exercise for I/O. Tried to do it by myself but it is currently not working, gets stuck in a while loop.

**Thoughts:** Today was okay, slightly mediocre. I find that it goes much better if I actually start to code right away.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/fbe69774760aa5d2f28c89c5650f574d3907cbdd)


## Day 41: July 14, 2022

**Progress:** Fixed the issues I was having with I/O, although I am still not entirely sure how these issues are happening.

**Thoughts:** Today I felt very good, I managed to be really focused and the code ended up working as expected, so I am very pleased.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/eaba82ac7b4356e855aa7b1965352af095e49178)


## Day 42: July 15, 2022

**Progress:** Realized thw cause of the issues I was having, rewrote same function but in simpler and more robust way.

**Thoughts:** Today okay, not super productive but still managed to learn a good pattern for reading data.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/51853c2d5651e85d1c3b27758146255817e9d8cc)


## Day 43: July 16, 2022

**Progress:** Did most of the Drill at the end of chapter.

**Thoughts:** Today was also a good day, although it seems I am forever stuck doing trivial exercises.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/37ac15ad50101b1b1598827d76670c6c788b128f)



## Day 44: July 17, 2022

**Progress:** Did some simple exercises: Read ints from file and do the sum. Write a file with temperatures with some random variation.

**Thoughts:** Today I felt concentrated in what I was doing, but I am getting a bit sick of these textbook exercises.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/5e5fc7f19e3d497c905d8b89eaf8dcd7e04122a2)


## Day 45: July 18, 2022

**Progress:** Did most of exercises 3 and 4, but need to fix it still.

**Thoughts:** Today I felt actually amazing, super into it. Vibing.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/0a8d38c6c0987e33ae0b56d98b4be6f6eb9eed4a)



## Day 46: July 19, 2022

**Progress:** Started studying for the quantum computing hackaton

**Thoughts:** Today I felt good, it is exciting to be starting quantum coomputing

**Link to Work:** [qiskit_training](https://github.com/guijmp/qiskit_training/commit/df428e8778eba19aba968cf615a9b50a73e86a80)


## Day 47: July 20, 2022

**Progress:** Did intro to Bloch Sphere, and also fixed the issue on input streams.

**Thoughts:** Today I was tired, but having dedicated the final 20 mins to debugging the input stream exercises was very rewarding.

**Link to Work:** [Drill](https://github.com/guijmp/Drills/commit/175420f6248595e6e1acaf889c72eec646210966)


## Day 48: July 21, 2022

**Progress:** Did a simple script that concatenates two text files. Solved a bug in the calculator program. Will return to calculator program to add functunality of reading input from text file.

**Thoughts:** Today went very well, I managed to do things quickly.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/b4e453996caacd4cddba9054891fc714dfe748ac)



## Day 49: July 22, 2022

**Progress:** Wrote the main body of the new feature to read commands from a file. Need to debug.

**Thoughts:** Today time went by very quickly, I barely noticed it flow.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/41c88010deb6daa488e870e3dd167bc22e0d4530)


## Day 50: July 23, 2022

**Progress:** The token 'from' and reading from file seems to be working!

**Thoughts:** Today was also a good day, easily went by.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/feee31ff4dd538846a3c3d2d78381a9c3c55e117)


## Day 51: July 24, 2022

**Progress:** Wrote a similar implementation for Token to, but need to find a way to naturally close the output stream.

**Thoughts:** I missed yesterday because I had a very full holiday day and I did not prepare in advance. So today I did almost two hours to account for it. It went well.

**Link to Work:** [Calculator](https://github.com/guijmp/Calculator/commit/51a714867f6e558f9f680926eb458ebbc16fb95a)


## Day 52, 53: July 25, 26
**Progress:** Worked on Quantum Computing examples provided by Qiskit.

**Thoughts:** Went well, did several hours of study.

**Link to Work:** None


## Day 54, 55: July 27, 28
**Progress:** Quantum Computing Hackathon

**Thoughts:** Very Intense, several hours of coding a day.

**Link to Work:** [Quantum Hackathon](https://github.com/phalgunlolur/NQCC_Team1)


## Day 56, 57, 58: July 29, 30, Aug 1

**Progress:** Finished Chapter 10 exercises on Input / Ouptut

**Thoughts:** THese days went quite well, I managed to be somewhat productive, considering I am still away from my house.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/894527110f854259237a5463939b1d8e69dbb2cb)


## Day 59: August 02, 2022

**Progress:** Wrote a wrapper to cin that ignores punctuation on an input stream.

**Thoughts:** It was incredibly hard to start today, mostly due to the heat and overall tiredeness from travelling back to Portugal. But as usual, it got much better in the final quarter of an hour.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/14845179a744c40684d53f11cf61e0197a98620f)


## Day 60: August 03, 2022

**Progress:** Did ex 1 and  2 from chpt 11.

**Thoughts:** Today was a good day, managed to do a good progress on simple but useful exercises.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/a4945de19312ae892dd44dd9aebe6276df35833b)


## Day 61: August 04, 2022

**Progress:** Did exercises 3 and 4.

**Thoughts:** Today was also a productive day, although I took way to long to do a simple exercise.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/5336d9cf8cb3d8efa73d975ecfc6f2f6a42bd289)


## Day 62: August 05, 2022

**Progress:** Did exercises 6 and 7

**Thoughts:** Today was a very good day, I was paying attention and successfuly completed the exercises.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/f3672d371970e346089ee4c81205f85c4728285a)


## Day 63: August 06, 2022

**Progress:** Almost finished all exercises.

**Thoughts:** Good vibes, nothing to report, although I did get myself want to be distracted.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/0d113743a8643e6164d2a5cac5fc4952ca5bc5c6)


## Day 64: August 07, 2022

**Progress:** Stuck on final exercise

**Thoughts:** Today was relaxed but did not manage to be productive.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/b460dac4f97c45440a89e2adc05a7d7349ac1a8e)


## Day 65: August 08, 2022

**Progress:** Solved final exercise with a very standard solution because could not find why seekg() was not working with characters '\n'.

**Thoughts:** Today I did my hour in the morning before work, so I was sharp.

**Link to Work:** [Drills](https://github.com/guijmp/Drills/commit/db90bfda0bd942f414d789e2807af9b909153937)


## Day 66: August 09, 2022

**Progress:** Tried to Build and Link external Graphical library. Was unsuccessful

**Thoughts:** Today I was not feeling it, so I did not make a lot of progress.

**Link to Work:** None


