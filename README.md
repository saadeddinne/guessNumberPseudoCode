&#xa0;

  <!-- Saad Eddine FEKI -->
</div>

<h1 align="center"> 🚀 Game : Guess Number !! ---- By Saad eddine</h1>

<!-- Status -->

<h4 align="center">
  🚀  CodeBoxx
</h4>

<hr>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/saadeddine" target="_blank">Saad eddine</a>
</p>

<br>

## :dart: About

/\*\*
*This game will have to offer different options and guide the player throughout the game.
*When launching the algorithm, you must first greet the user and ask them to choose a level *of difficulty. This choice will influence the number of trials as well as the range of *possible numbers. Here are the details for the different levels:
*Very easy: Unlimited trials, 1 to 10
*Easy: 5 tries, 1 to 10
*Medium, 5 tries, 1 to 100
*Difficult, 8 tries, 1 to 500
*Very difficult, 9 tries, 1 to 1000
*Once the difficulty is chosen, the algorithm selects a number at random and asks the user *to start guessing. For each incorrect attempt, it will be necessary to indicate whether the *number sought is smaller or larger.
*If the player manages to find the correct answer, the game is over and the player is *congratulated. If he cannot find the solution within the allotted number of tries, he gets *a game over and the number sought is displayed. The user then has the option to end the *program or start a new game.

- \*\*/

<p align="center">

Print :--- Hello to the user and explain rules
Input = choose level of difficulty
set level
if level == very easy
set valRandom in [1 to 10]

                //loop
            do {
                input = Ask user to give number
                if number > valRandom
                    print Too big
                else if number < valRandom
                    Print Too smaller
                else {
                    Print : congratulatulation
                    Option : play again
                           :Exit
                }

            } while number not equal to valRandom
            //-- End if

        if level == Easy
                set valRandom in [1 to 10]
                Set Tries to 1
                Do {
                    input = Ask user to give number
                    if number > valRandom
                         print Too big
                    else if number < valRandom
                         Print Too smaller
                     else {
                            Print : congratulatulation
                            Option : play again
                                   :Exit
                         }
                        // incrementation
                        Tries = Tries + 1
                } while number not equal to valRandom && Tries <= 5

                //-- End if

          if level == Medium
                set valRandom in [1 to 100]
                Set Tries to 1
                Do {
                    input = Ask user to give number
                    if number > valRandom
                        print Too big
                    else if number < valRandom
                        Print Too smaller
                    else {
                            Print : congratulatulation
                            Option : play again
                                   :Exit
                        }
                        // incrementation
                        Tries = Tries + 1
                } while number not equal to valRandom && Tries <= 5

                //-- End if

              if level == difficult
                    set valRandom in [1 to 500]
                    Set Tries to 1
                    Do {
                        input = Ask user to give number
                        if number > valRandom
                            print Too big
                        else if number < valRandom
                            Print Too smaller
                        else {
                                Print : congratulatulation
                                        Option : play again
                                               :Exit
                            }
                            // incrementation
                            Tries = Tries + 1
                    } while number not equal to valRandom && Tries <= 8

                    //-- End if

                if level == very difficult
                    set valRandom in [1 to 1000]
                    Set Tries to 1
                    Do {
                        input = Ask user to give number
                        if number > valRandom
                            print Too big
                        else if number < valRandom
                            Print Too smaller
                        else {
                                Print : congratulatulation
                                        Option : play again
                                                :Exit
                            }
                            // incrementation
                            Tries = Tries + 1
                    } while number not equal to valRandom && Tries <= 9

                    //-- End if

                    // End algorithm ./

</p>

## :white_check_mark: Requirements

No requirements

## :memo: License

- This project is under license from CodeBoxx.

Made with :heart: by <a href="https://github.com/saadeddinne" target="_blank">{{SaadEddine}}</a>

&#xa0;

<a href="#top">Back to top</a>
