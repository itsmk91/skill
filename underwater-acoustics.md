# Underwater Acoustics Skill

## Sound Speed in Water
Sound speed depends on three factors:
- **Temperature** — ~4.0 m/s per °C
- **Salinity** — ~1.1 m/s per PSU
- **Pressure (Depth)** — ~0.017 m/s per metre

**Typical range: 1450–1550 m/s**

Formula: `c ≈ 1449.2 + 4.6T − 0.055T² + 0.00029T³ + (1.34 − 0.010T)(S − 35) + 0.016D`

## Sound Speed Profile Types

### Mike Profile — Deep Sound Channel (SOFAR)
- Speed decreases to a minimum (~800–1200 m), then increases with depth
- Found in temperate/tropical open oceans
- Sound trapped in SOFAR channel — travels thousands of km

### November Profile — Negative Gradient
- Speed decreases continuously with depth
- Found in polar regions and cold water masses
- Sound bends downward, hits seabed — poor long-range performance

### India Profile — Surface Duct
- Speed increases with depth near the surface
- Found in tropical/warm surface layers
- Sound trapped near surface — excellent for detecting shallow targets

## Seabed Effect on Sonar

| Seabed Type | Reflection | Scattering | Sonar Return |
|-------------|------------|------------|--------------|
| Hard Rock   | Very High  | High       | Strong       |
| Sand        | Moderate   | Moderate   | Moderate     |
| Soft Mud    | Low        | Low        | Weak         |
