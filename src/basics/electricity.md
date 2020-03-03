# Electricity


There is a lot to say about electricity, but we'll keep it short and try to focus on what we need for our workshop.

This is mostly about defining terms and explaining what they mean and giving them some context. While it's not crucial at all to understand everything written here, it's still handy knowledge to have.

## What is electricity really?

*(This section is maybe a little over the top in terms of detail. Feel free to skip to [the next section]() if you're fine with not having to know every single last bit of how stuff works).*

Electricity is the flow of electric charge. Electric charge is a physical property of all matter, like mass or density, and can be measured.

On an atomic level, it is (negatively charged) electrons (hence the name) flowing from atom to atom. Some electrons are loosely attached to their atomic cores, we call them conductive. Some electrons are very strongly attached to their atomic cores, we call them insulated.

Electrons in conductive materials don't just start flowing on their own though, we need to give them a little push. If this push is constant and electrons are flowing constantly, we call it (electric) current.

The path that the electrons flow by is determined by the way of conductive material. The path we build for electrons is called a circuit. It is kind of circular must be free of any gaps.

Last piece we're missing is the constant push that makes the electrons flow. We need to store some electric potential energy in an electric field that we can use to do work (that's a fancy way of saying battery, huh?). This work consists of electric potential pushing electrons in one direction.

Electric potential is the term used to describe the amount of electric potential energy stored in electric fields (the electric potential energy divided by the amount of charge at one point). We usually refer to it as voltage, the difference between low and high points of electric potential in the electric field. It tells us about the pushing force of the field. It's unit is volt.

Now we have electricity!

We've left out some things and glossed over some others. If you want to dig deeper into the physics, Sparkfun has an extensive and really good post on [how electricity works](https://learn.sparkfun.com/tutorials/what-is-electricity/all).

## Voltage, current, resistance

When we talk about electricity in the context of electronics and electric circuits, we mostly concern ourselves with three properties: Voltage, current and resistance.

To help explain what each is what it's useful to know it, we'll use a common metaphor: water.

Instead of a circular circuit, we'll have water flowing downhill. A river. Like that we'll have similar conditions as with electrical charge.

### Voltage

Voltage describes the amount of potential energy in a circuit, more precisely the difference of potential energy between two points. Electrons will flow from a high point of potential energy to the low point, just like water in a river will flow from a higher altitude point to a lower altitude point. In the water metaphor, voltage would be the pressure with which the water flows downhill. The higher the difference in altitude between two points in the river the higher the pressure.

Voltage is measured in volts, using the letter **V** in schematics, named after [Alessandro Volta](https://en.wikipedia.org/wiki/Alessandro_Volta).

### Current

Current or flow is the amount of water that is in one point in the river at one point in time. Or the amount of electrons in one point in our circuit at one point in time. The higher the pressure or the voltage, the higher the current is going to be.

Current is measured in amperes or amps for short. It uses the letter **I** in schematics, named after [André-Marie Ampère](https://en.wikipedia.org/wiki/Andr%C3%A9-Marie_Amp%C3%A8re).

### Resistance

Resistance in the water metaphor would be anything that limits the current of the river, let's say the riverbed get narrower and therefore not as much water can pass by as before. The pressure stays the same, just the amount of water is limited. In the electric circuit, the resistance is something that limits the amount of electrons, while leaving the voltage untouched.

The physicist who described resistance (**R**) was [Georg Ohm](https://en.wikipedia.org/wiki/Georg_Ohm). Ohm says that 1 unit of resistance (or 1 **Ω** "Ohm"), is the resistance between two points, where one volt will push 1 ampere. So where one unit of  pressure will move a unit current.

### Ohm's Law

Putting the three together and into relation, we'll get Ohm's Law:

`V = I * R`

or

`1V = 1A * 1Ω`

Equipped with this formula we can calculate values in our circuit. Plus, knowing about these properties will help us understand how sensors manage to measure things. Exciting!


Once again, [Sparkfun has a more detailed guide](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law) with nice illustrations.
