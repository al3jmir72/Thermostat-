# Thermodynamics 1 — Chapter 2 (Extra Note, Lec. 2)

*Eng. Ahmed Eissa — Engineering & Science Institute.*

> **Source:** `note_chapter_2.pdf` (22 pages, scanned handwriting). `markitdown` returned an empty
> file because the PDF has no text layer, so this markdown was transcribed by hand from the page
> images. Page numbers refer to the note's own numbering.

---

## 1. Forms of Energy (p. 1)

- Energy can exist in several forms: thermal, mechanical, kinetic, potential, electric, magnetic, chemical and nuclear.
- The sum of all energies is the **total energy E** (kJ). Per unit mass: `e = E / m` (kJ/kg).

| Macroscopic | Microscopic |
|---|---|
| With respect to some outside reference frame, e.g. kinetic energy, potential energy | Related to the molecular structure of a system and the degree of molecular activity |
| | The sum of all microscopic forms is the **internal energy U** |

## 2. Kinetic, Potential and Total Energy (p. 2)

| Quantity | In J | In kJ | Per unit mass (kJ/kg) |
|---|---|---|---|
| Kinetic | `KE = ½ m V²` | `KE = m V² / 2000` | `ke = V² / 2000` |
| Potential | `PE = m g z` | `PE = m g z / 1000` | `pe = g z / 1000` |

```
E = U + KE + PE = U + mV²/2000 + mgz/1000      (kJ)
e = u + V²/2000 + gz/1000                       (kJ/kg)
```

## 3. Internal Energy (p. 3)

1. **Sensible energy** — associated with the kinetic energy of the molecules.
2. **Latent energy** — associated with the phase of the system.
   - Sensible + latent = **thermal energy**.
3. **Chemical energy** — associated with the atomic bonds in a molecule.
4. **Nuclear energy** — associated with the strong bonds within the nucleus of the atom itself.

## 4. Flow Rates and Mechanical Energy (p. 4)

```
Mass flow rate     ṁ = m/t = ρ V̇ = ρ A V        (kg/s)
Volume flow rate   V̇ = Vol/t = A V              (m³/s)
1 L = 1/1000 m³
```

**Mechanical energy** (turbines, pumps, fans): energy that can be converted to mechanical work completely.

```
Normal form:      E_mech = P·Vol + mV²/2000 + mgz/1000           (kJ)
                  (P·Vol is the flow energy / flow work: the energy needed to push the fluid)
Per unit mass:    e_mech = P/ρ + V²/2000 + gz/1000               (kJ/kg)     [v = Vol/m = 1/ρ]
Rate form:        ΔĖ_mech = ṁ [ (P₂−P₁)/ρ + (V₂²−V₁²)/2000 + g(z₂−z₁)/1000 ]   (kJ/s = kW)
```

> Note: in `(P₂−P₁)/ρ`, if P is in kPa the term is already in kJ/kg.

### Example — water jet (p. 5)
A water jet leaves a nozzle at 60 m/s at a flow rate of 120 kg/s and strikes the buckets of a wheel. Find the mechanical energy per unit mass and the power generation potential.

```
e_mech = V²/2000 = 60²/2000 = 1.8 kJ/kg            (no pressure or height term)
ΔĖ_mech = ṁ (V²/2000) = 120 × 1.8 = 216 kW
```

### Example — water reservoir (p. 5)
A large reservoir, 150 m high, feeds a turbine with a pressure difference of 1200 kPa. Find the power generation potential for 1800 kg/s.

```
ΔĖ_mech = ṁ [ ΔP/ρ + gΔz/1000 ] = 1800 [ 1200/1000 + 9.81(150)/1000 ] = 4808.7 kW
```

### Example — wind turbine (p. 6)
8 m diameter blades, wind at 15 m/s, ρ = 1.3 kg/m³. Find the mechanical energy per unit mass and the power potential.

```
A = (π/4) D² = 50.265 m²
ṁ = ρ A V = 1.3 × 50.265 × 15 = 980.167 kg/s
e_mech = V²/2000 = 15²/2000 = 0.1125 kJ/kg
ΔĖ_mech = 980.167 × 0.1125 = 110.268 kW
```

### Example — river / dam (p. 7)
A river flows at 1.75 m³/s; water is released from an 80 m elevation difference at 4 m/s. Find the power in kW, and the energy in kWh over 3 hours.

```
ṁ = ρ V̇ = 1000 × 1.75 = 1750 kg/s
ΔĖ_mech = 1750 [ 4²/2000 + 9.81(80)/1000 ] = 1387.4 kW
Energy  = 1387.4 × 3 h = 4162.2 kWh
```

### Problem 2-44 — fan in a duct (p. 7)
Fan in a 1 m × 1 m duct, outlet velocity 7 m/s, ρ = 1.2 kg/m³. Find the minimum electric power.

```
A = 1 m²,  ṁ = ρ A V = 1.2 × 1 × 7 = 8.4 kg/s
ΔĖ_mech = ṁ (V₂² − 0)/2000 = 8.4 × 49/2000 = 0.2058 kW
```

## 5. Energy Transfer by Heat (p. 8)

- Heat: energy transferred between two systems as a result of a **temperature difference**.
- Adiabatic (insulated) ⇒ no heat transfer.

```
Heat transfer       Q            (kJ)
Per unit mass       q = Q/m      (kJ/kg)
Rate                Q̇ = Q/t      (kJ/s = kW)
```

Mechanisms: **conduction** (solid ↔ solid), **convection** (solid ↔ liquid or gas), **radiation** (electromagnetic waves, e.g. the sun).

## 6. Energy Transfer by Work (p. 9)

- Work: energy transfer associated with a force acting through a distance. General form: `Work = Force × Distance`.

```
Work                W            (kJ)
Per unit mass       w = W/m      (kJ/kg)
Rate (power)        Ẇ = W/t      (kJ/s = kW)
```

- **Path functions** depend on the states *and* the path (heat and work).
- **Point functions** depend on the states only (properties: pressure, volume, …).

## 7. Sign Convention (p. 10)

| Term | Sign | Meaning |
|---|---|---|
| Q_in | + | heat transfer to the system |
| Q_out | − | heat transfer from the system (lost) |
| W_in | − | work done on the system |
| W_out | + | work done by the system |

Types of work: electrical, shaft, spring, and work done to raise or accelerate a body.

## 8. Electrical Work (p. 10)

```
W_ele = V I t / 1000      (kJ)      V = I R
```

### Example — resistance heater (p. 10)
150 V applied, current 1000 mA, used for 5 minutes.

```
W_ele = (150)(1000/1000)(5 × 60) / 1000 = 45 kJ
```

## 9. Shaft Work (p. 11)

```
W_sh = 2π n τ / 1000      (kJ)      τ = torque (N·m), n = number of revolutions
Ẇ_sh = 2π ṅ τ / 1000      (kW)      ṅ = n/t (rev/s)
```

### Example — car shaft (p. 11)
Torque 350 N·m, 4500 rpm.

```
ṅ = 4500/60 = 75 rev/s
Ẇ_sh = 2π (75)(350)/1000 = 164.933 kW
```

## 10. Spring Work (p. 12)

```
W_spring = ½ k (x₂² − x₁²) / 1000      (kJ)      k in N/m;  at rest (free length) x₁ = 0
```

### Problem 2-29 (p. 12)
Deflect a spring with k = 70 kN/m by 20 cm from rest.

```
k = 70 × 1000 N/m,  x₁ = 0,  x₂ = 0.2 m
W = ½ (70000)(0.2²) / 1000 = 1.4 kJ
```

### Example — preloaded spring (p. 13)
k = 4.5 kN/cm with an initial force of 0.55 kN; compress it another 2 cm.

```
k  = 4.5 × 1000 × 100 = 450 000 N/m
F₁ = k x₁  →  550 = 450000 x₁  →  x₁ = 1.222 × 10⁻³ m
x₂ = x₁ + 0.02 = 0.0212 m
W  = ½ k (x₂² − x₁²) / 1000 ≈ 0.10 kJ        (note gives 0.1007 kJ)
```

## 11. Work to Raise or Accelerate a Body (p. 14)

```
Acceleration (speed changes):   W_a = ΔKE = m (V₂² − V₁²) / 2000     (kJ)
Raising (height changes):       W_g = ΔPE = m g (z₂ − z₁) / 1000     (kJ)
Total work:                     W = W_a + W_g
Power:                          Ẇ = W / t                              (kW)
```

### Problem 2-32 — car climbing a hill (p. 15)
1150 kg car, 100 m road at 30°, in 12 s. Find the power for (a) constant velocity, (b) rest → 30 m/s, (c) 35 → 5 m/s.

```
z₂ − z₁ = 100 sin 30° = 50 m
(a) W_a = 0,  W = W_g = 1150(9.81)(50)/1000 = 564 kJ          Ẇ = 564/12 = 47 kW
(b) W = 1150(30² − 0)/2000 + 564 = 1081.57 kJ                  Ẇ = 90.1 kW
(c) W = 1150(5² − 35²)/2000 + 564 = −125.92 kJ                 Ẇ = −10.5 kW
```

### Problem 2-27 — accelerate a car uphill (p. 16)
1300 kg car, 10 → 60 km/h, vertical rise 40 m.

```
V₁ = 10 × 1000/3600 = 2.777 m/s,   V₂ = 60 × 1000/3600 = 16.666 m/s
W  = 1300(16.666² − 2.777²)/2000 + 1300(9.81)(40)/1000 = 685.645 kJ
```

### Problem 2-50 — escalator (p. 16)
50 people × 75 kg, constant 0.6 m/s, 45° slope. Find the minimum power.

```
m = 3750 kg,  W_a = 0 (constant speed)
W = m g D sin45 / 1000   →   Ẇ = m g (D/t) sin45 / 1000 = m g V sin45 / 1000
Ẇ = 3750(9.81)(0.6) sin45 / 1000 = 15.607 kW
```

## 12. The First Law of Thermodynamics (p. 17)

Conservation of energy (energy balance): energy can't be created or destroyed, but it can be converted from one form to another.

```
E_in − E_out = ΔE_system
(Q_in − Q_out) + (W_in − W_out) + (E_mass,in − E_mass,out) = ΔKE + ΔPE + ΔU
```

**Closed system:** stationary (ΔKE = 0, ΔPE = 0) and E_mass = 0

```
Q_net,in − W_net,out = ΔU        (kJ)
Q_in → +ve,  Q_out → −ve,  W_in → −ve,  W_out → +ve
```

**Cycle:** ΔU = 0 (U depends only on the final and initial states; if U₂ = U₁ then U₂ − U₁ = 0)

```
Q_net,in = W_net,out
```

### Problem 2-37 — heated, stirred pan (p. 18)
Closed pan: 30 kJ heat in, 5 kJ lost, paddle-wheel work 500 N·m, initial energy 10 kJ. Find the final energy.

```
Q_in = 30 kJ, Q_out = 5 kJ, W_in = 500 N·m = 0.5 kJ, U₁ = 10 kJ
(In a closed system, electric and shaft work are W_in.)
[30 − 5] − [−0.5] = U₂ − 10      →      U₂ = 35.5 kJ
```

### Problem 2-38E — piston-cylinder (p. 19)
65 kJ heat in, 8 kJ lost through the walls, vapor does 5 kJ of work.

```
[65 − 8] − [5] = ΔU      →      ΔU = 52 kJ
```

### Problem 2-43 — room with appliances (p. 19)
40 W bulb, 110 W TV, 300 W fridge, 1200 W iron; no heat through the walls.

```
Ẇ_in = 0.04 + 0.11 + 0.3 + 1.2 kW
Q̇ = 0:   −[−0.04 − 0.11 − 0.3 − 1.2] = ΔU̇      →      ΔU̇ = 1.65 kW
```

### Problem 2-39 — classroom air conditioning (p. 20)
40 people at 360 kJ/h each, 10 bulbs × 100 W, 15 000 kJ/h through walls and windows; room held at 21 °C; units of 5 kW each.

```
Q̇_persons = 40 × 360/3600 = 4 kW        (in)
Ẇ_bulbs   = 10 × 100/1000 = 1 kW         (in)
Q̇_walls   = 15000/3600 = 4.16 kW         (in)
Constant temperature → ΔU̇ = 0:
[4 + 4.16 − Q̇_air-cond] − [−1] = 0       →      Q̇_air-cond = 9.16 kW
Units = 9.16/5 = 1.832      →      2 units
```

### Example — two-path cycle (p. 21)
A → B along path X: receives 100 kJ heat, does 40 kJ work. B → A along path Y: work input 30 kJ. Find the heat in path Y.

```
Cycle:  Q_net,in = W_net,out
Q_X + Q_Y = W_X + W_Y
100 + Q_Y = 40 − 30      →      Q_Y = −90 kJ   (i.e. 90 kJ out)
```
