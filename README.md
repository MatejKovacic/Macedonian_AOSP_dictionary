# Macedonian AOSP dictionary

AOSP dictionary is the dictionary format used in the Android Open Source Project (AOSP), primarily for predictive text input, spell checking, and word suggestions on Android devices. This dictionary contains a list of words and their associated frequency or probability data, which allows Android's text input methods (like the Android keyboard) to predict and suggest words efficiently while typing.

I was testing [FUTO keyboard](https://keyboard.futo.org/), opensource keyboard that does Speech-To-Text for various languages and respects privacy (no data are sent to cloud, everything runs locallly on your device) and found out there is no AOSP dictionary for Macedonian language.

So I tried to compile my own following [these instructions](https://github.com/remi0s/aosp-dictionary-tools). I dowloaded a wordlist from [Frequency Words repository](https://github.com/hermitdave/FrequencyWords/tree/master/content/2016) (they compiled the wordlist and their frequency from OpenSubtitles and Wikipedia), and converted them (with a help of [mrihtar](https://github.com/mrihtar)) to AOSP format.

- [Macedonian AOSP dictionary](main_mk.dict) (you can import this file to FUTO Keyboard directly)
- [Macedonian wordlist](mk_wordlist.combined)
- [Macedonian Spellcheck Dictionary](https://github.com/gerazov/dictionary-mk/tree/master) (external resource).


*I am not Macedonian and do not speak Macedonian language very well, so please open any potential issues in English.*
