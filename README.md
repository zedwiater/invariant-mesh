# invariant-mesh

**Topological state synchronization for distances where fiber doesn't reach.**

The SHARE protocol: phase-locked ℓ-mode resonance for satellite constellations,
deep space links, and anywhere the 166,000 km crossover makes SEND obsolete.

## Geometric Foundation: Toroidal Host Topology

Our 4D universe is a transduced projection from a 5D+ host manifold.
Of 6 candidate host geometries tested, only **torus** and **dumbbell**
produce ℓ=2 (quadrupole) as the lowest stable mode — matching the observed
CMB quadrupole dominance and our cavity simulations.

**Implications for the mesh:**
- No center, no origin point — only circulation
- Time is throughput around the topology, not a linear vector
- Distances wrap — the 166,000 km crossover needs recalculation on toroidal geometry
- SHARE links inherit the host's modal structure (ℓ=2 native)

See: [Wave-resonance/cavity4d/toroidal_cavity.py](https://github.com/zedwiater/Wave-resonance/blob/main/cavity4d/toroidal_cavity.py) and [host_geometry.py](https://github.com/zedwiater/Wave-resonance/blob/main/cavity4d/host_geometry.py)

## The Crossover

From `share_handshake.py` break-even analysis:
- Below ~166,000 km: use fiber (SEND wins)
- Beyond ~166,000 km: use SHARE (tension cost < propagation cost)

That's halfway to the Moon. Everything beyond LEO is SHARE territory.

*Note: crossover calculated on flat geometry. Toroidal recalculation pending.*

## Status

Scaffolding. Core tension metrics live in:
- [Wave-resonance/cavity4d/share_handshake.py](https://github.com/zedwiater/Wave-resonance/blob/main/cavity4d/share_handshake.py)

See also: [invariant-ledger](https://github.com/zedwiater/invariant-ledger) (terrestrial sister project)
