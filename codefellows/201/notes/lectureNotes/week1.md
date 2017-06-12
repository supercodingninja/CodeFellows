Here's what I learned, thus far...

  **Ref. Course Books:

    "HTML & CSS: Designing and Building Web Sites," by Jon Ducket
    "JavaScript & jQuery: Interactive Front-End Development," by Jon Ducket

                      - ISBN-13: 978-1118907443
                      - ISBN-10: 1118907442

            - ~/supercodingninja/HTML and CSS design and build websites.pdf
            - ~/supercodingninja/javascript.pdf

  The more simple you can keep your CSS, the better it is; and remember to Control Flow.**


Code 201: Day 1

Ref. Vids:
Introduction: Class Overview: https://www.youtube.com/watch?v=EvLg8JkbAk0&index=4&list=PLVngfM2hsbi92FDMqnMcZNBnMgvcIelPf
Canvas Overview to Terminal (Intro.): https://www.youtube.com/watch?v=kjIY0hwo9Ag&list=PLVngfM2hsbi92FDMqnMcZNBnMgvcIelPf&index=2
Terminal (Intro. Continued): https://www.youtube.com/watch?v=dzN0zMmpZro&list=PLVngfM2hsbi92FDMqnMcZNBnMgvcIelPf&index=3
Terminal (Customization, with EZPrompt):
EZPrompt: http://ezprompt.net/
https://www.youtube.com/watch?v=w-nZelNln4c&list=PLVngfM2hsbi92FDMqnMcZNBnMgvcIelPf&index=1

*Mindnote (program for mindmap).
*Do’t be discourage: your first draft is rarely good/perfect.
*BE ON THE 15 MINUTE RULE: if you’re stuck on something, find some help.
*EMBRACE THE FAILURES: THEY’RE MOMENTS THAT DEVELOP YOU

Short-Cut: Key Commands: separate notes:
- terminal customization ( app/ page: __ )

Touch: __

Atom: __

Git:
ex. GarageBand v.2.2.2 (commonly referred to as “Semantic Versioning”)
	a) the first number is the major version (breaking)
	b) second number minor version (non-breaking)
	c) last number refers to some kind of bug fixed

Git Process Image ( http://nvie.com/img/git-model@2x.png )

A. C. P. Process (Add Commit Push)

Lab: ref. https://www.youtube.com/watch?v=dzN0zMmpZro&list=PLVngfM2hsbi92FDMqnMcZNBnMgvcIelPf&index=3


Short-Cut: Key Commands:
**Mac Terminal Commands Ref. http://images.apple.com/server/docs/Command_Line.pdf ***

Mac: Use Command Key + ___
  PC: Ctrl Key + __

Key(s): Function

S: save

C: copy

v: paste

x: cut

Y: redo

Z: undo

A: select all

u: underline

B: bold

Shift + 4: select screenshot

Shift + 3: whole screen

Tab: application switch

T: new tab

/ : comment

F: find

G: find next

D:

Up and down arrow: code mover (Atom IDE)

+ : enlarge text (terminal)

-  : decrease text size (terminal)


Terminal

Cd: change directory

Lis: list

Pwd: present working directory

Cd .. : return to home directory

K: clears screen

Touch: __

Atom: __



Code 201: Day 2

YouTube Channel:
https://www.youtube.com/playlist?list=PLVngfM2hsbi92FDMqnMcZNBnMgvcIelPf

HTML Topics:
All websites have a structure, just like all newspapers do.

Objects-Daa-Nouns-Arrays [Order Collection]

Events-Actions-Verbs- Flow & Function

Document Object= The HTML doc is also a JS object.

HTML (structure)-CSS (Style, and Layout: two separate things)-JS (Behavoir-Functionality-Interaction)- they all interact with each other

When JS runs

[Fig. On HS] Model View Controller (MVC) Architecture: most prevalent these days.

Seperation of Concerns (S. O. C.):

Pseudo Code:
-declare a variable; ex.: theMan= ‘BrianA.’  “theMan" is the declaration; and “BrianA." Is what it is being assigned.
-assign the variable a value via prompt () statement
-display the value to the user w/ an alert ()
-left ourselves a record of user with a console.log ()

***Remember, when you write code, you’re writing it for other people.***
-always strive for consistency.
-always strive for structure.
-always strive clean and clarity.

I learn how to first:
1. Create local project
2. Write up w/ GitHub
3. Write Codes

 Then I also learned how to first:
1. Create project on Github
2. Clone it on laptop
3. Write code

Git vs. GitHub:
Git:
		a. Software on laptops to version control.

GitHub:
			a. Cloud storage


Code 201: Day 3

*****IT IS HIGHLY VITAL, TO BE EMPATHETIC TO THE END USER*****

***Learn that CODE REVIEW IS VITAL AND AWESOME***

"use strict" it will prevent you from using variables that are not declare (not a good idea to not to declare variables).  It is a best practice to utilize 'use strict';
      Not utilizing the 'use script'; declaration is an interview flag.

Never use " ... " in Javascript (JS): ALWAYS USE ' ... ' IN JS.

cmd functions Short-Cut Key/Concepts:

      1. place cursor on line, without highlighting; and you can press Control key + Command + and either the up or down arrow.
      2. you can select multiple lines; and do this.
      3. Comment/uncomment a large body of code, by Command key + /


***I need to be mindful of the Control Flow on my page***

Control is the way we manage how our JS is manage; and they way we operate how/when things are manage.  Flow charts can become very complicated; but DO NOT let become overcomplicated.

      ex. when you think of a box think of it as a single box, that can have multiple ways, that lead into a story line.

Allow your thinking about Control Flow to be very, simple and easy.
  **Side note: Switch Statements are used by beginner programmers- everything you can do with your switch statements can be told by and better with an if/else statement.**
    Types of Control Flow:

                            1. if/else
                            2. if {
                                  else if
                                  else if
                                  etc.
                                }
                            3. While Loop (DANGER OF INFINITE LOOPS)
                                  - a DO WHILE statement will always check the condition within the code block of a While Loop, once; and then, compare it to the function.
                            4. For Loop

***I need to learn how to effectively look up information: because NO ONE knows everything***
  - W3Schools (easier for new beginners able to look up, and understand: but not professional)
  - MND (ANSWERS MORE IN DEPTH, more dense, more professional)
  - StackOverFlow (Everybody always uses StackOverFlow; and it can be a good source, if used properly.  Always remember there are no answers on top, answers are rated ("up votes"); and make sure your question is not already answer.)

  **SIDE NOTE: It's better to be methodical and bright in your coding; rather than fast, with a lot of typos.  It's normal o be slow at at coding.  DON'T WORRY: you'll get faster he more you code, over time.**

***Reviewed: CSS book (pgs. 229-2)***

    **Side Note: keep pg. 238 in "HTML and CSS design and Build Websites," by Jon Ducket on the side: a good reference for selectors.**


Code 201: Day 4

CSS Layout
Do not under-estimated CSS Layout.  We can make in line text act like block; and we can make block elements act like block.

- Normal flow is what happen if you don't try to change anything.

- Relative will let you offset something from a normal row.

- Absolute just let's the user scrolls up and down the page.  Absolute positions itself to it's closest relative parent.

- Fixed positions

- Floating elements


JS Functions
The way we're going to use a function, is how we use a line of cold: so we don't have to write a whole line of code.
variables inside of the scope { } are called function scope (always declare your variables).

When declaring functions, think of the variable being the container you want to put something in.

 'use script' is a literal expression, used in JS apps 1.8.5+; which indicates that the code should be used in strict mode.


Code Day 5:
***Pow WoW!!!***
- you have to specialize in the role that you want to be in. You need to put in additional effort that you want to be in.  An interview is all about perspective: it's how the other person see who you are.  If they can't tell how good of a person, of who you are, it's your fault: you didn't show them.  Use perspective to your advantage.  The end goal is the singular goal: you want to go to that interview; and get them to say, "Yes."  I am imagine of things I would want to talk about; and so, in my case, I worked that interview backwards [30' ft view].  No one really agrees on how a resume should look like; so, how is your resume suppose to look like: you write your resume to get people to want to talk to you.  Try to address people's bias that they may have of you, ahead of time.  An interview needs to be a conversation: ask them about the team- you have to address these balances (their/your own biases, and showing them you care about the team).  It's hard to remember facts; but it's easier to remember stories.  Try to target your stories to things they care about.  It's your responsibility to drive the conversation, be specific in the story.  Learn how to white board, learn how to narearate, and learn how to ask them questions: interviewers are trying to see if you're the person they're looking for.  write tests on the white board: they'll see that you're the person that runs tests.  Make sure that you're learning.  If you feel like you messed up, go back and try to rebuild: because that's your one shot.  Write resumes.  Build apps, even if they suck: they want to see people that get things done.  You want to get to a "Yes" as quickly as possible with the resume.  Test your stuff in production: if you don't get an answer, you may just need to rewrite your resume.
  -how do you cram 4years into 4 months:
      - look at cs programs and learn the topics they go over it.
      -education is great; but experiences sates how you apply what you know.  Build real websites, and how did you face them; and even if you mess up, write down what you learn from them.  Have a laundry lists of completed projects.  You be surprise, people just want people to solve their problems.  Everyone is just building something that solves real life problems.  Go to meet ups; and get referrals.  You got address the biases.  Show them commonalities.  Don't let age stop you.

***study touch***
- touch creates files (i.e. index.html, style.css, app.js)
