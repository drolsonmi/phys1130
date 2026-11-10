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
<title>Exam 2 Study Guide</title>
</head>

# Meteorology Exam Study Guide: Chapters 6–11

**How to use this guide:** Each chapter section lists the key ideas you need to know, the vocabulary you should be able to define, the equations you should be able to use, and links to related lessons from the National Weather Service's JetStream Online School for Weather. A set of practice problems (with answers) is at the end. If you can explain each bolded term in your own words and work every practice problem without looking at the answer, you are in good shape.

> **Tip:** Many exam questions connect chapters. For example, stability (Ch. 6) explains why cold fronts bring thunderstorms (Ch. 11), and adiabatic warming (Ch. 6) explains Chinook and Santa Ana winds (Ch. 9). Look for those links as you study.

---

## Chapter 6 – Stability and Cloud Development

### 6.1 Lapse Rates

A **lapse rate** is the rate at which temperature decreases with increasing altitude.

| Lapse rate | What it describes | Typical value |
|---|---|---|
| **Environmental lapse rate (ELR)** | The *actual* temperature change with height in the surrounding air, measured by a radiosonde (weather balloon). It changes from day to day and place to place. | Average ≈ 6.5 °C/km (3.6 °F/1000 ft) in the troposphere |
| **Dry adiabatic lapse rate (DALR)** | How fast a rising **unsaturated** parcel cools (or a sinking parcel warms). | 10 °C/km (5.5 °F/1000 ft) — a constant |
| **Moist (saturated) adiabatic lapse rate (MALR)** | How fast a rising **saturated** parcel cools. | Varies; ≈ 6 °C/km (3.3 °F/1000 ft) as an average |

Key point: The ELR describes the *environment*. The DALR and MALR describe a *parcel* moving through that environment. Stability comes from comparing the two.

### 6.2 Adiabatic Heating and Cooling

The ideal gas law:

$$PV = nRT$$

* Keep Temperature constant:
    * As pressure rises, volume drops (Increased pressure collapses a can) - *Inverse Relationship*
* Keep Volume constant:
    * As temperature rises, pressure also rises (Tire pressure goes up after a long drive or on a hot day; this is also why aerosol cans warn you not to heat them) - *Direct Relationship*
* Keep Pressure constant:
    * As temperature rises, volume also rises (A balloon shrinks in the freezer and expands again in a warm room; a hot air balloon's heated air expands and becomes less dense) - *Direct Relationship*
* Let all three change together:
    * In the atmosphere, an air parcel's pressure, volume, and temperature usually change at the same time. A rising parcel moves into lower pressure, so it expands and cools; a sinking parcel is compressed and warms.
    - An **adiabatic process** is one in which a parcel of air changes temperature **without exchanging heat** with its surroundings.
    - **Rising air expands** (lower pressure aloft) → the molecules do work pushing outward → the parcel **cools**.
    - **Sinking air is compressed** (higher pressure below) → the parcel **warms** (compressional or adiabatic warming).
    - An **air parcel** is an imaginary "bubble" of air, a few hundred meters across, that keeps its identity as it moves.

#### Moist vs. Dry Adiabatic Lapse Rates

Near the surface, a parcel of air will rise adiabatically.
- If the parcel is __unsaturated__, then it will rise at the __Dry Adiabatic Lapse Rate__ (DALR) of $10^\circ C/km$
- If the parcel is __saturated__, then it will rise at the __Moist Adiabatic Lapse Rate__ (MALR) of $6^\circ C/km$
    - Condensation releases **latent heat**, which partly offsets the cooling from expansion. That is why the **Moist Adiabatic Lapse Rate** (MALR) **is smaller than the DALR**
    - At higher altitudes, the MALR does vary
- **Dew point lapse rate:** in a rising *unsaturated* parcel, the dew point also drops, at about **2 °C/km** (≈1 °F/1000 ft). (In a saturated parcel, the dew point equals the temperature and falls at the moist rate.)
- Once a rising dry parcel cools to its dew point, it becomes **saturated** and water vapor condenses into cloud droplets.

#### Skew-T Log-P Diagrams

A **Skew-T** is a thermodynamic chart used to plot a radiosonde sounding and evaluate stability.

- **Isobars** (pressure): horizontal lines, spaced logarithmically (pressure decreases upward).
- **Isotherms** (temperature): straight lines **skewed** about 45° up and to the right.
- **Dry adiabats:** curved lines sloping up to the left — the path an unsaturated parcel follows.
- **Moist (saturated) adiabats:** curved lines that are steeper near the surface and bend toward the dry adiabats aloft — the path a saturated parcel follows.
- **Mixing ratio lines:** dashed lines used with the dew point to find moisture content and the LCL.
- **Plotted lines:** the **temperature** profile (usually red) and the **dew point** profile (usually green). Where they are close together, the air is nearly saturated (likely cloud layer).
- **Features to identify:**
  - **LCL (Lifting Condensation Level):** where a lifted parcel becomes saturated — the cloud base.
  - **LFC (Level of Free Convection):** where a lifted parcel becomes warmer than the environment and rises on its own.
  - **EL (Equilibrium Level):** where the parcel's temperature again equals the environment's — roughly the top of a thunderstorm.
  - **CAPE:** the positive area between parcel and environment (energy available for storms).
  - **CIN:** the negative area below the LFC (the "cap" that must be overcome).
  - **Inversions:** layers where temperature increases with height (very stable).

### 6.3 Stability

**Stability** describes what happens to a parcel after it is given a small push upward:

- **Stable:** the lifted parcel is **colder (denser)** than its surroundings and sinks back to where it started.
- **Unstable:** the lifted parcel is **warmer (less dense)** than its surroundings and keeps rising on its own.
- **Neutral:** the parcel is the same temperature as its surroundings and stays where it is.

> **Ball analogy:** A ball in the bottom of a bowl rolls back (stable). A ball balanced on top of an upside-down bowl rolls away (unstable).

#### The Three Stability Categories

| Condition | Rule | Meaning |
|---|---|---|
| **Absolutely stable** | ELR < MALR | Stable whether the parcel is dry or saturated |
| **Absolutely unstable** | ELR > DALR | Unstable whether the parcel is dry or saturated (rare except near a hot surface) |
| **Conditionally unstable** | MALR < ELR < DALR | Stable if the parcel is **unsaturated**, unstable if it is **saturated**. The "condition" is saturation. This is the typical state of the atmosphere. |

**Memory trick:** Compare the environment's lapse rate to the parcel's lapse rates. If the environment cools *faster* than the parcel, the parcel ends up warmer than its surroundings → unstable.

#### What Makes the Atmosphere More Stable or Unstable

- **More stable:** cooling the surface air (nighttime radiation, cold air moving over a cold surface), warming the air aloft (warm air advection aloft), **subsidence** (sinking air in high pressure), inversions.
- **More unstable:** heating the surface air (daytime sun, cold air moving over warm water), cooling the air aloft (cold air advection aloft), adding moisture at low levels, lifting an entire layer whose bottom is moist and top is dry (**convective instability**).

#### Weather Associated with Each

- **Stable:** layered **stratus/stratiform** clouds, fog, haze, poor air quality (pollution trapped near the ground), steady light precipitation, smooth flying.
- **Unstable:** **cumuliform** clouds (cumulus, cumulonimbus), showers, thunderstorms, gusty winds, turbulence, good visibility (pollutants mixed upward).

#### Equation: Altitude of Cloud Base (LCL)

A rising unsaturated parcel cools at 10 °C/km while its dew point drops at about 2 °C/km, so the two close in on each other by about 8 °C per km. Saturation (the cloud base) occurs when they meet:

```
H (meters) = 125 × (T − Td)      with T and Td in °C
H (feet)   ≈ 222 × (T − Td)      with T and Td in °F
```

where **T** = surface temperature, **Td** = surface dew point, and **(T − Td)** is the **dew point depression**.

*Example:* T = 24 °C, Td = 16 °C → H = 125 × 8 = **1000 m**.

### 6.4 The Four Triggers for Cloud Development (Lifting Mechanisms)

Clouds form when air **rises, expands, and cools** to its dew point. Four main ways air is lifted:

1. **Convection (surface heating):** The sun heats the ground unevenly; warm, buoyant bubbles of air (**thermals**) rise. Produces fair-weather cumulus that can grow into cumulonimbus if the air is unstable. Most common on warm afternoons.
2. **Topography (orographic lifting):** Air is forced up the **windward** side of a mountain, cools, and forms clouds and precipitation. On the **leeward** side, air sinks and warms → dry **rain shadow** (see Ch. 9 Chinook calculation). Can also form **lenticular (lens-shaped) clouds** downwind of mountains.
3. **Convergence into low pressure:** Surface air spirals **inward** toward a low; the air has nowhere to go but **up**, so it rises and cools. That is why lows are associated with clouds and storms (and highs with sinking, clear air).
4. **Frontal lifting:** At a front, warmer, less dense air is forced up and over colder, denser air. Cold fronts lift air steeply (cumuliform clouds, storms); warm fronts lift air gradually (layered stratiform clouds).

### Chapter 6 JetStream Resources
- [How Clouds Form](https://www.noaa.gov/jetstream/clouds/how-clouds-form)
- [Parcel Theory](https://www.noaa.gov/jetstream/upperair/parcel-theory)
- [Stability–Instability](https://www.noaa.gov/jetstream/upperair/bowls)
- [Radiosondes](https://www.noaa.gov/jetstream/upperair/radiosondes)
- [Skew-T Log-P Diagrams](https://www.noaa.gov/jetstream/upperair/skew-t-log-p-diagrams)
- [Skew-T Plots](https://www.noaa.gov/jetstream/upperair/skew-t-plots)
- [Skew-T Examples](https://www.noaa.gov/jetstream/upperair/skewt_samples)
- [The Core Four (cloud types)](https://www.noaa.gov/jetstream/clouds/four-core-types-of-clouds)
- [The Basic Ten (cloud types)](https://www.noaa.gov/jetstream/clouds/ten-basic-clouds)

---

## Chapter 7 – Precipitation

**Big idea:** A typical cloud droplet is about **20 micrometers** across, while a typical raindrop is about **2 millimeters** — roughly **100 times** wider and about a **million times** larger in volume. Condensation alone is far too slow to grow drops that large. Two processes do the job: **collision–coalescence** (warm clouds) and the **ice-crystal process** (cold clouds).

### 7.1 Collision and Coalescence (Warm-Cloud Process)

- Works in **warm clouds** — clouds with temperatures **above 0 °C** throughout (common in the tropics).
- Larger droplets fall faster (higher **terminal velocity**) than small ones, so they **collide** with smaller droplets in their path.
- **Coalescence:** colliding droplets merge into one bigger drop.
- Factors that help: a wide range of droplet sizes (e.g., large salt nuclei over oceans), **thick clouds** (longer fall path), and **strong updrafts** (keep drops in the cloud longer).
- **Collection efficiency:** not every collision results in coalescence; very small droplets can be swept around a falling drop by the airflow.
- Raindrops larger than about **5 mm** tend to break apart. Falling raindrops are shaped more like **hamburger buns** than teardrops.

### 7.2 Types of Liquid Precipitation

| Type | Description |
|---|---|
| **Virga** | Precipitation that **evaporates before reaching the ground**, seen as streaks hanging below a cloud. Common in dry climates. |
| **Drizzle** | Very small drops (**diameter < 0.5 mm**) falling slowly from **stratus** clouds; very light accumulation. |
| **Rain** | Drops **≥ 0.5 mm**, typically steady, from **nimbostratus** (stratiform) clouds. |
| **Showers** | Rain from **cumuliform** clouds that **starts and stops suddenly** and changes intensity rapidly. |
| **Downbursts** | Strong, concentrated **downdrafts** that spread out on hitting the ground, often driven by evaporative cooling of rain falling into dry air (which makes the air denser). A small downburst (< 4 km across) is a **microburst**; a dangerous hazard to aircraft. |

### 7.3 Ice-Crystal Process (Bergeron Process)

- Works in **cold clouds** (cloud temperatures below 0 °C) — the main process for precipitation in the middle latitudes.
- Cold clouds contain **supercooled water droplets** (liquid below 0 °C) and **ice crystals** side by side. Liquid droplets can stay supercooled down to about **−40 °C** because **ice nuclei** are scarce.
  - 0 to −10 °C: mostly supercooled droplets
  - −10 to −20 °C: a mix of droplets and ice crystals (most active zone)
  - below −20 °C: mostly ice crystals
- **Key physics:** The **saturation vapor pressure over ice is lower than over liquid water** at the same temperature. Air that is just saturated for the droplets is *supersaturated* for the ice crystals.
- Result: water vapor **diffuses toward and deposits on the ice crystals**, while the droplets **evaporate** to replace the lost vapor. The ice crystals grow **at the expense of the droplets** until they are heavy enough to fall.
- Falling snow may **melt into rain** on the way down — much of the rain in the middle latitudes starts as snow.

### 7.4 Accretion and Aggregation

- **Accretion (riming):** Ice crystals collide with **supercooled droplets**, which **freeze on contact**. Heavy riming produces **graupel**, and the same process grows **hail**.
- **Aggregation:** Ice crystals **collide and stick together**, forming larger **snowflakes**. Works best near **0 °C**, when crystals have a thin, sticky liquid film; produces large, fluffy flakes.

### 7.5 Types of Snow Precipitation

| Type | Description |
|---|---|
| **Fallstreaks** | Streaks of ice crystals falling from high clouds (often cirrus) that **sublimate before reaching the ground** — the snow version of virga. |
| **Flurries** | Light snow falling intermittently from cumuliform clouds; little or no accumulation. |
| **Snow shower** | Snow falling from cumuliform clouds with **rapidly changing intensity** for a short time; may accumulate. |
| **Snow squall** | A brief, **intense** snow shower with **strong, gusty winds**; can drop visibility to near zero suddenly — very dangerous for drivers. |
| **Drifting snow** | Loose snow **lifted by wind to a low height** (less than about 6 ft/2 m) and piled into drifts; visibility at eye level is not greatly reduced. |
| **Blowing snow** | Snow lifted by wind to **6 ft (2 m) or higher**, **reducing horizontal visibility**. |
| **Blizzard** | NWS definition: sustained winds or frequent gusts of **35 mph or more** **and** visibility **below ¼ mile** in falling and/or blowing snow, lasting **3 hours or more**. Temperature is *not* part of the definition. |

Note: Snow can reach the ground even when surface temperatures are slightly above freezing (up to about 4 °C/39 °F) if the air below the cloud is dry enough for evaporative cooling to keep the flakes from melting.

### 7.6 Cloud Seeding

- **Purpose:** Increase precipitation (or disperse fog, or suppress hail) by adding nuclei to clouds.
- **Cold-cloud seeding:** Inject **silver iodide** (its crystal structure resembles ice, so it acts as an ice nucleus) or **dry ice** (solid CO₂, which chills the air so much that droplets freeze spontaneously). This jump-starts the **ice-crystal process** in clouds with lots of supercooled water but few ice crystals.
- **Warm-cloud (hygroscopic) seeding:** Add salt particles to encourage larger droplets and collision–coalescence.
- **Overseeding:** Adding too many nuclei creates many tiny crystals that compete for the same water, so none grow large enough to fall — it can *reduce* precipitation.
- **Limitations:** Seeding only works on clouds that already have the right conditions; it is hard to prove how much extra precipitation fell compared to what would have happened anyway.

### 7.7 Ice Precipitation

The **vertical temperature profile** (the layers of above- and below-freezing air) decides what reaches the ground. Be able to sketch these profiles.

| Type | How it forms | Temperature profile |
|---|---|---|
| **Snow** | Falls through air that is below freezing all the way down | Entirely below 0 °C |
| **Sleet (ice pellets)** | Snow **melts** in a warm layer aloft, then **refreezes into ice pellets** while falling through a **deep** subfreezing layer near the ground. Pellets bounce when they hit. | Cold aloft → warm layer → **deep** cold layer at surface |
| **Freezing rain** | Snow melts in a warm layer aloft; the subfreezing layer at the surface is **too shallow** to refreeze the drops, so they arrive as **supercooled** liquid and **freeze on contact** with cold surfaces, forming a coating of **glaze**. Widespread events are **ice storms**. | Cold aloft → warm layer → **shallow** cold layer at surface |
| **Graupel (snow pellets)** | Ice crystals heavily **rimed** (accretion) until the original crystal shape is hidden; soft, white, crumbly pellets 2–5 mm. | Cold cloud with lots of supercooled water |
| **Hail** | Grows inside **cumulonimbus** clouds with **strong updrafts** that hold the hailstone aloft while it collects supercooled water. Layers form as it moves through regions with different amounts of supercooled water (clear "wet growth" layers and milky "dry growth" layers). Falls when the updraft can no longer support it. NWS **severe** hail = **1 inch** diameter or larger. | Deep, strong thunderstorm updraft |

### 7.8 Measuring Precipitation

- **Standard rain gauge:** A funnel directs rain into a narrow inner tube with **one-tenth** the cross-sectional area of the funnel, magnifying the depth **10×** so small amounts can be read precisely (to 0.01 in).
- **Tipping-bucket gauge:** Small buckets tip each time they fill (e.g., 0.01 in), sending an electrical signal; good for rainfall *rate*; underestimates in very heavy rain.
- **Weighing gauge:** Weighs the collected precipitation; works for rain and snow.
- **Snow:** Measure **depth** with a ruler at several spots, and **water equivalent** by melting the snow. The average snow-to-liquid ratio is about **10:1**, but it varies widely (wet snow ~5:1; dry, powdery snow 20:1 or more).

#### Radar

- **RADAR** = RAdio Detection And Ranging. The U.S. network is **NEXRAD** (WSR-88D).
- The radar sends out **pulses of microwave energy**; precipitation particles scatter some energy back. The **time** for the echo to return gives **distance**; the **strength** of the return (**reflectivity**, in **dBZ**) indicates precipitation intensity.
  - Roughly: ~20 dBZ light, ~40 dBZ moderate to heavy, 50+ dBZ very heavy rain and possibly hail.
- **Doppler radar** measures the **shift in frequency** of the returned signal to find how fast precipitation is moving **toward or away from** the radar (**radial velocity**). Used to detect rotation (mesocyclones, tornado signatures) and damaging winds.
- **Dual-polarization** radar sends both horizontal and vertical pulses, giving information about particle **size and shape** — helps distinguish rain, snow, hail, and even tornado debris.
- **Limitations:** The beam rises with distance (Earth's curvature), so it can **overshoot** low precipitation far from the radar; mountains can **block** the beam; ground clutter, insects, and birds create false echoes; a melting layer can create an exaggerated "**bright band**."

### Chapter 7 JetStream Resources
- [Precipitation](https://www.noaa.gov/jetstream/atmosphere/precipitation)
- [Hydrologic Cycle](https://www.noaa.gov/jetstream/atmosphere/hydro)
- [Hazard: Hail](https://www.noaa.gov/jetstream/hail)
- [Hazard: Damaging Wind (downbursts)](https://www.noaa.gov/jetstream/wind_damage)
- [Doppler Radar](https://www.noaa.gov/jetstream/doppler)
- [How Radar Works](https://www.noaa.gov/jetstream/doppler/how-radar-works)
- [Radar Images: Reflectivity](https://www.noaa.gov/jetstream/reflectivity)
- [Radar Images: Velocity](https://www.noaa.gov/jetstream/velocity)
- [Radar Images: Precipitation](https://www.noaa.gov/jetstream/precipitation)

---

## Chapter 8 – Air Pressure and Winds

### 8.1 Difference in Temperature → Difference in Pressure → Wind

1. Unequal heating makes one column of air **warmer** than its neighbor.
2. Warm air **expands**; the warm column becomes **taller**, while the cold column **shrinks**.
3. At any given height **aloft**, there is **more air above you** in the warm column → **higher pressure aloft over warm air**, lower pressure aloft over cold air.
4. Air **aloft flows** from the warm column toward the cold column (high to low).
5. Mass moves out of the warm column and piles into the cold column, so at the **surface**, the warm region develops **lower pressure** and the cold region **higher pressure**.
6. **Surface winds** blow from the cold (high) toward the warm (low) region, completing a **thermal circulation**.

> Takeaway: **Warm air aloft = high pressure aloft; cold air aloft = low pressure aloft.** Pressure differences are what drive the wind.

**Pressure basics:**
- Air pressure = the **weight of the air above** a given point (force per unit area).
- Pressure **decreases with height**, rapidly near the surface (~10 mb per 100 m in the lower atmosphere).
- **Standard sea-level pressure** = **1013.25 mb** = **1013.25 hPa** = **29.92 in Hg** = **760 mm Hg**. (1 mb = 1 hPa.)
- Typical surface range: about 980–1040 mb; extreme lows in strong hurricanes can be below 900 mb.

### 8.2 Measuring Pressure

- **Mercury barometer** (invented by **Torricelli**, 1643): A glass tube filled with mercury is inverted in a dish of mercury. Air pressure on the dish supports the mercury column; at standard sea-level pressure it stands **76 cm (29.92 in)** high. Mercury is used because it is very dense (a water barometer would need a tube over 10 m tall). Readings are corrected for temperature and gravity.
- **Aneroid barometer** ("without liquid"): A small, partly evacuated, flexible **metal chamber (aneroid cell)** expands when pressure drops and contracts when pressure rises; levers move a pointer on a dial. Portable; basis of the **altimeter** (calibrated in altitude) and the **barograph** (records pressure on a rotating drum).
- **Station pressure:** the pressure actually measured at the station's elevation.

#### Calculation for Sea-Level Pressure

Stations at different elevations would show very different pressures just because of altitude. To compare them on a map, station pressure is **reduced to sea level**:

```
Sea-level pressure ≈ Station pressure + (10 mb per 100 m of station elevation)
```
(equivalently, about **1 mb per 10 m**, or about **1 in Hg per 1000 ft**)

*Example:* A station at **1500 m** reads **850 mb** → 850 + (1500 ÷ 100 × 10) = 850 + 150 = **1000 mb**.

### 8.3 Forces That Affect the Wind

#### Newton's Laws of Motion
1. **First law (inertia):** An object at rest stays at rest, and an object in motion keeps moving in a straight line at constant speed, unless acted on by a **net force**.
2. **Second law:** **F = m·a** — the net force on an object equals its mass times its acceleration. For air, acceleration (change in speed **or direction**) happens only when forces are out of balance.
3. **Third law:** For every action there is an equal and opposite reaction.

#### Pressure Gradient Force (PGF)
- The force that **starts air moving**, directed from **higher toward lower pressure**, **perpendicular to the isobars**.
- **Closely spaced isobars** = steep pressure gradient = strong PGF = **strong winds**. Widely spaced isobars = light winds.

**Equation for pressure gradient:**
```
Pressure gradient = Δp / d       (difference in pressure ÷ distance)
```
*Example:* 1008 mb and 1000 mb, 200 km apart → 8 mb / 200 km = **4 mb per 100 km**.

**PGF per unit mass (acceleration):**
```
PGF = (1/ρ) × (Δp / d)
```
where ρ is air density (≈ 1.2 kg/m³ near sea level). Use pascals (1 mb = 100 Pa) and meters.

#### Coriolis Force
- An **apparent** force due to **Earth's rotation**; air moving over the rotating Earth appears to be deflected.
- Deflects moving air to the **right in the Northern Hemisphere** and to the **left in the Southern Hemisphere**.
- Its strength **increases with wind speed** and with **latitude**: **zero at the equator**, **maximum at the poles**.
- It changes only wind **direction**, never speed.
- Equation (for reference): `Coriolis = 2Ω·V·sin φ = f·V`, where Ω = 7.29 × 10⁻⁵ rad/s (Earth's rotation rate), V = wind speed, φ = latitude, and f = 2Ω sin φ is the **Coriolis parameter**.
- Important only for motions that are large and long-lasting (not your bathtub drain or a tornado).

#### Centripetal Force (Centripetal Acceleration)
- The **net inward-directed force** needed to keep air moving in a **curved path**. It is not a separate push; it is the imbalance between PGF and Coriolis in curved flow.
- Gives rise to the **gradient wind**, which flows parallel to **curved** isobars:
  - Around a **low**: PGF > Coriolis; wind speed is **subgeostrophic** (slower than geostrophic).
  - Around a **high**: Coriolis > PGF; wind speed is **supergeostrophic** (faster than geostrophic).
- **Northern Hemisphere:** **counterclockwise** around lows (**cyclonic**), **clockwise** around highs (**anticyclonic**). Reversed in the Southern Hemisphere.

#### Friction
- Acts in the **friction layer (planetary boundary layer)**, the lowest ~1 km of the atmosphere; stronger over rough land than over smooth water.
- **Slows** the wind → weaker Coriolis force → PGF wins, so surface winds **cross the isobars toward lower pressure** at an angle (about 30° on average; ~10–20° over water, up to ~45° over rough land).

### 8.4 Geostrophic Winds
- Wind that blows in a **straight path parallel to the isobars**, at a constant speed, when the **PGF and the Coriolis force are in balance** (equal and opposite).
- Found **aloft** (above the friction layer) with **straight**, evenly spaced isobars/contours.
- In the NH, with the wind at your back, **lower pressure is to your left**.
- Geostrophic wind speed: `Vg = (1 / (ρ·f)) × (Δp / d)` — stronger gradient → faster wind.

### 8.5 Surface Winds
- Because of friction, surface winds blow **across** the isobars toward lower pressure.
- **NH low (cyclone):** winds spiral **counterclockwise and inward** → **convergence** → **rising air** → clouds and precipitation.
- **NH high (anticyclone):** winds spiral **clockwise and outward** → **divergence** → **sinking air (subsidence)** → generally clear, dry weather.
- **Convergence aloft** over a surface high and **divergence aloft** over a surface low keep these systems going (upper-level divergence lets a surface low deepen).

### 8.6 Winds on Upper-Level Charts
- Upper-air charts are **constant-pressure (isobaric)** charts (e.g., 850, 700, **500**, 300, 200 mb). Instead of isobars, they show **height contours** — the altitude of that pressure surface.
- **Low heights = cold air** (low pressure aloft); **high heights = warm air** (high pressure aloft). Heights generally **decrease toward the poles**, so upper-level winds are mostly **westerly** in the middle latitudes.
- **Ridges:** elongated areas of **high** heights (contours bulge **poleward**) — usually fair weather beneath.
- **Troughs:** elongated areas of **low** heights (contours dip **equatorward**) — often unsettled, stormy weather.
- Upper-level winds blow **nearly parallel to the contours** (geostrophic or gradient flow); closer contours = stronger wind. The 500 mb level is about halfway up through the atmosphere's mass (~5.5 km).

### 8.7 Buys-Ballot's Law
- **Northern Hemisphere:** If you stand with your **back to the wind**, **lower pressure is to your left** and higher pressure to your right.
- At the **surface**, first turn **clockwise about 30°** (to account for friction), then low pressure is to your left.
- **Southern Hemisphere:** reversed — low pressure is to your right.
- Use it to locate storm centers from wind observations.

### Chapter 8 JetStream Resources
- [Air Pressure](https://www.noaa.gov/jetstream/atmosphere/air-pressure)
- [Wind (origin of wind)](https://www.noaa.gov/jetstream/synoptic/origin-of-wind)
- [Surface Weather Maps](https://www.noaa.gov/jetstream/wxmaps)
- [Upper Air Charts](https://www.noaa.gov/jetstream/upper-air-charts)
- [Pressure vs. Elevation](https://www.noaa.gov/jetstream/upper-air-charts/verses)
- [Common Features of Constant-Pressure Charts](https://www.noaa.gov/jetstream/upper-air-charts/common-features-of-constant-pressure-charts)
- [Basic Wave Patterns (ridges and troughs)](https://www.noaa.gov/jetstream/upper-air-charts/basic-wave-patterns)
- [500 mb Charts](https://www.noaa.gov/jetstream/upper-air-charts/constant-pressure-charts-500-mb)

---

## Chapter 9 – Wind: Small-Scale and Local Systems

### 9.1 Scales of Atmospheric Motion

| Scale | Typical size | Typical lifetime | Examples |
|---|---|---|---|
| **Microscale** | Meters to ~1 km | Seconds to minutes | Small turbulent eddies, gusts, smoke plumes, dust devils |
| **Mesoscale** | ~1 km to ~100 km | Minutes to hours (up to a day) | Thunderstorms, tornadoes, sea/land breezes, mountain/valley breezes, Chinooks, squall lines |
| **Synoptic scale** | Hundreds to thousands of km | Days to a week | Mid-latitude cyclones and anticyclones, fronts, hurricanes — the features on a weather map |
| **Global (planetary) scale** | Thousands of km to the whole Earth | Weeks to months or longer | Prevailing westerlies, trade winds, long waves, jet streams, monsoons |

(Synoptic and global scales together are often called the **macroscale**.) Key pattern: **bigger systems last longer**.

Related terms: **eddies** (swirls created when wind flows past obstacles), **mechanical turbulence** (from obstacles/surface roughness), **thermal turbulence** (from surface heating), and **wind shear** (change in wind speed or direction with distance).

### 9.2 Local Wind Systems

#### Thermal Circulations
Created by **differences in heating** between two nearby surfaces (see Ch. 8.1). Warm surface → surface low (thermal low) and high aloft; cool surface → surface high (thermal high) and low aloft.

- **Sea breeze (daytime):** Land heats faster than water → low pressure over land → cool, moist air flows **from sea to land** at the surface. The **sea breeze front** can trigger afternoon thunderstorms (e.g., Florida).
- **Land breeze (nighttime):** Land cools faster than water → air flows **from land to sea**; usually weaker than the sea breeze.
- **Lake breezes** work the same way around large lakes.
- **Valley breeze (daytime):** Mountain slopes heat faster than the air at the same height over the valley → air flows **upslope**; often forms cumulus over peaks in the afternoon.
- **Mountain breeze (nighttime):** Slopes cool quickly → cold, dense air drains **downslope** into the valley; cold air pools in valley bottoms.
- **Why water heats more slowly than land:** higher **specific heat**, sunlight penetrates deeper, mixing spreads heat, and evaporation uses energy.

#### Katabatic Winds
- **Cold, dense air** flowing **downhill under the force of gravity**, often from a high plateau covered with snow or ice.
- Can be very strong when funneled through canyons. Examples: winds off the ice sheets of **Antarctica** and **Greenland**; the **bora** (Adriatic coast) and **mistral** (Rhône Valley, France).
- Even though the air warms by compression as it descends, it starts so cold that it **arrives still cold**.

#### Chinook (Foehn) Winds
- **Warm, dry, downslope** winds on the **leeward (east) side of the Rocky Mountains**; called **foehn** in the Alps.
- Air descending the lee side warms by **compression** at the **dry adiabatic rate**. If precipitation fell on the windward side, the air also keeps the **latent heat** released there, so it ends up **warmer and drier** than when it started.
- Can raise temperatures by 20 °C or more within hours and quickly melt snow ("**snow eater**"). A **Chinook wall cloud** may sit over the mountain crest.

#### Santa Ana Winds
- **Hot, dry, gusty** winds blowing from the **east or northeast** into **Southern California**, most common in **fall and winter**.
- Driven by **high pressure over the Great Basin** and lower pressure offshore. The air sinks from the high plateau toward the coast, **warming by compression** and becoming extremely dry; funneling through canyons speeds it up.
- Major **wildfire** hazard: low humidity, dried vegetation, and strong winds.

#### Calculating Temperature and Dew Point in the Rain Shadow

**Rules:**
1. **Windward, below cloud base (unsaturated):** T drops **10 °C/km**; Td drops **2 °C/km**.
2. **Find cloud base:** H = 125 × (T − Td) meters.
3. **Windward, above cloud base (saturated):** T and Td are equal and drop together at the **moist rate (≈6 °C/km)**. Water condenses and falls as precipitation, so moisture is removed.
4. **Leeward descent (unsaturated):** T rises **10 °C/km**; Td rises **2 °C/km**.

**Worked example:** A parcel at sea level has T = 20 °C and Td = 12 °C and is pushed over a 3000 m mountain.
- Cloud base: 125 × (20 − 12) = **1000 m**.
- At 1000 m: T = 20 − 10 = **10 °C**; Td = 12 − 2 = **10 °C** → saturated ✓
- From 1000 m to 3000 m (2 km at 6 °C/km): T = Td = 10 − 12 = **−2 °C** at the summit.
- Descend 3000 m on the lee side: T = −2 + 30 = **28 °C**; Td = −2 + (3 × 2) = **4 °C**.
- **Result:** The air started at 20 °C/12 °C and ends at **28 °C/4 °C** — **warmer and much drier** on the leeward side. That is the rain shadow effect.

#### The Monsoon
- A **seasonal reversal of the prevailing wind**, caused by differential heating of a **continent vs. the ocean**, together with the seasonal shift of the **ITCZ**.
- **Summer monsoon:** Land is hot → thermal low over land → moist ocean air flows **onshore** → rises → heavy rain (e.g., India and southern Asia).
- **Winter monsoon:** Land is cold → high pressure over land → dry air flows **offshore** → dry season.
- It's like a giant, **seasonal** version of the sea/land breeze.
- The **North American Monsoon** brings summer thunderstorms to the **southwestern U.S.** and northwestern Mexico (typically July–September).

### Chapter 9 JetStream Resources
- [The Sea Breeze](https://www.noaa.gov/jetstream/ocean/sea-breeze)
- [The Marine Layer](https://www.noaa.gov/jetstream/ocean/marine-layer)
- [Wind (origin of wind)](https://www.noaa.gov/jetstream/synoptic/origin-of-wind)
- [The Transfer of Heat Energy](https://www.noaa.gov/jetstream/atmosphere/transfer-of-heat-energy)
- [Types of Weather Phenomena](https://www.noaa.gov/jetstream/synoptic/types-of-weather-phenomena)
- [Inter-Tropical Convergence Zone (link to monsoons)](https://www.noaa.gov/jetstream/tropical/convergence-zone)

---

## Chapter 10 – Wind: Global Systems

### 10.1 The Single-Cell Model

- Proposed by **George Hadley** (1700s). Assumes Earth is **uniformly covered with water**, the sun is always over the equator, and **Earth does not rotate**.
- Air heated at the **equator rises**, flows **poleward aloft**, cools and **sinks at the poles**, then returns **toward the equator at the surface**.
- One giant convection cell per hemisphere (a **Hadley cell**).
- **Problem:** Earth *does* rotate. The Coriolis force deflects the poleward-moving air, so a single cell cannot work — leading to the three-cell model.

### 10.2 The Three-Cell Model

Each hemisphere has three cells:

| Cell | Latitudes | Behavior |
|---|---|---|
| **Hadley cell** | 0°–30° | Thermally driven: air rises at the equator, sinks near 30° |
| **Ferrel cell** | 30°–60° | Driven indirectly by the other two cells; surface air flows poleward |
| **Polar cell** | 60°–90° | Cold air sinks at the pole, flows equatorward at the surface, rises near 60° |

#### Surface Pressure Belts and Wind Belts (Northern Hemisphere; mirror image in the Southern Hemisphere)

| Latitude | Feature | Weather |
|---|---|---|
| **0° (equator)** | **Equatorial low / ITCZ / doldrums** — rising air, converging trade winds | Light winds, frequent thunderstorms, heavy rain (tropical rainforests) |
| **0°–30°** | **Trade winds** — from the **northeast** (NH) / **southeast** (SH) | Steady, reliable winds |
| **~30°** | **Subtropical highs / horse latitudes** — sinking air | **Dry, clear, light winds → major deserts** (Sahara, Sonoran, Australian) |
| **30°–60°** | **Prevailing westerlies** — from the **southwest** (NH) | Changeable weather with mid-latitude storms |
| **~60°** | **Subpolar low / polar front** — where cold polar air meets milder air | Rising air, **storms** and precipitation |
| **60°–90°** | **Polar easterlies** — from the **northeast** (NH) | Cold winds |
| **90° (pole)** | **Polar high** — sinking cold air | Cold and dry (polar deserts) |

#### Semipermanent Highs and Lows
In reality, continents and oceans break the pressure belts into separate cells that shift with the seasons.

- **Semipermanent highs (sinking air, dry weather, deserts):**
  - **Bermuda–Azores High** (subtropical North Atlantic)
  - **Pacific (Hawaiian) High** (subtropical North Pacific) — keeps California dry in summer
  - Seasonal: **Siberian High** and **Canadian High** in winter (very cold continental air)
- **Semipermanent lows (rising air, storms):**
  - **Icelandic Low** and **Aleutian Low** — strongest in winter; regions where storms often form and intensify
  - Seasonal: **thermal lows** over hot continents in summer (e.g., the desert Southwest, southern Asia)
- **Seasonal shifts:** Highs and lows migrate **north in the NH summer** and **south in winter**, following the sun.

#### The ITCZ (Intertropical Convergence Zone)
- The band near the equator where the **NE and SE trade winds converge**, forcing air to rise → towering cumulonimbus and heavy rain.
- Visible on satellite images as a **band of clouds** circling the globe.
- **Migrates seasonally**, following the zone of strongest heating; it shifts much farther over **continents** than over oceans. Its movement controls **wet and dry seasons** in the tropics and plays a role in monsoons.

### 10.3 Jet Streams
- **Narrow, fast-moving rivers of air** near the top of the troposphere, generally flowing **west to east**. Speeds are often **over 100 knots** and can exceed 200 knots.
- Form where there are **strong horizontal temperature contrasts** (large pressure gradients aloft).
- **Polar front jet:** near **~10 km** altitude, above the **polar front** (around 30°–60°, shifting with the seasons); **stronger and farther south in winter**. It steers mid-latitude storms.
- **Subtropical jet:** near **~13 km**, around **~30°** latitude, above the poleward edge of the Hadley cell.
- Other jets: the **low-level jet** (a nighttime wind maximum over the Great Plains that feeds moisture to storms) and the **tropical easterly jet** (summer, over southern Asia/Africa).
- Jet streams **meander** in ridges and troughs (long waves/Rossby waves). Areas of **divergence aloft** near the jet help surface lows develop.

### 10.4 Ocean Currents
- Surface currents are driven mainly by the **prevailing winds** and deflected by the **Coriolis force**, forming large circular **gyres** (clockwise in the NH, counterclockwise in the SH) around the subtropical highs.
- **Warm currents** run poleward along the **western sides of ocean basins** (east coasts of continents): **Gulf Stream**, **Kuroshio**.
- **Cold currents** run equatorward along the **eastern sides of ocean basins** (west coasts of continents): **California Current**, **Canary Current**, **Peru (Humboldt) Current**.
- **Ekman transport:** Because of Coriolis, the **net** movement of the surface water layer is about **90° to the right** of the wind in the NH (to the left in the SH).

#### Upwelling
- When winds blow **parallel to a coast** such that Ekman transport pushes surface water **away from shore**, **cold, nutrient-rich water rises** from below to replace it.
- Example: northerly winds along the **California coast** in spring and summer → cold water → **summer fog**, cool coastal temperatures, rich fisheries. Also off **Peru** and **NW Africa**.

#### El Niño / La Niña / ENSO
- **Normal conditions (tropical Pacific):** Trade winds blow east to west, piling warm water in the **western Pacific** (near Indonesia/Australia, which is rainy). **Upwelling** keeps the eastern Pacific near **Peru/Ecuador** cool. The air circulation across the Pacific is called the **Walker circulation**.
- **El Niño:** The **trade winds weaken** (or even reverse). Warm water spreads **eastward** across the central and eastern Pacific; **upwelling weakens** off South America (harming fisheries). Heavy rain shifts east toward the central Pacific and South America; drought can affect Indonesia and Australia.
- **La Niña:** The **opposite** — **stronger trade winds**, **colder than normal** water in the central and eastern Pacific, enhanced upwelling.
- **Southern Oscillation:** The **seesaw in surface pressure** between the eastern and western tropical Pacific (measured between **Tahiti** and **Darwin, Australia**). When pressure is unusually low in the east and high in the west, El Niño tends to occur.
- **ENSO** (El Niño–Southern Oscillation) = the coupled ocean–atmosphere system; episodes recur irregularly about every **2–7 years**.
- **Typical U.S. winter impacts:**
  - **El Niño:** wetter and stormier across the **southern U.S.**; milder, often drier across the **northern U.S.**; a stronger subtropical jet; fewer Atlantic hurricanes.
  - **La Niña:** drier and warmer across the **southern U.S.**; colder and wetter in the **Pacific Northwest** and northern tier; more Atlantic hurricanes.
- Global effects of distant climate patterns like these are called **teleconnections**.

### Chapter 10 JetStream Resources
- [Global Atmospheric Circulations](https://www.noaa.gov/jetstream/global/global-atmospheric-circulations)
- [The Jet Stream](https://www.noaa.gov/jetstream/global/jet-stream)
- [Inter-Tropical Convergence Zone](https://www.noaa.gov/jetstream/tropical/convergence-zone)
- [Ocean Circulations](https://www.noaa.gov/jetstream/ocean/circulations)
- [El Niño/Southern Oscillation](https://www.noaa.gov/jetstream/tropical/enso)
- [ENSO Pacific Impacts](https://www.noaa.gov/jetstream/tropical/enso/enso-patterns)
- [ENSO Weather Impacts](https://www.noaa.gov/jetstream/enso_impacts)
- [Longwaves and Shortwaves](https://www.noaa.gov/jetstream/upper-air-charts/longwaves-and-shortwaves)
- [Climate Zones](https://www.noaa.gov/jetstream/global/climate-zones)

---

## Chapter 11 – Air Masses and Fronts

### 11.1 Air Masses

An **air mass** is an extremely large body of air (often over 1500 km across) whose **temperature and humidity are fairly uniform horizontally** at any given altitude.

- Air masses form over **source regions**: large, flat areas with **uniform surface** conditions (ice fields, oceans, deserts) where air can sit for days — typically under **high pressure** with light winds.
- They take on the **temperature and moisture** of the surface below them.

#### Classification

- First letter (moisture): **c = continental** (forms over land, **dry**); **m = maritime** (forms over water, **moist**).
- Second letter (temperature): **A = arctic** (extremely cold), **P = polar** (cold), **T = tropical** (warm/hot).

| Air mass | Properties | Source regions | Typical weather in North America |
|---|---|---|---|
| **cA (continental arctic)** | Extremely cold, very dry, very stable | Arctic Basin, Greenland ice cap, Siberia (winter) | Bitter cold outbreaks, clear skies |
| **cP (continental polar)** | Cold, dry, stable | Northern Canada, Alaska, Siberia | Cold, clear winter days; **lake-effect snow** when it crosses the Great Lakes; cool, pleasant summer air |
| **cT (continental tropical)** | Hot, very dry, unstable near the surface but often capped aloft | Desert Southwest U.S. and northern Mexico (mainly summer) | Heat waves, drought, very low humidity |
| **mP (maritime polar)** | Cool, moist, often conditionally unstable | North Pacific and North Atlantic | Pacific NW clouds, rain, and mountain snow; cool, damp weather in New England (**nor'easters**) |
| **mT (maritime tropical)** | Warm, very humid, often unstable | Gulf of Mexico, Caribbean, subtropical Atlantic and Pacific | Muggy summer weather, thunderstorms east of the Rockies; heavy rain events on the West Coast (e.g., the "**Pineapple Express**" from near Hawaii) |

#### Modified Air Masses
As an air mass moves away from its source region, it is **modified** by the surface it crosses:

- **Cold air over a warm surface** → heated from below → **less stable** → cumulus clouds, showers.
  - Example: **cP air crossing the unfrozen Great Lakes** picks up heat and moisture → **lake-effect snow** on the downwind (east/southeast) shores.
  - Example: mP air from the Pacific crossing the Rockies loses moisture on the windward side and arrives on the Plains drier.
- **Warm air over a cold surface** → cooled from below → **more stable** → fog, low stratus, drizzle.
- Air masses can also gain or lose moisture (evaporation, precipitation) and be changed by **lifting** or **subsidence**.
- Some textbooks mark this with a third letter: **k** (colder than the surface below) or **w** (warmer than the surface below).

### 11.2 Fronts

A **front** is a **transition zone between two air masses of different densities** (usually different temperatures and/or humidity). Fronts are drawn where they intersect the ground.

**How to locate a front on a surface map (look for these together):**
1. **Sharp temperature change** over a short distance
2. **Change in moisture** (dew point)
3. **Wind shift** (change in direction)
4. **Pressure changes** — fronts lie in **troughs** of low pressure (pressure falls ahead of the front and rises behind it)
5. **Clouds and precipitation** patterns

#### Stationary Front
- **Map symbol:** alternating **red semicircles** and **blue triangles** pointing in **opposite directions**.
- A front with **little or no movement**; winds blow nearly **parallel** to the front from opposite directions.
- Can bring **long-lasting** clouds and precipitation (and flooding) over the same area. Can turn into a warm or cold front if one air mass starts to advance.

#### Cold Front
- **Map symbol:** **blue line with triangles** pointing in the direction of movement.
- **Cold, dense air advances** and wedges **under** the warmer air, forcing it up steeply. **Steep slope** (about 1:50 to 1:100). Generally moves **faster** than warm fronts.
- **Ahead of the front:** warm, humid air; south or southwest winds (NH); **falling pressure**; possible cumulus building.
- **At the front:** a **narrow band** of cumulonimbus clouds — **showers, thunderstorms**, gusty winds, heavy but brief precipitation; sometimes a **squall line** ahead of it.
- **Behind the front:** **colder, drier** air; winds shift to **west or northwest**; **rising pressure**; rapid **clearing**; lower dew points.

#### Warm Front
- **Map symbol:** **red line with semicircles** pointing in the direction of movement.
- **Warm air advances** and rides **up and over** the retreating cold air. **Gentle slope** (about 1:200 or less) → clouds and precipitation spread **far ahead** of the front (hundreds of km).
- **Classic cloud sequence as it approaches:** **cirrus** → **cirrostratus** (halo around sun/moon) → **altostratus** → **nimbostratus** (steady precipitation) → **stratus/fog**.
- **Ahead of the front:** cool air; east or southeast winds; **falling pressure**; widespread, **light-to-moderate steady precipitation**. In winter, a warm layer aloft can produce **sleet and freezing rain** (see Ch. 7).
- **Behind the front:** **warmer, more humid** air; winds from the south or southwest; pressure levels off; clearing or partly cloudy skies (thunderstorms possible if the warm air is unstable).

#### The Dry Line
- Although your outline lists it here, the dry line is its **own type of boundary**: it separates **warm, moist mT air** (from the Gulf of Mexico) from **hot, dry cT air** (from the desert Southwest). The key difference across it is **moisture (dew point)** rather than temperature.
- **Map symbol:** a scalloped line (open semicircles), often drawn in **orange/brown**.
- Most common over the **southern and central Great Plains** (west Texas, Oklahoma, Kansas) in **spring and early summer**.
- The dry air behind it is less dense than the humid air ahead, so on hot afternoons it can lift the moist air → **severe thunderstorms**, including **supercells and tornadoes**, often form along it.
- Typically moves **east during the day** and **retreats west at night**.

#### Occluded Front
- **Map symbol:** **purple line** with **alternating triangles and semicircles** on the **same side**.
- Forms when a **faster-moving cold front catches up to and overtakes a warm front**, lifting the warm air in between **off the ground**. Usually a sign that a mid-latitude cyclone has reached its **mature stage** and will begin to weaken.
- The point where the cold, warm, and occluded fronts meet is the **triple point** — often a focus for severe weather.
- Weather combines features of both fronts: warm-front-type clouds and precipitation ahead, with showers near the front itself.

**Two types of occlusions** — decided by which cold air mass is colder:

| Type | Which air is coldest? | What happens | Where common |
|---|---|---|---|
| **Cold-type occlusion** | Air **behind** the cold front is **colder** than the air ahead of the warm front | The coldest air **wedges under** the cool air ahead of the warm front, lifting it | Central and eastern U.S. |
| **Warm-type occlusion** | Air **behind** the cold front is **milder** than the air ahead of the warm front | The cold front **rides up and over** the colder air ahead of the warm front | **West coasts** of continents (e.g., Pacific Northwest, Europe), where mild mP air meets colder continental air |

#### Connection: Fronts and the Mid-Latitude Cyclone
The **Norwegian cyclone model** describes how a low-pressure system forms on the polar front: a wave develops → warm and cold fronts form around the low → the cold front overtakes the warm front (occlusion) → the storm weakens. Knowing this life cycle helps explain *why* fronts and occlusions appear where they do on a map.

### Chapter 11 JetStream Resources
- [Air Masses](https://www.noaa.gov/jetstream/synoptic/air-masses)
- [Norwegian Cyclone Model](https://www.noaa.gov/jetstream/synoptic/norwegian-cyclone-model)
- [Surface Weather Maps](https://www.noaa.gov/jetstream/wxmaps)
- [Surface Weather Plots](https://www.noaa.gov/jetstream/wxmaps-max)
- [Ingredients for a Thunderstorm (lift from fronts and dry lines)](https://www.noaa.gov/jetstream/thunderstorms/ingredients-for-thunderstorm)

---

## Equation Summary Sheet

| What you're finding | Equation / rule | Units |
|---|---|---|
| Cloud base (LCL) | H = 125 × (T − Td) | meters, °C |
| Cloud base (LCL) | H ≈ 222 × (T − Td) | feet, °F |
| Unsaturated parcel cooling/warming | 10 °C per km (5.5 °F per 1000 ft) | DALR |
| Saturated parcel cooling | ≈ 6 °C per km (varies 4–9) | MALR |
| Dew point change in unsaturated parcel | ≈ 2 °C per km | — |
| Sea-level pressure | SLP ≈ station pressure + 10 mb per 100 m elevation | mb |
| Pressure gradient | Δp / d | mb per 100 km |
| Pressure gradient force | PGF = (1/ρ)(Δp/d) | m/s² (Pa, m, kg/m³) |
| Coriolis parameter | f = 2Ω sin φ, Ω = 7.29 × 10⁻⁵ s⁻¹ | s⁻¹ |
| Geostrophic wind | Vg = (1/(ρf))(Δp/d) | m/s |
| Newton's 2nd law | F = m·a | N |
| Standard sea-level pressure | 1013.25 mb = 29.92 in Hg = 760 mm Hg | — |

**Stability rules:** ELR < MALR → absolutely stable · ELR > DALR → absolutely unstable · MALR < ELR < DALR → conditionally unstable

---

## Key Vocabulary Checklist

Can you define each of these in one or two sentences?

**Ch. 6:** lapse rate, environmental lapse rate, adiabatic, air parcel, dry adiabatic lapse rate, moist adiabatic lapse rate, latent heat, Skew-T, LCL, LFC, CAPE, inversion, subsidence, absolutely stable, absolutely unstable, conditionally unstable, thermal, orographic lifting, rain shadow, convergence, frontal lifting

**Ch. 7:** terminal velocity, collision–coalescence, warm cloud, cold cloud, supercooled water, ice nuclei, Bergeron (ice-crystal) process, accretion (riming), aggregation, virga, drizzle, showers, downburst, microburst, fallstreaks, flurries, snow squall, drifting vs. blowing snow, blizzard, cloud seeding, silver iodide, sleet, freezing rain, glaze, graupel, hail, reflectivity, dBZ, Doppler radar, dual-polarization

**Ch. 8:** air pressure, station pressure, sea-level pressure, millibar/hectopascal, mercury barometer, aneroid barometer, altimeter, barograph, isobar, pressure gradient, pressure gradient force, Coriolis force, centripetal force, gradient wind, friction layer, geostrophic wind, cyclonic, anticyclonic, convergence, divergence, height contour, ridge, trough, Buys-Ballot's law

**Ch. 9:** microscale, mesoscale, synoptic scale, global scale, eddy, thermal circulation, sea breeze, land breeze, valley breeze, mountain breeze, katabatic wind, Chinook/foehn, Santa Ana wind, compressional warming, monsoon

**Ch. 10:** single-cell model, three-cell model, Hadley cell, Ferrel cell, polar cell, trade winds, doldrums, horse latitudes, westerlies, polar easterlies, polar front, subtropical high, Bermuda–Azores High, Pacific High, Icelandic Low, Aleutian Low, ITCZ, polar front jet, subtropical jet, gyre, Ekman transport, upwelling, El Niño, La Niña, Southern Oscillation, ENSO, Walker circulation, teleconnection

**Ch. 11:** air mass, source region, cA, cP, cT, mP, mT, lake-effect snow, air mass modification, front, stationary front, cold front, warm front, squall line, dry line, occluded front, cold-type occlusion, warm-type occlusion, triple point, Norwegian cyclone model

---

## Practice Problems

*Try these on your own first, then check your work with [the answer key](./Exam2ReviewSolutions.md).*

1. The surface temperature is 30 °C and the dew point is 14 °C. At what altitude will the base of a cumulus cloud form?
2. A radiosonde measures an environmental lapse rate of 7 °C/km. Is this layer absolutely stable, absolutely unstable, or conditionally unstable? Explain.
3. A parcel at sea level (T = 25 °C, Td = 17 °C) is forced over a mountain 2500 m high. Find the cloud base, the temperature at the summit, and the temperature and dew point when it returns to sea level on the leeward side. (Use 6 °C/km for the moist rate.)
4. A weather station at 800 m elevation reads a station pressure of 915 mb. What is its approximate sea-level pressure?
5. City A reports 1016 mb and City B, 300 km away, reports 1004 mb. What is the pressure gradient in mb per 100 km? Which way would the PGF point?
6. Draw (or describe) the vertical temperature profiles that produce snow, sleet, and freezing rain at the ground.
7. You are in the Northern Hemisphere standing with your back to the surface wind. In which direction is the center of low pressure?
8. Why is the moist adiabatic lapse rate smaller than the dry adiabatic lapse rate?
9. Explain why deserts are commonly found near 30° latitude.
10. Describe the changes in temperature, wind direction, pressure, and sky conditions you would observe as a cold front passes your location.
11. What air mass would you expect to bring a hot, humid, stormy summer day to the Midwest, and where does it come from?
12. During an El Niño, what happens to the trade winds and to upwelling off the coast of Peru?
13. Explain the difference between a cold-type and a warm-type occlusion.
14. Why do surface winds cross the isobars, while winds aloft blow parallel to them?

---

*All linked resources are from JetStream – An Online School for Weather, produced by the National Weather Service / NOAA: https://www.noaa.gov/jetstream*