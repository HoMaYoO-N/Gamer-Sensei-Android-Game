The Sudoku Sensei is the same as any other Sudoku puzzle except it uses words instead of numbers. 
Not only the players will have a fun time solving a Sudoku puzzle, they will also learn various words of a new language! 
Specifications: 
* The program is designed in VERTICAL mode.
* In the first page users can choose the difficulty level (currently just one).
In the puzzle page users.
* Can switch between languages.
* Get hints if they break Sudoku's rules.
* Get the translation if they tap on a word.  

Rquirements:
* It is built for Android. 
* It requires API 19. 
* It has been tested on NEXUS 5X smartphone, and on Pixel C tablet. 


User Stories

These set of stories are made to express a requirement, issue, need, and the reason behind that need, using the language of stakeholders. 

To do so, we consider ourselves as possible users of the app and develop stories that should be resolved by the developers. On the other hand, developers are required for estimating the time and effort to implement the stories, iteration by iteration.

Note that because we are in our very first iteration and we only have the basics of technical skills required, the first phase of stories tend to be more general and non-functional rather than detailed. Therefore, because of each iteration's time and complexity requirements, most of the user stories take a couple of hours by a single person to be implemented.

The agile developing style is used and stories are prioritized using the MoSCoW (Must Should Could Won't) approach. The goal of prioritizing the stories is so that we resolve the essential requirements first and continue with the elective requirements given we have sufficient time. Otherwise, they will remain for the next iteration.

Story#1(MUST)(**Added**): As a player of the game, I want a smooth and playable version of the game that can identify when I have the winning condition or when I lose with a delightful menu and interface so that I can actually experience playing the game.
* Example: A page that pops up if the user has the winning condition.
* Example: An user interface menu with?
* Example: An user interface game screen with?

Story#2(MUST)(**Added the features without coloring the row and the column**): As a player of the game, I want a 9 by 9 sudoku table containing visible and readable words with 3*3 subgrids(regions) divided from each other and colours demonstrating which row and column my current cell is located at.
* Example: Lines containing 3*3 Subgrids are bolded and divided from other lines(9 subgrids in total).
* Example: Words from both languages are blended in the cells yet visibile to the player. If the game is played on the phone and the word is too large to be read, the zoom-in option helps identifying it.

Story#3(MUST)(**Added**): As a player of the game, I want to be able to select the words to be inserted into a cell conveniently. 
* Example: Using a list beneath the sudoku table, the user may read and insert the words. They can also scroll the list to left or right to see the other word choices possible.
  * This option is better than a drop down menu for every cell because by using a drop menu, the icons would be too small to choose considering the game is played on a phone. 
  * This option is also better than a drop down menu in beneath of the table because then the menu could hide parts of the game being played.

Story#4(SHOULD)(**Added the feature with only two languages for now**): As a language learner, I want the ability to choose my preferred first and second language and interchange between them so that I can learn varieties of new languages by means of my first language.
* Example: Two languages, English and Mandarin are added and they are interchangeable.

Story#5(SHOULD)(**Added. The game is playable on tablets but some errors may happen**): As a teacher, I want the game to be playable on all
of the Android devices including tablets and phones so that the game can be installed on the tablets school provides to students and they will not use their phone during the class.
* Example: The development of the game is based on the proportions of the screen and therefore, no constant numbers of width and height are considered.

Story#6(SHOULD)(**Added**): As a player of the game, I want to be able to zoom in, zoom out and scroll through the table to see the words more clearly so that I can introduce it to my old grandmother who enjoys learning new languages and solving puzzles.
* Example: Added the features of zooming and scrolling so that words and phrases are more readable. When zooming, the list remains so that user can choose the words if intended to.

Story#7(SHOULD)(**Added**): As a player of the game, I do not want the size of the table to change if the word inserted is too wide.
* Example:  Words will wrap in the cells and even if they are unreadable, user can zoom and observe the letters more clearly.

Story#8(COULD)(**Added**): As a new language learner, I want to have a help button for the words to help me when I forget the translations.
* Example : There is a help button made so that it shows the translation of the new words momentarily.

Story#9(COULD)(**Not Added**): As a player of the game, I want to be notified if I entered a word that already exists in a row, column or subgrids so that I can stop the error before happening.
* Example: The colours that demonstrate the row and column of the cell being played turn into red.
* Example: A pop-up will notify the user about his/her mistake and the cell intervening with the answer will turn into red colour.

Story#10(COULD)(**Not Added**): As a teacher, I want the ability to add new 
languages or pairs of new words manually into the current library of the game so that my students can discover them.
* Example: User can insert new groups of words and they will be added in a local database. The user then will be asked if he/she is interested to contribute and add the pairs to the database on the internet that can be used by everyone.
* Example: Words and pairs will be randomly or manually inserted into the table for the languages of choice.

Story#11(COULD)(**Not Added**): As a teacher, I want to have access to a wide database of the new words and languages that could be added into the game so that I can explore new mixed words with my students.
* Example: A user data base will be created on Git so that everyone can contribute and add new words and new languages. When downloaded, random mixes of selected languages will be inserted into the table.

Story#12(COULD)(**Not Added**): As a teacher, I want the ability to take a quiz using the game from all of my students in the class. I want to connect them together so I can see their data and progression for grading them.
* Example: A laning ability will be put on the game so that many people can connect to the lan platform and then they all start the same or simillar game of admin's choice. Event has a limited time and whoever finishes the puzzle faster will get a higher score. Mistakes will reduce the score. The admin(in our case, the teacher) will observe each individual's perfromance and progress. He/she also observes everyone's score at each moment.

Story#13(COULD)(**Not Added**): As a player of the game, I want to have a multiplayer option so that I can connect to my friends and beat their records.
* Example: A multiplayer platform is created where players can compete with each other or in teams and they will be ranked based on their performance. They can also communicate with each other using a chat wheel. One form of the competition is that both players will be given the same table but with different languages of their choice. The game ends if the timer runs out as a draw or if one player finishes the puzzle.

Story#14(COULD)(**Not Added**): As a player of the game, I want the puzzling part to have
diversity meaning that each time, I do not have to play the same game. This adds more analyzation and complexity into the game.
* Example: Different versions of the actual sudoku are added with various difficulties.  

Story#15(COULD)(**Not Added**): As a new sudoku player, playing sudoku with words in new language can be challenging at first. Therefore, I want the game to have a learning option so that I am introduced to the basics of the sudoku and the game.
* Example: A learning sub-menu is added to the main menu where the player is introduced to the basics of the sudoku game and differences between this game and sudoku game. The options of adding a new language or words from the online data base are explained. It can be a video at first and as the game develops we will make it more interactive.

Story#16(COULD)(**Not Added**): As a player of the game, I want to have different sets of difficulties both in terms of words and sodoku itself so I can experience more challenging sets games.
* Example: Many diverse versions of actual sudoku are added into the database. Each time one of them will be chosen based on difficulty level and randomness.
* Example: Each time an auto generation algorithm will design the game differently.
* Example: Few diverse verions are added but each time the a few rows or columns are interchanged with each other to make a new puzzle.
* Example: Each time based on difficulty level and randomness, more complex combinations of the words will be added.

Story#17(WON'T)(**Not Added**): As a player of the game, I want a hint option that tells me which cell might be easier to fill so that when I have a clue when cannot find any cell to fill.
* Example: A sudoku solving algorithm will be implemented and each time(up to two times) a user asks for a hint, the next step cell selection of the algorithm will suggest a cell to him/her.
![image.png](https://www.dropbox.com/s/uy1gdmv7vawkvz6/image.png?dl=0&raw=1)


