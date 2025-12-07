---
title: Create Custom Waveforms on Control Panel
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

# Create custom waveforms on control panel

> This section applies to the work with the device control panel. For information about how to work with the external interface, see [Create Custom Waveforms on External Interface](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/dl_common_library/dl_manuals/dl_user_manual/HMC804x_UserManual_de_en_05.pdf).

---

Prerequistes:
- [The Arbitrary Waveform Creator is open](taskStartArbitraryWaveformCreator).

---

## Select the channel

1. If required, press the softkey for <uicontrol>PAGE</uicontrol> to select page 1/2.
1. Press the softkey for <uicontrol>CHANNEL</uicontrol>.
1. Turn and press the knob to select the appropriate channel.

## Load custom waveform

> Loading a previously saved custom waveform is optional. You can also start editing from scratch.

> <b>Notice:</b> To load a waveform configuration to a channel will overwrite the channel's active configuration. <!-- Das ist nur eine Vermutung. -->

1. Press the softkey for <uicontrol>PAGE</uicontrol> to select page 2/2.
1. Press the softkey for <uicontrol>SAVE/LOAD</uicontrol>.
    - The <wintitle>Save/Load waveform</wintitle> screen opens.
1. Select the file (from connected USB device) and load. <!-- Das Fenster / der Vorgang zum Laden ist nicht ganz klar, da nicht beschrieben. -->
    - The custom waveform settings are loaded to the active channel.

## Edit the waveform

You can create and edit up to 512 wavepoints. <!-- Es ist nicht vollständig klar, ob noch mehr Punkte angelegt werden können. Es können aber nur 512 zur Generierung einer Welle genutzt werden. -->

1. Press the softkey for <uicontrol>IDX</uicontrol> to activate the editing mode.
1. Turn and press the knob to select the appropriate wavepoint.
1. Press the arrow keys to select the column to edit.

> The following parameters can be set: voltage (<uicontrol>U</uicontrol>), current (<uicontrol>I</uicontrol>), duration (<uicontrol>Time</uicontrol>) and interpolation (<uicontrol>Intp</uicontrol>).

4. Turn and press the knob to select the appropriate value.

> You might also type in the values on the numeric keypad and press the knob to confirm.

5. Repeat the former steps to create all the required wavepoints.

## Save the waveform

1. Press the softkey for <uicontrol>PAGE</uicontrol> to select page 2/2.
1. Press the softkey for <uicontrol>SAVE/LOAD</uicontrol>.
    - The <wintitle>Save/Load waveform</wintitle> screen opens.
1. Select the storage location (active channel or connected USB device) and save. <!-- Das Fenster / der Vorgang zum Speichern ist nicht ganz klar, da nicht beschrieben. -->
    - Your custom waveform settings are saved.

---

Subsequent tasks:
- If required, [define the custom waveform behavior](taskDefineCustomWaveformBehavior).
- If required, [set a trigger mode for your custom waveform](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/dl_common_library/dl_manuals/dl_user_manual/HMC804x_UserManual_de_en_05.pdf).
- [Activate the channel to apply your custom waveform](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/dl_common_library/dl_manuals/dl_user_manual/HMC804x_UserManual_de_en_05.pdf).

---