# gTTS-google-text-to-speech
gTTS - Google Text to Speech

# Install gTTS python module from pip
```
$ sudo pip install gTTS

Collecting gTTS
Requirement already satisfied: six in /usr/local/lib/python2.7/dist-packages (from gTTS)
Collecting gtts-token (from gTTS)
Collecting requests (from gTTS)
  Downloading requests-2.18.4-py2.py3-none-any.whl (88kB)
    100% |████████████████████████████████| 92kB 929kB/s 
Collecting certifi>=2017.4.17 (from requests->gTTS)
  Downloading certifi-2018.1.18-py2.py3-none-any.whl (151kB)
    100% |████████████████████████████████| 153kB 1.5MB/s 
Collecting chardet<3.1.0,>=3.0.2 (from requests->gTTS)
  Downloading chardet-3.0.4-py2.py3-none-any.whl (133kB)
    100% |████████████████████████████████| 143kB 3.7MB/s 
Collecting idna<2.7,>=2.5 (from requests->gTTS)
  Downloading idna-2.6-py2.py3-none-any.whl (56kB)
    100% |████████████████████████████████| 61kB 3.1MB/s 
Collecting urllib3<1.23,>=1.21.1 (from requests->gTTS)
  Downloading urllib3-1.22-py2.py3-none-any.whl (132kB)
    100% |████████████████████████████████| 133kB 4.2MB/s 
Installing collected packages: certifi, chardet, idna, urllib3, requests, gtts-token, gTTS
  Found existing installation: chardet 2.3.0
    Uninstalling chardet-2.3.0:
      Successfully uninstalled chardet-2.3.0
Successfully installed certifi-2018.1.18 chardet-3.0.4 gTTS-1.2.2 gtts-token-1.1.1 idna-2.6 requests-2.18.4 urllib3-1.22
```

# Command line utility
```
$ gtts-cli
usage: gtts-cli.py [-h] [-f FILE] [-o DESTINATION] [-l LANG] [--slow]
                   [--debug]
                   [text]
gtts-cli.py: error: one of the arguments text -f/--file is required
```

# Outline
- [Install gTTS - google text to speech](https://github.com/mrolarik/gTTS-google-text-to-speech/blob/master/gTTS%20(Google%20Text%20to%20Speech).ipynb)
- [Using gTTS via python program](https://github.com/mrolarik/gTTS-google-text-to-speech/blob/master/gTTS%20-%20Thai%20language.ipynb)
- [Other speech engines](https://github.com/mrolarik/gTTS-google-text-to-speech/blob/master/speech-engines.ipynb)
