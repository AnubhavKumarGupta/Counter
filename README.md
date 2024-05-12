# Word_Counter
Link. 👉 


##
- Word Counter using HTML, CSS, and JavaScript, including features like counting characters, words, sentences, paragraphs, estimating reading time, and generating top keywords.

  
![image](https://github.com/AnubhavKumarGupta/Word_Counter/assets/122034618/f8661d0a-ed0b-4de2-83d6-4d7c9b388d16)




##


## Features:

- Counts characters, words, sentences, and paragraphs.
- Estimates reading time.
- Identifies and displays top keywords.


## 

## Usage:
- To view the project, simply open the index.html file in your web browser.
- You can also explore the code in your preferred text editor to understand how the HTML and CSS work together to create the layout and styling.


## 

## How it Works:

The webpage utilizes JavaScript to analyze the text entered in the textarea. The script performs the following actions upon every keypress:

- Character Count: Calculates the total length of the input text (including spaces and special characters).
- Word Count: Splits the text into words using a regular expression that accounts for hyphens within words and considers any sequence of characters surrounded by word boundaries as a word.
- Sentence Count: Splits the text into sentences using a regular expression that identifies common sentence delimiters (periods, exclamation points, and question marks).
- Paragraph Count: Splits the text into paragraphs based on newline characters.
- Reading Time: Estimates reading time based on an assumed average reading speed (e.g., 275 words per minute). Words are counted, and the estimated time is displayed in minutes and seconds.

**Top Keywords:**
    - Removes stop words (common words like "the", "a", "an", etc.) and numbers from the word list.
    - Creates a dictionary object to store each unique word as a key and its frequency as a value.
    - Sorts the dictionary by word frequency (descending order).
    - Extracts the top 4 keywords and their counts and displays them in a list within the webpage.


## 


## Code Structure:

The project consists of the following files:

* `index.html`: The main HTML file containing the webpage layout and structure.
* `word.css`: The CSS file that styles the webpage elements.
* `word.js`: The JavaScript file that handles the text analysis and manipulation functionalities.

## 

## Customization:

* You can modify the CSS file (`word.css`) to change the appearance of the webpage.
* The JavaScript file (`word.js`) offers opportunities for further customization, such as:
    * Adjusting the estimated reading speed in the reading time calculation.
    * Modifying the stop words list to exclude or include additional words.
    * Changing the number of top keywords displayed.


## 
Feel free to explore and customize this Word Counter project to fit your needs!

