# Weekly Schedule

* [Week 1 (1/18) - Introduction](#week1)
* [Week 2 (1/25) - Scraping, (ir)regular expressions](#week2)
* [Week 3 (2/1) - Assignment 1 Assemblage Presentations](#week3)
* [Week 4 (2/8)](#week4)
* [Week 5 (2/15) - Assignment 2 Fiction Presentations](#week5)
* [Week 6 (2/21)](#week6)
* [Week 7 (3/1) - Final Presentations](#week7)

## <a name="week1"></a>Week 1 - Introduction / Python & Colab

### Week 1 (1/17) Introductions / Group Exercise / Colab
- Course Overview
- Introductions

- Group exercise
- Introduction to Python
  - [Learn Python tutorials](https://www.learnpython.org/en/Welcome)
    - [Hello, World!](https://www.learnpython.org/en/Hello%2C_World%21)
    - [String Formatting](https://www.learnpython.org/en/String_Formatting)
  - [Python 3 Tutorial](https://www.programiz.com/python-programming/tutorial)
- Introduction to [Jupyter Notebook](https://jupyter.org/)
- Introduction to [Google Colaboratory (Colab)](https://colab.research.google.com/notebooks/intro.ipynb)
  - [Introduction to Colab and Python](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb)
  - [01 Random Sentence Colab](https://colab.research.google.com/drive/1Abh3NBesmR3eN7bArhg-bgs1fYO-OqTR?usp=sharing)
  - [Example text - Project Gutenberg: Alice In Wonderland](http://www.gutenberg.org/ebooks/11)
  - [02 Getting a webpage Colab](https://colab.research.google.com/drive/1sNHW7SQ_VBcExKnsUzh311Vkzkbb1enW?usp=sharing)

#### Homework (due before start of next class 1/20)
- **Join** (optional) the IM Discord server #softwareart channel. Use of Discord is optional but allows you to ask questions and share links with the professor and class at any time.

- **Create** a Colab notebook that can generate a paragraph of text using algorithmically chosen words. Use at least 2 different algorithms for generating the individual sentences. Generate 5 paragraphs of text and include the generated paragraphs as static text in your notebook. Include a short write up:
  - Explain in words how the sentence is generated.
  - Is the output what you expected?
  - How could you generate an unexpected output?
- **Add** a link to your Colab to the [Sketches Spreadsheet](https://docs.google.com/spreadsheets/d/1r7vP1i6M4yef5M0_E-yHuoVpyYvxM1T05yCEytOVe4E/edit?usp=sharing) (login to your NYU Google account to access)

<!--
- **Read**
  - [Villem Flusser "On Doubt"](https://github.com/periode/software-art-text/blob/master/assets/readings/flusser_doubt.pdf)
  - **Add** 2-3 paragraphs of response to the [Readings Doc](https://docs.google.com/document/d/1bHBWPR4_hHviqBfkgYN6biPDV4-LfBecwr46cApOEgo/edit?usp=sharing) (login to your NYU Google account to access)
-->
- **Add** the text of a poem you like to the [Readings Doc](https://docs.google.com/document/d/1bHBWPR4_hHviqBfkgYN6biPDV4-LfBecwr46cApOEgo/edit?usp=sharing) (login to your NYU Google account to access). Be prepared to explain what appeals to you about the poem in class

### Week 1 (1/20)
- Review Homework
  - Generated sentences
  - Collected poems
- Discussion on language and poetry
  - [Sentence Diagrams](https://en.wikipedia.org/wiki/Sentence_diagram)
  - [The Cut-up Technique](https://everything4writers.tumblr.com/post/130654244711/stuck-exercise-11-the-cut-up-technique)
  - [William Burroughs, "The Cut Up Method"](https://www.writing.upenn.edu/~afilreis/88v/burroughs-cutup.html)

#### Homework (due before start of next class 1/25)
- **Read** the intro to [code {poems}](https://github.com/NYUAD-IM/Software-Art-Text/blob/main/readings/bertram_codepoems.pdf)
  - **Add** your response to the [Readings Doc](https://docs.google.com/document/d/1bHBWPR4_hHviqBfkgYN6biPDV4-LfBecwr46cApOEgo/edit?usp=sharing)
    - When do you consider code to be poetry? (2 paragraphs)
    - Pick one of the code poems from the book and compare it's structure, vocabulary, and effect on you to the poem you choose last class. How are they similar? How are they different? (2 paragraphs)
  - **Create** a code poem in Colab
    - **Add** a link to your Colab to the [Sketches Spreadsheet](https://docs.google.com/spreadsheets/d/1r7vP1i6M4yef5M0_E-yHuoVpyYvxM1T05yCEytOVe4E/edit?usp=sharing)

## <a name="week2"></a>Week 2

### Week 2 (1/25)
- Review Homework

- Talk about Project 1 Assemblage **due Week 3 (2/1)**
  - **Create** a text artwork using Python. The artwork could be the generated text, the code itself, or a combination
  - The work should:
    - Use algorithms to generate the text
    - Use elements of an existing corpus of texts (e.g. a collection of songs, poems, or scraped web pages)
    - Be presented on a web page
    - Explore how algorithms can recombine generated and existing text to create new expressions
    - Have an emotional impact on the reader, for example through the choice of text corpus and recombination technique
  - The text should be accompanied by the following documentation:
    - A link to your Colab or source code
    - A writeup (on your webpage or in your Colab):
      - How does your algorithm work?
      - Why did you choose this content and algorithm?
      - How does the final output differ from what a person would write?
      - What thoughts or feelings does your output provoke?

- Web scraping
  - [02_Scraping code examples](https://github.com/periode/software-art-text/tree/master/02_scraping)
  - [02a Getting a webpage Colab](https://colab.research.google.com/drive/1sNHW7SQ_VBcExKnsUzh311Vkzkbb1enW?usp=sharing)
  - [Requests: HTTP for Humans™](https://requests.readthedocs.io/en/master/)
  - [Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)
  
- Regular expressions
  - [Python regular expressions](https://www.w3schools.com/python/python_regex.asp)


#### Homework (due before start of next class 1/27) 
- **Read** [grep command in Unix/Linux](https://www.geeksforgeeks.org/grep-command-in-unixlinux) page 1
- **Look** at the manual page for `grep` by running this command (OSX/Linux)
  - ```$ man grep```
  - **Or** look at the [grep man page](https://man7.org/linux/man-pages/man1/grep.1.html)
- **Read** [Grep: A Grammar by Loss Pequeño Glazier](https://github.com/periode/software-art-text/blob/master/assets/readings/glazier_grep.pdf)
  - Some of the output texts are [here](https://web.archive.org/web/20161008133926/http://wings.buffalo.edu:80/epc/authors/glazier/greps/) and [here](https://web.archive.org/web/20110704165723/http://wings.buffalo.edu/epc/authors/glazier/dp/appendices.html)
- **Create** a ```grep```-style text by scraping a text from the Internet and using regular expressions. Get at least 5 pieces of text out of the scraped text/web page and remix them into a new text using some of the techniques we've learned (or new ones).
    - **Add** a link to your Colab to the [Sketches Spreadsheet](https://docs.google.com/spreadsheets/d/1r7vP1i6M4yef5M0_E-yHuoVpyYvxM1T05yCEytOVe4E/edit?usp=sharing)
- **Start** thinking about your Assignment 1 Assemblage
  - What source texts will you use?
  - What kind of output do you envision? Poetry? Code? Sense? Nonsense?

### Week 2 (1/27)
- Codifying grammar
  - [03_language code examples](https://github.com/periode/software-art-text/tree/master/03_language)

## <a name="week3"></a>Week 3

### Week 3 (2/1)
- Project 1 Assemblage Presentations

### Week 3 (2/3)
- Introduction to Assignment 2 Fiction

<!--

## <a name="week4"></a>Week 4

### Week 4 (2/8)

### Week 4 (2/10)

## <a name="week5"></a>Week 5

### Week 5 (2/15)
- Assignment 2 Fiction Presentations

### Week 5 (2/17)

## <a name="week6"></a>Week 6

### Week 6 (2/22)

### Week 6 (2/24)

## <a name="week7"></a>Week 7

### Week 7 (3/1)
- Final Assignment Presentations

### Week 7 (3/3)
- Course Review
- Goodbyes!

-->

