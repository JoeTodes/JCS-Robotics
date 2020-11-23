---
title: NET 1010 Lesson 1
layout: post
---

Welcome to a brand new module: NET 1010 Digital Logic Systems 1. In this module we will use our knowledge of basic electrical circuits from ELT 1010 to build and experiment circuits that perform **digital logic**. The logical first step, then, is to figure out what **digital logic** even means.

Rather than reinvent the wheel, I'll let Carrie Anne from [Crash Course](https://www.youtube.com/channel/UCX6b17PVsYBQ0ip5gyeme-Q) explain the fundamental concepts. Make sure to follow along on the first page of your [Digital Logic Workbook](../extras/LogicGatesICsWorkbook.pdf).

<iframe width="560" height="315" src="https://www.youtube.com/embed/gI-qXk7XojA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## ICs
As explained in the video, it's fairly easy to construct logic gates from just a few transistors, but in practice we rarely do so. Instead we use something called an **IC**, which stands for **integrated circuit**. Imagine designing a circuit, making it as small as you can, stuffing it into a small plastic box with only some wires sticking out for power, inputs, and outputs, and then mass producing them. That's an **IC**. 

[ICs](../images/ics.jpg)

There are thousands of different kinds of **ICs** all with different functions, not just logic gates. **ICs** also come in a variety of shapes and sizes (AKA **form-factors**), the **ICs** included in your kit are all **Dual-Inline Pin (DIP)**, which is specifically designed for the standard breadboard hole pattern.

To start with, we will make a few circuits using just the **74HC00 IC** from your kit, but we'll see the other **ICs** in action later. The **7400** is a **"quad NAND gate IC**, which means that it contains 4 individual NAND gates. Here is an **internal logic diagram** that might shed some more light on what this means:

![74HC00 Internal Logic](../images/pinouts/74HC00-NAND.png)

Another common way of communicating how an IC works is a **pinout diagram** which just gives each pin a label. Here's the **pinout** for the **7400**:

![74HC00 Pinout](../images/pinouts/7400pinout.jpg)

In this case, **A** and **B** are used to indicate inputs to the NAND gates, **Y** is used for the outputs. **Vcc** and **GND** are standard labels for **positive** and **negative** voltage (**5V** and **0V** in our case). In any **IC** diagram you are looking from the top-down and both the diagrams and the **IC** itself will have some feature to know which end is which, either a small circle or an indent on one of the short sides. Pin numbering always starts with **1** and the bottom left (with the dot or indent on the left), and then counting up as you move **counter-clockwise** around the chip.

![Pin Numbering](../images/pinouts/pincount.png)

Armed with all this knowledge, let's first verify that our 7400 does in fact contain NAND gates. Plug your **74HC00** into your breadboard, spanning the gap. You might need to bend one row of pins slightly inward to get it to fit the first time. Using the diagrams above, connect the **Vcc** pin to **5V** and the **GND** pin to **0V**. **ALWAYS HAVE YOUR BREADBOARD POWER OFF WHEN CHANGING IC CONNECTIONS.**

![IC Breadboard Placement](../images/breadboards/dipplacement.jpg)

Now choose one of the 4 NAND gates available and connect the output pin to an **LED + current-limiting-resistor** combo. This will serve as an indication of whether the output is on or off. Finally, connect the two input pins to **0V** to set them initially to **off** AKA **false**. From your **NAND truth table**, we expect the output should be on, turn on your power to verify. Then verify for the other three combinations of inputs from the truth table. If your results don't agree with the truth table for NAND, check the following:
* Are you using the right IC? Look for the text "74HC00"
* Are you using the right pins? Double check the diagrams above
* Is your IC connected to power and ground?
* Is your indicator LED the right way around, and connected from the output pin to 0V along with a resistor?
* Do you have any idea what is going on? Ask for help if not