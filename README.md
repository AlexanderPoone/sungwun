# sungwun
:construction: :construction: :construction:

## Notes
```
>>> from os import system
>>> import pyttsx, colorama, nltk.corpus.wordnet as wn
>>> colorama.init()
>>> e=pyttsx.init()
>>> voices = e.getProperty('voices')
>>> for voice in voices:
>>>    if voice.id.endswith("ZIRA_11.0"):
>>>       e.setProperty('voice', voice.id)
>>>       break
>>> lemma="Tagus"
>>> begone=system("cls");entry=0;entry=int(lemma[-1:]) if lemma[-1:].isdigit() else entry;lemma=lemma[:-1] if lemma[-1:].isdigit() else lemma;phrase=wn.synsets(lemma)[entry].definition();print(colorama.Fore.GREEN+colorama.Style.BRIGHT+phrase+colorama.Style.RESET_ALL);e.say(phrase);e.runAndWait()
```
