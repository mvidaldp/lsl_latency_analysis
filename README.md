## XDF latency analysis of LSL data streams: Unity (triggered) vs EEG (measured)

### Situation
Every 500ms a beep sound is played and the background color changes one frame from black to white.

#### Unity (90 FPS):
- Color change (black or white background)
- Beep sound (audio playing or not)
#### EEG (1024 Hz):
 - Photodiode (light sensor)
- Microphone (audio sensor)


### How to run it
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
