---
title: Arbitrary Waveform Creator
language: en-US
author: Stephan Schwarz
type: concept

audience: user
context: 

component: software
category: function
application: Arbitrary Waveform Creator

prodname: HM123
series: 
brand: Manufacturer
---

# Arbitrary Waveform Creator

## Function

With the Arbitrary Wafeform Creator you can [create custom waveforms](taskCreateCustomWaveform.md) (for example step function, saw tooth etc.) and model their behavior according to your specific requirements.

You can create custom waveforms on the control panel or an external interface. When saved, the settings are stored for the channel. Additionally, it's possible to store custom waveforms and to import and apply them to other channels. When you activate the respective channel, your custom waveform is applied to its output.

## Parameters

The following parameters can be set for each wavepoint:
- voltage
- current
- time (application duration)
- interpolation (on/off)

## Limits

Limits to the application of custom waveforms are as follows:
- Custom waveforms can be reproduced within the voltage and current limits set by the instrument for the respective channel.
- The function can not be used simultaneously with sequencing.