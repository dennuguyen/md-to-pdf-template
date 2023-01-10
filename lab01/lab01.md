---
course: MTRN3100
year: 2023 T2
---

# Lab01

## How to Approach the Labs

We provide several options for how students can complete their lab material. We advise you bring with you:

- A laptop.
- Pen and paper.

You must use either the complete physical or digital copy of the lab manual.

Your lab answers must be entered onto a Moodle submission box that will only be open during your allocated lab time.

---

## Software

### Required

- Development environment for Arduino programming (Arduino IDE is recommended).
- CAD software (Solidworks is recommended).

### Suggested

- If your team has chosen to 3D print parts then Cura is the suggested 3D printing slicing software. Use of 3D printers can be done at the [ENG Makerspace](https://www.making.unsw.edu.au/engineering-makerspace/) in the Electrical Engineering School Building.

---

## Mechanical Assembly

You are provided the MTRN3100 robot kit which will be used for both the lab and project assessments.

The robot platform should compose:

- $1 \times$ chassis.
- $1 \times$ Arduino MEGA.
- $2 \times$ __ motors.
- $3 \times$ HC-SR04 distance sensors.
- $1 \times$ __ camera.
- $1 \times$ L298N motor driver.
- $1 \times$ __ lipo battery.

---

## Embedded Programming

- Avoid using the heap.
    - Can easily exhaust the heap with incorrect implementation during runtime.
    - Long runtimes can cause fragmentation.
- Keep interrupt service routines short as possible.
- Be aware of the number of bytes of datatypes allocated.
- Be aware of the number of instructions a C/C++ construct is.
- Use `while(1) {}` when handling failure and runtime exceptions.
- Be aware of the limitations of the compiler for the embedded microcontroller.

---

## KCL & KVL