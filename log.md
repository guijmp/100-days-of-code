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






