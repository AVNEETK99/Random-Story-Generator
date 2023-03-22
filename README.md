# Random-Story-Generator

A random story generator game is a game that generates stories randomly by combining different story elements such as characters, settings, and plot points. These games often have a database of pre-written story elements, which are selected at random and combined to create unique and often humorous stories.

Players of these games can often choose from different story genres such as science fiction, fantasy, or romance, and can also select different story elements to include or exclude from the story generation process.

These games are often used as a creative writing exercise or as a fun activity for groups of people to engage in storytelling together. They can be played online or through downloadable software.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python story.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The ```import random``` statement imports the random module in Python, which allows generating random numbers, selecting random elements from a sequence, and shuffling sequences randomly.

* The ```Sentence_starter```, ```character```, ```time```, ```story_plot```, ```place```, ```second_character```, ```age```, and ```work``` variables are lists of different story elements.

* The ```print``` statement prints a random combination of the above variables concatenated together to generate a random story. It does this by using the ```random.choice()``` method to randomly select one element from each of the variables and concatenating them with ```+``` signs.

* The output will be a randomly generated sentence that combines one element from each of the variables to create a sentence such as ```"Once upon a time there lived a farmer. One day he saw a man who seemed very old and feeble digging a well on the roadside." ```or``` "In the 20 BC there was a man named Jack. One full-moon night he saw a young lady who seemed to be in late 20s searching something."```

