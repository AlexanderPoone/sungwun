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
```
# Shard 0
---
- {yale: Lorum Ipsum, yt: Lorum ipsum, en: {en_gb: Lorum ipsum, en_us: Lorum ipsum}, fr: Lorum ipsum, es: {es_es: Lorum ipsum, es_ar: &B Lorum Ipsum; es_mx: *B}, ca: Lorum ipsum, example: [1, 2, 3], picture: !!binary R0lGODdhDQAIAIAAAAAAANnZ2SwAAAAADQAIAAACF4SDGQar3xxbJ9p0qa7R0YxwzaFME1IAADs=}
- {yale: Lorum Ipsum, yt: Lorum ipsum, en: Lorum ipsum, fr: Lorum ipsum, es: Lorum ipsum, ca: Lorum ipsum, example: [1, 2, 3], picture: !!binary R0lGODdhDQAIAIAAAAAAANnZ2SwAAAAADQAIAAACF4SDGQar3xxbJ9p0qa7R0YxwzaFME1IAADs=}
- {yale: Lorum Ipsum, yt: Lorum ipsum, en: Lorum ipsum, fr: Lorum ipsum, es: Lorum ipsum, ca: Lorum ipsum, example: [1, 2, 3], picture: !!binary R0lGODdhDQAIAIAAAAAAANnZ2SwAAAAADQAIAAACF4SDGQar3xxbJ9p0qa7R0YxwzaFME1IAADs=}

# Shard 1
---
- {yale: Lorum Ipsum, yt: Lorum ipsum, en: {en_gb: Lorum ipsum, en_us: Lorum ipsum}, fr: Lorum ipsum, es: {es_es: Lorum ipsum, es_ar: &B Lorum Ipsum; es_mx: *B}, ca: Lorum ipsum, example: [1, 2, 3], picture: !!binary R0lGODdhDQAIAIAAAAAAANnZ2SwAAAAADQAIAAACF4SDGQar3xxbJ9p0qa7R0YxwzaFME1IAADs=}
- {yale: Lorum Ipsum, yt: Lorum ipsum, en: Lorum ipsum, fr: Lorum ipsum, es: Lorum ipsum, ca: Lorum ipsum, example: [1, 2, 3], picture: !!binary R0lGODdhDQAIAIAAAAAAANnZ2SwAAAAADQAIAAACF4SDGQar3xxbJ9p0qa7R0YxwzaFME1IAADs=}
- {yale: Lorum Ipsum, yt: Lorum ipsum, en: Lorum ipsum, fr: Lorum ipsum, es: Lorum ipsum, ca: Lorum ipsum, example: [1, 2, 3], picture: !!binary R0lGODdhDQAIAIAAAAAAANnZ2SwAAAAADQAIAAACF4SDGQar3xxbJ9p0qa7R0YxwzaFME1IAADs=}
```
sphinx_rtd_theme  
```sudo apt-get install python3.5 idle-python3.5 python3-pip python3-colorama python3-nltk python3-pygments python3-pyqt5.qtsvg python3-pyqt5.qtopengl python3-opengl python3-matplotlib python3-scipy python3-pil python3-roman python3-yaml python3-pandas python3-sklearn python3-sphinx python3-sphinx-rtd-theme python3-flask python3-pymongo python3-mistune r-base r-cran-plotrix r-cran-yaml r-cran-rcurl r-cran-stringr``` 
  
```sudo pip3 install jupyter jupyter_qtconsole_colorschemes```  
  
```install.packages(c('pbdZMQ', 'devtools'))
devtools::install_github('IRkernel/repr')
devtools::install_github('IRkernel/IRkernel')
IRkernel::installspec()```
