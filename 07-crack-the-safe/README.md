# CRACK THE SAFE
For this project, you will develop an interactive adventure game called 'Crack the Safe'. The user will play as a thief who must crack a safe and make with the loot before the Coppers arrive to arrest them.

Make no mistake - making a game, even one as simplistic as this, **WILL** challenge you. However, the previous projects you have conquered have helped you to build your arsenal of web development weapons. Use what you've learned to create something amazing. Good luck, buddy; you've got this!

## SPECIFICATIONS
  * The page should initially be displayed with a title, a brief introduction to the game, an 'account' displaying how much loot the player has (more on this later), and a button which will allow the player to start cracking safe's.

  * The game begins when the player clicks the button. The starting button should go away and a form to crack the safe should be displayed.

  * The player will be given a limited amount of time to crack the code on the safe before being arrested.

      * The code should be randomly generated and consist of four random numbers from 0 to 9 (inclusive). Such as: 0873

      * The player will need to guess all four numbers correctly, and within the allotted time, in order to successfully crack the safe.

  * The game should indicate to the player whether each of the numbers they have guessed to crack the safe is too high, too low, or correct:

      * Display an 'H' and highlight the input red if the guess is too high.

      * Display an 'L' and highlight the input yellow if the guess is too low.

      * Display a 'C', highlight the input green, and disable the input if the guess is correct.

  * While the player is attempting to crack the safe, a timer should continue to tell them how much time they have left before the Coppers arrive to arrest them.

  * If the player successfully crack's the safe before the time runs out they will win:

      * When the player wins, a message should be displayed indicating the amount of loot they stole from the safe.

      * The amount of loot should be proportionate to the number of remaining seconds on the timer. i.e., there will be more loot if there were more seconds left than if there were fewer seconds left.

      * The loot that was stolen from the safe should be added to their 'account'.

      * The form to crack the safe should be hidden and a start button should be displayed to begin cracking a new safe.

      * When the button is clicked, the player will begin cracking a new safe with a newly generated code and a new timer.

  * If the player runs out of time attempting to crack the safe, they are arrested and thrown in prison:

      * When the player loses, a message should be displayed indicating they have lost.

      * The losing message should display a random penalty depending on how many numbers they got correct. i.e., the more numbers they got correct, the lower the penalty.

      * The penalty should be deducted from the players account, if they have any loot to take.

      - - -

      *A sane person might have just ended the game here. But you and I both know that neither of us are sane...*

      - - -

      * The name of the game should change to 'Escape the Prison' and the player will be given the opportunity to escape from their prison cell.

      * Luckily, this prison isn't very secure. To escape the prison they simply need to pick the lock of their cell. The lock consists of four pins in random positions from 0 to 9 (inclusive). Hopefully you're seeing a pattern here.

      * Just like with safe cracking, the player will be given a certain amount of time to pick the lock of their cell before the guard catches them.

      * If they are caught, the game will actually end and they will lose all of their loot. But if they escape, the game will change back to 'Crack the Safe' and they will be given the opportunity to continue cracking safe's and looting.

## EXTRA CREDIT
  * Use the browser's local storage to save the user's loot so that they keep the loot they've earned even if the game is closed.

  * Make it look purrrty! (Seriously, though. Don't under estimate the importance of a nice design and intuitive user experience. Even the best, most performant, applications and games fail if the user experience is terrible.)

## EXAMPLE
Awww, shucks! There is no example for this project just yet.
