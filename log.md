# 100 Days Of Code - Log

### Day 1: April 26, 2018

**Today's Progress**: 

- Started the 100 Days of Code in order to track my progress with completing a long time project: ZOGG.
- I am using this App for many years to help me with grading students group work during a course. So it may be considerd 'production ready'. However, there are some mandatory features missing in order to be used by someone else.
    - Installation procedure.
    - Most administration features.

Thus I started working on the adminstration...

**Thoughts:**

- The DB model needs improvements, should I correct it and restart most coding ? Or should I just keep that for later because 'it just works' ?
- I don't like the user interface even if I made it. It needs improvements too but I will focus first on features.

**Link to work:** [ZOGG: On Line Grading App](https://github.com/marcyves/ZOGG)

### Day 2: April 27, 2018

**Today's Progress**: 

- Looked into GitHub features to track my progresses. Created a project, wiki, issues. I still need to move the todo into issues.
- Administration now allows to create schools, programs and courses. Update and delete will follow soon.

**Thoughts:**

- The user interface of the new admin page needs (lots of) improvements too but I will focus first on features.

### Day 3: April 28, 2018

**Today's Progress**: 

- Administration now allows to delete schools, programs and courses. Update postponed... 

**Thoughts:**

- I'd like to have a clean install in order to prepare a demo website.

### Day 4: April 30, 2018

**Today's Progress**: 

- Preparing for installation procedure
- Created install folder with SQL to create and initialize tables
- Basic process described in the Wiki
- Prepared demo website at http://zogg.xdm-consulting.fr 
- Identified a lot of bugs in fresh install, I need to identify and list them

**Thoughts:**

I am amazed how much progress I could make on this project in a few days!

### Day 5: May 2, 2018

**Today's Progress**: 

- Administration improvements, mainly for the presentation. 

**Thoughts:**

- The demo site is very helpful to test different situations. It's more a test site than a demo one, my only constraint is to check I did not break anything before I stop working on it.

### Day 6: May 3, 2018

**Today's Progress**: 

- Small Administration improvements, creation of the assignment menu. 

**Thoughts:**

- Busy day. Making many progresses on this project, however I need to go back to normal life

### Day 7: May 5, 2018

**Today's Progress**: 

- Assignment menu and management quite working now. Creation and List, I need to improve the UI (again) and add a discard button and I will consider that enough for now.

**Thoughts:**
- I realized 'UserCake' is now called 'USerSpice', that I am stuck with version 2 and the current version is now 4. To make it short, I need to upgrade that!

### Day 8: May 7, 2018

**Today's Progress**: 

- Assignment menu and management working for professor and admin.
- admin can manage all (creation and delete)
- professor can manage only those for their courses

I created a new table to record which courses are attached to which professor, so now I need to propagate the usage of it to all the functions. Not urgent, I am actually the only user!

### Day 9: May 8, 2018

**Today's Progress**: 

- admin can update courses
- Admin and professor can update assignments

### Day 10: May 9, 2018

**Today's Progress**: 

- Vanilla Bootstrap theme creation
- Personalization of the theme (theme.php and style.php)

Some theme related stuff is in my_functions.php, I have to sort this out and move everything design related to theme.php

### Day 11: May 10, 2018

**Today's Progress**: 
No coding today. Reading bootstrap documentation in order to do it right from the begining

### Day 12: May 11, 2018

**Today's Progress**: 
Created new theme from StartBootstrap 
Modified theme.php and my_functions.php to move all design stuff to theme.php
Adapted, modified, updated everything and I have now a much better looking application

**Thoughts:**
Thank you BootStrap !
I made a mistake in the commit to GitHub and labeled it DAY 11 instead of 12. Just because I was looking to the last commit and forgot I did not code yesterday.

### Day 13: May 12, 2018
Upgraded FontAwesome from version 4 to 5 in order to get more icons.
Replaced some pictures with FA icons.
Improvements to startbootstrap theme.

### Day 14: May 13, 2018
Clean up login page
Learned to place sticky bootstrap footer at bottom of page

### Day 15: May 19, 2018
Better column positioning, removed large left margin.
Made a 1-click grading page. I used a PHP Array in the grading FORM in order to put only 1 button to submit the whole stuff instead of one button per team. Small change but huge usability improvement.

### Day 16: May 20, 2018
I changed to another project, using Python.
Now preparing small development Python projects in order to teach how to code.
I already have Tic Tac Toe covering procedural and OOP. I need to make a PyGame version.
I restared from scratch the farm project to make it more ambitious.
I am thinking about hosting those on GitHub, created a repository https://github.com/marcyves/Python-Pratique

### Day 17: May 22, 2018
farm simulation quite working

### Day 18: May 27, 2018
farm simulation working fine in 2 versions : procedural and OOP

### Day 19: May 22, 2018
Learned how to use Flask with Heroku to set up the farm simulation online

### Day 20: May 31, 2018
Completed Heroku setup, I need to move the farm code there now

### Day 21: June 2, 2018
Learned Selenium and BeautifulSoup to automate web testing and implement some Web Scrapping

**Thoughts:**
Many things to do to complete this Python thing.
 - update https://github.com/marcyves/Python-Pratique with the code I have done
 - complete the Heroku developement
 - create a script to update automatically Twitter (and this page?) every #100DaysOfCode

