# Our research

- [Home page](index.md)
- [Articles](articles.md)
- **Our research**
- [Events and seminars](events.md)
- [Strasbourg Students Physical Letters](journal.md)
- [References](references.md)

* * *

## Summary

- [Generalized screw theory for mechanics and twistors](#generalized-screw-theory-for-mechanics-and-twistors)
- [Semi-classical models](#semi-classical-models)
- [Primordial black holes and baryogenesis](#primordial-black-holes-and-baryogenesis)
- [Applied category theory](#applied-category-theory)

* * *

## Generalized screw theory for mechanics and twistors

Screw theory was invented at the end of the XIXth century to describe straight lines along which a translation and a rotation are operated. These very general objects (”screws”) thus contain two elements: a “translational” component that gives the direction of the line as well as the orientation and the amplitude of the translation, and a “rotational” component that gives the position of the line and the amplitude of the rotation. Screws can represent the instantaneous motion of a rigid body (translational and rotational velocities), the forces acting on a system (linear force and torque along), a total momentum (linear and angular momenta), etc.

We have developed [a new formalism for screw theory](articles.md#formalizing-screw-theory-with-3d-geometric-algebra) that generalizes the concept of a screw to any *weighted affine object* in a coordinate-free and origin-independent manner by using the geometric algebra (or real Clifford algebra) G(3), which is based on our familiar three-dimensional Euclidean space. In contrast, most formulations of screw theory either are origin-dependent or need to introduce an unphysical fourth dimension to space. By avoiding these traps, we have built an elegant formalism that helps us understand both the geometric and algebraic meanings of screws. A most natural formula for finite motion composition can also be derived in this setting.

> Part of our research is the development of numerical tools for treating generalized screws: 
>
> [GScrew](https://github.com/GenScrew/GScrew) is a Python module to manipulate generalized Screws and Coscrews with geometric algebras (Clifford algebras). To provide a complete and independant framework, GScrew also implements n-dimensional geometric algebras and multivectors.
> - [Documentation](http://gscrew.rtfd.io/)
> - [Pypi package](https://pypi.org/project/GScrew/)
>
> We are also working on a [C++ library](https://github.com/GenScrew/GSCL) that should implement n-dimensional geometric algebras and generalized screws to perform fast calculations on these objects.

We also observed that the idea of a straight line in space, along which something propagates while something else rotates, is strangely reminiscent of polarized light rays. *Twistor theory* takes advantage of the fact that light rays are nothing but geodesics in spacetime to construct general relativity (and relativistic quantum mechanics) from them. We are wondering whether screws can represent twistors, and thus whether we can formulate relativistic quantum mechanics and/or general relativity with screws.

## Semi-classical models

From the moment Einstein explained the photoelectric effect with light quanta in 1905, physicists tried to understand how to embed these new quantum effects into the well-known classical mechanics. Before Heisenberg (1925) and Schrödinger (1926) established their rigorous theory of non-relativistic quantum mechanics, the only thing that could be achieved consisted in imposing quantization rules to (quasi-)periodic classical systems. These methods, which are nowadays known as *semi-classical approaches*, yield astonishingly good results for several useful systems and can deepen our understanding of quantum mechanics. Among the most notorious semi-classical quantization schemes, we can cite the Bohr-Sommerfeld rule, the Einstein-Brillouin-Keller method and the Wentzel-Kramers-Brillouin approximation. Notable applications include the Bohr and Bohr-Sommerfeld models for the hydrogen atom, the Thomas-Fermi model for heavy atoms and the Maxwell-Boltzmann approximation for high temperature/low density statistics.

We want to propose a pedagogical approach to quantum mechanics that would use a semi-classical setting to introduce the basics of quantum theory in a consistent way. We are thus investigating a semi-classical model for the quantization of light, which allows us to derive the Planck-Einstein relation, the de Broglie relation, and the photon relativistic mass.

The possibility of semi-classically quantizing light seems indicative of the possibility of developing a complete Semi-Classical Field Theory that would apply the Bohr-Sommerfeld rule to classical fields and provide a first approximation to Quantum Field Theory (QFT). Hopefully, this might lead to a fully relativistic/partially quantum theory of elementary particles, whereas QFT is almost always approximated by a fully quantum/partially relativistic theory (the Feynman calculus). This should lead to a different phenomenology, and to possible applications to Quantum Electrodynamics, Quantum Chromodynamics and Quantum Gravity.

## Primordial black holes and baryogenesis

*Baryogenesis*, the unknown process that provoked the matter/antimatter asymetry in the early universe, remains to this day one of the most elusive mysteries of cosmology and high-energy physics, in spite of the identification of the three famous *Sakharov conditions* that it must satisfy. We propose to investigate the possibility that quantum fluctuations around the event horizon of small black holes in the early universe (hypothetical objects known as *primordial black holes*) may have produced more particles than antiparticles due to Hawking radiation, thus leading to baryogenesis.

## Applied category theory

Category theory is a branch of mathematics that describes processes between objects in a very general and abstract framework. Physicists and computer scientists developed at the beginning of the XXIst century a category-theoretical formulation of quantum mechanics, which has the advantage of revealing only what is essential to quantum mechanics, and forget what only depends on a particular formalism like the Hilbert space formulation.

We think category theory could have many applications in classifying methods, theories and formalisms in quantum mechanics, quantum chemistry or high energy physics, and determine their respective benefits and deficiencies. Beyond classification, category theory could provide a way to systematically build Quantum Field Theories, and perhaps all physical theories, through the use of functors (category morphisms).
