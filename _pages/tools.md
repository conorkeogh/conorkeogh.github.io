---
permalink: /tools/
title: "Research Tools"
excerpt: "Open source software and devices"
---

As part of my work, I develop tools to enable research in clinical and translational neuroscience and neuromodulation. I also provide technical support on device and tool development to other researchers to facilitate their work. This includes custom hardware, device drivers and software packages for research.

I make these tools available to other researchers to enable research and help others to overcome common issues we have encountered in neuromodulation research.

Please feel free to contact me if you feel you would benefit for support in implementing these tools in your own work or if you would like to collaborate on the development of custom devices and tooling for your research.

## WaveWriter
> Device and software for generating arbitrary stimulation waveforms

Research in electrical neuromodulation can be limited by the ability to generate the stimulation waveforms required for testing. Modern stimulation methods frequently use protocols far more complex than simple regularly spaced square waves. Generating these waveforms in a flexible way for testing the effects of varying waveform parameters or for testing novel waveforms is challenging.

We have developed a system for easily generating complex, arbitrary stimulation waveforms for electrical neuromodulation research. Using a Digitimer DS5 as a CE-marked, constant-current output stage, our custom hardware connects via USB to a computer running dedicated software to allow highly complex waveform designs to be easily specified and delivered. Drivers are included to allow easy integration into custom software and experimental tasks.

## ONIduino
> Custom microcontroller platform for the development of medical devices

Progress in the development of novel medical devices can be slowed down by the availability of appropriate development tools. Development boards exist for device prototyping, but these are frequently lack the specific features, computational power and interfaces required for active medical devices. 

We have developed a custom microntroller platform for developing novel medical devices and research tools. Using a high-power microcontroller with a range of additional peripherals and interfaces that we use frequently for device development, this provides a valuable platform for the rapid development of device prototypes.

## TriggerMate
> System for generating stimulation pulse trains with custom parameters

Research in electrical neuromodulation typically requires the delivery of ongoing pulse trains. Generating these pulse trains for testing frequently involves dedicated custom hardware and requires time-consuming reprogramming whenever parameters need to be altered. This limits the speed of progress.

We have developed a device for easily generating stimulation pulse trains. This is connected to a standard stimulator such as the Digitimer DS8 via its trigger port and allows for generation of tonic, high frequency and burst stimulation with straightforward control of stimulation parameters using on-device controls.

See [the website](https://conorkeogh.net/triggermate) for more details.

## SyncMaster
> System for synchronising behavioural tasks with recorded signals

Research in clinical and translational neuroscience frequently requires the recording of physiological signals, such as electrophysiological recordings, during a behavioural task. Reliably time-locking acquired signals to behavioural events can present a challenge.

We have developed a system for easily synchronising behavioural tasks with recorded signals. A custom device is connected to the computer running the behavioural task via USB. Custom drivers are used to control the device from within the task. The device is then connected to the recording system. Events within the task can then send signals over the device output to time-lock recordings to behavioural events.

This system allows for large numbers of complex event signals to be sent over a single recording channel. Analysis methods are included to recover the original event-specific timings from the single channel data to allow easy time-locked analysis of recorded signals.

See [the website](https://conorkeogh.net/syncmaster) for more details.
