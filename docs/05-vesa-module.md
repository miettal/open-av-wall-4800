# Open AV Wall 4800

## VESA Module Design

Version: 0.1

Status: Draft

---

# 1. Purpose

This document defines the modular VESA mounting system.

The goal is to allow displays to be mounted, removed, or replaced without modifying the structural frame.

Displays are treated as replaceable modules.

---

# 2. Existing Hardware

The project reuses existing wall-mount brackets.

Current bracket characteristics

| Item              |                    Value |
| ----------------- | -----------------------: |
| Wall plate width  |     approximately 750 mm |
| Wall plate height |     approximately 200 mm |
| Slot size         | approximately 35 × 10 mm |
| Material          |                    Steel |
| Mounting          |            Slotted holes |

The elongated holes provide sufficient installation tolerance.

No custom adapter plate is required for the first prototype.

---

# 3. Supported Displays

The module shall support

* 43-inch
* 55-inch
* 65-inch

Future display replacement shall require only repositioning of the VESA module.

The structural frame shall remain unchanged.

---

# 4. Design Philosophy

The VESA module is **not** part of the structural frame.

Instead

```text
Display
    │
VESA Module
    │
Structural Frame
```

The frame is permanent.

The VESA module is replaceable.

---

# 5. Mounting Method

Each VESA module shall be fixed using T-slot hardware.

Recommended hardware

* M8 T-nuts
* M8 socket head bolts
* Flat washers
* Spring washers (optional)

No drilling into aluminum extrusions shall be required.

---

# 6. Mounting Rails

Displays shall attach to dedicated horizontal rails.

The rails are separate from the structural beams.

Reasons

* Easier adjustment
* Easier replacement
* Better serviceability
* Future compatibility

---

# 7. Adjustment Range

Horizontal adjustment

Approximately ±100 mm

Vertical adjustment

Approximately ±50 mm

This tolerance allows installation of different display models without redesign.

---

# 8. Load Design

Design basis

65-inch display

20 kg

Dynamic safety factor

2.0

Target design load

40 kg per display position

The structural frame shall support significantly more than the expected operating load.

---

# 9. Module Numbering

Naming convention

| Prefix | Description  |
| ------ | ------------ |
| VM-01  | Upper Left   |
| VM-02  | Upper Center |
| VM-03  | Upper Right  |
| VM-04  | Lower Left   |
| VM-05  | Lower Center |
| VM-06  | Lower Right  |

Additional modules may be added later.

---

# 10. Assembly Procedure

1. Install T-nuts into the display rails.
2. Position the wall plate.
3. Lightly tighten mounting bolts.
4. Adjust display position.
5. Fully tighten bolts.
6. Install display.
7. Verify alignment.

No structural members shall require modification during installation.

---

# 11. Future Expansion

Future versions may support

* Quick-release VESA modules
* Tool-less adjustment
* Sliding display rails
* Height indexing
* Fine alignment screws

These features are intentionally excluded from Version 1.

---

# 12. Design Notes

The existing wall brackets are reused to reduce cost.

Because the wall plate already contains long slots, the aluminum frame does not require precision-machined adapter plates.

This significantly reduces manufacturing complexity while maintaining sufficient installation flexibility.

---

# Deliverables

This document defines the requirements for

* Fusion 360 VESA assembly
* Display mounting drawings
* Hardware BOM
* Assembly manual
