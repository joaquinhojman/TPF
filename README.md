# TPF
Trabajo practico profesional FIUBA.

NetworkX: https://github.com/networkx/networkx

## NetworkX performance related issues
- Parallelization (proposed by jarrodmillman): https://github.com/networkx/networkx/issues/4064. Reading the issue, the idea is to parallelize using _pure python_ (so, no low level bindings if we plan to merge). Also, they would like the code to remain simple to read and to be agnostic (Dask, Ray, or else as parallel frameworks, any of those). Some of the main contributors have plans on working on an api for NX to provide parallelization without making the code a complicated mess.
- Memory: https://github.com/networkx/networkx/issues/4210. Some algorithms may benefit from larger-than-memory processing approaches (disk or multicomputing).

## NetworkX Top contributors
- https://networkx.org/documentation/stable/developer/about_us.html

## NetworkX related frameworks/alternatives/wrappers
- nx_parallel: https://github.com/networkx/nx_parallel. Parallel wrappers for NX (few commits).
- rustworkx: https://github.com/Qiskit/rustworkx. Networkx like library with Python bindings implemented in Rust. It lacks the majority of algorithms.
- cugraph: https://github.com/rapidsai/cugraph. GPU accelerated graph analytics (CUDA).
- graph-tool (maybe legacy): https://github.com/antmd/graph-tool. Uses OpenMPI

## Benchmarks
TODO: Memory/CPU profile Rustworkx and Networkx on some common algorithms (Centrality, Shortests Paths, etc) and compare. 
