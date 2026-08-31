<head>
<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    displayMath: [['$$', '$$'], ['\\[', '\\]']]
  }
};
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<title>3 Energy, Temperature, and Heat</title>
</head>

## Energy
Energy is a measure of an object's ability to do physical work.

> __Demo__: Conservation of Energy Marble Track

Conservation of energy says that energy is not created or destroyed. It can only be converted from one form to another.

Meteorology is based completely on this premise. Energy comes from the sun and is converted into forms that move our atmosphere.

Types of energy:
* Radiant Energy / Light Energy (Sun)
* Kinetic Energy (Wind)
* Potential Energy (Clouds)
* Thermal Energy (Heated ground)
* Chemical Energy (Bonds within air molecules)

## Temperature
We need a way to measure energy. __Temperature__ is a measure of the kinetic energy (KE) of molecules. 

Molecules vibrate and move. The faster they vibrate and move (more KE), the warmer it feels on our skin. The slower they vibrate and move, the colder it feels on our skin.

### Temperature Scales
We have three main temperature scales
* Explain Fahrenheit scale
* Explain Celsius scale

$$T^\circ C = \tfrac{5}{9}(T^\circ F - 32^\circ F) \qquad T^\circ F = \tfrac{9}{5}T^\circ C + 32^\circ F$$

The problem with these scales is that none of these scales truly describes energy. Does $0^\circ F$ mean we are out of energy? No, because we can have less energy (get colder).

We need a 3rd scale that measures energy. The Kelvin scale is just the Celsius scale but shifted so that 0K is the temperature at which all KE is lost (motion stops). This temperature is known as __absolute zero__. This happens at $T_0 = 0K = -273^\circ C = -419^\circ F$

$$T^K = T^\circ C + 273$$

## Heat
Meteorology deals with energy being converted (or transferred) from place to place (The sun to the ground, the ground to the air, etc.). The process in which energy is transferred due to a difference in temperature is known as __heat__.
* Gaining heat = energy is transferred into the object
* Losing heat = energy is transferred out of the object

### Specific Heat
On the board, draw a cup with water. Label the temperature. Add ice.
* Indicate that the ice will cause the temperature of the water to drop
* This “change in temperature” is known as Specific Heat
* When an object gains energy, the temperature rises
* When an object loses energy, the temperature drops

### Latent Heat and States of Matter
* Indicate that while the temperature of the water drops, the ice in the cup will melt 
* This “change in the state of matter” is known as Latent Heat
* States of matter (include sublimation and deposition)
* When an object gains energy, it goes up one (or two) state(s) of matter
* When an object loses energy, it goes down one (or two) state(s) of matter

> __Demo__: Root Beer
> * Dry ice sublimates
> * Cloud is actually air cooling to the point that water is forced to condense

## Methods of Heat
How is this energy transferred?

### Conduction
Energy is transferred as one molecule hits another
* Pool balls

> __Demo__: Root Beer
> * Root beer is cooling from contact with Dry Ice

> __Demo__: Liquid N2 Ice Cream 
> * Conduction of energy from cream to N2 - causes cream to drop in T [specific heat] and N2 to evaporate [latent heat]

### Convection
> __Demo__: Convection Tube

> __Demo__: Root Beer
> * Cold air is more dense than warm air, so as the cloud comes out of the cooler, it sinks and pushes the warm air away, taking the energy with it

### Radiation
Electromagnetic waves (show picture from OpenStax 24.2)

![Concept of an Electromagnetic Wave](https://openstax.org/apps/image-cdn/v1/f=webp/apps/archive/20260105.231123/resources/d51b32ae43db26c62e088319af4c507e6302019d)

* The size of the wave determines the type of radiation

| Radiation Type | Wavelength                     |
| :------------: | :----------------------------: |
| Radio          | $\lambda > 1 m$                |
| Microwave      | $100 \mu m < \lambda < 1 m$    |
| Infrared       | $700 nm < \lambda < 0.1 \mu m$ |
| Visible        | $350 nm < \lambda < 700 nm$    |
| Ultraviolet    | $1 nm < \lambda < 700 nm$      |
| X-rays         | $1 pm < \lambda < 1 nm$        |
| Gamma rays     | $\lambda < 1 pm$               |

![The Electromagnetic Spectrum](https://openstax.org/apps/image-cdn/v1/f=webp/apps/archive/20260105.231123/resources/87ac85312b2e847d3bd7f7b2fa4fb6f5f4196179)

![The Visible Spectrum](https://openstax.org/apps/image-cdn/v1/f=webp/apps/archive/20260105.231123/resources/3f72ee1b28aa1be866672f74d2fe1c18ae534ff6)

#### Wein's Law
All objects emit radiation. The type of radiation depends on the temperature. We can measure the type of radiation using __Wein's Law__.

$$\lambda = \frac{3000 \mu m}{T}$$

* What type of radiation do we give off? ($T = 98.6^\circ F = 37.0^\circ C = 310 K$)

> __Demo__: IR Camera and Satellite Imagery

#### Blackbodies
If we assume all objects emit radiation perfectly, then there is a distribution of wavelengths given off. (show blackbody diagram)

Not everything emits perfectly, but most objects are close enough that this method works for studies.

#### Stefan-Boltzmann Law
The amount of radiation also depends on the temperature.

$$E = \sigma T^4$$

* $\sigma$ is just a constant number
* $T$ is the temperature in Kelvin

As the temperature rises, the energy emitted rises exponentially. (Compare height of blackbody profiles for Earth and the Sun)

## The full picture
All of these methods (conduction, convection, radiation) work to heat our atmosphere simultaneously.
* Radiation heats the surface (sun -> surface)
* Conduction heats the air (surface -> air)
* Convection distributes the heated air in the atmosphere (air -> atmosphere)

Likewise, these processes are used to cool the atmosphere
* Convection moves warm air away, such as in a cold front
* The atmosphere radiates energy into space
* Cold bodies of water will draw energy from warm air via conduction

The next lesson will look at the balance between gaining and losing energy.

-----

[Lecture Notes](./index.md)     Next lecture: [4: The Energy Budget](./04_EnergyBudget.md)