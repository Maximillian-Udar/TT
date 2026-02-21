<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A Full adder which takes three 1-bit inputs. It shows Sum (s) and Carry (c) up to 3 in binary

## How to test

Cycle the inputs one by one and observe:
### a) All instances with only one input high lead to Sum being high.
### b) Any combination of two inputs high show only Carry being high
### c) When all inputs are high, both Sum and Carry are high

## The logic realized:
$S(a,b,c)=(a\oplus b \oplus c)$

$C(a,b,c)=(a \wedge b)\vee(a \wedge c)\vee(b \wedge c)$

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
