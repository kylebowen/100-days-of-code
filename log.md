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
