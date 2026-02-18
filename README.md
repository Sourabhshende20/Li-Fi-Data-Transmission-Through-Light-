# Li-Fi-Audio-Transmission-System
## One-line description:
A working Li-Fi prototype that wirelessly transmits audio using modulated light — no Wi-Fi, no Bluetooth, just light.

## How It Works (detailed)
The system has two sides — a transmitter and a receiver.
On the transmitter side, audio from a phone (via aux/earphone cable) or a microphone enters an audio amplifier circuit. The amplifier modulates the LED's brightness in sync with the audio waveform — meaning the LED flickers faster or slower depending on the sound, invisibly to the human eye.
On the receiver side, a solar panel acts as a large-area photodetector. As the modulated light hits the solar panel, it generates a varying electrical current that mirrors the original audio signal. This weak signal is then amplified by a second audio amplifier circuit and fed into a speaker, recreating the original sound.

## Components Used
Transmitter PCB (yellow board):

9V battery + power switch
3.5mm aux/earphone input jack
Electret microphone (optional input)
Audio amplifier IC (e.g. LM386)
High-brightness LED (modulated output)
Resistors, capacitors (filter & bias)
Custom PCB (hand-etched or perfboard)

## Receiver:

Small solar panel (acts as photodetector)
Audio amplifier IC (e.g. LM386)
8Ω speaker
Resistors & capacitors
Breadboard or simple PCB


## Specs & Performance

Transmission range: ~10–15 feet (line of sight, low ambient light)
Signal type: Analog audio (AM-like intensity modulation)
Photodetector: Solar panel (larger surface = better sensitivity than LDR)
No digital encoding — purely analog signal chain
Works best in dim/indoor lighting conditions


## Skills Demonstrated

Analog circuit design (amplifier stages, biasing)
PCB layout and fabrication
Optical communication concepts (Li-Fi / VLC — Visible Light Communication)
Signal modulation and demodulation (intensity modulation)
Hardware debugging and calibration

