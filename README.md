# Multiple Gravity Assist Trajectory Planner for KSP
An online tool providing automatic design of trajectories with multiple gravity assists for Kerbal Space Program.

![Example trajectory](imgs/example_trajectory.png)

## Dependencies

This project requires type definitions for [THREE.js](https://github.com/mrdoob/three.js/), [Chart.js](https://github.com/chartjs)
and [js-yaml](https://github.com/nodeca/js-yaml). They can be obtained with the following commands:

```
npm install --save-dev @types/three
npm install --save-dev @types/js-yaml
npm install --save-dev @types/chart.js
```

## Used resources

- Ceriotti, Matteo (2010) Global optimisation of multiple gravity assist trajectories. PhD thesis. 
- Orbital Mechanics for Engineering Students by Howard D. Curtis
- [René Schwarz' website](https://www.rene-schwarz.com/web/Home) and his Memorandum Series
- [Astrodynamics Wikibook](https://en.wikibooks.org/wiki/Astrodynamics)
- [ESA's Lambert Solver script](https://github.com/esa/pykep/blob/master/src/lambert_problem.cpp) for pykep
- [Space Exploration StackExchange](https://space.stackexchange.com/) (more precisely [this](https://space.stackexchange.com/questions/54414/how-to-calculate-the-velocity-vector-in-the-case-of-a-hyperbolic-orbit) and [this](https://space.stackexchange.com/questions/54448/calculating-the-time-of-flight-between-two-anomalies-gives-a-negative-result) post)

