# 100 Days Of Code - Log

### Day 0: April 10, Sunday

**Today's Progress**: None, decided to have a go at the 100 days of code challenge. Have cleaned out a twitter account to focus on my coding.

**Thoughts:**
Worried about my commitment. Want this to be a successful experience.

**Link to work:** 
[Twitter Account](https://twitter.com/mattbooker401)


### Day 1: April 11, Monday

**Today's Progress**: GitHub set up and working. Decided to build a twitter follower analyser as my first small project. Should be easy enough to launch myself into the challenge. 

I've learned about python's responce method, seen it in use and played with it. Definition was found here [GeeksForGeeks](https://www.geeksforgeeks.org/response-methods-python-requests/)

Famous last words, Twitter has reduced the number of followers you can call to 1000, well below what i would need. I had fun exploring Tweepy, a python library I've used before. I also explored Twitter's own API, which while interesting, wasn't nearly neat enough for my liking.

Did learn about Twitter userID's, used the following website to discover those i needed for the tests [Twitter ID's](https://tweeterid.com/)

**Thoughts**: I need to spend some time going through the repros of other members of the challenge. Reasons are two fold, check to see the kinds of this others are doing, and to bring my formatting up to scratch. Need to redefine my task tomorrow...

**Link(s) to work**
1. [GitHub Repro](https://github.com/mattb00ker/100-days-of-code)
2. [Code I played with](https://github.com/mattb00ker/My100Days/blob/main/followerAnalyser.py)


### Day 2: April 12, Tuesday

**Today's Progress**: After yesterday I wanted more to show for my efforts, at least I didn't want to keep slamming my head into a brick wall. Decided to change tact (at least in the short term), today i spent my time getting back into JavaScript. It's been years since I last wrote some, and I feel very rusty (remember those semicolons is a giggle). I started the Odin Project some months back (another unfinished challenge started with the best of intentions), so I picked up where I left off in their JavaScript thread. 

**Today's Problems**: 
* Running JS from an external file (SOLVED)
* How to view the console log on both safari and chrome (SOLVED)
* Having JS material displayed as website opens (UNSOLVED)

**Thoughts**: Not sure if JS can be run as a website opens, think it needs a trigger (like a button), I do wonder if there's an "as website opens" function/command. Not seeing the huge advantage of JS yet. Looking forward to getting further into it.

**Link(s) to work**
1. [GitHub Repro](https://github.com/mattb00ker/My100Days/tree/main/JavaScript)
2. [Odin Project](https://www.theodinproject.com/lessons/foundations-fundamentals-part-2)


### Day 3: April 13, Wednesday

**Today's Progress**: Continued where i left off yesterday with JavaScript. Spent the first part of my hour brushing up on syntax, but as this isn't my first time with the language I decided the best way to continue was to build something. I settled on a card game of some sort. I'm not sure if i want to build a simple 'higher or lower' type game, or something more interesting like the game 'arsehole'. Anyway, I built a simple test page and started writing the JS. So far i've initiated an array to hold the deck of cards, have populated the array with some sample cards (i've used the nomencleture of AH for the ace of hearts for example). Once this was completed i wrote a function to pick a random card from the deck. 

**Today's Problems**: 
* None really, I need to decide what to do with the game first thing tomorrow, the structure is required!!

**Thoughts**: After deciding exactly what type of game to produce, I need to build a function to remove cards from the active (unused) deck. I should probably also decide on my variables at the same time. tomorrow may be conducted entirely on paper (or a suitable paper alternative).

**Link(s) to work**
1. [GitHub for a higher and lower game](https://github.com/arunkal1/Higher-Or-Lower/blob/master/js/app.js)
2. [card game website](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
3. [card game JS](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardSelector.js)
4. [info on random function](https://www.w3schools.com/JS/js_random.asp)
5. [finding array lengths](https://www.w3schools.com/jsref/jsref_length_array.asp)


### Day 4: April 14, Thursday

**Today's Progress**: No JavaScript today, instead i spent my time uploading the tinyGS operating system to a T-Beam LoRa board. This should have been quite straight forward, but there were issues I was unawear of when I started this morning. Today I became much more familiar with both platform.io, and VS Code. The issues I was having resulted in me going back over a process (uploading code to a smaller comuting device) I have done thousands of times. I am really enjoying using VS Code, and can see myself sticking with it for a while.

While dealing with the verious issues I had (things like changing board types), I did consider my own problem solving technique. Attacking a problem in a logical way yields the best results. Although others have managed to upload the firmwhere to the board type from my computer type, it didn't benefit me to struggle against why the drivers weren't working for me. I know how to load firmwhere, I've done it hundreds of times, after realising that the issue wasn't with my knowledge of VS Code, I was right to give up, switch to a windows based machine, and perform the update that way. 

**Today's Problems**: 
* Drivers are a pain

**Thoughts**: Make sure the problem you are trying to solve is fixable. There is a difference between not giving up, and flogging a dead horse. 

**Link(s) to work**
1. [Working tinyGS](https://tinygs.com/station/M0WHU@5051483323)


### Day 5: April 15, Friday

**Today's Progress**: Today I got back into JavaScript. I went back over the content I'd previosuly covered in building a number of functions. I then moved forward by both passing data between functions, and implamenting a switch case situcation to handle the scoring. I've decided to limit the scope of this card game to a simple higher and lower game. Short term goal is to finish the game over the weekend, then upload it to my website. Happy with the variables i have settled on.

**Today's Problems**: 
* None, though i still need to remove the cards from the active deck, this shouldn't be too hard, in theory.

**Thoughts**: I worry that I'm not streching myself enough. I am still early in the process, but i haven't come across any issues that i haven't been able to overcome, or understand, and I worry that this is a sign that I'm not pushing myself, and will therefore never make the jump between hobbist and professional. Ho humm...

**Link(s) to work**
1. [simple webpage i've been using](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [the java script that goes with it](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardSelector.js)
3. [switch statement support](https://www.w3schools.com/js/js_switch.asp)
4. [return statement support](https://www.w3schools.com/jsref/jsref_return.asp)


### Day 6: April 16, Saturday

**Today's Progress**: Kept on with the Java Script. Refined the webpage to add control buttons. Also added a forth button to observe the behaviour of my cardOne and cardTwo variables. Realised that I need to rethink and encorpourate classes mroe fundimentally. need to able to assign values to cards (though i may be able to do this though the return function... problem for future Matt)

**Today's Problems**: 
* Need to link rank to card name

**Thoughts**: Need to learn more about classes, might be able to get away with the return function

**Link(s) to work**
1. [html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [JS](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardSelector.js)


### Day 7: April 17, Sunday

**Today's Progress**: Sorted ranking system, which allowed the win/loss functions to work. Additionally I implamented a scoring system which resests on every loss. I still haven't sorted a system to remove cards from the active deck, i should do this!!! Started learning about DOM manipulation towards the end of my hour. Did go back and add a function for removing the cards form the deck, ended up being easiest to call the function right after requesting a new card.

**Today's Problems**: 
* Still need to remove cards from the active deck (done)
* Need to have the JS interact with the html
* Need to add the rest of the deck.

**Thoughts**: Need to just keep plodding forwards. The tasks i am undertaking will only become more complex the more time i dedicate to them!

**Link(s) to work**
1. [my html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [my js](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardSelector.js)
3. [DOM manipulation](https://www.w3schools.com/js/js_htmldom.asp)


### Day 8: April 18, Monday

**Today's Progress**: Not a huge amount to show for today. I did spend my time reviewing different options for displaying data through the Twitter API. None of the methods I explored met my criteria (I really want to use tables!). I looked at self generated graphs, self generated images, and the use of the formatting command in python. 

**Today's Problems**: 
* Twitter hates tables!

**Thoughts**: Either, write a script for inserting tables into tweets, or let this one go. 

This seems like my only option, I want to use a table. I may return to ASCII formatting, this may be an option (though very old fashioned (although this may appeal to the target audience in itself)).

**Link(s) to work**
1. [fotmatting in ptyhon](https://www.w3schools.com/python/ref_string_format.asp)
2. [auto generated images](https://auth0.com/blog/how-to-make-a-twitter-bot-in-python-using-tweepy/)
3. [something to look at tomorrow?](https://towardsdatascience.com/tweepy-for-beginners-24baf21f2c25)


### Day 9: April 19, Tuesday

**Today's Progress**: Added some more cards to both the initial array, and the value function. All cards added worked without issue. Game made much harder (I may just be tired!). Also looked into LoRa on a meshtastic network. There may be some scope in producing code to track airplanes, definately something for me to look into

**Today's Problems**: 
* None

**Thoughts**: Need to find a away to create more hours in a day/dedicate enough time to everything without feeling that i'm neglecting any single aspect of my life... answers on a postcard.

**Link(s) to work**
1. [my html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [my js](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardSelector.js)
3. [DOM manipulation](https://www.w3schools.com/js/js_htmldom.asp)
4. [something to look at tomorrow?](https://towardsdatascience.com/tweepy-for-beginners-24baf21f2c25)


### Day 10: April 20, Wednesday

**Today's Progress**: Good day. Finally launched into DOM manipulation. Have the JS updating the HTML with the score and the current card. Happy with the progress I've made, always a good feeling when you try something you learned in another language and it transfers over with minimal change! I've also started cleaning up the HTML

**Today's Problems**: 
* None

**Thoughts**: Very happy wih today's work, would love to push through and add some of the things i'm about to list. Need to clean up my HTML and JS, in my haste I also need to go back and comment all of the work. Tmorrow I'd like to look at the possibility of introducing pictures, also getting a better hod in my web design.

**Link(s) to work**
1. [my html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [my js](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardSelector.js)
3. [something to look at tomorrow?](https://towardsdatascience.com/tweepy-for-beginners-24baf21f2c25)


### Day 11: April 23, Saturday

**Today's Progress**: Returned to coding today, and returned to CSS. Went back over using flex, and built a couple of containers. Added background colour to the page, and am stopping there. 

**Today's Problems**: 
* moreving items around a webpage. Still need to spend more time with flex.

**Thoughts**: spend more time with flex.

**Link(s) to work**
1. [html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [css](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/style.css)


### Day 12: April 24, Sunday

**Today's Progress**: Continued again with flex and css, still not happy with my understanding of the concepts, will be returning to it tomorrow. Also spent some time messing around with the colours of different aspects, happy with the changes i made, and the way i set them up. 

**Today's Problems**: 
* Still not happy with my understanding of flex
* Was having issues with commiting changes to github. Although now fixed, this is something i'll need to keep an eye on.

**Thoughts**: 
Need to keep bashing away with flex, seems like my new tkinter, in a scary number of ways. All that needed was some thinking time too :)

**Link(s) to work**
1. [html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [css](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/style.css)


### Day 13: April 25, Monday

**Today's Progress**: Much the same as yesterday, watched a good video on flex and continued to push things around my little website. 

**Today's Problems**: 
* Still not happy with my understanding of flex

**Thoughts**: Not a huge amount to add here, I'm making progress, but the penny hasn't dropped yet. Will get back to it tomorrow. I will crack it!

**Link(s) to work**
1. [html](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/cardGame.html)
2. [css](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/style.css)
3. [video](https://www.youtube.com/watch?v=fYq5PXgSsbE)


### Day 14: April 26, Tuesday

**Today's Progress**: Still at it. Rebuilt the webpage to gain greater ease of use. Move everything to the center of the page, though have now lost the ability to effectively control the different aspect. Short term goals for tomorrow are to add a background, and short the buttons out. Longer term goals are to understand inheritance in JS. Found a template to help with my understanding :)

**Today's Problems**: 
* Lost the ability to effectively control aspects of the website (ie the buttons)
* 

**Thoughts**: Must keep swimming! Want to load my website onto my new template, job for the weekend maybe :)

**Link(s) to work**
1. [new webpage](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/higherlower.html)
2. [new non working css](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/style.css)
3. [template webpage](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/template.html)
4. [template css](https://github.com/mattb00ker/My100Days/blob/main/JavaScript/template.css)


### Day 15: April 27, Wednesday

**Today's Progress**: Good day of flex. Items moved as desired, all formatting is as i wanted. Quite happ with my progress :)

**Today's Problems**: 
* 
* 

**Thoughts**: 

**Link(s) to work**
1. []()


### Day 16: May 1, Sunday

**Today's Progress**: Got back in to it with the introduction of a reset feature. Started to added a high score system, but i havent managed to get it working yet, job for tomorrow. All cards now added to the full dack of 52.

**Today's Problems**: 
* Highscore not displaying, not sure if the designed function is even being called.
* Energy levels are low

**Thoughts**: After taking two days off my energy levels are still not back where i'd like them to be. Being a teacher, this is the busiest time of the year (2 weeks until exams start, these are also the first exams for two years). 

**Link(s) to work**
1. [Same as prevous!]()


### Day 17: July 5, Tuesday

**Today's Progress**: Arhhh, well i properly fell off. No excuses, just need to get back on. Going to start by adding a blog to my website. I've been looking at a couple of the static frameworks, but i'm not sure if they're really for me, it seems that you add the information, click 'go', the software builds the HTML, then you add that to your site. What i imagined is a seperate system where you write the article, click a button and it's added to the database (i assume that's how most of them work). I could have a go at building my own system using mysql, this would be a huge amount of work however, but i'd only need to do it once!

**Today's Problems**: 
*  working out the best way forward to added a blog to my website.
* 

**Thoughts**: 

**Link(s) to work**
1. []()


### Day 1: March 27, Monday

**Today's Progress**: So far nothing today, but i managed to get back on the horse yesterday! Built a RNN, and trained it on the tweets of the Donald! Really happy to actually write some code again, it had been almost a year! I broke the rpoject in two, producing a program that would train the model, and one to generate text. The only problem i have (other than the quiality of the data) I that it keep spitting out errs at the end, see below. Today i plan to fix the bug, and get back on with project Odin

WARNING:tensorflow:Detecting that an object or model or tf.train.Checkpoint is being deleted with unrestored values. See the following logs for the specific values in question.

Didn't manage to fix the bug, did manage to replicate it. Did manage to restart project odin. have started a course on js, all set up on my laptop, lesson 01 passed.

**Today's Problems**: 
*  removing my tensor flow error
*  getting back on with project Odin

**Thoughts**: 

**Link(s) to work**
1. [RNN](https://github.com/mattb00ker/My100Days/blob/main/RNN.py)
2. [text gen](https://github.com/mattb00ker/My100Days/blob/main/genTxt.py)
3. [JS exercise](https://github.com/mattb00ker/javascript-exercises/tree/main/01_helloWorld)


### Day 2: March 28, Tuesday

**Today's Progress**: Continued through the JS series i started yesterday, no big issues. Created a fuction that printed text a set number of times. Like the format i am using. There are only 12 lessons, i hope they become much more difficault! Had another swing at the tensor flow issue, still not there though getting closer. One problem I have is that i simply don't know enough about the lib. I've botched together something and to be honest I'm not sure exactly how it works. I understand the theory entirly, but it's moved on since I taught it, need to read the documentation, should have a chance soon, but tonight, i'm tired and i realise this will need me to rewrite the generator, and possibly the model builder.

**Today's Problems**: 
*  TF errors
*  Energy

**Thoughts**: semi colons are nice, didn't have an issue with themt today, though i did when i first learned JS back in the day. all in all good fun. It's the end of another term at school, my energy levels are non-existant, but i started now concisously, holiday next week, loads of time to tinker!!

**Link(s) to work**
1. [JS day 2](https://github.com/mattb00ker/javascript-exercises/tree/main/02_repeatString)
2. []()
3. []()


### Day 1: March 27, Monday

**Today's Progress**: 

**Today's Problems**: 
*  
*  

**Thoughts**: 

**Link(s) to work**
1. []()
2. []()
3. []()