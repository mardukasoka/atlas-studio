# Atomic, Molecular & Cosmic Chemistry — integration plan v0.1

## Architecture
Reuse canonical nuclear identity from Nuclides and Exotic Atoms. Distinguish nuclide, atomic species (nuclide + electrons + charge + electronic state), molecular species (atom identities, bond graph, stereochemistry, charge), material phase (composition, temperature, pressure, structure), and astronomical environment (location, physical conditions, observations). Never confuse conceptual renderings with solved electronic wavefunctions.

## Required views
1. Atomic structure: elements, isotopes, ionization stages, electronic configurations, spectra, photon absorption/emission. Stable links back to Nuclides and Exotic Atoms.
2. Molecular graph: atom vertices, bond edges with order/type, charge, stereochemistry; ring, chain, network and polymer classifications.
3. Water pilot: H2O geometry, hydrogen-bond network, ice Ih, liquid, vapour, phase boundaries, triple/critical points; phase state belongs to a thermodynamic sample, not an isolated molecule.
4. Cosmic chemistry: molecular clouds, icy grains, UV/cosmic-ray ionization, gas-phase chemistry, stellar nucleosynthesis, protoplanetary disks, and isotope pathways.
5. Multimessenger radiation: distinguish photon spectra, charged cosmic rays and neutrinos, including different propagation and detection physics.

## Canonical link contracts
- Existing QCD view: https://mardukasoka.github.io/chess-atlas/experiments/qcd-matter/
- Radiation process graph: ./radiation-processes.html
- Photons and waves: ./photons-waves.html
- Atlas canvas: ./canvas.html
- Provenance registry: ./references.html

## Initial evidence references
- NIST Chemistry WebBook water: https://webbook.nist.gov/cgi/cbook.cgi?Name=water&cTG=on&cTP=on
- Quanta, 2023 IceCube neutrino sky: https://www.quantamagazine.org/a-new-map-of-the-universe-painted-with-cosmic-neutrinos-20230629/
- Quanta, 2021 ultrahigh-energy cosmic rays: https://www.quantamagazine.org/cosmic-map-of-ultrahigh-energy-particles-points-to-long-hidden-treasures-20210427/

These Quanta articles are secondary reporting. Follow the underlying observatory publications for claim-level provenance. Avoid inferring astrochemical abundance maps from cosmic-ray or neutrino arrival maps.

## Integration gates
Locate canonical deployed Nuclides and Exotic Atoms object identifiers before writing outbound links. Confirm physical units, stable species identifiers and mobile performance. No duplicate nuclear records. Phase diagram should use an explicit equation of state or tabulated boundaries, not interpolated artwork presented as measurement.

## Interstellar molecule catalogue (observational registry)
- https://molecules-in.space/ — Mitsunori Araki, List of Observed Interstellar Molecules. Site update 2026-08-03 reports 353 species, with tentative detections included; use per-entry detection status, first detection paper, cloud, telescope, column density and detection year.
- Preserve source-specific species naming, isomer identity and observational confidence. Crosswalk to canonical chemical identifiers only after checking exact structural and charge identity. Do not treat all 353 as independently confirmed.
- Proposed interfaces: species ↔ atomic constituents / ions ↔ bond graph ↔ rotational-vibrational spectroscopy ↔ observed cloud / telescope ↔ original detection paper.
- Data import requires source permission/licensing review; until then link to original source rather than mirroring the downloadable spreadsheet.
