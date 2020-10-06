---
title: ELT 1010 Guide Book Lesson 1
layout: post
---

# ELT 1010 Guide Book Lesson 1

## Preamble
By this point in your education you've probably learned somethings about electricity. Terms like voltage, current, and circuit are probably familiar, though you may not quite remember exactly what they mean. The mechanics of electricity can be hard to conceptualize, these invisible forces and interactions are happening at such a small scale and extremely fast. I'll do my best here to explain the arcana of electricity, but there is a very good chance that my explanations won't quite *mesh* with the way your brain works. My hope is that by following along with the exercises that follow: reading schematics, building and analyzing circuits, and exploring the mechanics of electricity through experimentation, things become more clear. Reading explanations or listening to lectures can only take you so far; the *real* learning is in the **making**.

## Electricity 101
We're going to start from the absolute basic and work our way up in complexity, starting with our first vocabulary term: **VOLTAGE**
You may remember from an earlier grade that voltage is also known as "potential difference". In my experience, that definition is about all that most students remember from Grade 9 Science, but what does it really mean? What potential? A difference between what? Well to explain that let's look at a **voltage source** that you should all be familiar with:

![AA Battery](../images/AA%20Battery.png)

Let's zoom and enhance on that top terminal of the battery:

![Close up of AA Battery Terminal](../images/AA%20Zoom.png)

Zoom and enhance again:

![Even closer zoom of the AA Battery](../images/AA%20Zoom%202.png)

Once more?

![Illustration of Electrons](../images/AA%20Zoom%203.png)

See all those little particles packed together at the battery's negative terminal? Of course you do, it's an over simplified illustration. Regardless, those are **electrons**, the incredibly small, negatively charged particles that are one of the building blocks of atoms. What this AA battery does, what all **power supplies** do, is removes electrons from one terminal and force them to the other terminal. 

![But Why...](../images/memes/but-why.jpg)

Well there's an important detail above about electrons, which is that they are *negatively* charged. What happens when a bunch of negative charges are brought together? You probably remember that like *repels* like, things with the same charge are forced away from each other. So a bunch of electrons all forced together on one terminal of a power supply are just itching to spread out and get away from each other, much like if you and your extended family were all forced together on a tour bus across the country.

![Family Road Trip](../images/memes/family-road-trip.png)

Meanwhile, the positive terminal of the battery, with hardly any electrons, looks like a pretty appealing place for these claustrophobic particles to get to, so given the chance they will travel as fast as possible to get there. The concentration of electrons in a conductor is a form of **potential energy**. Just like something up high has the *potential* to start moving downwards when we let go (or the air in my bike tire has the *potential* to rapidly escape the tube when it pops right in the middle of my ride to work when I'm a 20 minute walk from any road that someone could come pick me up from...), The electrons have the *potential* to move somewhere with a lower concentration of electrons, if they are just provided a path.

The difference in the potential energy of electrons at two places, or *potential difference* (aahhh) is what we call **voltage** and is measured in **volts (V)**. So in our AA battery, which is a 1.5V battery, the negative end has 1.5 more volts of electrical potential energy than the positive end, and given a path (like say a wire connecting negative to positive), the electrons will flow as fast as they can from negative to positive. This *flow of electrons* is what we call **CURRENT**.


![Electron Flow](../images/1x/Electron%20Flow.png)


Here's where it is my solemn duty to thoroughly frustrate and confuse you. You see, back when folks were just starting to figure out this electricity business nobody knew about the electron, so early experimenters, including my guy Ben Franklin, assumed electricity was caused by the movement of *positive* particles. So diagrams were drawn with current flowing from the positive terminal to the negative terminal:

![Conventional Current](../images/1x/Conventional%20Current.png)

By the time scientists realized the truth, that they had the whole thing backwards, too many symbols and conventions had been developed under the positive charge assumption. Luckily it turns out not to matter which way we imagine it working, as long as we're all on the same page. So to this day we still draw diagrams and discuss electricity in the old-school, positive charge way AKA *conventional current*. 

![XKCD 'Urgent Mission'](https://imgs.xkcd.com/comics/urgent_mission.png)

Now, it should be said that the above description of voltage is a gross oversimplification, but the deeper physics around the *why* of electricity are beyond the scope of this course. The important concepts for our purpose when it comes to voltage are:
* Voltage is the *difference* between the energy at two points
* We usually refer to the negative terminal of our power supply as **0V** or ground (**GND**)
* Measuring or discussing voltage in a circuit always involves two different points in that circuit
  * Asking "what is the voltage of this wire?" is similar to asking "what is the difference between a duck?"
  * That said, unless otherwise specified, voltage is measured relative to 0V. So someone asking "what is the voltage of this wire" is likely asking "what is the voltage between this wire and the negative terminal of the power supply?"
* If there is a voltage between two points and a path between those points, electrical **current** will flow from positive to negative (I know, I know, just go with it)

![Conventional Current Meme](../images/memes/conventionalcurrentmeme.jpg)

Ok that's enough theory for now, in the next lesson we'll be breaking into your electronics kit and eventually building some circuits, so make sure you've got that handy, along with your **Electronics Components Worksheet**.

[NEXT LESSON](./ELT1010%20Guide%20Book%20Lesson%202.md)