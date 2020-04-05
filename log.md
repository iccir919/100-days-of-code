# 100 Days Of Code - Log

### Day 23: April 4, 2020

**Today's Progress**: Completed the exercises from Chapter 10: Modules from the book Eloquent JavaScript 

**Thoughts:** I had to use the hint for the last exercise from Chapter 10 of the book Eloquent JavaScript. Unfortunately, when I use the hints for an exercise question, I feel like I do not really understand the material of the chapter. The question covered circular dependencies, which is when one dependency requires another but that dependency that is being required also depends on the dependency requires it. Unlike other programming languages, JavaScript does allow circular dependencies because the require function is able to accomodate it without crashing since it stores a dependency in a cache before it actually loads the code. If a dependency is already in the cache, then the require function will not be load the same dependency over and over again. I feel this exercise question would make a great blog post topic since what I found online was not completely clear or helpful to me.

**Links to work:**
- [Solutions to Exercises from Chapter 10 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/10_modules/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)

### Day 22: April 3, 2020

**Today's Progress**: Reading through Chapter 10: Modules of Eloquent JavaScript

**Thoughts:** Modules have always been this magical part of JavaScript for me. Like in one sense, they seem like a really simple thing since they are snippets of code that can be exported and then imported into other code. The complicated part is understanding what is going on behind the scenes. I appreciated how this chapter went over (a maybe simplified version of) the require function. I would like to make a blog post in the future describing this for others (and myself). On a seemingly unrelated note (but I promise it has a point), today at work I attended a workshop on growing my career. I realized something that I want to do is help improve our internal documentation. However, I do not have much exerperience with writing stuff like it, so I can start now with making a blog.

**Links to work:**
- [Eloquent JavaScript](https://eloquentjavascript.net)

### Day 21: April 2, 2020

**Today's Progress**: Completed the exercises from Chapter 9: Regular Expressions from Eloquent JavaScript

**Thoughts:** Another day with not a lot of progress. After work, I went on a run with my dog, which I have not done in a while. I have gained a lot of weight since last summer, like 40 pounds. I hope to lose at least 20 pounds by the end of this challenge. Oh wait, this journal is about my code progress! I completed the exercises from the chapter about regular expressions in the book Eloquent JavaScript. I used the hints provided by the author. I feel a little weak for having to use the hints but there was still a great sense of accomplishment when I completed the exercises. It is cool that these exercises have tests inlcuded in them, so I really knew when I had the correct answer. It took three days to complete one chapter. I read about the progress made by others and again comes the feeling that I have not accomplished enough. Try not to compare yourself to them, Neil; keep focused on your [goals](goals.md).


**Links to work:**
- [Solutions to Exercises from Chapter 9 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/08_bugs_and_errors/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)

### Day 20: April 1, 2020

**Today's Progress**: Continuing my progress on Chapter 9: Regular Expressions from Eloquent JavaScript. Also, I reset my freeCodeCamp and Code Signal accounts. New beginnings!

**Thoughts:** To be honest, I did not make much progress today. It is my parents anniversary, so the time that I usually work on coding stuff was taken by preparing them dinner. Then after dinner, we watched a movie. Throughout all of this, we were all drinking alcohol. Now, at the end of it all, I feel pretty tired and not really able to code. I'm resetting my Code Signal and freeCodeCamp accounts so that I can relearn what I went over months and months ago. Hopefully, if I did actually absorb the material, then it should be quick to get back where I was before the reset. Completing some of the freeCodeCamp sections is one of the goals of this challenge. 

**Links to work:**
- [Eloquent JavaScript](https://eloquentjavascript.net)
- [freeCodeCamp Profile](https://www.freecodecamp.org/iccir919)
- [Code Signal Profile](https://app.codesignal.com/profile/iccir919)


### Day 19: March 31, 2020

**Today's Progress**: Working though Chapter 9: Regular Expressions from the book Eloquent JavaScript.

**Thoughts:** I kind of knew that the chapter of Eloquent JavaScript about regular expressions would take me longer than the previous chapters. In many ways, it feels like learning an entirely new language. I used to just ignore regular expressions because I never found myself needing to use them. However, they can be a key part of a task like data aggregation from other websites. JavaScript libraries like Puppeteer can help with navigating to and through web pages that have information, like rcdb.com for example, but to parse through the data regular expressions are needed to transform the information from HTML into useable JSON. Also, let's not forgot about the projects that Daniel Shiffman has created for text analysis using regular expressions. I started to work on one of these projects three years ago that rearranged the lyrics of Radiohead songs. 

**Links to work:**
- [Eloquent JavaScript](https://eloquentjavascript.net)
- [Programming from A to Z - Text Analysis](https://shiffman.net/a2z/text-analysis/)
- [Kid A Rearrange](https://github.com/iccir919/kidARearrange)

### Day 18: March 30, 2020

**Today's Progress**: Completed all of the exercises from Chapter 8 of Eloquent JavaScript. Topics like TypeScript and testing frameworks are briefly mentioned but understandably not covered. 

**Thoughts:** Chapter 8 of Eloquent JavaScript goes over handling bugs and errors. To be honest, none of the JavaScript code I have written previously handles errors. I always assume that everything will just work and this is wrong. TypeScript is a JavaScript dialect that I have been meaning to look into (as many job descriptions require knowledge of it) but I have not made the effort to learn it just yet. My assumption is that it makes JavaScript more like Java by requiring the programmer to declare the type (number, string, object, etc.) of a variable or output of a function. TypeScript will probably throw an error if the type is different than what is expected. Testing is also something that I have not done before for any of my projects (but is also a common recurring job description requirement). I have read often on Twitter that one thing programmers who have engineering jobs wish they knew more about before starting is testing. I want to level up on these topics, but right now, the goal is just to finally finish this book. 

**Links to work:**
- [Solutions to Exercises from Chapter 8 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/08_bugs_and_errors/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)

### Day 17: March 29, 2020

**Today's Progress**: Completed exercises from Chapter 7 and in the midst of reading Chapter 8 of Eloquent JavaScript. Also watching the accompanying YouTube videos for Chapter 1 of The Nature of Code that Shiffman has recently uploaded. 

**Thoughts:** I spent three hours on the second exercise, Robot Efficiency, from Chapter 7 of Eloquent JavaScript. I started out with the right idea to find the shortest route but my execution was poor. There was an error within my code that made the robot travel back and forth between the same places, never going anywhere else. I never investigated why this error was happening but instead just kept restarting. Then I read the hint for this exercise and it confirmed that I was on the right track with my thinking but did not provide much more help. I did complete the exercise in my own way. I imagine that if I had investigated why I kept running into the same error then I would have completed the exercise earlier.

It is important to review the content that I have covered with The Nature of Code and Eloquent JavaScript. From this point on, I believe that for every chapter I complete in Eloquent JavaScript, I should review a chapter from the past. For The Nature of Code, I am blessed to have YouTube videos to accompany the material. I really have enjoyed watching the YouTube videos for The Nature of Code for Chapter 1 because of Shiffman's enthusiasm for the material. Also, fact that Shiffman is releasing new videos when I am working on completing the book is an another example of synchronicity. I am almost one fifth of the way through this challenge. I don't feel that I have accomplished much unfortunately. 

**Links to work:**

- [Solutions to Exercises from Chapter 7 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/07_a_robot/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)
- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)
- [YouTube Playlist for The Nature of Code]((https://youtube.com/playlist?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM))


### Day 16: March 28, 2020

**Today's Progress**: Read all of Chapter 7 of Eloquent JavaScript. Worked on my Ecosystem project from The Nature of Code.

**Thoughts:** Today was not a very productive day. After hanging out with my little brother last night, I was very lethargic during all of today. I was inspired that Shiffman liked another tweet of mine. I worked on my Ecoystem project for The Nature of Code. I practiced creating classes, one general Creature class and a class for each type, and used inheritance to share methods from the master Creature calss among the diffent types. I read through Chapter 7 of Eloquent JavaScript, which focused on a project instead of a concept. Nevertheless, I still learned a lot, specifically about building an automaton, a little program that performs a task in a virtual world. Later today, I mistakenly opened up a pull request on the noc-examples-p5.js repository and I am annoyed because pull requests cannot be deleted from Github. 

**Links to work:**

- [Eloquent JavaScript](https://eloquentjavascript.net)
- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)
- [Ecosystem Project](https://iccir919.github.io/noc-examples-p5.js/chp01_vectors/Step_1_Ecoystem_Project/index.html)

### Day 15: March 27, 2020

**Today's Progress**: Completed Chapter 1 of The Nature of Code. The content of this chapter and Chapter 6 of Eloquent JavaScript (object oriented programming, vectors, and encapsulation) are in harmony with each other.

**Thoughts:** I finally completed Chapter 1 of The Nature of Code. For Eloquent JavaScript, I have been completing chapters by the day, and for The Nature of Code, one chapter took me all week. However, I am not upset by my lack of progress because as I mentioned yesterday, the content of these latest chapters beautifully overlap each other. When there is this sort of synchronicity, I believe that "meaningful coincidences" show that I am on the right path. I am upset with myself because I did not commit any new code to Github today (actually writing this entry the day after). I almost had a full week where I made commits to Github every day. 

**Links to work:**

- [Solutions to Exercises from Chapter 6 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/06_the_secret_life_of_objects/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)
- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)
- [Synchronicity](https://en.wikipedia.org/wiki/Synchronicity)

### Day 14: March 26, 2020

**Today's Progress**:  Chapter 6 of Eloquent JavaScript and progresed a little more of Chapter 1 of The Nature of Code

**Thoughts:** Today the world's of the two books I am reading, The Nature of Code and Eloquent JavaScript, have collided; both are discussing creating vectors (and also go into some of the math behind their mathematical operations like add, subtract, etc.), encapsulation, and creating classes. There is this strange feeling in me that I have written something similar in a previous attempt of this challenge. Today's entry is not very exciting and this is okay. I am finally starting to build a daily routine that includes coding. I walk with my dog at the same time and pass by the same people. Everyone else has had routines but I did not; or if I did, it wasn't a healthy one, which ultimately lead me into chaos. Since starting this challenge, I have lost a little bit of weight and my chess scores have increased. Interestingly, the last time I committed to Github every day of the week was also the time when I had the highest chess scores for puzzles and blitz games than ever before.

**Links to work:**

- [Solutions to Exercises from Chapter 6 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/06_the_secret_life_of_objects/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)
- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)

### Day 13: March 25, 2020

**Today's Progress**: Today is my two week mark (since I started my count at 0 like a programmer😎). I completed Chapter 5 of Eloquent JavaScript

**Thoughts:** This entry will be short. I completed another chapter today from Eloquent JavaScript today. I also was faced with the choice of whether or not to pay for Notion (the application I have been using to be taking notes for the book). I decided to not continue taking notes because I was just copying and pasting the material anyway. Why not just review the book, the source, when I need a refresher on the content? And as I mentioned yesterday, I should do this to keep the content fresh in my mind. These first five chapters have been easy for me, which proves I did gain some sort of knowledge over these past four, maybe five years, since I started the book. Wow, it has been four years since Hack Reactor, and look at me now. What have I really accomplished? Sometimes I really wish that I had just not went to Hack Reactor. It has cost me a lot of financial and emotional debt. Welp, I started this entry saying I would keep this short and here I am writing my head off. End it, Neil.

**Links to work:**

- [Solutions to Exercises from Chapter 5 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/05_higher_order_functions/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)


### Day 12: March 24, 2020

**Today's Progress**: Today I completed Chapters 3 and 4 of Eloquent JavaScript

**Thoughts:** Once again, I am not satisfied with my progress. I desperately want to be finished with this book, Eloquent JavaScript. I wish to be able say that I finally have completed it! I'm looking at the Twitter statuses of others who are in the midst of this 100 Days of Code challenge and they are all working on actual projects and not trying to complete a book like me. Neil, remember this is only the beginning of the challenge. There is plenty of time for work on other projects but Eloquent JavaScript has been on your reading list for years! I look forward to the day when I can look at any random page and be able to understand perfectly the material of that part. When I do complete this book, it will not be the end of this book. I know that I will need to review it often, making sure that the material has settled into my brain. 

**Links to work:**

- [Solutions to Exercises from Chapter 3 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/03_functions/exercises)
- [Solutions to Exercises from Chapter 4 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/04_data_structures/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)

### Day 11: March 23, 2020

**Today's Progress**: Completed Chapter 2 , Program Structure, from the book Eloquent JavaScript (https://eloquentjavascript.net) by Marijn Haverbeke 

**Thoughts:** My work today feels like not much. In fact, I feel very anxious. I have gone through these same chapters (like 1 through 6) of the same book (Eloquent JavaScript) many times for the past _four_ years now, and each time, I have given up on completing the entire book for whatever reason. I have this guilty pain in me that I should already be done with the book. I completed a chapter with ease today but it is because I have gone through it many times before. I feel like I should have completed more than just one chapter. But then, I breathe, and I remember that two weeks ago I completed no chapters. If I complete one chapter, or even just a part of one, I am still making some daily progress. I need to focus less on the finish line and just be sure that I am focusing on the now, completely understanding what material is currently in front of me.

**Links to work:**

- [Solutions to Exercises from Chapter 2 of Eloquent JavaScript](https://github.com/iccir919/eloquent-javascript/tree/master/02_program_structure/exercises)
- [Eloquent JavaScript](https://eloquentjavascript.net)

### Day 10: March 22, 2020

**Today's Progress**: Turned my work from yesterday into a public Github pull request for the p5.js examples and exercises from the Introduction chapter of The Nature of Code repository

**Thoughts:** I am ecstatic by the fact that Shiffman replied to my tweet and invited me to open up a pull request for the Nature of Code p5.js repository. I was debating with myself all yesterday wondering if I should keep contributing to a clone or a fork of The Nature of Code p5.js repository. I asked myself what is the point if Shiffman does not accept any pull requests? However, my fears have been swept away by this tweet from him. I now feel like I have a responsibility to contribute and I feel a sense of small purpose in this big great ocean that I am just a drop of.

Opening up a public Github pull request was a lot more challenging than I expected it to be. A couple of days ago, I opened up a pull request for some typos I found in the Introduction chapter of The Nature of Code. Then I changed the name of the branch the pull request was attached to. Github made the renamed branch a new branch, so any additional changes I made in the renamed branch were not able to be added to the commit attached to the pull request. These are the learning pains I am experiencing with pull requests but it feels amazing to finally contribute to something, especially a repository that I love so dearly.

**Links to work:**

- [Tweet Responded To By Shiffman](https://twitter.com/realNeilVR/status/1241625415409520640)
- [My Github Pull Request for Nature of Code p5.js Repository](<(https://github.com/nature-of-code/noc-examples-p5.js/pull/98)>)

### Day 9: March 21, 2020

**Today's Progress**: Converted the exercises/examples that are in the original Processing (Java) repository but missing in the p5.js (JavaScript) repository for the Introduction chapter of The Nature of Code by Daniel Shiffman and inserted them into my fork

**Thoughts:** Today's work, translating snippets of code from one language to another could be considered by some tedious, but for me, the result was worth the pain. I loved finally seeing my lines of code come to life in the form of small animations. A sketch that is a graph of the noise distribution and actually one of the most simplest, is my favorite because it shows so elegantly how all the magic works, a clear look behind the scenes.

**Links to work:**

- [Neil's The Nature of Code p5 Exercise Solutions](https://github.com/iccir919/noc-examples-p5.js)
- [Original Processing Repository](https://github.com/nature-of-code/noc-examples-processing)
- [Noise Distrubtion Graph](https://iccir919.github.io/noc-examples-p5.js/chp00_introduction/NoiseDistribution/)

### Day 8: March 20, 2020

**Today's Progress**: Completed the examples and exercises of the Introduction chapter of The Nature of Code by Daniel Shiffman. Also added the Chart component to the Bay Wheels Planner

**Thoughts:** Today I posted a video to my Twitter of a sketch I made for an exercise in the Introduction chapter of The Nature of Code that brought color to the 3D Perlin Noise visualization which I forked from the example by Shiffman. I also added some background music (After Hours by The Weekend). The combination of the visual and sound was amazing to me, like a minature theactrical experience within the confines of my room at home.

For the Bay Wheels Planner, I revised the logic for the elevation analysis and added the begginings of an elevation chart for each route. As it turns out, I did not perfectly understand the getElevations function from the Steepless application. As I worked on the Chart componenet, I realized I was not receiving the data I was expecting because the Bay Wheels Planner getElevations function did not fully operate the same as the one from Steepless. Troubleshooting was made difficult by the fact that the output of console.log(anObject) is misleading; the state of the object displayed is only resolved when you expand the > in the console. It is not the state of the object when you console.log'd the object.

**Links to work:**

- [Bay Wheels Planner](https://github.com/iccir919/bay-wheels-planner)
- [Steepless](https://github.com/cheeaun/steepless)
- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)
- [Neil's The Nature of Code p5 Exercise Solutions](https://github.com/iccir919/noc-examples-p5.js)

### Day 7: March 19, 2020

**Today's Progress**: For Bay Wheels Planner, I implemented analysis of elevation changes between two stations. Also, improved user experience by removing Submit button and making the search for routes automatic. For Nature of Code, completed more Introduction exercises/examples

**Thoughts:** Every day, I get a little closer to having a most viable version of the Bay Wheels Planner. Today I got all the data to be returned and analyzed. Now, the next step is to display the data in an interactive visualization. It's funny how horrible I have been at estimating the completion of this project since I am months, maybe years, behind from when I guessed I might be done.

The Submit button I had in the Bay Wheels Planner in the directions form as of yesterday was taking up a whole row and also added an extra click for the user to move to the next step. I came to the conclusion that if the user had clicked on other buttons that selected a begining and destination, then they should not have to click another to submit. So, I removed it, but that required me to come with some logic for the automatic detection that the stations had been selected. The answer was within the ComomponentDidUpdate function.

In terms of the Nature of Code exercise and examples, I am not content with my recent contributions. The different (Gaussian or custom distribution) alogorithms for the random walker do not seem that unqiue from one another. I was looking for better solutions (which there aren't many of) and I came across one person who used lines instead of dots. I hope in the future to make this change and better be able to see the difference between these algorithms.

**Links to work:**

- [The Other Dell Blog](http://simon.theotherdell.com/)
- [Bay Wheels Planner](https://github.com/iccir919/bay-wheels-planner)
- [Steepless](https://github.com/cheeaun/steepless)
- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)
- [Neil's The Nature of Code p5 Exercise Solutions](https://github.com/iccir919/noc-examples-p5.js)

### Day 6: March 18, 2020

**Today's Progress**: Successfully implemented a collection of calls to the Google Maps Elevation Service API for the available routes found between two Bay Wheels Bike stations with JavaScript Promises

**Thoughts:**
To be honest, this is not the first time that I have attempted to create a Bay Wheels Planner application through using the old Steepless code. However, I do not remember, nor seem to care, about how I implemented capturing the elevation data of the available routes between two stations in the older version. It doesn't matter because I have since forgotten about how JavaScript promises operate.

To reteach myself JavaScript promises, I used my two best current resources, Treehouse and the book Eloqent JavaScript. I appreciate Treehouse for providing amazing video tutorials and Eloquent JavaScript for describing the material in writing. My last shoutout would be to the Mozilla Documentation, however, I do not like straight documentation it is hard to read and learn about these concepts without any context/story.

**Links to work:**

- [MDN web docs for JavaScript Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [Treehouse Course for Asynchronous Programming with JavaScript](https://teamtreehouse.com/library/asynchronous-programming-with-javascript)
- [Elqouent JavaScript for Asynchronous Programming](https://eloquentjavascript.net/11_async.html)

### Day 5: March 17, 2020

**Today's Progress**: Worked on a paint splatter simulation that uses a normal distribution of random numbers to generate the dots positions and colors.

**Thoughts:** I was very tempted to copy the exercise answers from another person's Github repository to satisfy the answers for my own exercise answers that were not supplied by Shiffman. Wait, I'm copying the answers from Shiffman's Processing exercise answers? Yes, but I feel I am doing Shiffman a service by converting his own Processing exercise answers to p5. When I am copying answers that aren't written by Shiffman, I feel I am doing a disservice to myself.

I particularly love this exercise that simulates how a change of the normal distribution through the standard deviation because it demonstrates what the world is trying to accomplish by quarantining ourselves becuase of the COVID-19 virus. We want to accomplish flattening the bell curve by, so that there is not such a spike in virus cases so that we do not overwhelm our current health care system. In terms of the paint splatter simulation, when the standard deviation is increased, the range of color and position on the HTML canvas inreases.

**Links to work:**

- [Nature of Code Introduction](https://natureofcode.com/book/introduction/)
- [Neil's The Nature of Code p5 Exercise Solutions](https://github.com/iccir919/noc-examples-p5.js)

### Day 4: March 16, 2020

**Today's Progress**: I found the official YouTube learning playlist for the Nature of Code. I supplemented my reading of the Introduction chapter with watching the videos and worked through the exercises.

**Thoughts:** I skipped a day of this challenge because of some drinking alcohol, my 'ol nemesis in life. Instead of enjoying the small but continuous daily gains of learning, which benefit the overall plan of my professional development, I chose to instead joy the short-term pleasing but long-term destructive effects of escaping my currently mediocre life through ethanol.

When I found that Daniel Shiffman is this year working to improve the YouTube chanenl for the Nature of Code, I found it to be pretty awesome that he has not let the Nature of Code to become something stale but instead something continually works to improve and expand the audience of. Translating his exercises from Processing to p5 is 'easy' but also is helpful to helping me to understand the library more and more.

**Links to work:**

- [Nature of Code YouTube Channel](<(https://youtube.com/playlist?list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM)>)
- [Shiffman's The Nature of Code Processing Exercise Solutions](https://github.com/nature-of-code/noc-examples-processing)
- [Neil's The Nature of Code p5 Exercise Solutions](https://github.com/iccir919/noc-examples-p5.js)

### Day 3: March 14, 2020

**Today's Progress**: Completed the implementation of the Google Maps JavaScript API for the Bay Wheels Planner and the Introduction chapter of Nature of Code

**Thoughts:**
Getting the directions from the Google Maps JavaScript API was easy but the elevations part was difficult because it required implementing the Steepless code. All of the different routes elevations must be fetched before I can implement any of the analysis from Steepless. I am in the middle of retaking the Asynchronous Programming with JavaScript from Treehouse because of my rusty familiarity of the different methods.

I completed reading through the Introduction of Daniel Shiffman's, The Nature of Code, and I learned about the different ways to implement randomness. I do not feel I thoroughly understand the material because I was not able to complete the exercises in the Introduction chapter. I made goals today for the different things I want to accomplish during this challenge. Even if I only complete some I will be happy since many of these things have been on my To-Do list for two or more years.

**Links to work:**

- [Goals for this challenge](goals.md)
- [Bay Wheels Planner](https://github.com/iccir919/bay-wheels-planner)
- [Steepless](https://github.com/cheeaun/steepless)
- [Nature of Code](https://natureofcode.com/)
- [Nature of Code Github](https://github.com/nature-of-code)

### Day 2: March 13, 2020

**Today's Progress**: Continued studying the code of Steepless and also started reading the Nature of Code

**Thoughts:**
Today I deleted the code from my Bay Wheels Planner application just thrown in from the Steepless project without any understanding to what it did. Let's be real, the Steepless application is already better in a lot of ways (timing of release, the larger scope of audience, etc.), but my purpose for making Bay Wheels Planner is to use it as a project to learn from and honestly enjoy. The official Bay Wheels app does not have such a feature yet, or really any planning feature, so I am happy to learn and make something useful (even if only for myself).

Reading Daniel Shiffman's 'The Nature of Code' is always something I have wanted to do and it will be done by the end of this challenge. Sure the technology is nothing that will get me a job (p5 is not a very desired technology skill), but as my Tweet said for today, 'Nice thing bout havin a cool job (and not job searchin) is that I can work on the stuff I love ❤️ without worry if I'm 'doing the right thing.'

**Links to work:**

- [Bay Wheels Planner](https://github.com/iccir919/bay-wheels-planner)
- [Steepless](https://github.com/cheeaun/steepless)
- [Nature of Code](https://natureofcode.com/)
- [Nature of Code Github](https://github.com/nature-of-code)

### Day 1: March 12, 2020

**Today's Progress**: Continued studying the code of Steepless

**Thoughts:**
When I have a very a little amount of lines of code to commit to Github, I feel that I am unproductive. However, contrary to my belief, a deeper understanding of the code I am trying to implement is what will make me application great. In the past, a lot of times I start drawings with no plan and that is often how my coding has been in the past. They turn out fine. However, with code, I know it will help me to understand each part of the code and how each part integrates with another. Otherwise, it will get messy. Also, I won't be able to talk to anyone about it.

**Links to work:**

- [Bay Wheels Planner](https://github.com/iccir919/bay-wheels-planner)
- [Steepless](https://github.com/cheeaun/steepless)

### Day 0: March 11, 2020

**Today's Progress**: Started Life project, studied the code of Steepless

**Thoughts:**
Today I restart this challenge. I do not want to count how many times I have restarted. I looked up Lim Chee Aun, the creator of Steepless, the application that I am using parts of it's code for my Bay Wheels Planner application. Lim Chee Aun was featured on Hacker News for his Life application (https://github.com/cheeaun/life). Today I made a fork to help map out my own life.

**Links to work:**

- [Steepless](https://github.com/cheeaun/steepless)
- [Neil's Life](https://github.com/iccir919/life)
- [Bay Wheels Planner](https://github.com/iccir919/bay-wheels-planner)
