# invariant-mesh

**Topological state synchronization for distances where fiber doesn't reach.**

The SHARE protocol: phase-locked ℓ-mode resonance for satellite constellations,
deep space links, and anywhere the 166,000 km crossover makes SEND obsolete.

## The Crossover

From `share_handshake.py` break-even analysis:
- Below ~166,000 km: use fiber (SEND wins)
- Beyond ~166,000 km: use SHARE (tension cost < propagation cost)

That's halfway to the Moon. Everything beyond LEO is SHARE territory.

## Status

Scaffolding. Core tension metrics live in:
- [Wave-resonance/cavity4d/share_handshake.py](https://github.com/zedwiater/Wave-resonance/blob/main/cavity4d/share_handshake.py)

See also: [invariant-ledger](https://github.com/zedwiater/invariant-ledger) (terrestrial sister project)
