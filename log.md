# 100 Days Of Code - Log


### Day 1: August 19, Monday

**Today's Progress**: I worked a little on the createElement function of avocadohelpers

**Thoughts** I am currently struggling with how to type one of the parameters for the function. I think there might be a way to do this which is beyond my current understanding so tomorrow I will attempt switching tactics.

**Link(s) to work**
1. [avocadohelpers repo](https://www.github.com/theAvocadoCoder/avocadohelpers)


### Day 2: August 20, Tuesday

**Today's Progress**: 
1. I figured out how to type the parameter I had trouble with. I started working on the function. I learned a bit more about Typescript in the process.
2. I had an interview with a Creator Sponsor User for Avi. It was insightful: I learned about the post-production process and I realized there is another user to pay attention to. Curators. Similar to the Creator User in that they also make content, but are more closely related to the Consumer User in that they consume more content to create.

**Thoughts**:
1. I am observing that a good deal of my time is being spent researching things and figuring things out. I am feeling more confident about my process as I go so that's a good thing.
2. I will need to find a TypeScript roadmap or curriculum so I can have some guidance as I peruse the docs.

**Link(s) to work**
1. [avocadohelpers repo - commits for the day](https://github.com/theAvocadoCoder/avocadohelpers/commits/dom/?since=2024-08-21&until=2024-08-21)


### Day 3: August 21, Wednesday

**Today's Progress**:
1. I worked on my DOM utility functions.
2. The createElement function's option parameter has a property, attributes. The type of this attribute was pretty convoluted so I refactored to simplify it. I finished implementing the createElement function that creates a new element with attributes, styles and children.
3. I modified the style function so that rather than adding the styles to the element's inline styles, it accepts a stylesheet or creates a new one if absent. If no stylesheet is passed, it creates a style element and returns the element's generated id.

**Links(s) to work**
1. [avocadohelpers repo - commits for the day](https://github.com/theAvocadoCoder/avocadohelpers/commits/dom/?since=2024-08-22&until=2024-08-22)


### Day 4: August 22, Thursday

**Today's Progress**:
1. I solved some HackerRank problems.
2. I worked on a string case converter function for my helper functions package.

**Link(s) to work**:
1. [avocadohelpers repo - commits for the day](https://github.com/theAvocadoCoder/avocadohelpers/commits/string?since=2024-08-23&until=2024-08-23)


### Day 5: August 23, Friday

**Today's Progress**:
1. I fixed the bugs in my stringConverter function and expanded its functionality
2. I solved the FCC palindrome project

**Link(s) to work**: 
1. [avocadohelpers repo - commits for the day](https://github.com/theAvocadoCoder/avocadohelpers/commits/string?since=2024-08-23&until=2024-08-23)


### Day 6: August 24, Saturday

**Today's Progress**:
1. I solved the FCC roman numeral converter project


### Day 7: August 25th, Sunday

**Today's Progress**:
1. I started working on the daily bingo app. So far I'm just doing basic config stuff.

**Thoughts**:
1. Haven't touched Vue in a while and I've never used Nuxt so I'm enjoying the learning as I go. This feels like I will be out of my comfort zone for most of the project, which is fitting since it is supposed to be a challenge.


### Day 8: August 26th, Monday

**Today's Progress**:
1. I started working on the bingo card today. I've added functionality for marking a cell. I'll work on verifying a win for rows, columns, diagonals, and bingo.

**Thoughts**:
1. Using Nuxt is not so different from using Vie. I suspect the differences will become more evident when I have to do more complicated things.

**Link(s) to work**:
1. [daily-bingo repo - commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-08-27&until=2024-08-27)


### Day 9: August 27th, Tuesday

**Today's Progress**:
1. I changed the cell highlighter color and started defining win styles for the bingo card.


### Day 10: August 28th, Wednesday

**Today's Progress**:
1. I defined the basic win styles for the bingo card: rows, columns, corners, diagonals, and blackout.
2. Added an unselect feature in case of accidental markings.

**Link(s) to work**:
1. [daily-bingo repo - commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-08-29&until=2024-08-29)


### Day 11: August 29th, Thursday

**Today's Progress**:
1. I connected to a mongoDB cluster and defined the schema for the Bingo card.
2. I modified the bingo card to just be an array of cells rather than a 2d array. My rationale for this is that since the cell object already contains information about what row and column it belongs to, there's no need to group cells into rows.
3. I added a feature to reset the bingo card.

**Thoughts**:
1. Now that I'm doing more unfamiliar work, I ironically feel more at peace. I think this is the high I was chasing when I first started learning to code; staying up late, trying to fix a bug, hopping from article to documentation to StackOverflow, trying to understand concepts that dance just a little out of reach the longer you think about them. I wasn't expecting this project to be the one that gave me this feeling again, but I'm grateful all the same.
2. I started this challenge because I wanted to build projects that reflect my current skillset. Somewhere along my journey, I got discouraged. Maybe it was the constant struggle of trying to find my feet in a profession I felt grossly unqualified to be in. Maybe it was the constant stream of rejection emails reinforcing the imposter syndrome we all wrestle with. Maybe it was just life, life-ing.
3. Whatever it was, I'd lost that zest I had in the beginning. But I'm back now. I intentionally started this project with nothing more than a vague idea of my MVP. I tend to get lost in the weeds of perfectionism and I end up delaying things I could have started ages ago.
4. The app doesn't look like much yet but I'm proud of the progress I'm making.

**Link(s) to work**:
1. [MongoDB setup](https://github.com/theAvocadoCoder/daily-bingo/commit/b48ad3ab69a21e8738f886e0bcd38a733d11e0c2)
2. [Bingo Card structure modifications](https://github.com/theAvocadoCoder/daily-bingo/commit/5ae45f879c693a9cc26136b2dfaa1f7187536cf2)
3. [Reset feature](https://github.com/theAvocadoCoder/daily-bingo/commit/2f7ca7db4bbf4ab466b12aca394ef27fc06704fa)


### Day 12: August 30th, Friday

**Today's Progress**:
1. I setup Vuetify and started implementing the bottom navigation for the webapp
2. I started refactoring the bingo card to use a canvas instead of dynamically rendered divs. I think this will make it easier to convert the cards to downloadable images later on.

**Thoughts**:
1. I have a feeling marking a cell will be a lot harder to implement using canvas.
2. I am learning a lot about how Nuxt works. I think I'll get started on setting up unit tests tomorrow. I'm not familiar with testing but I know enough to know it's better to get started at the start of the project rather than later.

**Link(s) to work**:
1. [Vuetify refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/e4b4f9befb63b664183804c577cc2de8563ece62)
2. [Canvas refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/fec1537567db2da79ad71169a96d930b6a7d6bff)


### Day 13: August 31st, Saturday

**Today's Progress**:
1. I implemented feedback when a cell is marked. Essentially spent the whole day trying to figure out how to make changes to the canvas without having to re-render the whole thing. Did not make any headway on that front, so re-rendering it is.

**Thoughts**:
1. As it turns out, marking the cell isn't the part I have issues with. I can't figure out how to implement the highlight for some reason. I'll keep at it cause I know it's possible.

**Link(s) to work**:
1. [Feedback implementation](https://github.com/theAvocadoCoder/daily-bingo/commit/378d048af6f889ebbce85b218c2dda0566ad3100)


### Day 14: September 1st, Sunday

**Today's Progress**:
1. I completed the refactoring to render the bingo card using HTML canvas. 
2. I tweaked the controls to accommodate the canvas setup, so cells get registered and wins get updated properly.
3. I started working on a feature that updates the cell register based on which cells are marked during the first render.

**Thoughts**:
1. For the cell register, I might need to change my markCell function. Maybe break it up into smaller pieces. (I ran into an infinite loop problem trying to call it from the drawCell function. I will also need to create state to track cell registration. So when the card is fetched, the document returned will also contain cell registration information.
2. I'm shelving the highlight feature for now. I don't know if the multiple re-renders will affect performance and I'm spending too much time on a non-essential feature.

**Link(s) to work**:
1. [Canvas Refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/ebde9a4e909c71c1998ead8e5b364c50b345e5f4)


### Day 15: September 2nd, Monday

**Today's Progress**:
1. I fixed the infinite loop bug and completed the feature for registering cells during the first render. This way, progress made on a card will be trackable.
2. I added a confirmation dialog to the reset button.
3. I added linear progress bars for the win cases.

**Thoughts**:
1. I went through the Vue documentation for a refresher on Vue directives, which was insightful.
2. I got to apply some Material Design UX writing best practices and that was cool. I may need to make some wireframes in Figma so I have something more concrete to follow as I develop the app.

**Link(s) to work**:
1. [Inf loop bug fix](https://github.com/theAvocadoCoder/daily-bingo/commit/d1afc673360559e6965164b4d698a4b7fc448635)
2. [First render cell registration](https://github.com/theAvocadoCoder/daily-bingo/commit/46c434a618ed3274c34dddcef24a72ecd9bb5ff8)
3. [Confirmation dialog](https://github.com/theAvocadoCoder/daily-bingo/commit/5ed96e6e3a6d0a0a10d04b1fd956e21859c6e57b)
4. [Linear progress bars](https://github.com/theAvocadoCoder/daily-bingo/commit/1bfb40341f44605e229d96136b94735e8d84e22b)


### Day 16: September 3rd, Tuesday

**Today's Progress**:
1. I went over MongoDB, Nuxt, and Nitro docs to get familiar with data modeling and setting up my server
2. I defined data models for a user, a bingo card, a cell, and a bingo group
3. I refactored my Mongodb setup to use the official Mongodb driver (rather than Mongoose) and moved my configuration into a MongoIO class to make it cleaner.
4. I defined the user API route and fetched the user's username to be displayed on the / route

**Thoughts**:
1. I'm definitely feeling a bit over my head here with the backend stuff, but it's also exciting to see the pieces fall into place.

**Link(s) to work**:
1. [Data models](https://github.com/theAvocadoCoder/daily-bingo/commit/8810f5e1db5ec6d49c6bc95e357b29829be2e85a)
2. [Mongo refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/b2f6e80ad34d87854ac89b514d7b63b029f2a081)
3. [User route](https://github.com/theAvocadoCoder/daily-bingo/commit/074a7a9ce7a2979ab518f7e73e607a6102702675)


### Day 17: September 4th, Wednesday

**Today's Progress**:
1. I worked some more on the APIs; learned more about how nitro handles routing, defined the /api/user/:id route and the /api/cards/:id route, and wrote the handlers for getting resources at those endpoints.
2. I made the bingo card a component rather than a page since it will be reused throughout the app.

**Thoughts**:
1. The app is really starting to come together in my head. I still haven't done wireframes, but I'm getting a better sense of what I want the app to look like as I go, and since I'm using Vuetify, it'll be easier to use Material Design when I eventually put things down in Figma.
2. I want to use OpenAPI's npm package so I can generate texts for the card. I'm really looking forward to the reading I'll do for that as I've never worked with AI before.

**Link(s) to work**:
1. API routes - [MongoIO methods](https://github.com/theAvocadoCoder/daily-bingo/commit/d4f264c79e0a20d4cc50ca9e27a6cf351172be85) and [Request handlers](https://github.com/theAvocadoCoder/daily-bingo/commit/352fa5c2bd2e572628e906b240c09b5cfee476c5)
2. Bingo card refactor - [Component refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/f4a9185769a1588172ee21bc668565dacd6bd7e3) and [Usage](https://github.com/theAvocadoCoder/daily-bingo/commit/d43b90b68f27ab561c80f2a13b01f5d63bd084cb)


### Day 18: September 5th, Thursday

**Today's Progress**:
1. I worked on a feature for generating the daily bingo card from a random selection of phrases.

**Thoughts**:
1. I spent the day going over Hugging Face' docs. I couldn't find any model that did what I was looking for out of the box, so I'm shelving the AI integration until I've figured that out. I instead used ChatGPT to generate a few hundred phrases that will serve as the pool for random selections.

**Link(s) to work**:
1. API route - [Mongo methods](https://github.com/theAvocadoCoder/daily-bingo/commit/738bae7ada54b2a9cdd8146ef31452568cf8b985) and [Request handlers](https://github.com/theAvocadoCoder/daily-bingo/commit/b729782051a81ef7d30da504ff2b1cd0133537a8)
3. Bingo card - [Usage](https://github.com/theAvocadoCoder/daily-bingo/commit/7428cdb4d009dc9a4550518d34758ce548ff4e8d)


### Day 19: September 6th, Friday

**Today's Progress**:
1. Much of what I did today was fix tiny bugs with large consequences 🥲
2. I also implemented persistent storage for the current user and for the daily bingo card.

**Thoughts**:
1. A good deal of the work I seem to be doing right now is reading docs and checking out responses on Stack Overflow. I'm not complaining though, I enjoy the reading.
2. Figuring out that (correctly) implementing persistent storage was the solution to a bug I had where duplicate API calls were creating unused bingo cards, and then figuring out how to properly implement persistent storage was fun. I kind of wish it had taken less than 3 hours though 😅

**Link(s) to work**:
1. [Daily Bingo commits (bug fixes et al)](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-07&until=2024-09-07)


### Day 20: September 7th, Saturday

**Today's Progress**:
1. Got started working on the wireframe for the daily bingo app
2. Worked on a bug that blurs the canvas on smaller screens. Haven't found a fix I like yet.


### Day 21: September 8th, Sunday

**Today's Progress**:
1. Made some progress with the wireframes for the daily bingo app; I now have the mobile screens for the home, cards, and groups pages.


### Day 22: September 9th, Monday

**Today's Progress**:
1. Refactored to use dynamically rendered divs again. No more blurry text on mobile screens.
2. Got started implementing the mobile designs.
3. Made some LF wireframes for the desktop views.

### Day 23: September 10th, Tuesday

**Today's Progress**:
1. Implemented layouts for desktop and mobile screens
2. Started working on integrating Tailwind into the project

**Thoughts**:
1. Integrating Tailwind and Vuetify is giving me more trouble than I initially anticipated. I need Tailwind's flexible utility classes but I need Vuetify's components. I want to disable Vuetify's utility classes so I don't have any clashes and also to reduce bloat. But I seem to be doing something wrong (I suspect this is because of my inexperience with Sass). I'll keep at it tomorrow and hopefully make headway then

**Link(s) to work**:
1. [Layouts](https://github.com/theAvocadoCoder/daily-bingo/commit/1a98d953ee564979ef56850d34806f0eb1f22a9e)


### Day 24: September 11th, Wednesday

**Today's Progress**:
1. Made HF wireframe for home desktop view
2. Disabled Vuetify utility classes and refactored to use Tailwind.

**Thoughts**:
1. The solution I found to disabling Vuetify's utility classes still requires a few extra tweaks here and there but it works. Ironically, the vuetify-nuxt-module documentation that I went over, like, a thousand times had the answer I was looking for. I find it interesting how the solutions to problems can be in plain sight yet out of reach due to inexperience or lack of knowledge.

**Link(s) to work**:
1. [Vuetify-Tailwind Refactor](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-12&until=2024-09-12)


### Day 25: September 12th, Thursday

**Today's Progress**:
1. Implemented better, but still temporary solution for disabling Vuetify utility classes (but not all other styles)
2. Started styling the home page.

**Thoughts**:
1. So, apparently, the fix I found yesterday disabled some Vuetify's styles being used by some vuetify components but not all of them. So I had this situation where some Vuetify styling lingered and made it hard for me to apply my own custom styles.
2. I found a few issues on the vuetify-next-module repo that helped with this temporary fix. I essentially just reverted the versions of the module (and also nuxt). It seems to be some sort of compatibility issue but idk for sure.

**Link(s) to work**:
1. The fix: [Reverting versions](https://github.com/theAvocadoCoder/daily-bingo/commit/ea736dcb0db1ad933306b8553769f32e5c09f823) and [Configuring custom sass](https://github.com/theAvocadoCoder/daily-bingo/commit/89261b1c41f5b0db2df9432fc9b7cdb30d7b2a72)
2. [Home styling so far](https://github.com/theAvocadoCoder/daily-bingo/commit/21d24f12a65a72e85951fc79806e79a0fb2a8280)


### Day 26: September 13th, Friday

**Today's Progress**:
1. Got in touch with one of the maintainers of the vuetify-nuxt-module and the latest release now has a fix. I updated my dependencies and everything works as it should now.
2. Mostly worked on one of the mentorHub UIs today. I set up the routes (they only display hello world for now), configured the store to get the data I need from the API, and set up Docker.

**Thoughts**:
1. I can tell there's a lot about Docker I don't get yet. But from what I do understand, the usefulness of it, especially in collaborative projects blows my mind every time. I've also noticed that the more Dockerfiles I write, the less alien the commands seem to me.

**Link(s) to work**: 
1. Daily Bingo: [solution to the sass problem](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-13&until=2024-09-13)
2. MentorHub: [basic set up](https://github.com/agile-learning-institute/mentorHub-partner-ui/commits/create-ui-issue%231/?since=2024-09-13&until=2024-09-13)


### Day 27: September 14th, Saturday

**Today's Progress**:
1. I built and tested the container for the mentorhub partner UI. I learned a bit about configuring a proxy on the dev server.
2. I finally finished styling the daily bingo home page (just the desktop view though).

**Thoughts**:
1. I seem to be battling with vuetify components. I suspect this is partly because I am trying to style them with Tailwind
2. I should read up on SSR so I can fully take advantage of Nuxt's features. Right now, I feel like I'm using a combat knife to whittle; it works, but it's pretty obvious it's meant to be doing something else.

**Link(s) to work**:
1. MentorHub: [partner-ui](https://github.com/agile-learning-institute/mentorHub-partner-ui/pull/3)
2. Daily Bingo: [Home page desktop view](https://github.com/theAvocadoCoder/daily-bingo/commit/92700c91df9c688c828f59d35890aa7f3732b9fa)


### Day 28: September 15th, Sunday

**Today's Progress**:
1. I learned a bit about SSR; this allowed me understand the hydration mismatch warning I've been getting in the console and refactor my code so my server and client are getting the same content.
2. I styled the mobile view for the bingo home page.

**Link(s) to work**:
1. [Daily Bingo dev site](https://dailybingo.netlify.app/) (I'm not able to fetch the bingo card in production yet, but I'll figure it out soon)
2. [Fix for Hydration Mismatch](https://github.com/theAvocadoCoder/daily-bingo/commit/d35352ea23cdd3463a9b2af54c3de2d15599e031)


### Day 29: September 16th, Monday

**Today's Progress**:
1. Watched a few videos on Nuxt and did some more reading; came to the conclusion that my app is not a good use case for SSR. (guess I'll have to find some other project to do that is)
2. Configured Nitro for Netlify properly and removed the fixes I initially found for rehydration issues. Site now loads a random card and a placeholder user on Netlify
3. Moved the logic for fetching data to the components fetching, rather than the store. The site is not complex enough to warrant it and I'm finding it hard to get reactivity that way.

**Thoughts**:
1. I feel like I'm getting familiar with Nuxt which is nice. My original plan was to use Firebase for IAM and use MongoDB for data, I have a suspicion (though I have no reason to) that I will run into difficulties with that. Guess I'll just have to start to know.

**Link(s) to work**:
1. [Code stuff](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-17&until=2024-09-17)
2. [Live site](https://dailybingo.netlify.app/)


### Day 30: September 17th, Tuesday

**Today's Progress**:
1. I set up a service account in Firebase and got started setting up authentication on the Daily Bingo app.

**Thoughts**:
1. I spent a lot of time deliberating over whether or not to go with Firebase for authentication. I found a video that explained how to get authentication done with sidebase/nuxt-auth module. I'm contemplating giving that a go (perhaps I'll make separate branches so I can try both ways since I'm finding it hard to make a decision).


### Day 31: September 18th, Wednesday

**Today's Progress**:
1. I ditched the Firebase idea. For now. I'm going with Auth0. Seems like an option I can easily transition from and their free tier is just as generous. I configured the sidebase-auth module and it sort of works but I still need to work on the flow.

**Link(s) to work**:
1. [Sidebase config](https://github.com/theAvocadoCoder/daily-bingo/commit/3733f45ed7e4c994c70b693edd4aa2764d51ea47)
2. [Live site](https://dailybingo.netlify.app/)


### Day 32: September 19th, Thursday

**Today's Progress**:
1. I feel like the Daily Bingo app is starting to come together now. I've set up my auth routes and guest mode. The app displays the session user's details. User's details get saved to my dailybingo database upon registration. User's card details persist.

**Thoughts**:
1. My least favorite activity is trying to make sense of the changes I've made so I can make meaningful git commits. But I'm happy I take the time to do it anyway, I feel like it's a good habit to develop, so I'm not a pain to collaborate with.
2. I've gotten a partner for the Playlist app. This is the project I'm most excited about, and I think working on the Daily Bingo app has helped me to get some momentum with research and failing first. 


### Day 33: September 20th, Friday

**Today's Progress**:
1. I set up the profile page so the user can edit their display name on the Daily Bingo app


**Link(s) to work**:
1. [Profile menu](https://github.com/theAvocadoCoder/daily-bingo/commit/c1c798e2a007eb8bb2659b34c9fc47e33ffe2be0)
2. [Edit profile page](https://github.com/theAvocadoCoder/daily-bingo/commit/5b1e1d69ad7026e357c7a1c4e49859023121d20f)


### Day 34: September 21st, Saturday

**Today's Progress**:
1. I set up a route to handle changing the user's picture on Auth0. Will set up uploading to Cloudinary tomorrow.

**Link(s) to work**:
1. [Commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-21&until=2024-09-21)
2. [Live site](https://dailybingo.netlify.app/)


### Day 35: September 22nd, Sunday

**Today's Progress**:
1. Did week one of HackerRank's 3-Month preparation kit

**Thoughts**:
1. Moving forward, I'll take it much easier during the weekends and strive for only an hour of work to prevent burnout.


### Day 36: September 23rd, Monday

**Today's Progress**:
1. Completed implementing profile editing. Picture can be edited and so can username now. Will probably revisit that username editing functionality later. I set it so the DB doesn't update if the username was modified less than a month ago. Will need to give a warning and set up toasts so the user is aware of why the username isn't changing.

**Thoughts**:
1. I got to do some reading about Dates so I could figure out how to implement the 30 day username limitation.
2. I remember when I started learning to code, a lot of people would say that the only way you get better is by practicing. And even though I believed them then, I don't think I really understood. I can actually see the progress I've made. I can actually *feel* the progress. And this is only because I've been writing code, even when I'm not sure it'll do what I want it to.
3. I'm learning that the best way to get better at programming is to program. I'm getting more comfortable with writing code that isn't perfect the first time, I'm getting comfortable with sitting with working my way through error messages until I get the result I want.


### Day 37: September 24th, Tuesday

**Today's Progress**:
1. I added the save card functionality to the bingo card


**Link(s) to work**:
1. [Commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-24&until=2024-09-24)


### Day 38: September 25th. Wednesday

**Today's Progress**:
1. Added some features to the bingo card with regards to saving a card
  - Only save previously unsaved cards,
  - Update the card when the user marks a cell,
  - Persist the card state
2. Display the user's cards on the cards page

**Link(s) to work**:
1. [Commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-09-25&until=2024-09-25)


### Day 39: September 26th, Thursday

**Today's Progress**:
1. Added a feature to allow users name cards when they save them
2. Made the cards on the cards page clickable and handled opening a card. I used a currentCard localStorage item to track the currently opened card (this applies for all cards except the dailyBingo card)
3. Read up on how web sockets work, tried to find a way to integrate websockets into my severless app and came across [this article](https://dev.to/neagle/serverless-websockets-with-ably-1ip5). Will definitely be trying out Ably. I've been browsing the docs and it seems like the perfect solution for my case.

**Link(s) to work**:
1. [Commit for naming cards](https://github.com/theAvocadoCoder/daily-bingo/commit/912dd95bd46774017d43365b9d64e0d973f87d57)
2. [Commit for making cards clickable](https://github.com/theAvocadoCoder/daily-bingo/commit/dee5abef1576cff0157cf704d8586f62ca655a11)
3. [Commit for handling non-dailyBingo cards](https://github.com/theAvocadoCoder/daily-bingo/commit/e4c74174e206722071035a0facb93a2fbe7a5fcc)


### Day 40: September 27th, Friday

**Today's Progress**:
1. Added a feature to allow users change the name of saved cards
2. Browsed the Ably docs some more. Will begin working on the groups page next week

**Link(s) to work**:
1. [Commit for editing saved cards](https://github.com/theAvocadoCoder/daily-bingo/commit/dc9c914241c56c2878cad8896853889113ab51ba)


### Day 41: September 28th, Saturday

**Today's Progress**:
1. Fixed a bug on the mentorHub partner-ui that was preventing the docker container from being built and pushed when I merged with main. (Still waiting for a review on this)
2. Added a delete card feature to the saved bingo cards
3. Improved the Ui of the confirm dialog element by clearly distinguishing the primary action button

**Link(s) to work**:
1. [Commit for delete card feature](https://github.com/theAvocadoCoder/daily-bingo/commit/f19b890697d19a1890bf6c150bee95273cc09d9e)
2. [Commit for improving UI](https://github.com/theAvocadoCoder/daily-bingo/commit/50a6ff91f3969b86279c648c7f7d333b734a0a4b)


### Day 42: September 29th, Sunday

**Today's Progress**:
1. Added a back button to the saved card view, finally implemented toast messages, added a new card button and created the new card route.
2. Made the profile menu dropdown slightly more accessible by making it tabbable. I had to sacrifice the UX a bit. The menu no longer disappears when it blurs. The workaround I put for this is that the escape key dismisses it.


**Thoughts**:
1. As I write this log, I realize I might be able to make the menu dropdown tabbable without having to sacrifice the UX by moving the menu into the button element. I'll see if this works tomorrow.

**Link(s) to work**:
1. [Back button](https://github.com/theAvocadoCoder/daily-bingo/commit/ed326153ea5507df73d5d3a0d48eac4839f1f712), [Toast implementation](https://github.com/theAvocadoCoder/daily-bingo/commit/49f0934037b67d9cf6b1a7051c1d0d1f9598d389), [New Card button and route](https://github.com/theAvocadoCoder/daily-bingo/commit/62a8130ac02105b38555c6592019dfeac2e31c1a)
2. [Profile Menu Accessibility](https://github.com/theAvocadoCoder/daily-bingo/commit/333b6b69196b548b2f44092e16008926862e1e2e)


### Day 43: September 30th, Monday

**Today's Progress**:
1. Fixed the accessibility thing with the profile menu, fixed some bugs, did some refactoring here and there
2. Added a search feature to the cards list page
3. Added the create card feature

**Thoughts**:
1. So I didn't have to move the dropdown. I just needed to use separate event listeners for when the button is clicked and when the menu loses focus. Now it is tabbable, dismissable by clicking outside the menu (or on a menu item) or pressing the escape key.
2. I'm pleased with the search feature. For the new card feature, when the card is created, the user gets directed to the cards page but with their new card highlighted. I did this because I want the back button on the view card page to take the user to the cards list page rather than the create new card page.

**Link(s) to work**:
1. [toast bug](https://github.com/theAvocadoCoder/daily-bingo/commit/e91a6405cc0600579fb3aa52e99f138681e630fa), [cloudinary bug](https://github.com/theAvocadoCoder/daily-bingo/commit/9b826bddc8b7c9696a93a7914467cf8dfbe0a829), [delete button ui bug](https://github.com/theAvocadoCoder/daily-bingo/commit/129ad2c836de74e0ea3b44357789da8c7cdb8465), [bingo card prop refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/c1d04df66a664bcb722f69335965aa6e36083bf7), [cloudinary bug again, cause I didn't do it right the first time](https://github.com/theAvocadoCoder/daily-bingo/commit/3726803224ced066300e0ee6bc1483b35923d89a), [buildCellArray refactor](https://github.com/theAvocadoCoder/daily-bingo/commit/fea863eaefb00600a1e3f0c73e202f824f6f7cdc)
2. [Profile Menu Accessibility Final Fix](https://github.com/theAvocadoCoder/daily-bingo/commit/2391de0ffec4f0a214057de0d998d08329ad6b25)
3. [Search in cards list page](https://github.com/theAvocadoCoder/daily-bingo/commit/5bfd237f22cd52afb65292bb41f46682bd86ef21)
4. [Create card feature](https://github.com/theAvocadoCoder/daily-bingo/commit/b18cc5b9ba30eaa4a0944c6cf9338010a3021072) (and [directing users to cards list after](https://github.com/theAvocadoCoder/daily-bingo/commit/6748cfa86169222148b2db3a53ed996cf841e36f))


### Day 44: October 1st, Tuesday

**Today's Progress**:
1. Solved some HackRank problems in the 3-month prep kit
2. Started setting up Ably for realtime messaging on Daily Bingo.

**Link(s) to work**:
1. [Commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-10-01&until=2024-10-01)


### Day 45: October 2nd, Wednesday

**Today's Progress**:
1. Solved some HackerRank problems in the 3-month prep kit
2. Learned about Typed arrays and generator functions


### Day 46: October 3rd, Thursday

**Today's Progress**:
1. Completed CS50x week 0 problem set after 1 year of avoiding it.

**Thoughts**:
1. I started the CS50x course in August 2023, and for some reason, scratch just always seemed so alien. I couldn't figure it out. I had basically given up, completed all the other weeks but this one simple thing held me back. But I think this challenge has taught me perseverance. Today, I body-doubled with a good friend of mine and I actually got it done. It's a small victory but one that I'm very happy about.

**Link(s) to work**:
1. [Scratch project](https://scratch.mit.edu/projects/918778615)


### Day 47: October 4th, Friday

**Today's Progress**:
1. Did a lot of refactoring with my Mongo IO class. Some methods were doing too much so I tried to make them observe single responsibility.
2. Changed the data model for the user so the user document doesn't keep card data other than the card_id which is immutable.
3. Implemented a soft-delete feature for the cards. Added a reference counter field to the card model. Will impelment the periodic cleanup later.

**Link(s) to work**:
1. [Commits for the day](https://github.com/theAvocadoCoder/daily-bingo/commits/main/?since=2024-10-05&until=2024-10-05)


### Day 48: October 5th, Saturday

**Today's Progress**:
1. Solved week 2 of HackerRanck's 3 month prep kit.


### Day 49: October 6th, Sunday

**Today's Progress**:
1. Improved the UX on the new card page of the Daily Bingo app.
2. Started working on the groups pages.

**Link(s) to work**:
1. [Card UX improvement](https://github.com/theAvocadoCoder/daily-bingo/commit/1240ea97f3c532fa6e9d111fbd6342a13693829a) and [a bug fix](https://github.com/theAvocadoCoder/daily-bingo/commit/52274b2397baf4d629c6624fab7a4e726a2d1c1b).
2. [Groups list page](https://github.com/theAvocadoCoder/daily-bingo/commit/4a0c5604ae3bda788bbc649afc824551e7ecc057), [new group page](https://github.com/theAvocadoCoder/daily-bingo/commit/b9d5ab2e7eec9e4b52d45b541ec04ff5074597e3), and [a minor UI change](https://github.com/theAvocadoCoder/daily-bingo/commit/2d1413f66a6fe5af3bb5a620d6689f40ab4c6199)


### Day 50: October 7th, Monday

**Today's Progress**:
1. Worked on the groups list page so it's not just a copy of the cards list page.
2. Started working on the group chat page. Yet to implement realtime messaging, but there's a placeholder feature for sending messages.

**Link(s) to work**:
1. [Group list modifications](https://github.com/theAvocadoCoder/daily-bingo/commit/f14dcd8a9e10180690ad5204addd8647fe94e99b)
2. [Chat page](https://github.com/theAvocadoCoder/daily-bingo/commit/62c01aefe092eb6816e10a913d2d9f83a56920db)


### Day 51: October 8th, Tuesday

**Today's Progress**:
1. Finally got around to implementing realtime messaging! Now I just need to figure out how to persist the messages to my DB.

**Link(s) to work**:
1. First tried [moving the Ably config to a Nuxt plugin](https://github.com/theAvocadoCoder/daily-bingo/commit/710493ecb2974ba55ed60f828ba945fbaf920956) then realized to do that, I'd need to [reconfigure the setup to use Auth Tokens](https://github.com/theAvocadoCoder/daily-bingo/commit/900fa1fee1e446360e9a2c799e201d476c7798ab). And finally, i was able to [implement pub/sub on the chat page](https://github.com/theAvocadoCoder/daily-bingo/commit/858c7d5c8ef20436f88267e3f2c6b519620974fd).


### Day 52: October 9th, Wednesday

**Today's Progress**:
1. Added the Ably integration to invoke my serverless function when message events are published.
2. Wrote the api route to be invoked and messages now persist.

**Link(s) to work**:
1. [Commit for the api route](https://github.com/theAvocadoCoder/daily-bingo/commit/ed0e81cda97676272b180b9e3d4121e70a60d717) and [when I finally got the payload structure right](https://github.com/theAvocadoCoder/daily-bingo/commit/0dcb3950a80a1869c7a656841f7ef401e122fa74)


### Day 53: October 10th, Thursday

**Today's Progress**:
1. On the bingo app: Fixed some bugs, set a default group image during creation, and nested the group details page in the group chat page.

**Link(s) to work**:
1. [Bugs](https://github.com/theAvocadoCoder/daily-bingo/commit/06a4cb9522d2d2a4a242e28ca88e2fbafe276c20), [default group image](https://github.com/theAvocadoCoder/daily-bingo/commit/3ae5f3f6b13263a178efc0d16c90c08d03e79e8d), and [the page nesting](https://github.com/theAvocadoCoder/daily-bingo/commit/fa7e9313db93dee500ed960fc4605b0d5bd88f9f)


### Day 54: October 11th, Friday

**Today's Progress**:
1. Learned about throttling and debouncing and memoization, implemented util functions in avocadohelpers.


### Day 55: October 12th, Saturday

**Today's Progress**:
1. Worked some more on the memoization function, worked on a small webpage to get geolocation info from postcodes.io


### Day 56: October 13th, Sunday

**Today's Progress**:
1. Finished with the geolocation webpage. Honestly, it felt nice working with plain HTML and JS after so long. I think I'll do this more often during the weekends.

**Link(s) to works**:
1. [Repo for the webpage](https://github.com/theAvocadoCoder/uk-postcodes/) and the [live site](https://github.com/theAvocadoCoder/uk-postcodes/)


### Day 57: October 14th, Monday

**Today's Progress**:
1. Brushed up on Unit Testing, started setting up for testing in Daily Bingo and I regret not trying TDD. Testing in nuxt is much more complex than I anticipated 🥲


### Day 58: October 15th, Tuesday

**Today's Progress**:
1. Finished working on the memoization function for avocadohelpers. Got to work with Symbols which was fun (I've been looking forward to getting to use them in a project since I first learned about them). I used it to make unique keys in a map that I use to cache function calls.
2. Started writing tests for the helper functions I've done so far. I'll hold off on implementing any new helpers till I've written tests for the available ones. I want to try test driven development.

**Thoughts**:
1. I've gained some confidence over the course of this challenge and that is very encouraging. I often worry that I'm doing a lot of things but not making any real progress but I can definitely see some improvement and that strengthens me to keep going.

**Link(s) to work**:
1. [Commits for the memoization function](https://github.com/theAvocadoCoder/avocadohelpers/commits/utils?since=2024-10-16&until=2024-10-16)
2. [Setup](https://github.com/theAvocadoCoder/avocadohelpers/commit/052da70d91046c0a5f6ba5f4b3cba1bb48c8a7ea) and [first tests](https://github.com/theAvocadoCoder/avocadohelpers/commit/2c6f9c14c89cff30e62731e0b7a2d79c344bb805) commits for testing


### Day 59: October 16th, Wednesday

**Today's Progress**
1. Wrote test suites for the DOM functions: style, addClass, and removeClass. Modified code to pass failing tests.

**Link(s) to work**:
1. [Test suites](https://github.com/theAvocadoCoder/avocadohelpers/commit/5d93c91e41b38bdfb6f84bad93030399392ab865) and [their modified implementations](https://github.com/theAvocadoCoder/avocadohelpers/commit/f0c7a2b2ac522ef2135c733d636c7cf4cacd0ec7)


### Day 60: October 17th, Thursday

**Today's Progress**:
1. Started working on an admin dashboard for a developer assessment at a job I applied for. Started marking up and styling components. Got to work with custom components, which is always fun. Looking forward to the challenge of making an SPA without a framework.

**Link(s) to work**:
1. [The repo](https://github.com/theAvocadoCoder/alphatwelve-dashboard)


### Day 61: October 18th, Friday

**Today's Progress**:
1. I practiced writing CLI scripts with typescript. I want to work on a project that's a CLI tool but I don't have any ideas on that front.
2. Did some more work on the admin dashboard. Finished the component I was working on yesterday, started on the navigation.

**Thoughts**:
1. It's unreal how much easier this assessment feels than when I had to do a similar assessment last year. I distinctly remember things like CSS variables and darkmode toggles being too complex for me. I'm very grateful for this growth. It's so easy to focus on all the things I don't know or can't do. But here I am, doing better than I did last year. I'm encouraged.


### Day 62: October 19th, Saturday

**Today's Progress**:
1. Completed the mobile view for the navigation. This was a little more challenging than I expected, but I'm pleased with the result. I also added transitions; the switch to dark mode was rather jarring.
