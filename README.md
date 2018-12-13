# README-project-1-extra-assginment

DATA STRUCTURES--- In the scope of this project I will utlize html, jquery, json, javascript & ajax, css/sass for styling, and inside those languages will be objects, arrays, strings, IDs, and classes. It is more than likely there are also other structures that aren't immediately coming to mind at the moment. :)

GAME BOARD--- The game board will be made by creating a series of arrays and objects controlled by click-events which will trigger the internal storing of the current game board. Utilizing Jquery and Ajax will be instrumental to accomplishing this.

APPROACH--- My plan is to focus on keeping myself to the schedule outlined with this project. To start out I want to make certain I have my full scope of the project mapped out, with plain-speak commented out as far as I can go, giving myself a framework to build off of going forward, and further enabling me to approach trickier problems as they arise.

USER STORIES--- //rewrite User 1 - Makes a profile, does not play a game but can log in again in the future User 2 - Makes a profile, logs in, selects "X", plays 1 game, logs out. User 3 - Attempts to log in, enters incorrect credentials, is prompted to create a new password, and plays a few games. User 4 - Logs in, plays several games without refreshing the page. The page tallies their win/loss score. User 5 - Player 1 logs in. Player 2 logs in. Both play a couple games against eachother, winning, losing, and creating a draw. Final win loss score is tallied User 6 - User logs on. Plays a draw each time by putting their marker into the center cell on the 2nd turn. Possibly an error message pops up informing them to the error of their infinite draws.

MODULAR BUILD--- Effective use of well maintained separation of concerns will be my focus to maintain modular code; in addition, this will enable me to work on the many different project pieces.

CREATIVE LICENSE--- In laying out the available time for this project I intend to spend some time ensuring the design elements will not be bare and/or stark. In this realm I'll primarily be focusing on an engaging board, fun interactive modal notifications (win, loss, draw, log in success, log in error, etc.), and creative game pieces. Who says a tic tac toe has to be X's and O's? This mainly implements styling however. Using .Hide & .Show to clear and reset the board after each game will add dynamic movement to the game. Going forward, I'm further pondering what other choices I can play with to really put life in this game.

VERSION CONTROL--- Github and keeping a commented record of progress will be immeasurably valuable to me in the process of this project. I've worked for many years keeping my own notes and folders filled with versions; the ease in which github enables me to continue this, in a much better format, I am incredibly excited for.

-The Devlopmnet Story
  -The Development Process
    -The development process stated with some rough wireframes, some user stories, and a quick planning outline. I divided development into feature groups and created a branch in Git for each group. The branches were as follows:
      -setupGrid - The game engine with the visualization based on a table.
      -setupAuth - The authentication of the user. This is the infrastruture for registering a user, and allowing a user to logon. The code is divided between api, events, and ui files. The api file makes the actual Ajax calls to the api provided.
      -SetupGameApi - similr to the authenticaion code this was focused on setting up the use the apu that was provided.
    -addStatistics - The focus here was on setting up the statistics.
    -updateStatistics - The statistics took sometime and needed a lot of testing and debuggung when defects were identified.
    updateUIUX - The UI was first developed with everything visible. This branch focused on providing some UI cleanup displaying only those UI elements that were relavent for a particular context.
    updateDocuments - The last branch was focused on updating the documentation.

    -Problem-Solving Strategy
      -Initial primary strategy was to use console.log to print out       information at specific areas in the program flow.

      -Node was used to explore specific issues with objects and arrays.
    I began to use more of the debugging facilities in the DevTools. I setup breakpoints and stepped through the code examining values of objects as I stepped through.

<!-- BONUS ROUND--- With projects such as these I start with my ideal, set my baseline of what must be completed, and then regulate based on what the parameters of my resources and the project deadline will allow. Using this method I've found I don't unnecessarily limit a project by deciding and defining at the start a lowered expectation, and will pace myself to accomplish the bonuses as well as exceed my baseline. -->
