# sungwun
:construction: :construction: :construction:

## Notes
```
>>> from os import system
>>> import pyttsx, colorama, nltk.corpus.wordnet as wn
>>> colorama.init()
>>> e=pyttsx.init()
>>> voices = e.getProperty('voices')
>>> e.setProperty('voice', voices[0].id)
>>> lemma="Tagus"
>>> system("cls");phrase=wn.synsets(lemma)[0].definition();print(colorama.Fore.GREEN+colorama.Style.BRIGHT+phrase+colorama.Style.RESET_ALL);engine.say(phrase);engine.runAndWait()
```
