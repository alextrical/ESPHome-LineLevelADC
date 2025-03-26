# Line Level Audio ADC ESP32 devkit for ESPHome

ESPHome + ESP32-based Audio ADC with line level analog input for music streaming to local network using WiFi.

Simple goal is to provide proof-of-concept development hardware for ESPHome and Music Assistant developers.

Example use-case and flow-chart:

* Turntable LP-Player -> Preamplifier -> ESP32 with I2S line level ADC -> WiFi -> Music Assistant -> Speakers

What this would basically achieve is a network-attached stereo sound capture device for analogue HiFi sources.

Note! Developer help wanted with ESPHome Audio ADC drivers and pipeline for streaming to Music Assistant.

Current draft prototype is schematic PCB design in KiCad of development board with header for an ADC module.

This early draft is designed to use ESP32-S3 and PCM1808 modules together to enable a 3.5mm jack for input.

Related community discussions:
- https://github.com/orgs/music-assistant/discussions/3763
- https://github.com/orgs/FutureProofHomes/discussions/21
- https://github.com/orgs/music-assistant/discussions/2343
