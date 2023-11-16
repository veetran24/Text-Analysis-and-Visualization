# Text-Analysis-and-Visualization

## Purpose:
The goal of this project is to analyze the frequency of key character mentions across the Harry Potter book series. Text data from seven books was combined and preprocessed to extract valuable insights. The analysis focuses on major characters, including Harry, Ron, Hermione, Dumbledore, Hagrid, Snape, Voldemort, etc. This can provide insight into which characters play central roles in the overall story.

## Data Prepocessing:
The text data from all 7 books is read in and combined into one large corpus. To prepare the text, punctuation is removed to ensure uniformity in word frequencies for the corpus text. Additionally, common English stop words like "the", "and", "a", etc. were filtered out because they do not provide meaningful information for the analysis. This cleaning process results in cleaner text focused only on the key words and eliminates extraneous punctuation and unnecessary words.

## Data Manipulation:
The cleaned text then underwent some manipulation to transform the text into useful frequency data. The first step was  splitting the long string (sentences) of text into individual words. With the words separated, it was possible to count the occurrences of each unique word using a Counter. This provided frequency distributions of the words. The 20 most common words were found to explore the overall data and mostly were character names around main character Harry Potter. Then to specifically analyze character names, fuzzy string matching was implemented to catch alternate spellings and nicknames of chosen names. By matching different versions of the names, the total frequency of each character could be determined regardless of how their name was written and How common frequency the names be appeared in the text. These steps converted the cleaned text into processed data on word and character name frequencies ready for analysis and visualization.

## Visualization and Text encodings explanation 

![chart](https://github.com/veetran24/Text-Analysis-and-Visualization/assets/116127511/516aa731-93f1-4b38-9b32-47a4161f0edf)

The bar chart visualization aims to clearly present the frequency of appearance of major characters Harry Potter  across the book series. Blue colored bars offer visual appeal without distraction. To make the plot easy to read, I use a large figure size, increased the font sizes of the axes labels to 14 points and bold, and made the title biggger font size. The 18 point bold title concisely conveys the plot's purpose. The most important customization is the descriptive X and Y axes labels like "Character Names" and "Frequency Count", which explain what is being plotted. The X-axis labels are rotated 45 degrees to fit the long character names and set at 12 points. I also added data labels above each bar to directly display the frequencies. A more descriptive title like "Frequency of Major Character Appearances across Harry Potter Book Series" could provide additional context, but may be too lengthy - so my improved version of "Appearance of Key Characters" is more explanatory. I also added a caption to provide context that this plot analyzes the Harry Potter book series which be offering transparency to the audience, so the font size 10 point caption is represented and placed as footnote in this visualization. Overall, design choices with including color, font sizes, label rotation, and data labeling aim to balance visual appeal to create a clean and easy-to-understand visualization with interpretability. Decisions around font size in particular focus on drawing attention to the most important elements like axes labels, while preserving readability. The result is a clean, easy to understand visualization supporting comprehension of character frequencies.  The result is a well-crafted visualization that strikes a thoughtful balance between visual appeal and the effective communication of character frequencies in the Harry Potter series.

## Word Cloud
The word cloud cleverly illustrates prominent Harry Potter character names in a cup-shaped image mask that evokes Harry Potter and The Goblet of Fire book. This creative visualization emphasizes key figures and provides an insightful glimpse into the character-driven narrative across Harry Potter book series.
![wordcloud](https://github.com/veetran24/Text-Analysis-and-Visualization/assets/116127511/8578283f-44bc-488e-9d6d-c8f7b95a77fa)


I also tried with the text from Book 2 - Harry Potter and the Chamber of Secrets. I used an image of Dobby - the Free Elf as preference for this book and it also showed the character names mostly appear from this sequel.
![dobby](https://github.com/veetran24/Text-Analysis-and-Visualization/assets/116127511/2dba07d9-3dcc-4e09-b6bb-f0a6fdb149e4)
