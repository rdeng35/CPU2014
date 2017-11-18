
# Final-Project
##
# Design  Document

### PROBLEM TO BE SOLVED:
Determine trigrams and calculate the frequencies of each trigrams
Determine the similarity between two vectors using a cosine similarity formula

### FUNCTIONS:
inFile.open(file)
  #Opens the file
  #Reads the text from the file

getText()
  #Returns text

getTrigram(getText)
  #Reads 3 characters at a time including spaces from the sequence
  #Returns trigrams

getFrequency(trigrams)
  #Calculates the number of times the Trigram appears in a sequence
  #Stores frequency into a vector 27^3 elements long
  #Returns frequency

getSimilarity(frequency)
  #Compares two vectors
  #Implements cosine similarity formula
  #Returns 0 or 1

getLanguage(frequency)
  #gets filenames(languages) from the language executable
  #TRAINING DATA = all the filenames except for the last
  #TEST DATA = Last filename
  #gets the frequency of each trigram for each TRAINING data and the TEST data
  #checks which trigram frequency closely matches up with the languages from the TEST data using the Cosine Similarity Formula
  #x=getSimilarity(frequency)
  #Outputs the filename with most-similar training input on a new line

FILES NEEDED:
frequency.h
language.h

LIBRARIES:
string
fstream
iostream
algorithim
vector
cstdlib


MAIN:
milestone1-
#Opens the filename
#Gets the text and reads the text 3 characters at a time returning a Trigram
#Gets the frequency of each trigram within the text


milestone2-
#Allows user to input 2 or more command-lines on the LANGUAGE executable
#Command-lines become the filename
#Computes the frequency of each trigram for EACH filename
#Compares the frequency of the LAST inputted filename to the other filenames
#Based on frequency, calculates the similarity between all filenames


COMPILE:
