# Sequential Digital Logic Circuit

A Sequential digital logic circuit is different from a combinational logic circuit. In sequential circuits the output of the logic device is not only dependent on the present input to the device, but also on past inputs.

In other words, the output of a sequential logic circuit depends on present input as well as the present state of the circuit.

## Schematic
![Sequential digital logic circuit](https://www.elprocus.com/wp-content/uploads/2014/01/Sequential-digital-logic-circuit.jpg)

## Components

Unlike combinational circuits, the sequential circuits have memory devices in order to store the past outputs. In fact sequential digital logic circuits are nothing but combinational circuit with memory.These types of digital logic circuits are designed using finite state machine.

![Classification of combinational logic circuit](https://www.elprocus.com/wp-content/uploads/2014/01/comb3.gif)

There are two inputs which are operated by combinational logic circuits in order to produce various outputs.

The output from the memory devices are fed to the combinational logic circuit. The internal inputs and outputs form part of the secondary devices.

Secondary inputs devices are state variables produced by the storage elements, where as secondary outputs devices are excitations for the storage elements.

Output of sequential circuits can be pulsed output or level output.

*Pulsed output*: A pulsed output is an output that lasts for the duration of a particular input pulse but can be less in some cases. For the clocked sequential circuits, the output pulse is of the same duration as that of the clock pulse.

*Level output*: A level output refers to an output that changes state at the start of an input pulse or clock pulse and remains in that state until the next input or clock pulse.

## Uses

Examples of sequential logic circuits are counters, and flip-flops, constructed using digital logic gates and memory.

![Sequential circuits: J/K Flip flop](https://www.elprocus.com/wp-content/uploads/2014/01/JK-1299047714_463_278.png)

## Examples

1. *Clock Driven Circuits*
    These are synchronous digital logic circuit, where the output state transition takes place only when the input signal is applied along with clock pulses. Synchronous sequential circuit uses pulsed or clock inputs.
2. *Event Driven Circuits*
    These are asynchronous digital logic circuits, where the output state transition takes place even if we don’t apply the input signal along with the clock pulses. Asynchronous circuit uses pulses of inputs instead of clock signal.

## Sources

https://www.elprocus.com/different-types-of-digital-logic-circuits/
https://www.electronics-tutorials.ws/sequential/seq4.gif
http://d3i5bpxkxvwmz.cloudfront.net/resized/images/remote/http_s.eeweb.com/quizzes/2011/4/02/JK-1299047714_463_278.png
