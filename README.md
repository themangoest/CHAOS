# CHAOS

chaos-generating circuit that has a manually set evolution rate (or, roughly speaking, frequency). Although quite simple, it can produce a wide range of chaotic signals. It is a circuit analog for a standard textbook problem in chaos theory, that of a particle in an oscillating double-well potential. It requires an external driving oscillator for operation, such as a standard synthesizer LFO or VCO.

The circuit consists of two identical integrators and a nonlinear circuit, all connected in a loop. The third opamp actually serves triple duty -- in addition to producing a nonlinearity of the form f(x) = x(1-x2), it provides a feedback path for damping of the first integrator as well as a node for injecting the external driving signal.

