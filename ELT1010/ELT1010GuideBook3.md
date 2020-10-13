---
title: ELT 1010 Guide Book Lesson 3
layout: post
---

## Enter Multimeter
At the end of Lesson 2 we had constructed this simple LED circuit:

![Simple LED Circuit](../images/schematics/circuit3-simpleled.svg)

If the LED is on, that means we know for sure that there is not only a **voltage** present, but also that we've created a **closed loop**, so the electrons can flow (**current**) through the LED, which is what makes it light up. But in order to know much more about what is going on here, we're going to need a way to **measure** the **voltage** between various parts of our circuit, as well as the amount of **current** that is flowing.

That's where this beauty comes in:

![A Multimeter]()

This is a **multimeter**, so named because it's actually a collection of **multiple** different measuring tools. In this course we will mainly use our **multimeters** to measure **voltage** and **current**. It's handy to have this functionality in one tool, but there are subtle differences in **how** we use it in each case, so pay close attention.

Let's start with the easy one: **voltage**. The dial in the center of the **multimeter** selects the *mode*: what you are measuring. The **DC voltage** modes are in the top left corner of the dial, and you can see that there are a few options: 200mV, 2V, 20V, 200V, and 600V. You want to use the mode with the smallest number that is still higher than your supply voltage. In our case, working with a **5V** power supply, we want to always use the **20V** mode (right around 10 o'clock).

A good first step would be to verify that our supply voltage is in fact **5V**. Remember that **voltage** is the *difference* in electrical energy between two points. Our **supply voltage** is the difference between our (-) and (+) rails, so to measure **voltage** we need to connect one of the multimeters **probes** to the (+) rail, and the other to the (-) rail, like this:

![Measuring Supply Voltage](../images/schematics/circuit3c-ledvolttot.svg)

That **(V)** symbol of course represents our multimeter (in **voltmeter** mode). There are some options when it comes to how to actually connect the probes to the rails but the easiest way makes use of any exposed conductors that are already connected to the rails. In our case, he leg of R1 that is connected to the (+) rail is an easy place contact with one probe, and likewise with the leg of the LED going into (-). Make sure the circuit is turned on (your LED should be lit), and measure the **supply voltage** (also known as V<sub>ss</sub> or V<sub>tot</sub>). **Record the result in your Workbook**

You should see a value *close* to 5V, though likely not exactly. This is something to get used to in the world of electronics: while we talk about electronics in **ideal** terms with nice round numbers, the reality is a lot messier. So any **supply voltage** between 4.9V and 5.1V is perfectly normal. Whenever asked to record a measurement, write down the actual measured value. We'll often compare it to a calculated value, just remember that **close is good enough**.

>You might get a reading of around **-5V**. All this means is you have the probes backwards: the **red** one should be used for the higher voltage point. Functionally it doesn't matter, you'll get the same number either way, just with a (-). In these cases, record the **actual** voltage **as if you had the probes the right way around**.

>If you aren't getting anything near **5V** or **-5V** on your multimeter, first make sure it's in the **20V** mode. Double check that you're circuit is turned on, and that you are contacting the probes to the right parts of the circuit. Our multimeters also have a **pause** function (called **hold**), which freezes the display. If there is a small **H** on your screen, press the **HOLD** button to unfreeze the display. If you've done your best to figure it our on your own and are still not getting a reading near **5V**, then ask for help.

Now for some more practice, **measure and record V<sub>R1</sub>**, the voltage *across* the resistor:

![Measuring V<sub>R1</sub>](../images/schematics/circuit3a-ledvolt.svg)

And **V<sub>LED</sub>**, the voltage *across* the LED:

![Measuring V<sub>R1</sub>](../images/schematics/circuit3b-ledvolt2.svg)




## More on Resistors

If wires are like 4-lane highways, **resistors** are like winding, bumpy, dirt roads; electrons can still travel through them, but have to take their time. This might be a bit of a misleading analogy though, because the resistor not only affects the speed of electrons while they travel through it, but the speed of **all** electrons everywhere in the resistor's circuit. Electrons are always in a bumper-to-bumper traffic jam, so they all move only as fast as the slowest ones.

Another way to think about resitors is imagining electrical current like water flowing from your sink down to the sewer line. If the pipe is clean, the water can flow as fast as possible (thanks gravity), but if there is a wad of cat hair stuck halfway down the pipe, not only will the water flow slowly through the hairball, but all of the water above the clog will also be moving slowly, and after the clog there will also only be a trickle entering the sewer.
