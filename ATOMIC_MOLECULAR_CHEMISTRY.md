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

## Unconventional bonding and quantum bound-state watch (2026-10-09)
- **Carbon–carbon one-electron sigma bond** — experimentally established in oxidized hexaphenylethane derivative; X-ray diffraction, Raman and DFT; C–C distance 2.921(3) Å at 100 K. Shimajiri et al., Nature 634, 347–351 (2024), DOI: https://doi.org/10.1038/s41586-024-07965-1 . Link to carbon atom, molecular cation, oxidation, sigma orbitals, spectroscopy and bonds.
- **Vibrational bond, Br–Mu–Br** — high-level quantum-chemical support; definitive assignment of muon-spin experimental signal is unresolved versus van der Waals complex. Fleming et al. (2012), DOI: https://doi.org/10.1039/C2CP41366C ; theoretical study https://doi.org/10.1002/anie.201408211 . Link to muonium, exotic atoms, zero-point energy and isotope effects. Do not label unequivocally experimentally confirmed.
- **Actinide phi bonding** — track orbital symmetry, oxidation-state dependence, primary structure and spectroscopy; independent primary-paper audit required. Institutional overview: https://www.lanl.gov/media/newsletters/ste-highlights/actinide-bonding .
- **Bethe strings** — quantum many-body bound states, not conventional chemical bonds. 2026 ultracold cesium experimental claim requires primary-paper verification before establishing exact experimental status. Cross-link Quantum Matter, integrable one-dimensional systems, spin correlations.
### Data-model implications
Represent bond *order*, *electron occupancy*, *orbital symmetry*, *nuclear quantum dynamics*, *measurement method*, *theory/experiment status* separately. Bound-state classification is not equivalent to chemical-bond classification.

## Interactive implementation
- [Bonding & Quantum Bound States Explorer](./bonding.html) — filterable taxonomy with evidence labels, sources, JSON export and links to radiation/QCD. Committed as conceptual classification, not orbital calculation.

- [Water & Ice Phase Explorer](./water-ice.html) — interactive schematic with equilibrium and metastable/ordering layers, ice III–IX relationship, source links and JSON export. **Not a quantitatively accurate pressure–temperature phase diagram.** Next step: obtain validated IAPWS / primary phase-boundary tables and resolve exact ice-polymorph boundaries before numerical cursor readouts.
