# Open AV Wall 4800

## Layout Design

Version: 0.1

---

# Purpose

This document defines the physical layout of the Open AV Wall 4800.

Unlike the structural design documents, this document focuses on equipment placement and coordinate planning.

The output of this document becomes the basis for the Fusion 360 skeleton model.

---

# Overall Dimensions

| Item       |               Value |
| ---------- | ------------------: |
| Width      |             4810 mm |
| Height     |    2450 mm (target) |
| Base depth | 1500 mm (tentative) |

---

# Display Layout

Maximum configuration

```
+---------+---------+---------+
|   TV1   |   TV2   |   TV3   |
+---------+---------+---------+
|   TV4   |   TV5   |   TV6   |
+---------+---------+---------+
```

Supported display sizes

* 43 inch
* 55 inch
* 65 inch

Maximum design:

65 inch × 6

---

# Structural Grid

The structural frame shall be based on a regular vertical grid.

Target pitch:

480 mm

Reasons

* Easy future expansion
* Camera mounting
* Lighting installation
* Wiring flexibility
* Symmetrical appearance

The grid is a structural reference only.

Display centers do **not** need to align exactly to the grid.

---

# Coordinate System

Origin

```
Top View

        Front

          ↑ +Y

          │

(-X) ─────┼───── (+X)

          │

          └────→ +Z (Height)
```

Coordinate origin:

Floor center of the entire wall.

X = Left / Right

Y = Front / Rear

Z = Height

All CAD models shall use this coordinate system.

---

# Display Clearance

Minimum clearance between displays:

10–20 mm (tentative)

Clearance may be adjusted depending on bezel width.

---

# Maintenance Space

Reserve at least:

Rear clearance:

150 mm

Purpose

* HDMI replacement
* Power cable routing
* LAN cable routing
* VESA maintenance

---

# Cable Space

Cable routing area shall exist behind every display.

Recommended routing

* AC power
* HDMI
* DisplayPort (future)
* Ethernet
* USB
* PoE

---

# Future Expansion

The layout shall allow installation of:

* PTZ cameras
* Conference cameras
* Speakers
* LED lighting
* Microphones
* Mini PCs
* Signage controllers

without redesigning the structural frame.

---

# Layout Principles

1. Structure first
2. Infrastructure second
3. Displays third

Displays are replaceable equipment.

The aluminum structure is the permanent asset.

---

# Deliverables

This document defines the reference layout for:

* Skeleton CAD
* Structural design
* VESA module design
* Assembly drawings
* BOM
