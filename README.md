# MCV Whisper Robot
TODO

## Build
Create a Python virtual environment, activate it, `git clone` the project, and install the required dependencies.
```bash
python3 -m venv mcv-whisper-robot
source mcv-whisper-robot/bin/activate
cd mcv-whisper-robot
git clone git@github.com:irtlab/mcv-whisper-robot.git
pip3 install -r mcv-whisper-robot/requirements.txt
```

To install Whisper, run the following command: (see instructions for more details: https://github.com/openai/whisper#setup)
```
pip install git+https://github.com/openai/whisper.git 
```

## Usage
You have the option to run the project in two modes: Whisper and Google Speech-to-Text.
#### Whisper Option
```bash
python speech_to_text_muti.py whisper <experiment run ID>
```

#### Google Speech-to-Text option
```bash
GOOGLE_STT_KEY=<GSTT Key> python speech_to_text_muti.py GoogleSTT <experiment run ID>
```
