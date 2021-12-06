
# Project Veda-Vyasa

Project Veda Vyasa is a grammar correction model, developed through Natural Language Processing. Some of the main NLP concepts used in this project include Sentence Segmentation, Data Collection, Lemmatization, Parts-of-Speech Tagging, etc. The basic vision is that once a specific paragraph or file is entered, the system checks for grammatical errors in the same and produces the corrected version.


## Phase 1
Phase 1 of Project Veda-Vyasa consists mainly of three simple but important steps. The first step is Sentence Segmentation, where the paragraph in the text file that is uploaded are divided into multiple sentences and saved in an array. This is the second step of Data Collection, where sentences are all uploaded to a csv file and saved. The third step is Data Pre-Processing, where the csv file is imported as a DataFrame and Pre-Processing steps like expanding the words, removing unwanted spaces, removing punctuations, changing all the letters to lowercase, etc. is done. After that is over, we are left with a pre-processed DataFrame which can be used further in Phase 2.

## Features

- Can perform basic sentence segmentation
- Can perform required Data Pre-Processing
- Uses Spacy and Python3

## Libraries
The libraries used in Phase 1 of this project are spacy, pandas, re and csv.

Spacy is a library file used solely in NLP programs. Spacy was selected after extensive research on different library files, as it is faster, lighter and has better usage in Neural Networks and Deep Learning.

Pandas is a basic library file used for importing and using DataFrames, which is primarily used in Data Analysis and Pre-Processing. 

A regular expression (or RE) specifies a set of strings that matches it; the functions in this module let you check if a particular string matches a given regular expression (or if a given regular expression matches a particular string, which comes down to the same thing).

Csv is a library file used for creating, using and saving data in CSV file.

## Program Flow(This is according to Phase 1 V2)
When the main function is called, the user is asked to enter the paths to their .txt file and a new .csv file. If nothing is entered in the input, the system takes a default file that contains a short paragraph of around 12 sentences. The main function then calls the SentenceSegmentation() function, where the english language model for spacy reads the paragraph. Two arrays are created and the lines are segmented into separate sentences. The senteces are placed in the array and again in another array as separate array values. A .csv file is created, where the data is stored in different rows and saved. THe function then calls the DataPreProcessing() function, which imports the .csv file as a DataFrame and performs multiple Pre-Processing steps like expanding the words, removing unwanted spaces, removing punctuations, etc. The DataFrame is edited to have the new, modified values and is returned.

## References
[Grammar Error Correction](https://towardsdatascience.com/grammar-error-correction-af365dad794)

[Spacy](https://spacy.io)

[NLP Libraries and Functions](https://www.upgrad.com/blog/python-nlp-libraries-and-applications/)

[Top 10 NLP Libraries](https://analyticsindiamag.com/top-10-python-nlp-libraries-for-2019/)

[Ashutosh Tripathi Sentence Segmentation](https://ashutoshtripathi.com/2020/05/04/how-to-perform-sentence-segmentation-or-sentence-tokenization-using-spacy-nlp-series-part-5/)

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Authors

- [@SaiRaghava106](https://github.com/SaiRaghava106)


## Related

Here are some related projects

[Conundrum Archives](https://github.com/Conundrum-Archives)

