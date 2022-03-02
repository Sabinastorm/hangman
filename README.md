# Hangman game
For my Milestone Project 3 on Code Institute's Diploma in Software Developement course I have created a hangman game.

For link to the app click [Here](https://python--hangman.herokuapp.com/) 

## Who is this website for?

This is a hangman game suitable for adults 18+.

## The owner

The owner of this game is Sabina Storm Björlestrand

## What does it do?

The qame has 20 words that are chosen at random. The player can guess att a letter or a word. The player has six guesses until it's game over.

## User experience

### User stories

#### From customers perspective

- As a user I want to know navigate easily in the game
- As a user I want to know if myanswer was correct or not
- As a user I want to be able to restart the game 

#### Customers perspective fulfilment

- The game guides the player from the beginning by telling the player to guess a word or a letter
- The game tells the player if the guess is correct or not
- At the end the player is asked if they would like to play again and is given the option to press Yes or No



## Features
### Exsisting Features
created in Python
- Words file
- Hangman code file

### Feature for future implementation
- More words to word file.
- Possibility for player to receive hints.
- A score traker so the user can compare their score with other users

## Technologies used

- [Python](https://en.wikipedia.org/wiki/Python_(programming_language) for code to build the game
- [Git](https://gitpod.io/) for version control
- [GitHub](https://github.com/) for keeping the files, documents and deployment of the website
- [PEP8online](http://pep8online.com/) for validating the code

## Resources

- [Code Institute](https://learn.codeinstitute.net/) course materials
- [Code Institute](https://learn.codeinstitute.net/) Slack Community
- [5pence](https://5pence.net/) for markdown
- [Youtube](https://www.youtube.com/watch?v=m4nEnsavl6w) for python code 

## Testing

### Browser testing

Website has been tested in Google chrome and Safari

### Validators

The website has been through PEP8online check with a few errors:


Code	Line	Column	Text
E111	44	16	indentation is not a multiple of four
E111	45	16	indentation is not a multiple of four
E111	46	16	indentation is not a multiple of four
E111	48	16	indentation is not a multiple of four
E111	49	16	indentation is not a multiple of four
W291	54	20	trailing whitespace
E201	63	15	whitespace after '['
W291	67	37	trailing whitespace
W291	68	36	trailing whitespace
W291	69	37	trailing whitespace
W291	73	4	trailing whitespace
W292	147	11	no newline at end of file

All the errors are now fixed.

### Local testing

Testing of the game in Heroku shows no problems

## Version control

### Git and Github

I used GitPod as a local repository and GitHub as a remote repository. The process of version control was:

- First i created a new repository in GitHub
- Then opened that repository in GitPod and started coding
- In GitPod i created my files and folders
- I then saved my work and pushed it to GitHub repository to keep it safe

Saving, commiting and pushing it to remote repository in terminal:
- git add . 
- git commit -m "Commit message" 
- git push to update work to GitHub

## Deployment

To deploy the website, I followed the below steps on [Heroku](https://id.heroku.com/).

- Create a new app
- Go to settings and add buildpacks: 
1. `heroku/python`
2. `heroku/nodejs`
- Create a _Config Var_ called `PORT`. Set this to `8000`
- Connect my GitHub repository and deploy.
