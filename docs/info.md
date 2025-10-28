<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The output is toggled by the input clock. This is a rather simple circuit, that only utilizes an XOR gate and a D Flip-Flop. The inverting output of the D-Flip Flop is put into the XOR gate, with the other input connected to the clock line.

## How to test

Drive the clock frequency with any desired frequency, or through use of a push button.

## External hardware

An LED on OUT0 is ideal, but any way to show the state change is acceptable. 
