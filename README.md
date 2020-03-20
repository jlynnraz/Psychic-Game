
## Psychic Game
Can you read my mind? Press a letter to guess what letter I'm thinking of. Careful, you only get 10 guesses!

## Motivation
Psychic Game was designed to show the basic power of JavaScript technology. The computer will randomly generate a letter, and you will have to match it within 10 guesses.
  
## Sneak Peak
![Psychic](https://user-images.githubusercontent.com/53287044/74380058-16c2da80-4da6-11ea-8333-d69e4f275417.jpg)

## Installation
* Fork It
* Clone It
* Open in your default browser, or view the live demo  [HERE](https://jlynnraz.github.io/Psychic-Game/) 

## Technologies
* JavaScript 
* HTML 
* CSS

## Behind the Scenes
A series of if's and else's determines whether or not your guess matches with the computer's.

~~~
 if (userGuess === computerGuess) {
                console.log("You win");
                alert("YOU WIN! Press refresh to play again.");
                win++;
                winsText.textContent = win;
            }



            else if (userGuess !== computerGuess) {
                console.log("You're wrong");
                guessesSoFar.push(event.key);
                guessesLeft--;
            
                if (guessesLeft === 0) {
                    alert("Game over");
                    console.log("Game over");
                    losses++;
                        var playAgain = confirm("Play Again?");
                    if(playAgain === true){
                        guessesLeft = 10;
                        guessesSoFar = []
                    } 
                    
                }
~~~

## Contact
Please contact me directly with any comments of questions!
* jlynnraz@gmail.com
* [LinkedIn](https://www.linkedin.com/in/jaimee-razee/)
* [Portfolio](https://jlynnraz.github.io/Portfolio2/)



