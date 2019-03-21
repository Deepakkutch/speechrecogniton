# SPEECH RECOGNITION 

# Group Members

Arun Kumar S-711715104009

Deepak G-  711715104012

Karthik Raja M- 711715104028



SpeechRecognition
=================


# Problem statement

Design a system to convert speech to text files from audio and video files to extract keywords or keyphrases.


# Installing
----------

First, make sure you have all the requirements listed in the "Requirements" section. 

The easiest way to install this is using ``pip install SpeechRecognition``.

Otherwise, download the source distribution from `PyPI <https://pypi.python.org/pypi/SpeechRecognition/>`__, and extract the archive.

In the folder, run ``python setup.py install``.

# Requirements
------------

To use all of the functionality of the library, you should have:

* Python 2.7
* speechrecognition 3.8.1
* moviepy 1.0.0
* rake-nltk 1.0.4
* Pyaudio 0.2.9



# Quickstart

```
pip install speechRecognition
```
To install Speech Recognition python package to convert speech to text

```
pip install rake-nltk

```

To install RAKE algorithm for the extraction of the keywords

```
pip install moviepy
```
To import Moviepy package used in the conversion of video files to text

```
pip install tkinter 

``` 
Python package to install tkinter used in the development of the user interface


# Develope Environment

Pycharm IDE 3.4

# Module Splitup

**Module 1:**
   User interface creation
   
**Module 2:**
   Speech to text conversion
   
**Module 3:**
   Keyword Extraction

# Task Splitup

Arunkumar ---> User interface(Tkinter) and Design of the project workflow

Deepak ---> Implementation of speech to text conversion for both audio and video

Karthik Raja  --->Implementation of Keyword Extraction using RAKE algorithm

# Technologies used

Python

Tkinter

# Processes done so far

Conversion of structured and unstructured audio and video files using google speech recognition api.

Extraction of keywords from the output file using RAKE(Rapid Automatic Keyword Extraction) algorithm.

Main feature of selecting RAKE algorithm is that it is domain independent and can analyse the frequency of the word appreance and its 
co-occurance with other words in the text. 



# Future plan 

Extracting knowledge using the obtained keywords.
User can search any keywords and the program can deliver all the audio & video corresponding the 
search query.




