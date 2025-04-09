# Bio-Inspired Whale Flipper Rocket with Fin-Controlled Steering

This project explores the application of biomimicry in aerospace by designing a rocket that uses fin-based control inspired by the flippers of whales. Unlike traditional rockets that rely solely on gimballed thrust or small control surfaces, this rocket mimics the natural, efficient movement of whale flippers to achieve enhanced stability, agility, and maneuverability.


# CAD

| <img src= "CAD/IMG/Screenshot 2025-04-08 201051.png" > | <img src="CAD/IMG/Screenshot 2025-04-08 201104.png" > |
| --------------------------- | --------------------------- |

# CFD for BIO inspired FIN's



| <img src= "CFD/Screenshot 2025-04-08 212336.png" > | <img src="CFD/Screenshot 2025-04-08 212457.png" > |
| --------------------------- | --------------------------- |

CFD Simulation Explanation:

The CFD simulation shows the airflow behavior around a rocket fin. The streamlines indicate that the flow remains mostly smooth and attached across the surface of the fin, even with the presence of the leading-edge bumps (tubercles). These bumps slightly disturb the incoming flow, creating small, controlled vortices that help keep the boundary layer energized. This delays flow separation, which improves stability and control at various angles of attack. The velocity distribution reveals higher speeds over the upper surface of the fin, especially near the curved leading edge, reaching up to around 2178 m/s. The color gradient from blue to red confirms that the flow accelerates smoothly without any major zones of turbulence or flow detachment. Overall, the CFD results suggest that the biomimetic fin design enhances aerodynamic performance by maintaining steady airflow and reducing the risk of stall.


# Open rocket 

| <img src= "OPEN ROCKET/Screenshot 2025-04-08 203237.png" > | <img src="OPEN ROCKET/graph.png" > |
| --------------------------- | --------------------------- |

# Design Features:

Whale Flipper-Inspired Fins:
The control fins are shaped based on the unique morphology of whale flippers, featuring leading-edge bumps (tubercles) that improve lift, reduce drag, and delay stall at high angles of attack. This ensures better control even in turbulent conditions.

Active Fin Control:
The fins are actuated independently using high-torque, fast-response servos. By adjusting the fins’ angles dynamically during flight (similar to how whales adjust their flippers), the rocket can pitch, yaw, and roll precisely.

Enhanced Stability and Maneuverability:
The whale-inspired design naturally improves aerodynamic performance. The flipper-like fins help distribute forces more evenly, offering smoother control and reducing the chance of abrupt stalls or loss of stability.


# Analysis

| **Concept**                | **Mathematical Explanation**                                                                 | **Effect**                                          |
|-----------------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------------|
| Flow Separation Delay       | Lift = 0.5 × ρ × V² × A × Cl <br> With bumps, Cl drops slower at high angles of attack.      | Flow stays attached longer, delays stall.           |
| Lift-to-Drag Ratio (L/D)    | L/D increases because lift increases and drag decreases with energized flow.                 | Higher aerodynamic efficiency.                     |
| Vortex Generation           | Vortex strength Γ = ∫ V_tangential dr (stronger vortices = better flow control).              | Stabilizes flow, keeps it attached to the surface.  |
| Effective Area Changes      | Local angle of attack (alpha_local) varies slightly along the fin.                           | Smoothens stall behavior, more stable flight.       |


The tubercles on the whale fin generate streamwise vortices that energize the boundary layer, delaying flow separation. Mathematically, this leads to an increase in maximum lift coefficient (
𝐶
𝐿
C 
L
​
 ), higher stall angles, improved lift-to-drag ratio (
𝐿
/
𝐷
L/D), and greater aerodynamic efficiency. The bumps locally modify the angle of attack and cause small-scale vortex generation, which stabilizes the flow over the fin.

# Whale Fin Design Pros:

More stable: Handles air better, less chance of tumbling.

Less drag at angles: Flies smoother even when tilted.

More lift: Can get better lift with smaller fins.

Good in wind: Stays stable in rough air.

