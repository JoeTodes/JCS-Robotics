---
title: NET 1010 Outline
layout: post
---

v2

## NET 1010 Outcomes
1. Describe Binary Number System and Logic Gates
2. Construct and Verify Basic Logic Gates
3. Construct a Simple Logic Circuit
4. Identify Pinouts and Use Various ICs

## Topics
### Binary Number System
* why do we use base 10?
* place value - powers of 10
* how adding works - reset to 0 and carry-over
* Binary - same thing, just base 2
  * only 2 possible numerals
  * place values - powers of 2 (1,2,4,8,16,32,64...)
  * adding (and all other math) still works in the same way

### Logic Gates
* electrical circuit with inputs and an output
* the state of the output depends on the states of the inputs
* Logic gate circuits can be constructed using transitors, as we'll see
* inputs and outputs can only have 2 values - 0 or 1, on or off, true or false, 0V or 5V
* truth tables
* NOT gate
  * pretty simple, if the input is 0 the output is 1, and vise versa
  * truth table
  * NOT Circuit
* AND gate
  * output is only true if both inputs are true
  * eg. you can only come to school if you have no symptoms AND wear a mask. 
  * truth table
  * AND Circuit
* OR gate
  * output is on if atleast one input is on
  * eg. you can come into the school if you are a student OR a teacher
  * truth table
  * OR Circuit
* NAND, NOR, XOR, XNOR
  * Description and truth tables

### ICs
  * By combining logic gates in interesting ways, you can achieve complex systems, from the examples we're about to make, all the way up to the Central Processing Unit (CPU) in your computers and phones
  * NAND Oscillator
    * Use of an oscillator
    * NAND Oscillator Circuit
    * rather than making 3 NAND gates from transistors - ICs
    * IC - useful circuits made really tiny and shoved into little boxes
      * thousands of different ICs, all with different behaviour, not just logic gates
      * many others in your kits, we need 74HC00
      * datasheet/pinout - how to find and read
     * how to breadboard the circuit
   * NAND Half Adder
     *  First step towards an ALU, a component of a CPU
     *  The ALU in your CPU can do 32 or 64 bit (digit) addition, lets just start with 1 bit
     * One bit addition logic - just like XOR (aside from the carry-over)
     * Could use an XOR IC, but where's the fun in that?
     * NAND Half Adder Circuit
     * For more bits (digits), just need one Adder circuit per bit, plus some way to handle the "carry-over" 
     * Called "Half Adder" because it can't handle a carry-over from a previous bit.
     * A Full Adder made with NAND gates requires 9 NAND gates per bit
  
### More Fun with ICs
* 555
  * ubiquitous and multifunction
  * let's use it to make another oscillator
    * NAND oscillator was limited to symettrical output
    * 555 Oscillator Circuit
* Other ICs in Kit
  * Quick description
  * Where to find pinout

### Final Project
   * Voltage Regulator Circuit
   * Make something cool using everything we've learned
   * Verify that it works on the breadboard
     * on/off switch
   * Design an enclosure for 3D Printing in CAD
     * Protoboard mounting
     * IO mounting
     * Assembly/Fastening
     * Battery mounting
     * Drawing sheets for Approval

## Circuits to Diagram
1. NOT Gate
2. AND Gate
3. OR Gate
4. NAND Oscillator Circuit
5. NAND Half Adder Circuit
6. 555 Oscillator Circuit
7. Voltage Regulator Circuit

## Evidence of Learning
* Completed binary and truth tables worksheet (O1)
* NOT, AND, and OR circuits breadboarded (O2)
* NAND Oscillator and NAND Half Adder Circuits breadboarded (O3)
* 555 and Final Project Circuits (O4)
