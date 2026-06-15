# GAME PHYSICS ENGINE

## About
This project is for the final project of Harvard University's CS50x Introduction to Computer Science for the year 2026.

It's a simple physics engine with one working demo. The demo showcases some basic features of the engine — forces, contacts, and shapes. The engine is heavily inspired by Ian Millington's *Game Physics Engine Development*, but incorporates my own interpretation of some ideas.

> Watch the demo [here](https://youtu.be/Hh4ZnpWwukk)

---

## Features

### Data structures & Algorithms
- Separating-axis theorem test
- Sutherland-Hodgman Algorithm
- Bounding Sphere Hierarchy
- Binary Spatial Partitions

### Physics & Mathematics
- Euler's method
- Sequential Impulses (based on Box2D)
- Gyroscopic effect

---

## Usage
From the root directory:
```
python demos/spring_and_buoyancy.py
```
- **RMB** — control camera angle
- **MMB** — move camera

---

## References
- [Erin Catto 2006](https://box2d.org/files/ErinCatto_SequentialImpulses_GDC2006.pdf)
- [Erin Catto 2014](https://box2d.org/files/ErinCatto_UnderstandingConstraints_GDC2014.pdf)
- [Dirk Gregorious - Robust Contact Creation](https://media.steampowered.com/apps/valve/2015/DirkGregorius_Contacts.pdf)
- Ian Millington, *Game Physics Engine Development: 2nd Edition*
- [Inertia tensors explained](https://www.youtube.com/watch?v=GYc99lMdcFE)
- Google AI Studio and GitHub Copilot — *"I've commented where there is direct involvement, but the large majority is assisted learning and debugging"*
