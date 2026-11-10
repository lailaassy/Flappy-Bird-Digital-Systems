# Flappy Bird on FPGA

A Verilog recreation of Flappy Bird for a VGA-based hardware system.

**Verilog · FPGA · Quartus · ModelSim**

## Overview

This team project brings the core Flappy Bird gameplay into digital hardware: moving a bird through generated pillars, detecting collisions, and tracking the score.

## Core features

- Bird movement and pillar generation
- Collision detection
- Score tracking
- VGA display output

## Explore the source

| File | Purpose |
| --- | --- |
| [`vga_demo.v`](vga_demo.v) | Game and display logic |
| [`birdy_rom.v`](birdy_rom.v) | Bird sprite ROM |
| [`intro_rom.v`](intro_rom.v) | Intro screen ROM |
| [`gameover_rom.v`](gameover_rom.v) | Game-over screen ROM |

## Tools

Developed with Quartus and ModelSim for an FPGA-based system. This repository contains Verilog source; running it on hardware also requires the appropriate board configuration, pin assignments, and referenced display assets.

## Team

Laila Assy · Margaret Boychuk · Manahil Saeed
