# SPEECH RECOGNITION 

# Group Members

Arun Kumar S-711715104009

Deepak G-  711715104012

Karthik Raja M- 711715104028



SpeechRecognition
=================

# Installing
----------

First, make sure you have all the requirements listed in the "Requirements" section. 

The easiest way to install this is using ``pip install SpeechRecognition``.

Otherwise, download the source distribution from `PyPI <https://pypi.python.org/pypi/SpeechRecognition/>`__, and extract the archive.

In the folder, run ``python setup.py install``.

# Requirements
------------

To use all of the functionality of the library, you should have:

* **Python** 2.6, 2.7, or 3.3+ (required)
* **PyAudio** 0.2.11+ (required only if you need to use microphone input, ``Microphone``)
* **PocketSphinx** (required only if you need to use the Sphinx recognizer, ``recognizer_instance.recognize_sphinx``)
* **Google API Client Library for Python** (required only if you need to use the Google Cloud Speech API,



**Quickstart:** ``pip install SpeechRecognition``. See the "Installing" section for more details.

To quickly try it out, run ``python -m speech_recognition`` after installing.


Python
~~~~~~

The first software requirement is `Python 2.6, 2.7, or Python 3.3+ <https://www.python.org/download/releases/>`__. This is required to use the library.

PyAudio (for microphone users)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`PyAudio <http://people.csail.mit.edu/hubert/pyaudio/#downloads>`__ is required if and only if you want to use microphone input (``Microphone``). PyAudio version 0.2.11+ is required, as earlier versions have known memory management bugs when recording from microphones in certain situations.

If not installed, everything in the library will still work, except attempting to instantiate a ``Microphone`` object will raise an ``AttributeError``.

The installation instructions on the PyAudio website are quite good - for convenience, they are summarized below:

* On Windows, install PyAudio using `Pip <https://pip.readthedocs.org/>`__: execute ``pip install pyaudio`` in a terminal.
* On Debian-derived Linux distributions (like Ubuntu and Mint), install PyAudio using `APT <https://wiki.debian.org/Apt>`__: execute ``sudo apt-get install python-pyaudio python3-pyaudio`` in a terminal.
    * If the version in the repositories is too old, install the latest release using Pip: execute ``sudo apt-get install portaudio19-dev python-all-dev python3-all-dev && sudo pip install pyaudio`` (replace ``pip`` with ``pip3`` if using Python 3).
* On OS X, install PortAudio using `Homebrew <http://brew.sh/>`__: ``brew install portaudio``. Then, install PyAudio using `Pip <https://pip.readthedocs.org/>`__: ``pip install pyaudio``.
* On other POSIX-based systems, install the ``portaudio19-dev`` and ``python-all-dev`` (or ``python3-all-dev`` if using Python 3) packages (or their closest equivalents) using a package manager of your choice, and then install PyAudio using `Pip <https://pip.readthedocs.org/>`__: ``pip install pyaudio`` (replace ``pip`` with ``pip3`` if using Python 3).

PyAudio `wheel packages <https://pypi.python.org/pypi/wheel>`__ for common 64-bit Python versions on Windows and Linux are included for convenience, under the ``third-party/`` `directory <https://github.com/Deepakkutch/speechrecogniton>`__ in the repository root. To install, simply run ``pip install wheel`` followed by ``pip install ./third-party/WHEEL_FILENAME`` (replace ``pip`` with ``pip3`` if using Python 3) in the repository `root directory <https://github.com/Deepakkutch/speechrecogniton>`__.





# Problem statement

A speech to text conversion system.

Can process both audio and video files.

Has the ability to extract keywords from the processed audio.

Can identify the flavour of the processed audio or video file.

# Minimum System Requirements

* Python 2.7
* speechrecognition
* moviepy
* rake-nltk

# Technologies used

Python

Tkinter

# Processes done so far

Conversion of structured and unstructured audio and video files using google speech recognition api.

Extraction of keywords from the output file using RAKE(Rapid Automatic Keyword Extraction) algorithm.

Main feature of selecting RAKE algorithm is that it is domain independent and can analyse the frequency of the word appreance and its 
co-occurance with other words in the text. 

# Splitup

Arunkumar-----User interface(Tkinter) and Design of the project workflow

Deepak--------Implementation of speech to text conversion for both audio and video

Karthik Raja--Implementation of Keyword Extraction using RAKE algorithm

# Future plan 

Extracting knowledge using the obtained keywords.
User can search any keywords and the program can deliver all the audio & video corresponding the 
search query.




