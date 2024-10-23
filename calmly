#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <time.h>

void provide_affirmations() {
    char response[10];

    printf("Hey there! I'm Calmly. How are you feeling today? (good/bad): ");
    scanf("%s", response);

    if (strcmp(response, "good") == 0 || strcmp(response, "Good") == 0) {
        printf("That's fantastic to hear! 😊 What’s been going well for you today? (work/school/personal): ");
        scanf("%s", response);

        if (strcmp(response, "work") == 0) {
            printf("Ah, it's always nice to feel productive! What's something you've accomplished at work today?\n");
            scanf("%s", response);
            printf("That's amazing! Small steps always lead to big victories. Keep that momentum going!\n");
        } else if (strcmp(response, "school") == 0) {
            printf("School can be tough, but you're nailing it! What's been your highlight of the day?\n");
            scanf("%s", response);
            printf("That sounds great! Remember, learning is a journey, and you're on the right path. 🚀\n");
        } else if (strcmp(response, "personal") == 0) {
            printf("It's awesome when personal goals or life moments bring us happiness. What was your highlight?\n");
            scanf("%s", response);
            printf("That's so wonderful! Cherish those moments—those are what keep life exciting!\n");
        }

        printf("Do you want to hear some motivational advice to keep this good energy going? (yes/no): ");
        scanf("%s", response);
        if (strcmp(response, "yes") == 0 || strcmp(response, "Yes") == 0) {
            printf("Remember, every day is a chance to grow, even when things are going well.\n");
            printf("You're building your future, one step at a time, and trust me, it's going to be extraordinary!\n");
        } else {
            printf("No worries! You're already on a roll, so just keep riding this positive wave!\n");
        }
    } 
    else if (strcmp(response, "bad") == 0 || strcmp(response, "Bad") == 0) {
        printf("I'm really sorry you're feeling that way. 😞 Want to tell me a bit more about what's on your mind? (yes/no): ");
        scanf("%s", response);

        if (strcmp(response, "yes") == 0 || strcmp(response, "Yes") == 0) {
            printf("Go ahead, I’m all ears. What’s been bothering you lately?\n");
            scanf("%s", response);  // User explains briefly

            printf("Thank you for sharing that. You know, it's okay to feel like this sometimes. Life has its ups and downs, and it's important to remember that tough times don't last forever. You're stronger than you think.\n");

            printf("Would you like me to suggest something that could help brighten your mood? (yes/no): ");
            scanf("%s", response);
            if (strcmp(response, "yes") == 0 || strcmp(response, "Yes") == 0) {
                printf("How about we take a quick moment to reflect on the things you enjoy? What's something that usually makes you smile? (hobby/friend/family): ");
                scanf("%s", response);

                if (strcmp(response, "hobby") == 0) {
                    printf("Hobbies are such a great escape! Take a break today and indulge in it for a while—you deserve some 'you' time!\n");
                } else if (strcmp(response, "friend") == 0) {
                    printf("Friends are the best support system. How about you call or message that friend now? I bet they’ll make you feel better!\n");
                } else if (strcmp(response, "family") == 0) {
                    printf("Family always brings comfort. Spending a little time with them, even a chat, can make a big difference.\n");
                }
                printf("Remember, it’s okay to lean on the people and activities that bring you joy. You're never alone.\n");
            } else {
                printf("I get it. Sometimes, we just need to sit with our feelings for a bit, and that's perfectly okay.\n");
                printf("Whenever you're ready, just know I'm here to lift you up. You're not alone in this journey.\n");
            }
        } else {
            printf("That's totally okay. Sometimes words can’t fix everything, but just know you're not alone.\n");
            printf("Would it help if we took a few deep breaths together? Inhale... Exhale... Feeling even a little better?\n");
        }

        printf("Would you like to hear some uplifting words to help shift your mood? (yes/no): ");
        scanf("%s", response);
        if (strcmp(response, "yes") == 0 || strcmp(response, "Yes") == 0) {
            printf("You are stronger than any challenge you face. Remember, every setback is a setup for a comeback!\n");
            printf("Sometimes it's the darkest skies that produce the brightest stars, and you're shining brighter than you realize.\n");
        } else {
            printf("That's okay, take things at your own pace. Just know you're doing your best, and that’s enough.\n");
        }
    } 
    else {
        printf("I'm not sure I understood that, but regardless of how you're feeling, remember that you're doing great just by showing up today!\n");
    }

    // Conversation continues
    printf("Do you feel like talking a bit more or trying something fun to distract yourself? (talk/fun): ");
    scanf("%s", response);

    if (strcmp(response, "talk") == 0) {
        printf("I'm all ears! Anything you'd like to share or talk about? (yes/no): ");
        scanf("%s", response);
        if (strcmp(response, "yes") == 0) {
            printf("Great! Feel free to open up, I’m here for you.\n");
            // Continue conversation
            scanf("%s", response);
            printf("Thank you for sharing. I believe in you and your ability to handle this. You’re resilient, and every challenge is helping you grow stronger.\n");
        } else {
            printf("That’s okay too! Sometimes, just knowing someone is there is enough.\n");
        }
    } 
    else if (strcmp(response, "fun") == 0) {
        printf("Awesome! Let’s do something fun! We could play a game, or I can offer some interesting trivia. What do you think? (game/trivia): ");
        scanf("%s", response);

        if (strcmp(response, "game") == 0) {
            printf("Great choice! How about a quick number-guessing game or Tic-Tac-Toe to lighten the mood? (guess/tic): ");
            scanf("%s", response);
            if (strcmp(response, "guess") == 0) {
                printf("Let's start! Guess a number between 1 and 100...\n");
                number_guessing_game();
            } else {
                printf("Tic-Tac-Toe it is! Let's play!\n");
                tic_tac_toe();
            }
        } 
        else if (strcmp(response, "trivia") == 0) {
            printf("Here’s a fun fact: Did you know that octopuses have three hearts? Pretty cool, right?\n");
            printf("Or that honey never spoils? You could eat honey that’s over 3,000 years old!\n");
        }
    }

    printf("It’s been so nice chatting with you! 😊 Just remember, no matter what happens, you’ve got this. One step at a time!\n");
}

void math_helper() {
    int num1, num2, result;
    char op, response[10];
    
    printf("Hey there! Ready to crunch some numbers? (yes/no): ");
    scanf("%s", response);
    
    if (strcmp(response, "no") == 0) {
        printf("No problem! Come back anytime if you need help with math. 😊\n");
        return;
    }
    
    printf("Awesome! Let's get started. What type of math operation would you like to do today?\n");
    printf("I can help with:\n");
    printf("1. Addition (+)\n");
    printf("2. Subtraction (-)\n");
    printf("3. Multiplication (*)\n");
    printf("4. Division (/)\n");
    printf("Type the operator you'd like to use ( + - * / ): ");
    scanf(" %c", &op);

    printf("Great choice! Now, let me know the first number: ");
    scanf("%d", &num1);
    
    printf("Got it! And the second number? ");
    scanf("%d", &num2);
    
    switch (op) {
        case '+':
            result = num1 + num2;
            printf("Adding %d and %d gives us... %d! Simple, right? 😎\n", num1, num2, result);
            break;
        case '-':
            result = num1 - num2;
            printf("Subtracting %d from %d gives us... %d! You're on fire! 🔥\n", num2, num1, result);
            break;
        case '*':
            result = num1 * num2;
            printf("Multiplying %d and %d gives us... %d! Impressive math skills! 💪\n", num1, num2, result);
            break;
        case '/':
            if (num2 != 0) {
                result = num1 / num2;
                printf("Dividing %d by %d gives us... %d! Nicely done! 🧠\n", num1, num2, result);
            } else {
                printf("Oops! Dividing by zero isn't allowed. 😅 Let's try a different operation.\n");
                return;
            }
            break;
        default:
            printf("Hmm... that operator doesn't seem right. How about we try again? 😊\n");
            return;
    }

    // Continue the conversation
    printf("Want to try another calculation or something else? (yes/no): ");
    scanf("%s", response);
    
    if (strcmp(response, "yes") == 0) {
        printf("Fantastic! How about we add some more fun to it?\n");
        printf("Would you like to try:\n");
        printf("1. A more complex calculation with more numbers\n");
        printf("2. Some interesting math trivia\n");
        printf("3. Go back to basic operations\n");
        printf("Choose an option (1/2/3): ");
        int choice;
        scanf("%d", &choice);

        if (choice == 1) {
            int num3;
            char op2;
            printf("Alright! Let's make this more challenging! Enter a third number: ");
            scanf("%d", &num3);
            printf("Now, pick another operator ( + - * / ): ");
            scanf(" %c", &op2);

            // Perform additional calculation based on second operator
            switch (op2) {
                case '+':
                    result += num3;
                    printf("Adding %d to our previous result gives us... %d! You're unstoppable! 😎\n", num3, result);
                    break;
                case '-':
                    result -= num3;
                    printf("Subtracting %d from our previous result gives us... %d! You're a math wizard! 🧙‍♂️\n", num3, result);
                    break;
                case '*':
                    result *= num3;
                    printf("Multiplying with %d gives us... %d! Incredible work! 👏\n", num3, result);
                    break;
                case '/':
                    if (num3 != 0) {
                        result /= num3;
                        printf("Dividing our result by %d gives us... %d! You're a genius! 🤓\n", num3, result);
                    } else {
                        printf("Oops! We can't divide by zero. Let's stick to valid numbers. 😅\n");
                    }
                    break;
                default:
                    printf("Hmm, that operator doesn't seem right. Let's go back and fix that. 😊\n");
                    return;
            }
        } 
        else if (choice == 2) {
            printf("Cool! Here's a fun math fact for you:\n");
            printf("Did you know that zero is the only number that can't be represented by Roman numerals?\n");
            printf("Or that a 'googol' is a 1 followed by 100 zeros? Now you do!\n");
            printf("Math is full of wonders! 💡\n");
        } 
        else if (choice == 3) {
            printf("Let's keep it simple! What operation would you like to do now?\n");
            math_helper();  // Recursively call the function for another basic operation
        } 
        else {
            printf("Oops, that option doesn't seem right. Let's try again. 😊\n");
            math_helper();  // Restart if the choice is invalid
        }
    } 
    else {
        printf("Alright! I'm always here if you need some help with numbers again.\n");
        printf("Remember, math may seem tricky, but you're smarter than any problem you face! 🙌\n");
    }
}


void number_guessing_game() {
    int random_number, guess, attempts = 0, max_attempts;
    char difficulty, play_again[10];

    printf("Welcome to the Number Guessing Game! 🎮\n");
    printf("Let's start by choosing a difficulty level:\n");
    printf("E - Easy (Unlimited attempts)\n");
    printf("M - Medium (10 attempts)\n");
    printf("H - Hard (5 attempts)\n");
    printf("Choose your difficulty (E/M/H): ");
    scanf(" %c", &difficulty);

    if (difficulty == 'E' || difficulty == 'e') {
        max_attempts = -1;  // No limit for Easy
        printf("You've chosen Easy mode! Let's see how quickly you can guess the number! 😎\n");
    } else if (difficulty == 'M' || difficulty == 'm') {
        max_attempts = 10;
        printf("Medium mode selected! You have 10 chances to guess correctly. Let's go! 🔥\n");
    } else if (difficulty == 'H' || difficulty == 'h') {
        max_attempts = 5;
        printf("You've chosen Hard mode! Only 5 attempts, but I believe in you! 💪\n");
    } else {
        printf("Oops! That wasn't a valid option. Let's stick with Easy mode. 😊\n");
        max_attempts = -1;
    }

    srand(time(0));  // Seed random number generator
    random_number = rand() % 100 + 1;  // Random number between 1 and 100

    printf("I've picked a number between 1 and 100. Let's see if you can guess it!\n");

    while (1) {
        printf("Enter your guess: ");
        scanf("%d", &guess);
        attempts++;

        // Provide feedback to the user
        if (guess > random_number) {
            printf("Too high! 🔼 Try something smaller.\n");
        } else if (guess < random_number) {
            printf("Too low! 🔽 Go a bit higher.\n");
        } else {
            printf("🎉 Congratulations! You guessed the number %d in %d attempts! You're amazing! 🏆\n", random_number, attempts);
            break;
        }

        // Check if user has run out of attempts in Medium or Hard mode
        if (max_attempts != -1 && attempts >= max_attempts) {
            printf("Oh no! You've run out of attempts. The correct number was %d. 😓\n", random_number);
            break;
        }

        // Give the user a hint after a few attempts
        if (attempts == 3) {
            printf("Hint: Try focusing on numbers in the middle range. You're getting close! 😏\n");
        } else if (attempts == 5 && difficulty != 'E' && difficulty != 'e') {
            printf("Hint: The number is %s than 50.\n", random_number > 50 ? "greater" : "less");
        }
    }

    // Ask if the user wants to play again
    printf("Would you like to play again? (yes/no): ");
    scanf("%s", play_again);

    if (strcmp(play_again, "yes") == 0 || strcmp(play_again, "Yes") == 0) {
        printf("Awesome! Let's do another round!\n");
        number_guessing_game();  // Restart the game
    } else {
        printf("Thanks for playing! Come back anytime for more guessing fun. 👋\n");
    }
}


void tic_tac_toe() {
    char board[3][3] = { {'1', '2', '3'}, {'4', '5', '6'}, {'7', '8', '9'} };
    int player = 1, choice;
    char mark;
    char play_again[10];

    // Function to print the Tic-Tac-Toe board
    void print_board() {
        printf("\nTic Tac Toe Board:\n");
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                printf(" %c ", board[i][j]);
                if (j < 2) printf("|");
            }
            if (i < 2) printf("\n---|---|---\n");
        }
        printf("\n");
    }

    // Function to check if there's a winner
    int check_winner() {
        // Check rows and columns for a win
        for (int i = 0; i < 3; i++) {
            if (board[i][0] == board[i][1] && board[i][1] == board[i][2]) return 1;
            if (board[0][i] == board[1][i] && board[1][i] == board[2][i]) return 1;
        }
        // Check diagonals for a win
        if (board[0][0] == board[1][1] && board[1][1] == board[2][2]) return 1;
        if (board[0][2] == board[1][1] && board[1][1] == board[2][0]) return 1;
        return 0;
    }

    // Function to check if the board is full (draw)
    int check_draw() {
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                if (board[i][j] != 'X' && board[i][j] != 'O') {
                    return 0;
                }
            }
        }
        return 1;
    }

    // Conversation starter
    printf("Welcome to Tic-Tac-Toe! 🎮\n");
    printf("Player 1 will use 'X', and Player 2 will use 'O'. Let's see who dominates the board!\n");
    print_board();

    // Main game loop
    while (1) {
        player = (player % 2) ? 1 : 2;
        mark = (player == 1) ? 'X' : 'O';

        printf("Player %d, it's your turn! 🌀\n", player);
        printf("Enter a number to mark your spot (1-9): ");
        scanf("%d", &choice);

        // Convert choice into row and column
        int row = (choice - 1) / 3;
        int col = (choice - 1) % 3;

        if (choice >= 1 && choice <= 9 && board[row][col] != 'X' && board[row][col] != 'O') {
            board[row][col] = mark;
            print_board();
        } else {
            printf("Oops! That spot is already taken or invalid. Try again, Player %d! ⛔\n", player);
            continue;  // Let the same player choose again
        }

        // Check for winner
        if (check_winner()) {
            printf("🎉 Hooray! Player %d has won the game with a masterful strategy! 🏆\n", player);
            break;
        }

        // Check for a draw
        if (check_draw()) {
            printf("It's a draw! Both players gave it their all. 🤝 Let's call it a tie!\n");
            break;
        }

        // Switch player
        player++;
    }

    // Play again option
    printf("Would you like to play another round of Tic-Tac-Toe? (yes/no): ");
    scanf("%s", play_again);

    if (strcmp(play_again, "yes") == 0 || strcmp(play_again, "Yes") == 0) {
        // Reset board for a new game
        char reset_board[3][3] = { {'1', '2', '3'}, {'4', '5', '6'}, {'7', '8', '9'} };
        memcpy(board, reset_board, sizeof(reset_board));  // Copy reset board back to board
        tic_tac_toe();  // Restart the game
    } else {
        printf("Thanks for playing! Hope to see you back for more Tic-Tac-Toe soon! 👋\n");
    }
}


void rock_paper_scissors() {
    int user_choice, bot_choice;
    char *choices[] = {"Rock", "Paper", "Scissors"};
    char play_again;

    srand(time(0));  // Seed random number generator for bot choice

    do {
        printf("\n=== Rock, Paper, Scissors ===\n");
        printf("Make your choice:\n");
        printf("1. Rock ✊\n");
        printf("2. Paper ✋\n");
        printf("3. Scissors ✌️\n");
        printf("Enter the number of your choice: ");
        scanf("%d", &user_choice);

        if (user_choice < 1 || user_choice > 3) {
            printf("Invalid choice! Please choose between 1 and 3.\n");
            continue;
        }

        bot_choice = rand() % 3 + 1;  // Bot randomly chooses between 1 and 3

        printf("\nYou chose %s! Calmly chose %s!\n", choices[user_choice - 1], choices[bot_choice - 1]);

        // Determine the winner
        if (user_choice == bot_choice) {
            printf("It's a tie! 😐 Let's try again.\n");
        } else if ((user_choice == 1 && bot_choice == 3) || 
                   (user_choice == 2 && bot_choice == 1) || 
                   (user_choice == 3 && bot_choice == 2)) {
            printf("You win! 🎉\n");
        } else {
            printf("Calmly wins! 🤖 Better luck next time!\n");
        }

        // Ask if user wants to play again
        printf("\nDo you want to play again? (y/n): ");
        scanf(" %c", &play_again);
        
    } while (play_again == 'y' || play_again == 'Y');

    printf("Thanks for playing! 😊\n");
}

#include <stdio.h>
#include <string.h>
#include <ctype.h>

void hangman() {
    const char *words[] = {"programming", "computer", "developer", "software", "algorithm", "data", "science", "challenge", "hangman", "function"};
    int num_words = sizeof(words) / sizeof(words[0]);
    const char *chosen_word = words[rand() % num_words];
    int word_length = strlen(chosen_word);
    char guessed[word_length];
    char incorrect_guesses[26]; // To keep track of incorrect guesses
    int incorrect_count = 0;
    int attempts = 6; // Total attempts allowed

    // Initialize guessed array with underscores
    for (int i = 0; i < word_length; i++) {
        guessed[i] = '_';
    }
    guessed[word_length] = '\0'; // Null-terminate the string

    printf("\n=== Hangman Game ===\n");
    
    while (incorrect_count < attempts && strcmp(guessed, chosen_word) != 0) {
        printf("\nCurrent word: %s\n", guessed);
        printf("Incorrect guesses: ");
        for (int i = 0; i < incorrect_count; i++) {
            printf("%c ", incorrect_guesses[i]);
        }
        printf("\nAttempts remaining: %d\n", attempts - incorrect_count);
        
        char guess;
        printf("Guess a letter: ");
        scanf(" %c", &guess);
        guess = tolower(guess); // Convert to lowercase

        // Check if the letter has already been guessed
        if (strchr(incorrect_guesses, guess) || strchr(guessed, guess)) {
            printf("You've already guessed that letter. Try again!\n");
            continue;
        }

        // Check if the guessed letter is in the chosen word
        int found = 0;
        for (int i = 0; i < word_length; i++) {
            if (chosen_word[i] == guess) {
                guessed[i] = guess;
                found = 1;
            }
        }

        if (!found) {
            // Add to incorrect guesses
            incorrect_guesses[incorrect_count++] = guess;
            printf("Incorrect guess! 😢\n");
        } else {
            printf("Good guess! 🎉\n");
        }
    }

    // Game result
    if (strcmp(guessed, chosen_word) == 0) {
        printf("\nCongratulations! You've guessed the word: %s!\n", chosen_word);
    } else {
        printf("\nGame over! The word was: %s. Better luck next time!\n", chosen_word);
    }
}


#define SIZE 4 // Size of the memory grid (4x4)

void display_grid(int grid[SIZE][SIZE], int reveal) {
    printf("\nMemory Grid:\n");
    for (int i = 0; i < SIZE; i++) {
        for (int j = 0; j < SIZE; j++) {
            if (reveal) {
                printf("%2d ", grid[i][j]); // Show numbers
            } else {
                printf(" ? "); // Hide numbers
            }
        }
        printf("\n");
    }
}

void memory_challenge() {
    int grid[SIZE][SIZE];
    int user_guess[SIZE][SIZE] = {0}; // Array to store user guesses
    int correct_count = 0;
    int attempts = 3; // Number of attempts to recall the grid

    // Seed random number generator
    srand(time(0));

    // Fill the grid with random numbers (1-9)
    for (int i = 0; i < SIZE; i++) {
        for (int j = 0; j < SIZE; j++) {
            grid[i][j] = rand() % 9 + 1; // Random numbers from 1 to 9
        }
    }

    // Display the grid with a delay
    display_grid(grid, 1); // Show the grid
    printf("\nMemorize the numbers! You have 5 seconds...\n");
    sleep(5); // Delay for 5 seconds
    system("clear"); // Clear the screen (use "cls" for Windows)

    // Hide the grid
    display_grid(grid, 0); // Hide the grid

    // User attempts to recall the numbers
    printf("\nNow, recall the numbers. You have %d attempts:\n", attempts);
    for (int attempt = 0; attempt < attempts; attempt++) {
        printf("\nAttempt %d:\n", attempt + 1);
        
        for (int i = 0; i < SIZE; i++) {
            for (int j = 0; j < SIZE; j++) {
                printf("Enter your guess for position [%d][%d]: ", i + 1, j + 1);
                scanf("%d", &user_guess[i][j]);

                if (user_guess[i][j] == grid[i][j]) {
                    correct_count++;
                }
            }
        }

        printf("\nYou recalled %d out of %d numbers correctly!\n", correct_count, SIZE * SIZE);
        if (correct_count == SIZE * SIZE) {
            printf("Amazing! You remembered everything! 🎉\n");
            return; // Exit if all numbers are remembered
        }
        correct_count = 0; // Reset for the next attempt
    }

    printf("\nGame over! Better luck next time! 😢\n");
    printf("The correct grid was:\n");
    display_grid(grid, 1); // Reveal the correct grid
}




void jokes() {
    int choice;
    char user_joke[256];

    // Array of jokes (variety of types)
    char *jokes_list[] = {
        "Why don't skeletons fight each other? They don't have the guts! 💀",
        "What do you call cheese that isn't yours? Nacho cheese! 🧀",
        "I used to play piano by ear, but now I use my hands. 🎹",
        "Why was the math book sad? It had too many problems. 📖",
        "Did you hear about the kidnapping at the playground? They woke up! 😴",
        "Why can’t your nose be 12 inches long? Because then it would be a foot! 👃",
        "What did the janitor say when he jumped out of the closet? Supplies! 🧹",
        "I invented a new word! Plagiarism! 🤓",
        "How does a penguin build its house? Igloos it together. 🐧",
        "Why did the coffee file a police report? It got mugged! ☕",
        "I'm terrified of elevators, so I'm going to start taking steps to avoid them. 🏢",
        "What do you call a factory that makes good products? A satisfactory. 🏭",
        "I only know 25 letters of the alphabet. I don’t know Y. 🤔",
        "What's brown and sticky? A stick! 🌳",
        "Why don't eggs tell jokes? They'd crack each other up! 🥚",
        "Why did the golfer bring two pairs of pants? In case he got a hole in one! ⛳",
        "What did the ocean say to the beach? Nothing, it just waved! 🌊",
        "I asked my dog what’s two minus two. He said nothing. 🐶",
        "Why can’t you give Elsa a balloon? Because she’ll let it go! 🎈",
        "What lights up a soccer stadium? A soccer match! ⚽",
        "Knock knock.\nWho's there?\nBoo.\nBoo who?\nDon't cry, it's just a joke! 😢",
        "Why don’t sharks eat clowns? Because they taste funny! 🤡",
        "Why did the tomato turn red? Because it saw the salad dressing! 🍅",
        "What’s the best thing about Switzerland? I don’t know, but the flag is a big plus! 🇨🇭",
        "I’m on a seafood diet. I see food, and I eat it! 🍤",
        "Why don't some couples go to the gym? Because some relationships don’t work out! 🏋️",
        "Why are skeletons so calm? Because nothing gets under their skin! 💀",
        "What’s a skeleton’s least favorite room? The living room! 🏠",
        "I would tell you a chemistry joke, but I know I wouldn’t get a reaction. ⚗️",
        "Why did the bike fall over? Because it was two-tired! 🚲",
        "I told my computer I needed a break, and now it won’t stop sending me Kit-Kats. 🍫",
        "Why do cows wear bells? Because their horns don’t work! 🐄",
        "What did the big flower say to the little flower? Hey, bud! 🌼",
        "Why was the stadium so hot? Because all the fans left! 🏟️",
        "Did you hear about the two guys who stole a calendar? They each got six months! 📅",
        "What do you call a pile of cats? A meow-tain! 🐱",
        "Why do seagulls fly over the ocean? Because if they flew over the bay, they’d be bagels! 🥯",
        "Why did the picture go to jail? Because it was framed! 🖼️",
        "Why don't ants get sick? Because they have tiny ant-bodies! 🐜",
        "I don’t trust stairs because they’re always up to something! 🚶",
        "What do you call a snowman with a six-pack? An abdominal snowman! ⛄",
        "Why did the man put his money in the blender? He wanted to make some liquid assets! 🤑",
        "What do you call an alligator in a vest? An in-vest-igator! 🐊",
        "What do you get when you cross a snowman with a vampire? Frostbite! 🧛‍♂️",
        "I tried to catch fog yesterday. Mist. 🌫️",
        "Want to hear a joke about construction? I’m still working on it. 🏗️"
    };

    int total_jokes = sizeof(jokes_list) / sizeof(jokes_list[0]);
    int joke_index = 0;

    printf("\nAlright, let's have some laughs! 😂\n");
    printf("I'll start with some of my favorite jokes, and if you're up for it, you can share some too!\n");

    while (1) {
        printf("\n=== Joke Time ===\n");
        printf("1. Tell me a joke\n");
        printf("2. I want to tell you a joke!\n");
        printf("3. I'm done laughing for now, take me back!\n");
        printf("Choose an option: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                // Tell a joke from the list
                if (joke_index < total_jokes) {
                    printf("\n%s\n", jokes_list[joke_index]);
                    joke_index++;
                } else {
                    printf("\nLooks like I've told you all my jokes! You can share one if you want! 🤔\n");
                    joke_index = 0;  // Reset to allow repeating jokes if needed
                }
                break;
            case 2:
                // Allow the user to share their own joke
                printf("\nGreat! I'd love to hear your joke! Type it below:\n");
                getchar(); // To clear the newline from the input buffer
                fgets(user_joke, sizeof(user_joke), stdin);
                printf("\nHaha, that's a good one! 😄 Here's a virtual high-five for that! ✋\n");
                break;
            case 3:
                // Exit the jokes section
                printf("\nAlright, I'll save the laughs for another time! 😂 Take care!\n");
                return;
            default:
                printf("Oops! That's not a valid choice. Try again! 🤔\n");
        }
    }
}


void motivational_quotes() {
    int choice;
    char user_quote[256];

    // Array of motivational quotes
    char *quotes_list[] = {
        "The only way to do great work is to love what you do. – Steve Jobs",
        "Success is not the key to happiness. Happiness is the key to success. – Albert Schweitzer",
        "Don’t watch the clock; do what it does. Keep going. – Sam Levenson",
        "The future belongs to those who believe in the beauty of their dreams. – Eleanor Roosevelt",
        "Believe you can and you're halfway there. – Theodore Roosevelt",
        "It does not matter how slowly you go as long as you do not stop. – Confucius",
        "Your limitation—it’s only your imagination.",
        "Push yourself, because no one else is going to do it for you.",
        "Great things never come from comfort zones.",
        "Success doesn’t just find you. You have to go out and get it.",
        "Don’t stop when you’re tired. Stop when you’re done.",
        "Wake up with determination. Go to bed with satisfaction.",
        "Do something today that your future self will thank you for.",
        "Little things make big days.",
        "It’s going to be hard, but hard does not mean impossible.",
        "Don’t wait for opportunity. Create it.",
        "Sometimes we’re tested not to show our weaknesses, but to discover our strengths.",
        "Dream it. Wish it. Do it.",
        "Success is what happens after you have survived all your mistakes.",
        "The harder you work for something, the greater you’ll feel when you achieve it.",
        "Dream bigger. Do bigger.",
        "Don’t let yesterday take up too much of today. – Will Rogers",
        "The only limit to our realization of tomorrow is our doubts of today. – Franklin D. Roosevelt",
        "Act as if what you do makes a difference. It does. – William James",
        "Keep your face always toward the sunshine—and shadows will fall behind you. – Walt Whitman",
        "What lies behind us and what lies before us are tiny matters compared to what lies within us. – Ralph Waldo Emerson",
        "Failure will never overtake me if my determination to succeed is strong enough. – Og Mandino",
        "We generate fears while we sit. We overcome them by action. – Dr. Henry Link",
        "Do what you can with all you have, wherever you are. – Theodore Roosevelt",
        "What you get by achieving your goals is not as important as what you become by achieving your goals. – Zig Ziglar",
    };

    int total_quotes = sizeof(quotes_list) / sizeof(quotes_list[0]);
    int quote_index = 0;

    printf("\nLet's get inspired! 💪\n");
    printf("I'll share some motivational quotes, and you can share yours too if you'd like!\n");

    while (1) {
        printf("\n=== Motivation Station ===\n");
        printf("1. Give me a motivational quote\n");
        printf("2. I want to share a motivational quote!\n");
        printf("3. I'm feeling inspired, take me back!\n");
        printf("Choose an option: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                // Provide a motivational quote from the list
                if (quote_index < total_quotes) {
                    printf("\n%s\n", quotes_list[quote_index]);
                    quote_index++;
                } else {
                    printf("\nThat's all the quotes I have for now! Do you have one to share? 🤔\n");
                    quote_index = 0;  // Reset to allow repeating quotes if needed
                }
                break;
            case 2:
                // Allow the user to share their own motivational quote
                printf("\nI'd love to hear your motivational quote! Type it below:\n");
                getchar();  // Clear the newline from the input buffer
                fgets(user_quote, sizeof(user_quote), stdin);
                printf("\nWow, that's so inspiring! 🌟 Thanks for sharing!\n");
                break;
            case 3:
                // Exit the motivational section
                printf("\nAlright, stay motivated! 💪 I'll be here whenever you need more inspiration!\n");
                return;
            default:
                printf("Hmm, that's not a valid choice. Try again! 🤔\n");
        }
    }
}

void deep_conversations() {
    int choice;
    char user_thoughts[256];

    // Array of deep conversation questions
    char *deep_questions[] = {
        "What does happiness mean to you?",
        "If you could change one thing about the world, what would it be?",
        "What do you think is your purpose in life?",
        "Is there such a thing as absolute truth, or is everything subjective?",
        "What moment in your life has shaped you the most?",
        "Do you believe that everything happens for a reason?",
        "What is one thing you wish you could tell your younger self?",
        "How do you define success, and are you working towards it?",
        "If today were your last day, how would you spend it?",
        "What do you think happens after we die?",
        "Do you think technology is bringing us closer together or pulling us apart?",
        "What role does fear play in your life?",
        "What do you think is the meaning of life?",
        "Do you believe in destiny, or do we control our own fates?",
        "Is there a person in your life who changed you in a profound way?",
        "How do you measure your own worth?",
        "If you had all the money in the world, what would you do with your life?",
        "What does love mean to you?",
        "What do you fear the most?",
        "How do you handle the pressures of society’s expectations?"
    };

    int total_questions = sizeof(deep_questions) / sizeof(deep_questions[0]);
    int question_index = 0;

    printf("\nLet's have a deep conversation. Sometimes, it's good to reflect on the bigger questions in life. 💭\n");
    printf("I'll ask you some questions, and you can share your thoughts. Feel free to ask me questions too!\n");

    while (1) {
        printf("\n=== Deep Conversations ===\n");
        printf("1. Ask me a deep question\n");
        printf("2. I want to share my thoughts\n");
        printf("3. I need some time to think, take me back\n");
        printf("Choose an option: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                // Ask the user a deep question from the list
                if (question_index < total_questions) {
                    printf("\n%s\n", deep_questions[question_index]);
                    question_index++;
                } else {
                    printf("\nWe've explored a lot of deep questions! Do you have something on your mind? 🤔\n");
                    question_index = 0;  // Reset for new questions if needed
                }
                break;
            case 2:
                // Allow the user to share their own thoughts on any deep topic
                printf("\nI'm here to listen. What's on your mind?\n");
                getchar();  // Clear the newline from the input buffer
                fgets(user_thoughts, sizeof(user_thoughts), stdin);
                printf("\nThat's really profound. 🌿 It sounds like you're reflecting deeply on this. Do you want to explore it more?\n");
                break;
            case 3:
                // Exit the deep conversations section
                printf("\nIt's important to take time to think. When you're ready, we can continue our conversation. 🌌\n");
                return;
            default:
                printf("Hmm, that's not a valid choice. Try again, let's dive deeper! 🌊\n");
        }
    }
}

void therapist() {
    int choice;
    char user_feelings[256];
    
    printf("\nIt seems like you're going through something right now. I'm here to listen and help guide you. 💙\n");
    printf("Remember, you're not alone, and sometimes talking it out can help. Let's explore some options together.\n");

    while (1) {
        printf("\n=== Therapist Assistance ===\n");
        printf("1. I'm feeling uncertain, can you help guide me through my thoughts?\n");
        printf("2. Let's talk about my feelings more in depth.\n");
        printf("3. I need some motivational advice to get through this.\n");
        printf("4. I need a therapist's contact number.\n");
        printf("5. I need a doctor's contact number.\n");
        printf("6. I want to go back to the main menu.\n");
        printf("Choose an option: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                // Guiding the user through uncertainty
                printf("\nIt’s okay to feel uncertain sometimes. We all go through moments like these. 🌱\n");
                printf("Let’s break things down. When you feel unsure, start by asking: What’s making me feel this way?\n");
                printf("Is it a specific situation or an overwhelming mix of thoughts?\n");

                printf("\nWhat would you say is the biggest thing on your mind right now? You can tell me, I’m here to listen.\n");
                getchar();  // Clear newline
                fgets(user_feelings, sizeof(user_feelings), stdin);
                printf("\nThanks for sharing that with me. It sounds like you’re dealing with something important. 🌿\n");
                printf("When you’re faced with challenges, it’s helpful to break them down into smaller pieces. Can you focus on one small step at a time?\n");
                printf("Also, remember that it's okay to not have all the answers right now. Give yourself the space to take things one step at a time.\n");
                printf("Take a deep breath. Let’s move through this together, one thought at a time. 🌸\n");
                break;

            case 2:
                // Diving deeper into emotions
                printf("\nLet’s talk about your feelings in more depth. 💬 Sometimes putting words to emotions can help.\n");
                printf("What emotion are you feeling the most strongly right now? Is it fear, sadness, frustration, or something else?\n");
                getchar();  // Clear newline
                fgets(user_feelings, sizeof(user_feelings), stdin);
                printf("\nI see. That’s a powerful feeling, and it’s completely valid. 🌼\n");
                printf("When we feel these emotions, it’s important to let ourselves experience them without judgment. It’s okay to feel what you’re feeling.\n");
                printf("Think about how you can be kind to yourself during this time. Maybe give yourself a break, talk to someone you trust, or even write down your thoughts.\n");
                printf("Emotions are like waves – they come and go. The key is to let them flow without holding onto them too tightly. 🌀\n");
                break;

            case 3:
                // Providing motivational advice
                printf("\nYou're stronger than you think. 🌟 No matter what you're facing right now, remember that every challenge is an opportunity to grow.\n");
                printf("Even when things feel tough, you have the inner strength to keep moving forward. Sometimes it's about taking one small step, no matter how hard it feels.\n");
                printf("Think about the times you’ve overcome difficulties in the past. What helped you push through then?\n");
                getchar();  // Clear newline
                fgets(user_feelings, sizeof(user_feelings), stdin);
                printf("\nThat’s amazing! 💪 You’ve already come so far, and I believe you can handle this too. Keep reminding yourself of the strength you’ve already shown.\n");
                printf("Here’s something to remember: Progress isn’t always linear. It’s okay if some days feel harder than others. What matters is that you keep trying.\n");
                printf("Take a deep breath, and know that you have everything you need to overcome this. I believe in you. 🌈\n");
                break;

            case 4:
                // Provide the contact number for a therapist
                printf("\nHere's a contact number for a trusted therapist: 123-456-7890. 📞\n");
                printf("Talking to a professional can be incredibly helpful, even if it’s just to have someone listen and help you organize your thoughts.\n");
                printf("Therapists are trained to help guide you through tough times. Don’t hesitate to reach out if you feel ready. 🌻\n");
                break;

            case 5:
                // Provide the contact number for a doctor
                printf("\nHere's a contact number for a doctor: 987-654-3210. 🩺\n");
                printf("If you feel that your mental or physical health is affected, a doctor can help provide more specific advice or refer you to a specialist.\n");
                printf("It’s okay to seek help, and reaching out to a professional is a brave and important step. 🌺\n");
                break;

            case 6:
                // Return to the main chatbot menu
                printf("\nIt’s been great talking with you. Remember, you're not alone in this. 💙 Take care of yourself, and I'll be here if you ever need to talk again.\n");
                return;

            default:
                printf("Hmm, that's not a valid choice. Let's try again. 💭\n");
        }
    }
}



void chatbot() {
    int choice;
    char mood[20], play_again[10];
    
    printf("\nWelcome to Calmly, your friendly chatbot! 😌 How are you feeling today?\n");
    printf("Type how you're feeling (e.g., happy, sad, stressed, excited): ");
    scanf("%s", mood);
    
    printf("\nThanks for sharing that you're feeling %s! 😊 Now, how can I assist you today?\n", mood);
    
    while (1) {
        printf("\n=== Calmly Chatbot ===\n");
        printf("1. Talk to me (Words of Affirmation)\n");
        printf("2. Play a game\n");
        printf("3. Math helper\n");
        printf("4. Therapist/Doctor contact\n");
        printf("5. Jokes (Need a good laugh?)\n");
        printf("6. Motivational quotes (Get inspired!)\n");
        printf("7. Deep conversations (Let's get real)\n");
        printf("8. Exit\n");
        printf("Choose an option: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                provide_affirmations();
                break;
            case 2:
                printf("\nGreat! Let's have some fun. 😄\n");
                printf("Choose a game from the list below:\n");
                printf("1. Number Guessing\n");
                printf("2. Tic-Tac-Toe\n");
                printf("3. Rock, Paper, Scissors\n");
                printf("4. Hangman\n");
                printf("5. Memory Challenge\n");
                printf("Which game would you like to play? Enter the number of your choice: ");
    
                 int game_choice;
                    scanf("%d", &game_choice);
    
                    switch (game_choice) {
                    case 1:
                        printf("You chose Number Guessing! Let's test your guessing skills. 🎯\n");
                        number_guessing_game();
                        break;
                    case 2:
                        printf("Tic-Tac-Toe it is! Get ready for some strategy! 🤓\n");
                        tic_tac_toe();
                        break;
                    case 3:
                     printf("Rock, Paper, Scissors! Let's see who wins! ✊✋✌️\n");
                        // Placeholder for rock_paper_scissors function
                        rock_paper_scissors();
                        break;
                    case 4:
                     printf("Hangman, a word puzzle awaits you! 🧠\n");
                        // Placeholder for hangman function
                        hangman();
                        break;
                    case 5:
                     printf("Memory Challenge, let's see how sharp your memory is! 🧠\n");
                        // Placeholder for memory_challenge function
                     memory_challenge();
                     break;
                    default:
                        printf("Oops! That’s not a valid game choice. 😅 Let's try again.\n");
                    }
            break;

            case 3:
                math_helper();
                break;
            case 4:
                therapist();
                break;

            case 5:
                // Placeholder for jokes function
                printf("Let's lighten the mood with some jokes! 😄\n");
                jokes(); // To be defined later
                break;
            case 6:
                // Placeholder for motivational quotes function
                printf("Need a motivational boost? Let me inspire you! 💪\n");
                motivational_quotes(); // To be defined later
                break;
            case 7:
                // Placeholder for deep conversations function
                printf("I'm here for a deep conversation. Let's talk. 🧠\n");
                deep_conversations(); // To be defined later
                break;
            case 8:
                printf("Goodbye! Take care, and come back anytime! 👋\n");
                exit(0);
            default:
                printf("Invalid option! Please try again.\n");
        }
    }
}



int main() {
    chatbot();
    return 0;
}
