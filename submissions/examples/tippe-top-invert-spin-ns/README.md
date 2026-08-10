# Tippe Top Invert Spin (#71067)

A pure CSS 3D physics demonstration recreating the classic **tippe-top** toy motion sequence, where rapid rotation leads to precession and a mid-cycle inversion onto its narrow stem.

## Features
- **3D Inversion Mechanics:** Multi-axis keyframe sequence orchestrating synchronous `rotateY` continuous spin and `rotateX` full 180° vertical inversion.
- **Hierarchical CSS Sub-Elements:**
  - `__a`: Main weighted spherical body with radial light gradient.
  - `__b`: Equator band providing visual orientation cues during rotation.
  - `__c`: Dynamic contact floor shadow scaling relative to vertical displacement.
  - `__d`: Upper stem taking load during inverted phase.
- **Zero Dependencies:** Standard CSS transition/keyframe rules using BEM methodology for drop-in maintainer standardization.
- **Accessible Design:** Features `aria-hidden="true"` on decorative motion elements and `prefers-reduced-motion` fallbacks.

## File Hierarchy
- `style.css` - Component 3D perspective setup, keyframes, and geometry styling.
- `demo.html` - Self-contained HTML structure.
- `README.md` - Technical specification and maintainer documentation.
