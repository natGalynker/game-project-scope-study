# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
I create a rough draft by hand of what I saw the page looking like at various stages
both on a mobil device and on a desktop.
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.

-   4-8 user stories for your game project.
- As a user, I want to create an account so that I can play tic tac toe
- As a user I want to login so that I can start the game
when player 1 loses
when player 1 wins
-stalemate what will happens
-   How you plan to keep your code modular.
Putting al the JS files in the scripts directory. There would be different JS
file which would handle different functions. One would handle all the ajax calls,
one which would handle the events such as submitting forms or anything which would
require an event handler. There would be a file which would manage the verification
of the event handlers. I would make sure that circular dependecy would not happen
by doint so.
-   What creative spin will you add to your project. I would like to really utilize
SASS. I have used bootstrap before but I have heard really great things about SASS
SAST and am excited to try it. I would like to
-   How you will use version control to backup / track your project.
I would create separate branches for HTML, CSS, and JS at the very least. I would
commit as often as I can, ideally after verifying that the functionality of a
submit or other action was indeed working. I would not want to commit only once
a day or once every few hours because that would make taking a step back much more
problamatic than helpful.
-   Do you plan to attempt any of the bonuses. I would like to. I want to first
get my code working well completed on its own before attempting the bonuses.
these are the bonuses that appeal to me and which I would like to attempt:
Keep track of multiple game rounds with a win counter.
Allow players to customize their tokens (X, O, name, picture, etc).
Get inventive with your styling.
