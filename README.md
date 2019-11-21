# VisualGold
### Simple Sound Visualizer
#### WORKS ONLY WITH Python3.6
#### Oscilloscope and Spectrum Analyser based on PyQtGraph
it will listen to "stereomix" you can find that in the soundsettings > recording
double click it and go to the listen tab, select your output device. then install the requirements:

install all requirements with ```pip install -r requirements.txt```

this will likely fail at pyaudio (if you are on windows) to fix that install and use pipwin
```
pip install pipwin
pipwin install pyaudio
```

now download and install PyQtGraph from http://www.pyqtgraph.org/

everything else should work after starting main.py

by clicking on the "A" next to the graphs you can auto-adjust the range that's displayed

___

## Help
```
usage: main.py [-h] [-V] [-v] [-x]

VisualGold for Windows (Python3)

optional arguments:
  -h, --help     show this help message and exit
  -V, --version  Displays current version
  -v, --verbose  Sets logger level to show debug info
  -x, --xtreme   Sets logger level to show even more debug
  ```
