## XDF latency analysis of LSL data streams: Unity (triggered) vs EEG (measured)

### Situation
Every 500ms a beep sound is played and the background color changes one frame from black to white.

![Changing Background](https://raw.githubusercontent.com/mvidaldp/lsl_latency_analysis/master/img/background.gif)

#### Unity (90 FPS):
- Color change (black or white background)
- Beep sound (audio playing or not)
#### EEG (1024 Hz):
 - Photodiode (light sensor)
- Microphone (audio sensor)

### How to run it
Just install the Python requirements:
```bash
pip install -r requirements.txt
```
