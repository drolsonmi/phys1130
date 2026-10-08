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
<title>Atmospheric Stability</title>
</head>

## Reading
a

### Resources
* [Skew-T Diagram]()
* [Animation of Conditional Instability](https://drolsonmi.github.io/phys1130/9_AtmosphericStability/parcel-lift-animation.html)

## Environmental Lapse Rate
In the troposphere, the temperature drops with increasing altitude
* Avg Lapse Rate = $6.5^\circ C / km$ (or $3.5^\circ F / 1000ft$)
* This changes from day to day and from time to time
    * At night, the ground cools and forms a nighttime inversion, so the lapse rate is smaller
    * On a very hot day, the temperatue at the surface is hotter, so the lapse rate is larger
    * On a typical day, it is $6.5^\circ C / km$

### Skew-T diagram
Launch Weather Balloons to record data higher up in the atmosphere and get the actual atmospheric lapse rate.

> __Demo__: Radiosonde (NWS and my own)
> * Show my radiosonde
>   * Launch 2 times a day: 0000UTC and 1200UTC (coordinated so that we get a snapshot of the entire atmosphere)   
> * Look at most recent 0000UTC radiosonde
> * How the Skew-T works
>   * Pressure lines (Solid Black)
>   * Temperature lines (Solid Red)
>   * Mixing Ratio (Dotted Green)

## Atmospheric Stability
Thermal (a bubble of air, or a parcel of air) cools and expands as it rises

$$PV = nRT$$

- $P$ = Pressure
- $V$ = Volume
- $n$ = mass (assumed to not change)
- $R$ = Constant (doesn't change)
- $T$ = Temperature

Relate pressure, volume, and temperature
- Let's hold the temperature constant
    * As pressure rises, volume drops
    * As pressure drops, volume rises
- Let's hold the volume constant
    * As pressure rises, temperature rises also
    * As pressure drops, temperature drops also

Stable vs. Unstable 

![Stable Environment 1](https://www.noaa.gov/sites/default/files/2022-05/stability1.png)![Stable Environment 2](https://www.noaa.gov/sites/default/files/2022-05/stability2.png)![Stable Environment 3](https://www.noaa.gov/sites/default/files/2022-05/stability3.png)![Stable Environment 4](https://www.noaa.gov/sites/default/files/2022-05/stability4.png)

A condition is stable if it's current condition is preferrable to any potential change.

![Unstable Environment 1](https://www.noaa.gov/sites/default/files/2022-05/instability1.png)![Unstable Environment 2](https://www.noaa.gov/sites/default/files/2022-05/instability2.png)![Unstable Environment 3](https://www.noaa.gov/sites/default/files/2022-05/instability3.png)![Untable Environment 4](https://www.noaa.gov/sites/default/files/2022-05/instability4.png)

A condition is unstable if a change is preferrable to it's current condition.

If we raise a thermal into the air, what would determine whether it rises or sinks?
* Density
    * Warm air is less dense
    * Cool air is less dense
* Temperature differences also determine whether it will rise or sink

### Stable Atmosphere
Imagine,
* Air temperature at surface is $30^\circ C$
* Atmospheric lapse rate is $4^\circ C / km$
* > Draw this scenario, then lift the thermal dry and moist

Either way (dry or adiabatic), the thermal will sink to the ground

Atmosphere is stable if Atmospheric Lapse Rate $< 6^\circ C / km$

### Unstable Atmosphere
Imagine,
* Air temperature at surface is $30^\circ C$
* Atmospheric lapse rate is $11^\circ C / km$
* > Draw this scenario, then lift the thermal dry and moist

Either way (dry or adiabatic), the thermal will rise

Atmosphere is unstable if Atmospheric Lapse Rate $> 11^\circ C / km$

### Conditionally Unstable Atmosphere
Atmosphere is conditionally unstable if $6^\circ C / km \le$ Atmospheric Lapse Rate $\le 11^\circ C / km$.

Will the thermal rise or fall?
* It depends on the humidity
    * If the thermal is saturated, then the atmosphere is unstable
    * If the thermal is unsaturated, then the atmosphere is stable

[Animation of Conditionally Unstable Atmosphere](https://drolsonmi.github.io/phys1130/9_AtmosphericStability/parcel-lift-animation.html)

## Thermal forcing
4 major ways to force thermal to rise
1. Heating
    * Sunny days, forest fires
2. Orographic Uplift
3. Cold Front
4. Low Pressure System