# Dungeness Lighthouse / St Ann's Lighthouse Foghorn Modulator
Tritone modulation of the famous Foghorn from the Dungeness Lighthouse #5 and the St Ann's Lighthouse.

The "Foghorn TriTone Modulator" is a very simple project I made to remind us of the famous and very specific tone of the foghorn.

[![mqdefault](https://github.com/user-attachments/assets/a4291fa6-7701-457b-bf08-5615f4d61b39)](https://www.youtube.com/watch?v=U48cCQ7XAnM)  
Click this image to hear the sound.  
_Source : YouTube -  St Anns Fog Signal / "Association of Lighthouse Keepers" Channel_

![Dungeness_Lighthouse5](https://github.com/user-attachments/assets/e70831a2-b632-449e-95ce-c0a468b009c6)
[![Dungeness_Lighthouse5_FogHornSPK](https://github.com/user-attachments/assets/9082918b-a841-4a59-bbd4-6a6540af9e12)](https://www.youtube.com/watch?v=Ncq_DsAXrBo)  
Click this image to hear the sound.  
_Source : YouTube -  Dungeness 5 fog horn: 26 minutes of Tannoy fog horn / "hellooldchap" Channel_


> In 1954-56, trials had been carried out at Dungeness of a triple-frequency electric fog signal, sounded through tannoy emitters built into a curved stack of precast concrete blocks. The experiment was deemed a success, and tannoy stacks were subsequently installed by Trinity House at around a dozen lighthouse stations. At Dungeness itself, a stack of sixty such emitters was incorporated into the design of the lighthouse tower itself; these remained in use until the year 2000, when they were replaced by an electronic signal installed at the base of the tower. It sounded three blasts every minute (altered in 2022 to one blast every 30 seconds).  
_Source : [Wikipedia](https://en.wikipedia.org/wiki/Dungeness_Lighthouse)_

## Electronic Schematic

![FogHorn_Schema](https://github.com/user-attachments/assets/d8f37a57-602c-405a-a426-b0a4faaee443)

This modulator is very simple, bases on 3 NE555 Timer IC for each tone, the NE555 can easily create square wave tone with few component for tuning and each NE555 have a 5 Order LowPass Filter to transform squares waveforms tones into sines waveforms tone.

The power input voltage are 12VDC equiped with a LM7805 5VDC for the NE555.

Each channel have a multiturn potentiometer for precision frequency tuning.

The modulator are equiped with a passive inboard mixer, 3 potentiometer (1 pot for each channel, regulate the volume of each tone) and 1 for the main volume to regulate the main mix.

## Printed Circuit Board

![FogHorn_PCB_1](https://github.com/user-attachments/assets/c273fff4-aa2a-49a4-9845-ff16bc259622)
