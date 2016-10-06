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
___
`sphinx_rtd_theme`  
NOTE: Jupyter, like its predecessor, uses the `.ipynb` extension. The notebook files are simple JSON documents.

```sudo apt-get install python3.5 idle-python3.5 python3-pip python3-colorama python3-nltk python3-pygments python3-pyqt5.qtsvg python3-pyqt5.qtopengl python3-opengl python3-matplotlib python3-scipy python3-pil python3-roman python3-yaml python3-pandas python3-sklearn python3-sphinx python3-sphinx-rtd-theme python3-flask python3-pymongo python3-mistune r-base r-cran-plotrix r-cran-yaml r-cran-rcurl r-cran-stringr libcurl4-gnutls-dev libssl-dev```

```# Instead of "sudo apt-get -y install libcurl4-gnutls-dev libssl-dev", we can use "sudo apt-get -y build-dep libcurl4-gnutls-dev" to install all dependencies of the R packages pbdZMQ and devtools.``` 
  
```sudo pip3 install jupyter jupyter_qtconsole_colorschemes ipywidgets```  
  
```
sudo R

install.packages(c('pbdZMQ', 'devtools'))
devtools::install_github('IRkernel/repr')
devtools::install_github('IRkernel/IRkernel')
IRkernel::installspec()
q()
```
```
jupyter nbextension enable widgetsnbextension --py
jupyter qtconsole --kernel=ir --style=solarizeddark
demo('colors')
library(plotrix)
svg(file='chart.svg')
cat('# # # Something')
pie3D(c(1,2,3,4,5,6,7,8),labels=c('Alpha','Beta','Gamma','Delta','Epsilon','Zeta','Eta','Theta'),col=terrain.colors(8),main='Untitled',explode=0.1)
dev.off()
q()
```
This application uses geographically distributed replica sets, lorum ipsum dolor sit amet.  
But wait, there's more.  
In case of emergency:
```
npm install bower js-yaml angular mongoose typescript --save
bower install semantic-ui angular-semantic-ui --save
```
## Don't close your laptop's lid!
Use this instead:
```
from os import startfile
startfile('C:\Windows\SysWOW64\scrnsave.scr')
```
Sample build script:
<pre>
import sys
from cx_Freeze import setup, Executable
base = "Win32GUI"				#Declare that we don't need a console window upon launch of the application.
setup(name = "TakeANap",
      version = "1.0",
      description = "Turn off the screen",
      executables = [Executable(r"<strong>{.py file location}</strong>", base=base, icon=r"<strong>{Icon location}</strong>")])
</pre>
## Go instructions
:wink:
<pre>
sudo apt-get install golang-lang git libtool pkg-config build-essential autoconf automake libzmq5 <strong>libzmq5-dev</strong> python3-zmq
go get golang.org/x/tools/cmd/goimports
go get -tags zmq_4_x github.com/gophergala2016/gophernotes
sudo cp -r $GOPATH/src/github.com/gophergala2016/gophernotes/kernel/* ~/.local/share/jupyter/kernels/gophernotes
sudo nano ~/.local/share/jupyter/kernels/gophernotes # change "/go/bin/gophernotes" to "<strong>{insert GOPATH here}</strong>/bin/gophernotes"
sudo jupyter notebook # superuser is required unless you chmod 777 -R everything
</pre>
## Changelog
### [pre0] () (2000-01-01)
**Added**
- Links to Oxford Dict, Merriam-Webster, Larousse, and Duden.
[//]: # (UNDECIDED: Furigana?)
