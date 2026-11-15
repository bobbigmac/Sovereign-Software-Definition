# License definitions — index

Documents that define what counts as "open"/"free": the criteria a license or work must satisfy to belong to a category. Peers of `../SSD.md`, kept verbatim from canonical sources for diffing.

## The DFSG lineage

- **[SOCIAL-CONTRACT.md](SOCIAL-CONTRACT.md)**: Debian Social Contract v1.2, ratified October 1, 2022. The document containing the DFSG; it states the DFSG was adopted as the basis of the Open Source Definition. The remainder is Debian's community governance commitments.
- **[DFSG.md](DFSG.md)**: The Debian Free Software Guidelines, the original ten-criterion license test. Ancestor of the OSD and the definitions derived from it, not of the freedoms lineage.
- **[OSD.md](OSD.md)**: The Open Source Initiative's Open Source Definition 1.9, derived from the DFSG. The canonical "open" test for software and the document the SSD was diffed against.
- **[OPEN-DEFINITION.md](OPEN-DEFINITION.md)**: Open Definition 2.1 (Open Knowledge Foundation). Applies the same shape to any knowledge work rather than software alone: adds work-level requirements (whole-work access, machine readability, open format) and splits license terms into required permissions (§2.1) and a closed list of acceptable conditions (§2.2: attribution, integrity, share-alike, notice, source, technical-restriction prohibition, non-aggression). The closest structural peer to the SSD.
- **[OPEN-SOURCE-HARDWARE.md](OPEN-SOURCE-HARDWARE.md)**: Open Source Hardware Definition 1.0 (OSHWA), which states it is based on the Open Source Definition. Adapts it to physical artifacts across twelve criteria, adding design-file documentation requirements and a no-trademark-use obligation.

## The freedoms lineage

- **[FREE-SOFTWARE-DEFINITION.md](FREE-SOFTWARE-DEFINITION.md)**: The FSF's definition: four essential freedoms (run, study, redistribute, share modifications) rather than a criteria list. Separate lineage from the DFSG; frames "free" as user control and treats nonfree distribution schemes as equally unethical.
- **[FREEDOM-DEFINED.md](FREEDOM-DEFINED.md)**: Definition of Free Cultural Works v1.1. Applies the freedom set to cultural works and distinguishes free works from the licenses that protect them, with its own list of permissible restrictions. Discourages "Open Content" and "Open Access" as labels that don't convey a clear definition of freedom.
- **[OPEN-SOURCE-AI-DEFINITION.md](OPEN-SOURCE-AI-DEFINITION.md)**: Open Source AI Definition 1.0 (OSI). Applies four freedoms (use, study, modify, share) to AI systems; the document states they are derived from the Free Software Definition. Extends "preferred form" to training data, code, and model parameters.

## Not included

- **Fedora Free/Libre license criteria**: Fedora publishes license approval machinery (allowed/not-allowed lists, SPDX expressions, review process), not a standalone definition document.
- **Ethical Source Definition**: the Organization for Ethical Source publishes ethical licenses (Hippocratic etc.) but no formal definition document; nothing canonical to file.

## Relation to the SSD

The DFSG-lineage definitions share the same skeleton: source availability, free redistribution, derivative rights, non-discrimination, and license propagation. The freedoms-lineage documents state the same idea as user freedoms rather than criteria. The SSD keeps that skeleton but flips the restriction criteria into licensor permissions (#3–#6, #8–#10), leaving source, free distribution, and automatic pass-through as the floor. The Open Definition is the nearest comparison: it already separates required permissions from acceptable conditions, but its acceptable list is closed and small while the SSD's is open.
