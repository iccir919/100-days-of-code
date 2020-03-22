# 100 Days Of Code - Log

### Day 9: March 21, 2020

**Today's Progress**: Converted the exercises/examples that are in the original Processing (Java) repository but missing in the p5.js (JavaScript) repository for the Introduction chapter of The Nature of Code by Daniel Shiffman and inserted them into my fork

**Thoughts:** Today's work, translating snippets of code from one language to another could be considered by some tedious, but for me, the result was worth the pain. I loved finally seeing my lines of code come to life in the form of small animations. A sketch that is a graph of the noise distribution and actually one of the most simplest, is my favorite because it shows so elegantly how all the magic works, a clear look behind the scenes.

**Links to work:**

- [Neil's The Nature of Code p5 Exercise Solutions](https://github.com/iccir919/noc-examples-p5.js)
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

I particularly love this exercise that simulates how a change of the normal distribution through the standard deviation because it demonstrates what the world is trying to accomplish by quarantining ourselves becuase of the CORVID-19 virus. We want to accomplish flattening the bell curve by, so that there is not such a spike in virus cases so that we do not overwhelm our current health care system. In terms of the paint splatter simulation, when the standard deviation is increased, the range of color and position on the HTML canvas inreases.

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
