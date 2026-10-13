# AEROGENESIS | 3D LEO Mega-Constellation & ISL Laser Mesh Simulator

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://tareq0001.github.io/AeroGenesis-Satellite-Constellation/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**AEROGENESIS** is an enterprise-grade 3D aerospace simulation workstation modeling **Low Earth Orbit (LEO) Mega-Constellations** (such as Starlink, Kuiper, and SDA Tranche architectures) and autonomous **Inter-Satellite Optical Laser Crosslinks (ISL)** with Dijkstra dynamic shortest-path routing.

---

## 🛰️ Core Astrodynamics & Space Engineering Systems

1. **Walker Delta Constellation Geometry ($T/P/F$):**
   - Parametric modeling of orbital altitude ($h$), inclination ($i$), number of orbital planes ($P$), and satellites per plane ($S$).
   - Calculates orbital velocity $v = \sqrt{\mu / r}$, orbital period $T$, and nodal precession $\dot{\Omega}$ induced by Earth's $J_2$ oblateness.

2. **Optical Inter-Satellite Laser Link (ISL) Mesh:**
   - Dynamic 100 Gbps crosslink generation within spatial line-of-sight threshold ($< 5,000$ km).
   - Autonomous shortest-path graph routing (Dijkstra) providing direct intercontinental sub-35ms routing (e.g. Abha Ground Hub $\longleftrightarrow$ Tokyo Gateway).

3. **Conjunction Assessment & Space Debris Mitigation:**
   - Evaluates Conjunction Data Messages (CDMs) from space surveillance networks.
   - Computes Miss Distance and Probability of Collision ($P_c$).
   - Interactive Collision Avoidance Maneuver (CAM) chemical/electric thruster burn execution.

4. **Multi-View 3D Astrodynamics Engine:**
   - **3D LEO Globe:** Interactive rotating Earth sphere with atmospheric Rayleigh scattering and 3D satellite orbital planes.
   - **2D Ground Track Projection:** Equirectangular trajectory tracing showing orbital shift due to diurnal rotation.
   - **ISL Topology Network Graph:** Visualizes graph connectivity, degree distribution, and link survivability.

5. **Internationalization (i18n):**
   - Seamless Arabic and English language toggling with RTL support.

---

## 🚀 Live Access

Explore the live simulation: [https://tareq0001.github.io/AeroGenesis-Satellite-Constellation/](https://tareq0001.github.io/AeroGenesis-Satellite-Constellation/)

Developed by **Tareq Aboushi** (أ. طارق ابوعشي).
