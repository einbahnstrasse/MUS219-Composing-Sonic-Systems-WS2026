---
layout: single    
title: Modulation Synthesis + bach Integration    
permalink: /assignments/modulation-bach-integration/    
toc_icon: "graduation-cap"  
toc: true      
toc_sticky: true   
read_time: true    
date: 2026-02-11    
last_modified_at: 2026-02-11    
---

<!-- # Connecting Modulation to `bach.roll` + `poly~`      -->

## Deadline  
**Saturday, February 21, 2026, at 11:59 PM**   

## Overview     

Last week, we used:     

- `<bach.roll-` for event generation       
- `<poly~-` for polyphony       
- a **simple sine wave engine** inside a `<poly~-` voice abstraction       

For this brief assignment, your task is conceptually simple:     

- Replace (or extend) the sine wave engine with one of our **modulation synthesis cores**  
- and drive it using `<bach.roll-` through `<poly~-`.       
- Create your own notes, chords, or other events inside `<bach.roll-` to drive your new synth.  
- Make a simple patch that does this and be prepared to share this in our next class.       

You must use **one** of the following synthesis types:     

- **RM (Ring Modulation)**       
- **AM (Amplitude Modulation)**       
- **FM (Frequency Modulation)**       

The key requirement:     

- The modulation synthesizer must be controlled by `<bach.roll-`       
- and instantiated using `<poly~-` inside our scaffold patch structure.     

---

## What To Do     

### 1. Use the Scaffold Structure     

You must work inside:     

- `_scaffold.v01.maxpat` (or your updated scaffold)     
- Your own `<poly~-` abstraction for voices     
- Your own `<bach.roll-` object for event sequencing     

This assignment is about **integration**, not inventing something totally from scratch.       

You should therefore **reuse and adapt** our previous templates.        

You are encouraged to use:     

- `<line-`  
- `<function-`  
- `<expr random()-` or some other random process like we've been using in class     

to control synthesis parameters in addition to pitch and rhythm: for example, carrier and modulator frequencies, modulation depth, amplitude envelope, etc.     

This should **not** take a large amount of time — keep it focused and clear. This is just a "proof of concept" patch.        

---

### 2. Build (or Adapt) a Modulation Voice Abstraction     

Inside your `<poly~-` voice patch:     

- Implement RM, AM, **or** FM       
- Accept pitch, velocity, and duration from `<bach.roll-`       
- Use proper gain staging       
- Avoid clipping       

Your modulation voice must clearly include:     

- A **carrier oscillator**     
- A **modulator oscillator**     
- A controllable **modulation index / depth / ratio**     

---

### 3. Dynamic Parameter Control (Important)     

In addition to triggering pitch and duration, your system must demonstrate dynamic control over at least **one** of the following:     

- Carrier frequency behavior       
- Modulator frequency       
- Carrier/modulator ratio       
- Modulation index / depth       

You must use at least one of these objects to create motion:     

- `<line-` (for smooth ramps)     
- `<function-` (for shaped envelopes)     
- `<expr random()-` (for stochastic parameter variation)     

Static modulation values will not receive full credit.     

We are exploring:     

- _Modulation as a time-varying system, not a fixed formula_.     

---


