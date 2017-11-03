# CRACK THE SAFE
For this project, you will develop an interactive game called 'Crack the Safe'. The user will play as a thief who must crack a safe and make with the loot before the Coppers arrive to arrest them.

Make no mistake - making a game, even one as simplistic as this, **WILL** challenge you. However, the previous projects you have conquered have helped you to build your arsenal of web development weapons. Use what you've learned to create something amazing. Good luck, buddy; you've got this!

## SPECIFICATIONS
  * The page should initially be displayed with a title, a brief introduction to the game, how much loot the player has (more on this later), and a button which will allow the player to start cracking safe's.

  * The game begins when the player clicks the start button. Once the start button is clicked, a form to crack the safe should be displayed.

  * The player will be given a limited amount of time to crack the code on the safe before being arrested.

      * The code should be randomly generated and consist of four random numbers from 0 to 9 (inclusive). Such as: 0873

      * The player will need to guess all four numbers correctly, and within the allotted time, in order to successfully crack the safe.

      * *HINT*: Sounds similar to the number guessing game...

  * The game should indicate to the player whether each of the numbers they have guessed to crack the safe is too high, too low, or correct:

      * Display an 'H' and highlight the input red if the guess is too high.

      * Display an 'L' and highlight the input yellow if the guess is too low.

      * Display a 'C', highlight the input green, and disable the input if the guess is correct.

  * While the player is attempting to crack the safe, a timer should continue to tell them how much time they have left before the Coppers arrive to arrest them.

  * If the player successfully crack's the safe before the time runs out they will win:

      * When the player wins, a message should be displayed indicating the amount of loot they stole from the safe.

      * The amount of loot found in each safe should be randomized.

      * The loot that was stolen from the safe should be added to their total loot.

      * The form to crack the safe should be hidden and a start button should be displayed to begin cracking a new safe.

      * When the button is clicked, the player will begin cracking a new safe with a newly generated code and a new timer.

  * If the player runs out of time attempting to crack the safe, they are arrested and thrown in prison:

      * A message should be displayed indicating they have lost.

      * The losing message should display a random penalty where the player loses a portion of their loot.

      * The penalty should be deducted from the players total loot.

      - - -

      *A sane person might have just ended the game here. But you and I both know that neither of us are sane...*

      - - -

      * The title should change to 'Escape the Prison' and the player will be given the opportunity to escape from their prison cell.

      * Luckily, this prison isn't very secure. To escape the prison they simply need to pick the lock of their cell. The lock consists of four pins in random positions from 0 to 9 (inclusive). Hopefully you're seeing a pattern here.

      * Just like with safe cracking, the player will be given a certain amount of time to pick the lock of their cell before the guard catches them.

      * If they are caught, the guard will take more of their loot. This can continue until they have no loot left to take, which will then end the game.

      * If the player successfully escapes from prison, the title will change back to 'Crack the Safe' and they will be given the opportunity to continue cracking safe's and looting.

## EXTRA CREDIT
  * Use the browser's local storage to save the user's loot, the stage of the game, and whether or not they are arrested so that they can continue playing the game from the place they left off even after closing the browser window.

  * I encourage you to spend a fair amount of time on the CSS for this mini-game. Please do not under estimate the importance of design and user experience. Even the best applications can fail due to poor user experience and design.

## EXAMPLE
[Here is an example](https://codepen.io/tophergates/full/GMXzqx/) of how this might look. **DO NOT LOOK AT THE SOURCE CODE! THAT'S CHEATING!!**
