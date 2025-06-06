## 🛰️ Risk Assessment Heuristic

We use the satellite's latitude to compute `distance_from_equator`, serving as a simplified proxy for orbital inclination risk assessment:

- **Low Risk**: ≤ 10° — Minimal orbital intersection (e.g., geostationary)
- **Medium Risk**: 10–50° — Moderate risk due to intersecting orbits
- **High Risk**: > 50° — Polar orbits; high potential for debris and crossing paths

This method helps visualize potential collision exposure in a low-computation-cost model.
