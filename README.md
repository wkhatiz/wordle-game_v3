**Warning**
{: This project is still in progress. This readme document will be uploaded once the application is functional.}

# Wordle Game.V3

This is a Wordle game created using [Next.js](https://nextjs.org/) bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Setup 

A live demo of this version is not available therefore the app will need to be run locally. 

To run the application locally:
1. Install the latest version of [Node.js](https://nodejs.org/en/). The project was developed using version 19.6.0.
2. Install the latest version of [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
3. Open your computers command line. eg, Command Prompt for Windows, Terminal for MacOS, GNOME Terminal for Linux, etc. 
4. Clone the project locally
```
 git clone https://github.com/wkhatiz/wordle-game_v2.git
```
5. Navigate to the project directory
```
 cd wordle-game_v2
```
6. Install the project dependencies
```
 npm install
```
7. Run the local development server
```
 npm run dev
```
8. Open [localhost:3000](http://localhost:3000/) in a browser to view the project. 

## How To Play

This is a clone of the [wordle game](https://www.nytimes.com/games/wordle/index.html) popularised by The New York Times in 2021.

- Upon loading or reloading the page, a random word is selected from a list of valid english words. 
- The word that is selected will be the answer to the puzzle. The word is always 5 letters long. 
- You will have 5 guesses to find which 5 letter english word is the answer. 
- Each guess you make will have to also be a valid 5 letter english word. No gibberish. For example, submitting 'xyrgb' as a guess
- Upon making a guess, the word you guessed with be shown in the grid with each letter colored either grey, yellow or green, 
- Green means the letter is in the answer and in the correct column in the grid. 
- Yellow means the letter is in the answer but is found in another column. 
- Grey means that letter is not in the answer at all. 
 
