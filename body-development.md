# Conceptual body-development brief

This is a preliminary concept brief, not a validated mechanical design or manufacturing drawing.

## Design intent
A compact spherical housing with modular internal mounting, accessible electronics, visible status lighting, and safe stationary operation.

## Proposed modules
1. **Outer shell:** serviceable hemispheres; material and wall thickness selected after thermal, impact, and fabrication review.
2. **Internal frame:** removable rails or cage for compute board, sensor mounts, and cable management.
3. **Compute module:** commercially supported single-board computer or mini-PC selected for the software workload.
4. **Sensor module:** begin with one low-risk sensor; define range, field of view, calibration, and limitations.
5. **Power module:** certified, correctly rated supply for bench testing; battery operation only after protection and charging requirements are engineered.
6. **Thermal module:** passive ventilation first; measure temperature under sustained load.
7. **User interface:** status LED ring, physical power control, and accessible emergency shutdown.
8. **Mobility:** excluded from the first prototype. Add only after stationary testing and hazard assessment.

## Initial test sequence
- Inspect wiring and polarity before powering on.
- Use a current-limited supply where appropriate.
- Verify idle and sustained-load temperatures.
- Test one sensor at a time and record expected versus observed readings.
- Verify safe shutdown and restart behavior.
- Document faults; do not bypass protection circuits.

## Not specified yet
Dimensions, material, mass, sensor models, compute board, battery, motor design, magnetic field strengths, and manufacturing tolerances require requirements and component selection. This brief is not a build-ready engineering drawing.
