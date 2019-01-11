# pleco-mega-big-chinese-dictionary
Chinese language dictionary for Pleco, in correct headword/pinyin format, that joins together several frequency rankings (Giga db, Junda, subtlex), char metadata from Unihan (e.g. stroke count, unicode representation, and more coming), char count per word, HSK level for words and their constituent chars, and suggested orderings for language acquisition - including Yan, HSK, Heisig (coming soon), and - possibly the best out of all - Loach, whose method uses a topographic sort on a hierarchy of Chinese radicals -> characters -> words with weights based on frequency (common usage), stroke count, and radicals/chars required to compose the char/word. , download the XLS and export any of the fields or tables you want to TSV, then upload to Pleco as a user dictionary.

## Get started
To use, download big-table.xlsx and start pivoting!

## Add to Pleco as a user dictionary
1. To get it into Pleco's dictionary, export the fields you're interested in to a text (.txt) file in TSV format (each word on a new line, each line "<simplified>[<traditional>]\t<pinyin>\t<definition>" without the quotes and angle brackets.
2. Save the text file somewhere that can be accessed by mobile device. iCloud for iPhone or Google Cloud for Android is easiest.
2. Go to Pleco and create a new user dictionary.
3. Import the text file. (Search for "pleco import user dictionary" for a more detailed guide.)
  
## Add to Pleco as flashcards for practice
1. Sort the table by the preferred ranking/ordering and apply any interesting filters (e.g. stroke count, HSK level, etc.). Or create a weight score based on all of the rankings/orderings/metadata and sort by that. Alternatively, go to the sheet in the Excel for the specific ordering desired.
2. Copy only the words column into a text editing tool like Notepad++.
3. Every n lines, create a new line, where n is the preferred number of cards per flashcard set.
4. For every set, add a heading in the format "//<any text here>" without the quotes and angle brackets. Search "Pleco flashcards import" for more information on flashcard format.
5. Save this to a text (.txt) file.
6. Go to Pleco and manage flashcards.
7. Import the text file.
