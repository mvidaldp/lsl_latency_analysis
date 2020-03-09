## __XDF latency analysis of LSL data streams: Unity (triggered) vs EEG (measured)__

### __Situation__ 
Every 500ms a beep sound is played and the background color changes one frame from black to white.

#### __Unity (90 FPS):__
- Color change (black or white background)
- Beep sound (audio playing or not)
#### __EEG (1024 Hz):__
 - Photodiode (light sensor)
- Microphone (audio sensor)


### Requirements
Since it's meant to run on JupyterLab with interactive matplotlib plots, install:
- Python requirements
```bash
pip install -r requirements.txt
```
- Nodejs: https://nodejs.org/en/download/
- JupyterLab extensions:
```bash
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
```
