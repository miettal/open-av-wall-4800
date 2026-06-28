# ADR-001

## Title

Adopt Modular Structural Architecture

Status

Accepted

---

## Context

The required wall width is approximately 4810 mm.

A single-piece structure would be difficult to:

* Transport
* Assemble
* Modify
* Repair

The system must also support future expansion.

---

## Decision

Adopt a modular architecture.

The frame shall be divided into three structural modules.

Displays shall not define the structural layout.

Instead, the structural frame shall provide a reusable infrastructure platform.

---

## Consequences

Positive

* Easier assembly
* Easier transport
* Lower replacement cost
* Future expansion
* Better maintainability
* Better open-source collaboration

Negative

* More connecting hardware
* Additional assembly time

These disadvantages are acceptable considering the project's goals.

---

## Future

Future variants should reuse this architecture.

Possible products:

* Open AV Wall 2400
* Open AV Wall 3200
* Open AV Wall 4800
* Open AV Wall 6400

Only the number of structural modules changes.

