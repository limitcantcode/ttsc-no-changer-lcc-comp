# No Changer (no-op) Voice Changer

## What is this for?
In case you don't want to use a voice changer and can't disable voice changer requirements. You can use this pluging to pass back exactly what you get from TTSG.

## Setup
Windows
```
conda create -n jaison-comp-ttsc-no-changer python=3.12
conda activate jaison-comp-ttsc-no-changer
pip install -r requirements.txt
```

Unix
```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Testing
Assuming you are in the right virtual environment and are in the root directory:
```
python ./src/main.py --port=5000
```
If it runs, it should be fine.

## Configuration
There is no configuration.

## Related stuff
Project J.A.I.son: https://github.com/limitcantcode/jaison-core

Join the community Discord: https://discord.gg/Z8yyEzHsYM

