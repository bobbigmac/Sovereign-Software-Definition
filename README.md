# Sovereign Software Definition

Most "open" licenses can't say no to anyone — this project defines what a sovereign license *can* restrict.

## Why?

The OSD forbids discriminating against persons or fields of endeavor, so a license that excludes corporations or military use is definitionally not open.

The [SSD](SSD.md) keeps the [DFSG](definitions/DFSG.md)/[OSD](definitions/OSD.md)'s mechanics and makes everything else the licensor's explicit choice. We recognise a license can be open-with-exceptions, and that developers have sovereign rights over their work, even under open licences.

## The Sovereign Software Definition

[SSD.md](SSD.md) is a validation metric derived from the DFSG/OSD, with the prohibitions on restriction flipped to permissions. A sovereign license:

- **must** provide source code, allow free distribution (no required fee), pass rights to recipients automatically, and bar arbitrary revocation;
- **may** restrict who is eligible, what the software may be used for, whether derivatives exist, and what other software it touches.

Most Open Source licenses are sovereign licenses.

## What's here

- **[SSD.md](SSD.md)** — the definition.
- **[conformant/CANP.md](conformant/CANP.md)** — my own Corporations Are Not People Public License, drafted with the [SSD](SSD.md): natural persons get full rights (including working on behalf of employers); legal entities get none.
- **[conformant/](conformant/)** — verbatim texts of evaluated licenses that satisfy the [SSD](SSD.md): permissive (MIT, Apache-2.0, BSD), copyleft (GPL, AGPL, MPL), and source-available with restrictions (BUSL, SSPL, Elastic, FSL, PolyForm variants, Hippocratic, Climate Strike, JSON, Commons Clause).
- **[nonconformant/](nonconformant/)** — source-available licenses that fail: PolyForm Strict, Internal-Use, and Free-Trial forbid distribution entirely.
- **[definitions/](definitions/)** — peer license definitions (DFSG, OSD, Social Contract, Free Software Definition, Open Definition, Free Cultural Works, OSHW, OSAID) kept verbatim for diffing; see [INDEX.md](definitions/INDEX.md).

## FAQ

**Is SSD a license?** No. It's a metric for validating licenses, the same job the OSD does for "open". The licenses themselves live in `conformant/` and `nonconformant/`.

**So is a sovereign license open source?** Not necessarily. SSD exists to validate licenses that restrict who can be licensees, and what licensees can do.

**Why "sovereign"?** Because the licensor keeps control over who may use the work, what for, and whether derivatives exist.

**Does conformant/ mean you endorse these licenses?** No. Conformant means it clears the SSD's mechanical floor: source, free distribution, automatic pass-through, no arbitrary revocation. Judging the conditions is editorial.

**Can a sovereign license still be restrictive?** Yes. Eligibility, fields of endeavor, derivatives, other software, and technology are all the licensor's call.

**Is [CANP](conformant/CANP.md) open source?** No. It's a sovereign license: natural persons get full rights, including working on behalf of employers; legal entities get none.

**Will OSI or SPDX recognise SSD?** No, and they shouldn't. It's a different definition for a different category.

**So this open source for some and closed source for others?** Yes. Precisely. 'Open' licensing was always optimistic, and while real people have always been exploited by open source, the trade-offs were often worth it. LLMs heavily tilt the scales of that exploitation, and there was no definition for licenses that want to be open, but with exceptions.

**Isn't that really stupid?** Yes. Probably. SSD validates "no nazis" and "no jews" if that's what your license says.

**Why would you do this?** I like [DBAD](conformant/DBAD.md), and wanted to qualify it, because to anybody except a lawyer, it's the perfect license. Learning a lot about how open source optimistically became pro-business/anti-human and qualifying my own [CANP](conformant/CANP.md) was just a bonus.
