# 100 Days Of Code - Log

### Day 0: January 3, 2017

**Today's Progress:** Finished the toy_app from Michael Hartl's Ruby on Rails Tutorial.

**Thoughts:** Feels good to have started. Feels good to have _finished_ something- even if it's just a super small 'toy_app'. I know the '_rules_' say to avoid tutorials, but I'm ok with starting where I am. I have some ideas for projects to move on to once I finish working through the full tutorial.

**Link to work:** [Toy App](https://obscure-peak-37908.herokuapp.com/)

### Day 1: January 4, 2017

**Today's Progress:** Started the sample_app from Michael Hartl's Ruby on Rails Tutorial. Got it installed locally, pushed to Github, and deployed to Heroku. I mean, it doesn't _do_ anything yet, but that will come.

**Thoughts:** Spent most of my time tracking down a bug that was stopping me from doing a `gem install` to get started. Turned out to be something from the interplay between Homebrew, RVM, and OpenSSL. Had to `brew uninstall --force --ignore-dependencies openssl` and then reinstall to get it working again. Felt a little bad spending most of my time debugging, but I guess that's just the way it goes sometimes.

**Link to work:** [Sample App Repo](https://github.com/kylebowen/sample_app)

### Day 2: January 5, 2017

**Today's Progress:** Added a new branch in git with a few static pages for the sample_app. Started playing with erb and TDD.

**Thoughts:** Went longer than my standard hour today because I had some unexpected free time. Learning to decipher the Rails error messages while TDDing. Helps to keep the application flow in mind as I'm working. Found myself getting ahead when making changes to get the tests to pass- I'd edit the controller before adding a route and then the test would still fail. Then I'd have to go back and undo my changes to the controller before getting the test to pass so that I'd be able to see the right error message once I added the right route. Possibly overkill, but the discipline helps me learn faster in the long run.

**Link to work:** [Sample App Repo](https://github.com/kylebowen/sample_app)

### Day 3: January 6, 2017

**Today's Progress:** Finished up the branch with a few static pages. Set up Guard to help with automatic testing.

**Thoughts:** Spent most of my time working through Chapter 4 of the Ruby on Rails Tutorial which was looking at core Ruby functionality. Mostly basic review that didn't get committed to the app, but I did it anyway to develop more muscle-memory in my fingers by actually typing out all the exercises in the Rails Console. Frustrating to not get more done, but I'll be able to make more progress over the weekend.

**Link to work:** [Sample App Repo](https://github.com/kylebowen/sample_app/commits/master)

### Day 4: January 7, 2017

**Today's Progress:** Added styling to sample_app via Bootstrap and Sass. Added a Header and Footer using Partials. Started using Named Routes and set up my first Integration test.

**Thoughts:** Tired. Busy day, so I didn't start until 11:30pm. Got in the zone and kept going until 1:30am. Going to regret that tomorrow... (today?)

**Link to work:** [Sample App (today's commit)](https://github.com/kylebowen/sample_app/commit/df6787bb5cd2e1313be296ae368e3409660fc3a3)

### Day 5: January 8, 2017

**Today's Progress:** Created a User model and test-drove addition of data validations on User.

**Thoughts:** Really looking forward to finishing this tutorial in a week or two and starting on my own projects. Feels like I'm going really slow with all the reading necessary to follow the tutorial, but I realize I'm probably going faster than I think. Still learning a bunch by going through the process.

**Link to work:** [Sample App (today's commit)](https://github.com/kylebowen/sample_app/commit/9a2480f64711ea1658a8dcb778b9ff6e95bd2bb6)

### Day 6: January 9, 2017

**Today's Progress:** Added a basic User page with Gravatar image integration. Added secure passwords to users hashed through bcrypt.

**Thoughts:** It's crazy the stuff that Rails includes off the bat. Secure passwords and stuff. Got in all my coding on the train today. Progress still feels slow and doesn't seem very hard. Tutorial said it would be ramping up in difficulty very soon, so we'll see how it goes over the next few days.

**Link to work:** [Sample App (commits overview)](https://github.com/kylebowen/sample_app/commits/sign-up)

### Day 7: January 10, 2017

**Today's Progress:** Finished adding User signup functionality. Configured sample_app to use SSL and Puma webserver in production on Heroku.

**Thoughts:** Picked up some speed today. Found some success in trying to get ahead of the tutorial and then using it to check my work. There were times today where I disagreed with some of the testing recommendations. The author said that testing for a 'success' flash message on signup was too brittle and to just test to make sure the flash message wasn't empty, but I was able to replicate a situation where the test passed while there was no flash message. I set up the tests how I want and figure I'll learn a good lesson if/when I run into pain from my 'brittle' tests. =)

**Link to work:** [Finish user signup](https://github.com/kylebowen/sample_app/commit/c35726bea06b4fe00b2a4b08e77cbae789a62160), [Use SSL and Puma webserver in production](https://github.com/kylebowen/sample_app/commit/b3abb23ab3ca4e69f5d0cc640492726294443cc5)

### Day 8: January 11, 2017

**Today's Progress:** Today I implemented a basic login system. It allows users who have signed up to actually log in and out of the app! Plus, the nav-bar links change depending on your logged-in status.

**Thoughts:** Nothing profound today. Finishing earlier because I've been lacking in sleep lately. Still exciting to be making visible progress. Looking forward to my own projects once this is finished. I've got a few in mind that I'm excited to work on.

**Link to work:** [Sample_app basic login](https://github.com/kylebowen/sample_app/commit/c61c78b9370527f87c13f324bbdb10435af7695f)

### Day 9: January 12, 2017

**Today's Progress:** Today I upgraded the login system to use cookies and add an optional 'remember me' checkbox.

**Thoughts:** I'm starting to feel the increase in difficulty as the tutorial progresses. Definitely had to read a few sections multiple times to understand what was going on or why we were doing something. I'd heard that this tutorial was great because it used testing so much and was a great introduction to TDD. I'm finding that we don't test nearly as much as I'd prefer. I may have been spoiled by exercism.io with regard to test-driving my development.

**Link to work:** [Sample_app advanced login](https://github.com/kylebowen/sample_app/commit/c645cfa8b0436e66ec41c1c1090ba420d1fa781e)

### Day 10: January 13, 2017

**Today's Progress:** Factored out a form partial for the signup and settings pages.

**Thoughts:** We went to visit with some of my wife's family today, so it was tough to squeeze in my time. I tried working there after dinner, but couldn't accomplish much. Finished up my coding time when we got home. Excited for tomorrow's when I'll actually make the user edit form functional!

**Link to work:** [Sample_app form partial refactoring](https://github.com/kylebowen/sample_app/commit/ef98b772b20f554c46fd2c8e6fd6f4dfb80cf521)

### Day 11: January 14, 2017

**Today's Progress:** Added authorization checks for editing and updating users.

**Thoughts:** Feeling a little frustrated today. Had planned to spend several hours working, but other obligations came up to fill the day. Still managed to get in my time, so that's a plus. The tutorial I'm following does a good job of walking you through what you need to do, but it's lacking in the explanation for _why_ that's what you need to do. Definitely feeling like I'm in over my head, but keep going...

**Link to work:** [Sample_app authorization checks](https://github.com/kylebowen/sample_app/commit/64e649fe7bb3ad193a26c2249f0b0cec27d5cc37)

### Day 12: January 15, 2017

**Today's Progress:** Added a Users index with pagination. Using the Faker and Will_Paginate gems to generate data.

**Thoughts:** Lazy day of coding while watching my wife play 'A Link to the Past' on Wii. Yay family bonding! =)

**Link to work:** [Sample_app adding Users index with pagination](https://github.com/kylebowen/sample_app/commit/e2aa58d21ceabd0202a0dd94f34954af112aaf68)

### Day 13: January 16, 2017

**Today's Progress:** Added admins with the ability to delete other users.

**Thoughts:** Just continuing to work my way through. Tired tonight. First night I've been ready to move on at the 1-hour mark. Two weeks: done!

**Link to work:** [Sample_app adding admins with ability to destroy users](https://github.com/kylebowen/sample_app/commit/c396382f3db525d1cfb2fedd580d8006a8de81a9)

### Day 14: January 17, 2017

**Today's Progress:** Added account activations for users. Users are now sent an email upon signup with a link they must click to activate their account. Emails sent through a SendGrid addon from Heroku.

**Thoughts:** Plugging away. Feel like I'm riding the line of 'stuff that makes sense'. From what I hear, that's a pretty good place to be. =) I kinda think my git commits are too spread-out, but including a link to my day's work here incentivizes me to just do one big commit for the day.

**Link to work:** [Sample_app account activations 1](https://github.com/kylebowen/sample_app/commit/d61954be2b966d0c67f5186cd322cee3cd3e605c) [Sample_app account activations 2](https://github.com/kylebowen/sample_app/commit/768ce02232e99a369115b68ca576e615d3c823b5)

### Day 15: January 18, 2017

**Today's Progress:** Added the ability to do password resets.

**Thoughts:** Still a bit confused on why sometimes I used 'password_reset_url' and other times used 'password_resets_url'. I think it has something to do with which controller action it was prefixed by, but not totally sure? Also, my hands are tired because I'm not used to typing that much. I type out all the code instead of cutting-and-pasting to build up muscle-memory. I'm still getting use to using so many [ { = } ] _ +

**Link to work:** [Sample_app adding password resets](https://github.com/kylebowen/sample_app/commit/c53279ccf7396e8ee71d36e545a81483fcd2e07d)

### Day 16: January 19, 2017

**Today's Progress:** Added microposts. Which are like Tweets, except without the copyright infringement.

**Thoughts:** Got my time in today. Had a bunch going on so I don't feel like I was as productive as I have been, but some days are like that.

**Link to work:** [Sample_app adding microposts](https://github.com/kylebowen/sample_app/commit/e4af884e287f5fc373252af42b06ada6e85c9de0)

### Day 17: January 20, 2017

**Today's Progress:** Added the ability for users to create and destroy their microposts. Also added a 'feed' of microposts to the Home and User pages.

**Thoughts:** Super busy day at work with the Inauguration today. Felt really tired and thought I'd scrape in my hour and take an easy day. Alas, my brain didn't go along with that plan. Got a second wind after dinner and worked for a few hours. Ran into some serious troubleshooting where the Home page went blank suddenly and it took almost an hour to realize I'd just forgotten 2 'equal-signs' in the .erb template. Don't ever look down on people for taking a long time to notice typo's, Future Kyle!

**Link to work:** [Sample_app micropost feed/create/delete](https://github.com/kylebowen/sample_app/commit/0701c4739df6645829b7411cefc0b8902b7f95f5)

### Day 18: January 21, 2017

**Today's Progress:** Added image uploading option to microposts. Set up an AWS account with an S3 bucket.

**Thoughts:** So much troubleshooting! So exhausted. I finally got image uploading to work in production, but it involved a good bit of Google-Fu. AWS is not easy to set up and the access management system is not what I'd call 'beginner-friendly'. Glad to be done. Hoping to finish the app tomorrow, but we'll see how it goes.

**Link to work:** [Sample_app image uploading](https://github.com/kylebowen/sample_app/commit/a5563171d0efb0d154c3316b2c4cc24f19d6f2a2)

### Day 19: January 22, 2017

**Today's Progress:** Added Relationships so that Users can follow other Users.

**Thoughts:** Busy day. Managed to squeeze in my hour. Wanted to put in more time and finish this today, but life did not work out that way. Keeping the streak alive...

**Link to work:** [Sample_app add Relationships](https://github.com/kylebowen/sample_app/commit/0df14cf07bf8e147246c9116dba1063217539901)

### Day 20: January 23, 2017

**Today's Progress:** Added a (non-functional) 'follow/unfollow' button to user profiles. Added pages to view followers/following.

**Thoughts:** Plugging away. Been at it for 3 weeks now. Only 15-ish to go! It's actually really exciting when I put it that way. I can hardly wait to see what I can get built in that time. Only a couple days of work left on this tutorial/project. Time to really pick what to work on next!

**Link to work:** [Sample_app following/followers pages](https://github.com/kylebowen/sample_app/commit/dd3a02b0430aef2018dd9e4d90f1528ed09a33fe)

### Day 21: January 24, 2017

**Today's Progress:** Added functionality to the 'follow/unfollow' button and a 'feed' of posts on the Home page. Finished the Rails Tutorial!

**Thoughts:** Finished the Rails Tutorial tonight. Snuck up on me there! Got a new project set up to start on tomorrow. Still a lot that I'm hazy on when it comes to building apps, but I'll just keep on working and learning. =) If I can keep up this rate, I'll have 4 more apps done by the end of the 100 Days. I'll be happy with just 1 or 2 though- we'll see how complex they get. Also, I'm going to need to start getting into Javascript...

**Link to work:** [Sample_app Code](https://github.com/kylebowen/sample_app) [Sample_app Live Site](https://dry-sands-22040.herokuapp.com/)

### Day 22: January 25, 2017

**Today's Progress:** Started work on my next project. It's going to be an app to help when my team plays games during our meetings at work. Today I initialized up a new Rails app, started sketching a basic wireframe, and put together some User Stories on Trello.

**Thoughts:** A fresh start is nice. I realize that a good chunk of what this app will entail is much the same as the Rails Tutorial app that I just finished, so I'll likely still refer to it now and then if I have questions. Will continue to add new sources for reference as well. Got some good help from the official Rails Guides on Routing syntax as I started back up.

**Link to work:** [Team Awesome Gaming app](https://github.com/kylebowen/team-awesome-gaming)

### Day 23: January 26, 2017

**Today's Progress:** Added a few more User Stories to the backlog. Started creating a few skeleton pages in the app- mostly just site layout stuff.

**Thoughts:** Still trying to wrap my head around how to structure some of these ideas. Not sure what should be its own model and what should just be attributes. I'll figure it out... eventually...

**Link to work:** [Team Awesome Games - Update site layout](https://github.com/kylebowen/team-awesome-gaming/commit/e5b2b5eb0d51ced76afaab175dac90a593e0ea5c)

### Day 24: January 27, 2017

**Today's Progress:** Switched database from SQLite3 to Postgresql in development. Added placeholder-ish text to the Static pages. Added a User model.

**Thoughts:** Decided that instead of going crazy trying to plan out all of the everything that I would just do the things I know for sure need to be done until it becomes obvious what should be the next thing to work on. Is that what 'Agile' is? "I'm not sure how this is all going to work, but I know that _this_ is missing..."

**Link to work:** [Team Awesome Games](https://teamawesomegames.herokuapp.com/) - [Database update](https://github.com/kylebowen/team-awesome-gaming/commit/7d3bbf9a42e27aaa16fcb572e74138603d34550c) & [Placeholder text](https://github.com/kylebowen/team-awesome-gaming/commit/b8c19f89dde183306b1788aa56072eb2961c848f)

### Day 'Pass': January 28, 2017

**Today's Progress:** N/A

**Thoughts:** Super busy day with Life. My brain was fried by the time I sat down to do my coding. Decided to take a 'Pass' for the day.

**Link to work:** N/A

### Day 25: January 29, 2017

**Today's Progress:** Added a basic User model. Finished sign-ups. Added SSL and tweaked Puma settings.

**Thoughts:** Stayed up way too late and got really grumpy. Need to start pacing myself.

**Link to work:** [Team](https://github.com/kylebowen/team-awesome-gaming/commit/9278fcf599cb5d4786f9dfa9c38b964650c317f3) [Awesome](https://github.com/kylebowen/team-awesome-gaming/commit/3ad2d37e5331b580ae4d8fa9b140900d41a7a5a0) [Games](https://github.com/kylebowen/team-awesome-gaming/commit/e09e770445e66e166fa80044ed4ac44f361959e7)

### Day 26: January 30, 2017

**Today's Progress:** Added a user login page and additional tests.

**Thoughts:** Trying to test-drive this as much as possible. Didn't feel much like coding when I started, but really got in the groove after a while. Had a hard time stopping =) I decided to leave a failing test so that I know right where to start tomorrow.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/b758eda0728859917594111cbcd6d2cc198aff13)

### Day 27: January 31, 2017

**Today's Progress:** Added the User login logic with sessions.

**Thoughts:** Still test-driving. Feels very satisfying to work through the problem on my own until I get it figured out. Had to refer out to documentation several times today, but managed to make progress by dealing with one problem at a time.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/dc5e7712b8c1d1f31f1035edaa811144126f9b11)

### Day 28: February 1, 2017

**Today's Progress:** Users can now log in and out.

**Thoughts:** Still test-driving. I had included the 'SessionHelper' in the 'TestHelper' even though the Tutorial I used before didn't do that, because I couldn't think of a good reason not to. Today, I found that good reason. Testing a user's logged-out state wasn't passing even though the test looked right and manual testing verified. Turns out it was because I was using the 'real' logged_out? check from SessionHelper instead of the custom version the Tutorial used in TestHelper. Not quite sure what makes the difference, but I'm sure I'll find out sooner or later.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/239db6fc404f716065ed475b8ccc9d2f1f0291c9)

### Day 29: February 2, 2017

**Today's Progress:** Worked on adding a cookie-based advanced login system, but didn't make much progress.

**Thoughts:** Still attempting to test-drive, but I may be hitting the limits of either my testing knowledge or my Rails knowledge or both. I can follow the reasoning in the Tutorial on how to get there, but I can't seem to figure out how to test my way to the same solution. I'll give it one more day before I just go ahead and write the code.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/b16d7f4ffe9cbf204297ef365fbe1b5ead8470e9)

### Day 30: February 3, 2017

**Today's Progress:** Finished adding the advanced login system.

**Thoughts:** Finally found the error near the end of my session that was causing so many issues the last couple days. I was trying to set `session[:remember_me]` when I should have been setting `params[:session][:remember_me]`. Once I made the change, everything went smoothly. I feel like I have an inadequate understanding of `sessions` and `params` and how they work with all the 'Rails magic'. So glad for all this time coding and working on projects for helping me to discover what I need to understand better!

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/a7389961c5d1c61a4dfb1e47eb461bf4f82c6bfd)

### Day 31: February 4, 2017

**Today's Progress:** Worked on the User Update page. Added tests for a few things.

**Thoughts:** Starting to get a little stressed about adding the new functionality arounds Games and Scorekeeping. Hoping to start on that tomorrow and just start hacking away at the problem. I'm just not sure where to start with the structure. Maybe, instead of waiting until I have it all figured out, I can just start doing stuff and then refactor! That's weird and scary, but probably the right move?

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/796303132de76eb1377e6b1108ad5d26fdb6fa18)

### Day 32: February 5, 2017

**Today's Progress:** Finished User update page. Started working on authorization and access control.

**Thoughts:** No profound thoughts today. Just plugging away at this project. Going to try to knock out a ton tomorrow, but we'll see what life has in store.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/3be1040cac8a1f6219c1fba4edd45ff261b0f74e)

### Day 33: February 6, 2017

**Today's Progress:** Finished access control for update, index, and delete actions. Also added friendly-forwarding.

**Thoughts:** Done with modifications to User model for now. Tomorrow begins the journey into the unknowns of keeping score and working game logic.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/39dbf4b69962ec73dd9c87eb5e9df949661fe9e6)

### Day 34: February 7, 2017

**Today's Progress:** Added a basic scoreboard for a single user.

**Thoughts:** Well, I did my first feature implementation without reference material guiding me. Feels _super_ hacked-together, but I got it working for a single user. We'll see how much it has to change in order to manage multiple users at once on the same screen. Feels good to have figured it out and got it working on my own, though.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/5a97098f46d652ba01ed7facede73260f6bde086)

### Day 35: February 8, 2017

**Today's Progress:** Added tests for the layout of the single-user scoreboard.

**Thoughts:** Don't feel like I accomplished much today, but I do have a better understanding of how some of the tests work. So _that's_ something.

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/d03b776da79694b143bf76506d45102d4e034f3b)

### Day 36: February 9, 2017

**Today's Progress:** No new code. =( Spent my time brainstorming and planning how in the world to make multiplayer work. Think I almost have it...

**Thoughts:** Frustrating day. Got really sucked into figuring out some problems at work and used up most of my productive brain. Hope tomorrow is better spent.

**Link to work:** N/A

### Day 37: February 10, 2017

**Today's Progress:** Started adding a new model to be able to persist GameplaySessions so that they can be shared with other players.

**Thoughts:** Hoping this idea works. Not convinced it will. Super frustrated and demotivated. Logically, I know I'll get past this, but it's tough going for now...

**Link to work:** [Team Awesome Games](https://github.com/kylebowen/team-awesome-gaming/commit/795738bcbb41a7a0b3530efff160f1cbb1631b40)
