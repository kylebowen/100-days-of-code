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

### Day X: [Month] XX, 2017

**Today's Progress:**

**Thoughts:**

**Link to work:** []()
