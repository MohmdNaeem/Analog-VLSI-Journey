# MOS Transconductance (gm)

## What is gm?

gm (transconductance) tells how strongly a MOSFET converts a change in input voltage (Vgs) into output current (Id).

In simple terms:
A small change in Vgs causes a change in Id, and gm measures how large that change is.

So,
Vgs = input  
Id = output  

gm acts like a "gain" from voltage to current.

---

## Why gm matters

1. Determines amplifier gain  
Gain ≈ gm × Rout  
Higher gm → Higher gain

2. Measures transistor efficiency  
High gm means the transistor is more sensitive to input changes.

3. Core parameter in analog design  
Used in:
- Amplifiers  
- Current mirrors  
- Differential pairs  

Without gm, analog circuit design is not possible.

---

## Key Formulas

1. Definition:
gm = dId / dVgs

2. In saturation region:
gm = 2Id / (Vgs - Vth)

3. Alternate form:
gm = √(2 * μn * Cox * (W/L) * Id)

---

## Key Insight

Understanding gm changes the way we look at transistors — not just as switches, but as controlled current sources.
