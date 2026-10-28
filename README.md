# EEG-Blink-Game
Developed an EEG-controlled frog game using the Upside Down Labs single-channel EEG kit. Implemented blink detection through EEG signal processing to trigger in-game actions, exploring real-time brain-computer interaction (BCI) using Python and Arduino.
Developed an interactive EEG-controlled frog game using the Upside Down Labs single-channel EEG kit, exploring real-time brain-computer interaction (BCI) through blink detection and EEG signal processing.

The game allows players to control a frog using eye blinks and directional inputs derived from EEG signals, creating an alternative to conventional keyboard-based gameplay. A single blink triggers a jump, while a double blink triggers a double jump, enabling the frog to overcome obstacles and navigate the game environment. Left and right directional controls allow the frog to move across the screen, making gameplay more dynamic and interactive.

The system uses the single-channel EEG kit to acquire signals associated with eye blinks. These signals are processed to identify blink patterns and distinguish between individual and double blinks. The detected events are mapped to specific in-game actions, enabling real-time interaction between the EEG hardware and the game.

The project integrates EEG signal acquisition, signal processing, serial communication, and game development to establish a functional connection between physiological signals and gameplay mechanics. It demonstrates how low-cost EEG hardware can be used to explore accessible and engaging BCI applications.

Technologies Used: Upside Down Labs single-channel EEG kit, Python, Arduino, EEG Signal Processing, Serial Communication, and Brain-Computer Interface (BCI).
