# Mini-1864

This is a replacement for the hard-to-find RCA CDP1864 video chip. It is currently a work in progress, the goal is to implement the original functionality using three Atmel ATF750C programmable devices, and using surface-mount TSSOP packages, create a circuit that will drop into an existing DIP 40 footprint.

The plan is to distribute the circuitry as follows: One 750C will implement the sound feature, a second will implement the video shift register, color latches, background sequencer, and the associated multiplexing and logic. And the third will implement the control and timing logic.
