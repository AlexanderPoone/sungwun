# sungwun
:construction: :construction: :construction:

## Notes
```
# NOT using Jupyter
>>> __author__= 'Alex Poon <alexander@cuhk.edu.hk>'
>>> from os import system
>>> from re import compile, escape, sub
>>> from string import punctuation
>>> from nltk.corpus import wordnet as wn
>>> import pyttsx, colorama, wordcloud as cd
>>> colorama.init()
>>> e=pyttsx.init();s=''
>>> voices=e.getProperty('voices')
'''
from os import system;from re import compile, escape, sub;from string import punctuation;from nltk.corpus import wordnet as wn;import pyttsx, colorama, wordcloud as cd;colorama.init();e=pyttsx.init();s='';voices=e.getProperty('voices')
'''
>>> for voice in voices:
>>>   if voice.id.endswith("ZIRA_11.0"):
>>>     e.setProperty('voice', voice.id)
>>> break
>>> lemma='vandal1' # ,'bollocks2' or 'ottoman3'
>>> begone=system('cls');entry=0;entry=int(lemma[-1:]) if lemma[-1:].isdigit() else entry;lemma=lemma[:-1] if lemma[-1:].isdigit() else lemma;phrase=wn.synsets(lemma)[entry].definition();print(colorama.Fore.GREEN+colorama.Style.BRIGHT+phrase+colorama.Style.RESET_ALL);e.say(phrase);e.runAndWait();lemma+=str(entry) if entry!=0 else '';corrected=compile('[%s]' % escape(punctuation)).sub('', phrase);s+=corrected+' '
>>> import matplotlib.pyplot as plt
>>> nimbus=cd.WordCloud().generate(s[:-1]);plt.figure().set_facecolor('darkOliveGreen');plt.imshow(nimbus);plt.axis("off");plt.show()
''' 
if " " in lemma:
  lemma=lemma.split()
#if isinstance(lemma, list):
'''
```
