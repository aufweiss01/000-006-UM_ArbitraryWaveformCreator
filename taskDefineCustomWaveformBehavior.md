---
title: Define the Custom Waveform Behavior
language: en-US
author: Stephan Schwarz
type: task

audience: user
context: operation

component: software, control panel
category: function
application: Arbitrary Waveform Creator

prodname: HM123
series: 
brand: Manufacturer
---

# Define the custom waveform behavior

> This section applies to the work with the device control panel. For information about how work with the external interface, see [Create Custom Waveforms on External Interface](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/dl_common_library/dl_manuals/dl_user_manual/HMC804x_UserManual_de_en_05.pdf).

---
Prerequistes:
- [The Arbitrary Waveform Creator is open.](taskStartCustomWaveformCreator.md)
---

## Set the number of repetitions

> If the number of repetitions is set to '0', the custom wave is repeated infinitely until the channel's output is manually deactivated. 
The maximum definite number that can be set for the repetition is '65535'.

1. If required, press the softkey for <uicontrol>PAGE</uicontrol> to select page 1/2.
1. Press the softkey for <uicontrol>REPETITION</uicontrol>.
1. Turn and press the knob to select the number of repetitions.
- Your settings are stored for the channel.

## Set the endpoint behavior

> If the number of repetitions is definite and the endpoint behavior is set to 'HOLD', the last defined wavepoint will be held until the channel's output is manually deactivated. 
If endpoint behavoir is set to 'OFF' (default), the respective channel is deactivated automatically when repetitions are finished.

1. Press the softkey for <uicontrol>PAGE</uicontrol> to select page 2/2.
1. Press the softkey for <uicontrol>END BEHAV.</uicontrol> to change the endpoint behavior.
- Your settings are stored for the channel.


## Save the waveform

1. Press the softkey for <uicontrol>PAGE</uicontrol> to select page 2/2.
1. Press the softkey for <uicontrol>SAVE/LOAD</uicontrol>.
- The <wintitle>Save/Load waveform</wintitle> screen opens.
1. Select the storage location (active channel or connected USB device) and save. <!-- Das Fenster / der Vorgang zum Speichern ist nicht ganz klar, da nicht beschrieben.>
- Your custom waveform settings are saved.

---
Subsequent tasks:
- If required, [set a trigger mode for your custom waveform](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/dl_common_library/dl_manuals/dl_user_manual/HMC804x_UserManual_de_en_05.pdf).
- [Activate the channel to apply your custom waveform](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/dl_common_library/dl_manuals/dl_user_manual/HMC804x_UserManual_de_en_05.pdf).
---