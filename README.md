# Fibaro

This repository serves as inspiration for your own Homey app, to help you understand Homey Apps SDK concepts in a real-life context.

Read the [Homey Apps SDK Documentation](https://apps.developer.homey.app) for more information about developing apps for Homey.

> Because this repository is a clone of the live code, pull requests will be ignored.

## What does this app do?

The Fibaro app connects to Fibaro devices using the Z-Wave protocol. Devices are paired by putting them in pairing mode, if the device is in range, Homey will receive these pairing commands and add the device. Using command classes, Homey can send and receive data from Fibaro Devices, this is handled through the ZwaveDriver library. Read more about Z-Wave development at https://apps.developer.homey.app/wireless/z-wave.
