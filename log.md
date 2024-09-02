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

