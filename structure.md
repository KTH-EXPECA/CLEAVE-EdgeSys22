# CLEAVE Paper for CNERT'21

Maximum paper length: 6 pages

## Title Page and Abstract [0.5 page]

## Introduction [1.5 Pages]

### Networked Control Systems [0.5 page]

- Start by briefly introducing NCS and why they are interesting.
- Segway into Edge Computing.

### NCS on the Edge [0.5 page]

- Why is Edge Computing such a great oportunity for NCS?
- What are the challenges?

### Other NCS benchmarking platforms [0.5 page]

- NCSBench and others.
- Highlight our main difference: fully emulated plant, communication over real network.

## CLEAVE - ControL bEnchmArking serVice on the Edge [2 - 2.5 pages]

### Fundamental concepts for CLEAVE [0.5 - 1 page]

- Emulation-based: Plant is emulated on general purpose hardware, whereas we use the real network and a real controller.
- Everything runs in real-time.
- Design geared towards as general an approach as possible, ensuring that almost any plant can be emulated.

### General architecture [1.5 pages]

This section should mimic somewhat what we currently have on the [online documentation.](https://cleave.readthedocs.io/en/latest/usage.html#building-a-ncs-emulation-from-scratch).

- Plants:
    - State
    - Semantic Variables
    - Sensors
    - Actuators
    - Internal event loop
    - Networking abstractions
    
- Controller Services:
    - Controller
    - Networking abstractions

## Experimental Validation [1 - 1.5 pages]

- Introduce our inverted pendulum implementation.
- Describe experimentation: setups and parameters.
- Present a few results, but we really can't fit much here, can we?

## Conclusions, Future Work and References [0.5 page]

...

## Appendix: Demo description [+1 page]

Describe the inverted pendulum simulation (with visualization) and a number of setups we want to show. For instance, we could present different ways of implementing noise in the sensors and actuators, try different controllers and alter the network link.