Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
1- INTRODUCTION AND BASIC CONCEPTS
1-1 Thermodynamics and Energy
 What is Thermodynamics?
Therme  heat, dynamics  power
 Thermodynamics  Convert heat into power
- Also include other aspects of energy and energy transportation:
□ Power production □ Refrigeration
 1st law of thermodynamics (Conservation of energy):
- Energy cannot be created or destroyed, but can change from one form to
another  Total amount of energy is constant.
 2nd law of thermodynamics (Quality of energy):
- Cup of hot coffee cools in a cooler room
- Cup of hot coffee cannot warm in a cooler room
 Processes occur in a certain direction (decreasing quality of energy), not in
just any direction
1-2 Importance of Dimensions and Units
- Physical quantities are characterized by dimensions (L, V, T, ..etc.)
- Magnitude of the dimensions are called units
- Basic dimensions are called primary (fundamental) dimensions (m, L,
t, T)
- Secondary dimensions are expressed in terms of the primary dimensions
(V, v, E).
 Two main sets of units are used:
1. Metric, International system (SI)
- Simple system based on decimal relationship between units
( 1m = 100 cm, 1 kg = 1000 gm, .. etc.)
- Mostly used around the world
2. English system
- Difficult, no numerical base
( 1 ft = 12 in, 1 lb = 16 oz, ..etc.)
1-1

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
 Mass
m
[kg] [lbm] [Slug = 32.174 lbm]
 Force
F = ma
[N] = [kg][m/s2] [kgf] = 9.807 [kg][m/s2] [lbf] = 32.174 [lbm][ft/s2]
 Weight
W = mg
t
- Weight is different than mass (Weight scale measures the weight not the mass)
 Work
W = FS
[J] = [N][m] [Btu] = 778.169 [lbf][ ft]
- more common, [kJ] = [103 J], [therm] = [105 Btu]
 Dimensional Homogeneity
- All terms in an equation must have the same units.
 The equation is dimensionally homogeneous.
1-2

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
1-3 Systems and Control Volumes
- System: region chosen for study
- Surroundings: region outside the system
- Boundary: surface outside the system
 Two kind of systems :
1) Closed System (Control mass)
- Constant mass  mass cannot cross the boundaries
- Energy can cross the boundaries (heat and work)
2) Open System (control volume)
- Mass and energy can cross the boundaries.
- Boundary  Control surface
* Special case:
Closed system + No energy cross the boundaries  Isolated system
1-3

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
1-4 Properties of a System
- Property of a system: any characteristic of a system
Intensive: Independent of size
Properties
Extensive: Vary with size
Note:
Extensive properties per unit mass  Intensive properties
1-5 Density and Specific Gravity
 Density, 
Mass per unit volume [kg/m3, lbm/ft3]
m

V
 Specific volume, 
Volume per unit mass [m3/kg, ft3/lbm]
V
v    = 1/
m
 Molar Specific volume, 
Volume per unit mole [m3/kmole, ft3/kmole]
V
v 
N
N = No. of moles = m/M, M = Molecular weight
 Specific gravity


H O
2
 Specific weight, 
s
Weight per unit volume [N/m3, lbf/ft3]
 = W/V = mg/V = g
s t
1-4

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
1-6 State and Equilibrium
 State:
- System not going any change.
- Properties known throughout the system.
 State of the system: Properties that describe the system.
 State postulate:
The thermodynamic state of a simple compressible system is
completely specified by two independent intensive properties.
- Note: simple compressible system  no magnetic, gravitational, motion, and
surface tension effects.
 Equilibrium:
- The system experiences no change when it is isolated from its
surroundings.
- Types of Equilibrium:
1) Thermal equilibrium:
Temperature is the same throughout the system.
2) Mechanical equilibrium: Uniform pressure.
3) Phase equilibrium: The mass of the two phases
(ex. Ice & water) in equilibrium.
4) Chemical equilibrium: no chemical reaction.
 System is not in thermodynamic equilibrium unless the conditions of all
types of equilibrium are satisfied.
1-5

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
1-7 Processes and Cycles
- Process: any change that a system undergoes
from one equilibrium state to another.
- Path: the series of states through which a system
passes during a process.
- Quasi-equilibrium process
- In some processes one thermodynamic property is held constant:
Isobaric Process
Constant pressure 
Isothermal Process
Constant temperature 
Isochoric Process
Constant specific volume 
Pvn = constant  Polytropic Process
- Process diagram:
Plot the process using the thermodynamic properties (T, V, P)
Ex.: P-V diagram.
- Cycle: system returns to its initial state at the end of the process.
1
2
1-6

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
 The Steady-Flow Process
- No change with time.
- The fluid properties can change from point to point within the control volume,
but at any fixed point they remain the same during the entire process.
1-8 Temperature
- Temperature: a measure of the energy content of a mass.
- Thermal equilibrium: two bodies are in thermal equilibrium when they have
reached the same temperature
- The zeroth law of thermodynamics: If two bodies are in thermal equilibrium
with a third body, they are also in thermal equilibrium with each other.
 Temperature Scale:
- SI  Celsius scale [C]
Kelvin scale: the thermodynamic temperature scale of the SI units [K].
T [K] = T [C] + 273
Note:
T [K] = T [C]
- English units  Fahrenheit scale [F]
Rankine scale: the thermodynamic temperature scale of the EU [R].
T [R] = T [F] + 460
Note:
T [R] = T [F]
- SI  English units
T [F] = T [C] + 32
T [F] = T [C]
1-7

Engineering Thermodynamics - ENGR 208                            يميلعلا دمحم .د
1-9  Pressure
  - Pressure: force exerted per unit area.
P = F/A

[Pascal] = [N/m2]
|     |     |     |     |     | 1 kPa = 103 Pa  |
| --- | --- | --- | --- | --- | --------------- |
1 MPa = 106 Pa = 103 kPa
|     |     |     |     |     |                                   |
| --- | --- | --- | --- | --- | --------------------------------- |
|     |     |     |     |     | 1 bar = 100 kPa                   |
|     |     |     |     |     | 1 atm = 101.325 kPa  100 kPa     |
|     |     |     |     |     | 1 mmHg = pressure of 1 mm of Hg.  |
    Absolute Pressure
- Pressure:
|       |     |     Gage Pressure: relative to atmospheric pressure.  |       |     |     |
| ----- | --- | ----------------------------------------------------- | ----- | --- | --- |
|      | P   |  =  P                                                 |  -  P |     |     |

|      | gage |        | abs atm |      |     |
| ---- | ---- | ------ | ------- | ---- | --- |
|      |      |        | P  = P  |  - P |     |
| if P |  < P |       |         |      |     |
|      | abs  | atm    | vac     | atm  | abs |

|     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- |

  1-8

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
 Example 1-1
A vacuum gauge connected to a tank reads 30 kPa at a location where the
atmospheric pressure is 98 kPa. What is the absolute pressure in the tank?
 Pressure difference
P
1
h Fluid
P = P + gh
2 1
P
2
 Pressure in a cylinder
P
atm
mg
P  P 
atm
Subs.
A
 Pressure properties:
- Pressure is the same in all directions.
- Pressure of a gas in a tank is uniform.
- Pressure at the same level for the same fluid is the
same.
- Pressure varies vertically only.
 Measure the pressure using: (Manometer, Barometer, other.. see text)
1-9

Engineering Thermodynamics - ENGR 208 يميلعلا دمحم .د
1-10 The Manometer
- Used to measure small and moderate pressure differences.
- Neglect gravitational forces in the tank.
P = P + gh
atm
P = gh
gage
 Example 1-2
Tank filled with air. Measure the absolute pressure of the tank using a
manometer containing oil ( = 850 kg/m3). The oil-level difference is 45 cm.
P = 98 kPa.
atm
 Different fluids and differential pressure
P – P = (gh
1 2  
1-11 The Barometer and Atmospheric Pressure
- Used to measure the atmospheric pressure.
- Atmospheric pressure sometimes called the barometric pressure.
P = gh
atm
1-10