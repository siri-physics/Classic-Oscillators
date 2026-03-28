# Classic-Oscillators
During my internship, I worked on classical oscillators and studied various integration methods, including the Runge–Kutta method, the Euler method, and the velocity Verlet method.

## Analytical Classical Oscillators 
Classical oscillators are fundamental systems in physics that describe periodic motion around an equilibrium position. They appear in many areas, from simple mechanical systems like springs to more complex phenomena in field theory and quantum mechanics. Their dynamics are governed by differential equations that encode the interplay between forces, inertia, and external influences.

## Undamped Harmonic Oscillator
The undamped harmonic oscillator describes an ideal system without energy loss, where the restoring force is proportional to the displacement. This leads to the equation of motion
d²x/dt² + ω₀² x = 0
whose solution is purely oscillatory. The motion is characterized by a constant amplitude and a natural frequency determined by the system parameters.

## Damped Harmonic Oscillator
In more realistic systems, dissipative forces such as friction must be taken into account. This results in the damped oscillator, described by
d²x/dt² + γ dx/dt + ω₀² x = 0
where the damping term causes the amplitude to decrease over time. Depending on the strength of the damping, the system may exhibit oscillatory decay or a non-oscillatory return to equilibrium.

## Driven Harmonic Oscillator
If an external time-dependent force acts on the system, one obtains the driven oscillator. Its equation of motion is given by
d²x/dt² + γ dx/dt + ω₀² x = F₀ cos(ωt)
The solution consists of a transient part, which decays due to damping, and a steady-state motion determined by the driving force. This leads to characteristic phenomena such as resonance and phase shifts between the driving force and the system response.
