# Examples, tests, benchmarks and profiling of [empymod](https://github.com/empymod/empymod).

## Examples

* [Frequency_Single-and-Crossplot](./Frequency_Single-and-Crossplot.ipynb):
  Frequency example, for a single frequency and crossplot frequency vs offset.
* [Frequency_Dipole-vs-Bipole.ipynb](./Frequency_Dipole-vs-Bipole.ipynb):
  Comparison of a 800 m long bipole with a dipole at its centre.
* [Time_Step-and-Impulse](./Time_Step-and-Impulse.ipynb): Comparison of QWE,
  FHT, FFTLog, and FFT for frequency-to-time transformation.
* [TLE2017_examples](./TLE2017_examples.ipynb): 8 frequency- and time-domain
  examples, originally published in *The Leading Edge, April 2017*; see
  [article-tle2017](https://github.com/empymod/article-tle2017).
* [Halfspace-Dipole_comparison](./Halfspace-Dipole_comparison.ipynb):
  Comparison of `kernel.halfspace` with `dipole` for half- and fullspaces;
  in the case of fullspace `dipole` uses internally `kernel.fullspace`
  (`xdirect=True`)
* [Full-Diffusive_comparison](./Full-Diffusive_comparison.ipynb):
  Comparison of the diffusive with the full wavefield
  full-space solutions.
* [Benchmark](./Benchmark.ipynb): Example benchmark to check which method is
   best for a given problem.

## Developing

* [Comparing](./Comparing.ipynb): Comparing results of current version of
  `empymod` with previously generated data.
* [Profiling](./Profiling.ipynb): Example for profiling the code.
