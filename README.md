# SonicBreathing
This repository contains Google Drive-links to a Max MSP application for Windows and MacOS and experimental data from the study   
  [Van Kerrebroeck B., Maes PJ., 2020, Musical Sonification of Breathing Patterns to Reduce Stress during the COVID-19 pandemic]
  
- MacOS: https://drive.google.com/file/d/1mCGNgTzYYqB5C31ryBHpY1OTDf-ZkW0H/view?usp=sharing
- Windows: https://drive.google.com/file/d/1plYJoof5MfVGKLdi-yE9vttX7X05yC49/view?usp=sharing

### Purpose ###
The SonicBreathing application takes keyboard-presses as input that indicate your breathing (left for inhalation, right for exhalation) and plays sounds to accompany you. After selecting a session and pressing start, you will hear 1 minute of silence and then 7 minutes of synchronised sounds. 

Sounds will be tempo-aligned after minute 1, become increasingly phase-aligned after minute 2 and become (tempo-dependent) phase-delayed after minute 5. You are expected to start tapping the keys and indicate your breathing from the start of a session. The session and sounds will end automatically after the 8 minutes. Keypresses are the only data being captured by the app and for this purpose it will store some .txt files locally in the application's folder after each session. The main .txt-file logs timestamps of every keypress, the others are derivatives thereof (breathing and sound phase and tempo, phase delay).

### Steps ###
A typical session would look like this:
1. Get a comfortable seat somewhere calm and put on headphoens
2. Open the .app or .exe and click on 'Test Audio' and 'Test VST'
3. If you hear a gong sound and a marimba chord progression, continue to the next step.   
Otherwise, click on 'Audio settings' to select the proper audio output
4. Select a session:  
      A = Noise sonification  
      B = Binaural soundscape  
      C = Musical phrase  
5. Press start
6. Indicate the start of an inhalation with your left key, the start of an exhalation by pressing the right key
7. Relax!

### (For MacOS users): ###
FileVault prevents the storing of local .txt-files of apps from an unidentified developer. The error is non-blocking for the apps other functions but if you want to prevent the error and store .txt files of your session, please follow these steps:
1. Download and unzip the SonicBreathing app
2. Create a folder somewhere outside the SonicBreathing folder
3. Drag the SonicBreathing.app into the new folder
4. Drag the SonicBreathing.app back into the original SonicBreathing folder
5. Run the .app and relax
