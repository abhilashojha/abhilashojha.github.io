---
title: "Rotating Rayleigh Benard Convection"
collection: portfolio
share: false
---

<figure style="text-align: center; margin: 0 auto; display: block;">
  <img src="/images/rbc.png" alt="Rayleigh Benard Cell experimental setup" style="max-width: 100%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="text-align: center; margin-top: 10px; font-style: italic; display: block; width: 100%;">
    Experimental setup, schematic, and 3D vector field visualization of rotating Rayleigh Benard convection
  </figcaption>
</figure>

This work presents a comprehensive investigation of rotating Rayleigh Benard convection, combining experimental measurements with computational fluid dynamics (CFD) simulations to understand the complex interactions between rotation, surface roughness, and heat transfer. The experimental apparatus consists of a custom-built rotating Rayleigh Benard Cell (RBC) system featuring a cylindrical convection cell with controlled heating at the bottom and cooling at the top. The entire assembly is mounted on a rotating table, with a rotating mechanism that includes combined rotary union and slip rings to maintain electrical connections for sensors and power supply during continuous rotation. A CCD camera positioned above the cell enables real-time visualization and data acquisition of convective flow patterns, allowing systematic investigation of rotating convection over a wide range of rotation rates.

The introduction of rotation fundamentally alters the convective flow dynamics through the formation of Ekman boundary layers. A key finding of this research is the critical role of Ekman boundary layer thickness in determining the interaction between surface roughness and the bulk flow. At low rotation rates, the Ekman boundary layer thickness is relatively large, and under these conditions, surface roughness effects are confined within the thick boundary layer and do not penetrate into the bulk flow region. The roughness remains decoupled from the bulk convection, resulting in minimal impact on overall heat transfer characteristics. However, as the rotation rate increases, the Ekman boundary layer thickness decreases significantly. At high rotation rates, the thin Ekman layer can no longer contain the roughness perturbations, allowing them to penetrate into the bulk flow layer. This penetration perturbs the bulk convection, leading to enhanced mixing and a substantial increase in heat transfer. The transition from roughness-insensitive to roughness-sensitive regimes occurs when the Ekman layer thickness becomes comparable to the roughness scale, demonstrating a fundamental coupling between rotation, boundary layer dynamics, and surface properties.

<figure style="text-align: center; margin: 20px auto; display: block;">
  <img src="/images/roughness_effect.png" alt="Roughness effect on flow" style="max-width: 100%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="text-align: center; margin-top: 10px; font-style: italic; display: block; width: 100%;">
    Effect of surface roughness on rotating convection flow patterns
  </figcaption>
</figure>

The CFD simulations reveal the intricate three-dimensional structure of rotating convection rolls, showing characteristic rotating roll patterns where hot fluid rises and cold fluid sinks, organized by the rotational constraint. The simulations clearly demonstrate Ekman pumping, a key phenomenon in rotating flows where fluid is drawn into the Ekman boundary layers and then expelled into the bulk flow, creating vertical transport. This Ekman pumping mechanism enhances the mixing between the hot and cold regions, contributing to the increased heat transfer observed at high rotation rates. The computational results provide detailed insights into the flow topology, velocity fields, and temperature distributions that complement and validate the experimental measurements, offering a comprehensive understanding of how rotation modifies convective heat transfer in this fundamental flow configuration.

<figure style="text-align: center; margin: 20px auto; display: block;">
  <img src="/images/cfd_rotate.png" alt="CFD simulation of rotating flow" style="max-width: 100%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="text-align: center; margin-top: 10px; font-style: italic; display: block; width: 100%;">
    Computational fluid dynamics simulation of rotating Rayleigh Benard convection
  </figcaption>
</figure>

