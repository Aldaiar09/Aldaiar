# Aldaiar

# **GUI Translator**

Language Translator using *Google Translate APIs in Python* – Instantly Translate texts, words, phrases from one language to another.
The program can translate over 100 languages and it can translate both words and sentences.

![](https://github.com/xNazim/intro-final/blob/main/screenshot.PNG)

### This project built by using *googletrans* and *Tkinter* libraries.


# Installation


```bash
pip install googletrans==3.1.0a0
```

*Tkinter is a standard GUI Python library. We don't have to install it*

# Usage

### Tkinter

```python
from tkinter import *
from tkinter import ttk

# creating display window
root = Tk()
root.geometry('1080x400')
root.resizable(0,0)
root.config(bg = 'ghost white')
root.mainloop()
```
### googletrans

```python
from googletrans import Translator
>>> translator = Translator()
>>> translator.translate('안녕하세요.')
# <Translated src=ko dest=en text=Good evening. pronunciation=Good evening.>
```

# License

[AIU](http://alatoo.edu.kg/)

### Project was done by:
*@aldaiar--->Aldaiar Ramis uulu
