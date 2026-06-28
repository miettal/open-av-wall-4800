# Open AV Wall 4800

## Structure Design

Version: 0.1
Status: Draft

---

# 1. Purpose

This document defines the structural design of Open AV Wall 4800.

The structure shall work as a self-standing AV equipment wall rather than a display stand.

---

# 2. Structural Concept

The frame consists of three structural modules.

```text
+------------+----------------+------------+
| Module L   | Module C       | Module R   |
| 1500 mm    | 1810 mm        | 1500 mm    |
+------------+----------------+------------+

Overall Width = 4810 mm
```

The center module provides additional service space for wiring and future AV equipment.

---

# 3. Main Dimensions

| Item             |             Value |
| ---------------- | ----------------: |
| Width            |           4810 mm |
| Height           |  2450 mm (Target) |
| Base Depth       |           1500 mm |
| Display Capacity | Up to 65-inch × 6 |

---

# 4. Aluminum Profiles

## Primary Structure

Tentative profile

* 50×50 mm aluminum extrusion

Purpose

* Main columns
* Base frame
* Main load path

---

## Secondary Structure

Tentative profile

* 40×40 mm aluminum extrusion

Purpose

* Horizontal beams
* Display rails
* Structural reinforcement

---

## Accessory Rails

Tentative profile

* 30×30 mm aluminum extrusion

Purpose

* Cameras
* Lighting
* Cable support
* Future accessories

---

# 5. Structural Load Path

```text
Display
   ↓
VESA Bracket
   ↓
Display Rail
   ↓
Vertical Column
   ↓
Base Frame
   ↓
Leveling Feet
   ↓
Floor
```

Casters shall not normally support static loads.

---

# 6. Vertical Columns

Columns are arranged using a regular structural grid.

Target spacing

480 mm

Reasons

* Easy display mounting
* Camera flexibility
* Lighting flexibility
* Future expansion
* Symmetrical appearance

Display centers do not need to align exactly with the structural grid.

---

# 7. Horizontal Members

The following horizontal levels are planned.

| Member             | Purpose                  |
| ------------------ | ------------------------ |
| Top Beam           | Overall rigidity         |
| Upper Display Rail | Upper displays           |
| Center Beam        | Structural reinforcement |
| Lower Display Rail | Lower displays           |
| Bottom Beam        | Base stiffness           |

Exact Z positions shall be finalized during CAD design.

---

# 8. Base Frame

Target depth

1500 mm

The base frame shall contain

* Front beam
* Rear beam
* Side beams
* Internal cross members
* Caster mounting plates
* Leveling foot mounts
* Optional ballast space

---

# 9. Casters

The structure shall include casters for occasional movement.

Normal operation

* Leveling feet deployed
* Casters unloaded or lightly loaded

Transport

* Retract leveling feet
* Unlock casters
* Move slowly with multiple people

---

# 10. Bracing

Preferred method

Wire brace + turnbuckle

Locations

* Rear X-brace
* Side triangular brace
* Center module reinforcement

Reasons

* Lightweight
* Low cost
* Easy adjustment
* Easy replacement

---

# 11. Module Connections

Requirements

* Bolted joints only
* No welding
* Replaceable modules
* Adjustable during assembly

---

# 12. Naming Convention

| Prefix | Meaning                |
| ------ | ---------------------- |
| P      | Vertical Post          |
| H      | Horizontal Beam        |
| B      | Base Member            |
| V      | VESA Rail              |
| C      | Caster / Leveling Foot |
| W      | Wire Brace             |
| J      | Joint / Bracket        |

Examples

```
P-L01
P-C03
H-R02
V-01
B-C04
```

---

# 13. Safety

Primary design considerations

* Overturn prevention
* Structural stiffness
* Display retention
* Stable floor contact
* Easy maintenance

Priority order

1. Stability
2. Serviceability
3. Cost
4. Weight

---

# 14. Future Work

The following documents will refine this design.

* 05-vesa-module.md
* 06-base-frame.md
* 07-cable-management.md
* 08-bom.md
* Fusion 360 Skeleton Model
