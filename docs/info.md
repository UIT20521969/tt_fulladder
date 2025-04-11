<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Fulladder 2 bit

## How to test

This circuit implements a two-bit adder, where each input has one bit.

`A + B + Cin = S with Cout`

While there is an OR gate in the design, there are several other [logic gates](/digital_design/logic_gates) too. **Using the truth table below, can you make sense of the other logic gates?**

| Cin     | A       | B      | S      | Cout   |
|---------|---------|--------|--------|--------|
| 0       | 0       | 0      | 0      | 0      |
| 0       | 0       | 1      | 1      | 0      |
| 0       | 1       | 0      | 1      | 0      |
| 0       | 1       | 1      | 0      | 1      |
| 1       | 0       | 0      | 1      | 0      |
| 1       | 0       | 1      | 0      | 1      |
| 1       | 1       | 0      | 0      | 1      |
| 1       | 1       | 1      | 1      | 1      |

**Extra credit: using this circuit, can you build a four-bit full adder?** This circuit needs to accept two two-bit values, A and B, and a carry-in bit. It needs to output a two-bit value, S, and a carry-out bit.

Feel free to play around to try to figure it out. You can always return to the [logic gate tutorial](/digital_design/logic_gates) if you need a refresher. 


## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
