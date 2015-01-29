Electrical energy from (water) flow/stream.
===
A low head, low flow, energy harvesting machine system.



Components
---
###Each component is just a recommendation.
Exchange components if desired, but then the overall system may no longer work. It's assumed, you know what you are doing if a component is exchanged.

e.g. if you exchange the generator, then the electronic load controller module might also need to be exchanged.

###Component = Subdirectory
Each subfolder is a component. Look into the folder and read the corresponding README for more information.

The components have repositories of their own.

Which technology/machine/technical realisation of a subsystem is chosen, may change. The simplest, cheapest, best fit still our goals fulfilling solution will be adopted as suitable component.
e.g. if it turns out a small propeller turbine is as simple/easy to manufacture and has better efficiency - or can use more widely available materials, then it'll preempt the waterwheel.



World development:
---
*For the goals we bake, the best and simplest (yet ethical) solutions we take.*

Goals
---

* A green, ecological world. Environment friendly.
* Improve living standard of the world. => Less pain. Terrorists also might have a potentially more difficult life recruiting poor people if they know we care for them (open technology, for a better world).


Reflections:
---
###Energy source to Turbine link:
(missing information)

###Turbine to Generator link (transmission or not):
Attached to the turbine axle in a way that depends on the chosen generator type:
If very low Kv/RPM, then a direct coupling to the turbine may work (calculate it).
If low Kv/RPM, then the transmission ratio can be chosen small, potentially decreasing losses.

Though for common induction motors as generator the transmission ratio will be quite big for run-of-the-stream systems where water flow speed is low.

###Generator to electrical load link:
Generator 3phase -> 1phase: If the way from the stream to the electric loads is long, consider using the 3 phase machine as 1 phase (which will double line-to-line voltage, info is in the web). This way one transformer only at the consumer side is enough. The loss formulas will be integrated in the open ecological engineering document when we have time. Then it's easier to see when it's worth it and when not. Best is to not at all use transformers (if losses are low enough due to short connection or multiple wires soldered together -- in AC, thick wires won't help due to skin effect!).

Off-grid systems may prefer using permanent magnet generators. Otherwise self-excitation capacitors need installation across the generator windings. A controller will be necessary in off-grid systems if the power source (flow of water) or the load power demand vary a lot. Otherwise voltage and rotation of the motor will change, thus the induction generator may lose more and more torque. Excitation current frequency must be increased, or a load controller be used to stabilize voltage and generator rpm.



