# Awesome Finite Element Method (FEM) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<h3 align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/FAE_visualization.jpg" width="30%">
</h3>

> A curated list of awesome stuff related to Finite Element Analysis (FEA) Software for Structural Engineering.
> The [finite element method (FEM)](https://en.wikipedia.org/wiki/Finite_element_method) is a numerical method for solving problems in engineering and mathematical physics.
> Typical problem areas of interest include structural analysis, heat transfer, fluid flow, mass transport, and electromagnetic potential.

This list is a collection of tools, projects, images, and resources conforming to the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)

Contributions _very welcome_ but first see [Contributing](CONTRIBUTING.md).

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [CAD](#cad)
- [Mesh](#mesh)
- [Others](#others)
- [PDE Solver](#pde-solver)
- [Physics-Informed Neural Networks](#physics-informed-neural-networks)
- [Tutorial](#tutorial)
- [Visualization](#visualization)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## CAD

- [CadQuery](https://cadquery.readthedocs.io/en/latest/) – A python parametric CAD scripting framework based on OCCT
- [FreeCAD](https://www.freecad.org/) – A free and opensource multiplatform 3D parametric modeler.
- [Shapely](https://github.com/shapely/shapely) – Manipulation and analysis of geometric objects.

## Mesh

- [Gmsh](https://gitlab.onelab.info/gmsh/gmsh) – A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities.
- [Netgen/NGSolve](https://ngsolve.org/) – Netgen/NGSolve is a high performance multiphysics finite element software. It is widely used to analyze models from solid mechanics, fluid dynamics and electromagnetics. Due to its flexible Python interface new physical equations and solution algorithms can be implemented easily.
- [pyGIMLi](https://github.com/gimli-org/gimli) – Geophysical Inversion and Modeling Library
- [pygmsh](https://github.com/nschloe/pygmsh) – pygmsh combines the power of Gmsh with the versatility of Python. It provides useful abstractions from Gmsh's own Python interface so you can create complex geometries more easily.
- [pyvista-gridder](https://github.com/INTERA-Inc/pyvista-gridder) – Structured and unstructured mesh generation using PyVista for the Finite-Element (FEM), Finite-Difference (FDM), and Finite-Volume Methods (FVM).
- [t8code](https://github.com/DLR-AMR/t8code) – Parallel algorithms and data structures for tree-based AMR with arbitrary element shapes.

## Others

- [DefElement](https://defelement.org/) – an encyclopedia of finite element definitions

## PDE Solver

- [dolfinx](https://github.com/FEniCS/dolfinx) – Next generation FEniCS problem solving environment
- [FeenoX](https://github.com/seamplex/feenox) – Cloud-first free no-fee no-X uniX-like finite-element(ish) computational engineering tool.
- [FElupe](https://felupe.readthedocs.io/en/latest/) – finite element analysis for continuum mechanics of solid bodies
- [GetFEM](https://getfem.org) – Framework for solving systems of coupled nonlinear PDEs.
- [Gridap.jl](https://github.com/gridap/Gridap.jl) – Grid-based approximation of partial differential equations in Julia
- [MFEM](https://mfem.org/) – Lightweight, general, scalable C++ library for finite element methods
- [pyelmer](https://github.com/nemocrys/pyelmer) – A python interface to Elmer.
- [PyMAPDL](https://github.com/ansys/pymapdl) – The PyMAPDL project supports Pythonic access to MAPDL.
- [scikit-fem](https://scikit-fem.readthedocs.io/en/latest/) – Simple finite element assemblers
- [scikit-topt](https://github.com/kevin-tofu/scikit-topt) – Scikit Topology Optimization with SciPy
- [Symfem](https://symfem.readthedocs.io/en/latest/) – A symbolic finite element definition library
- [Xara](https://github.com/peer-open-source/xara) – A batteries-included Python package for fast nonlinear finite element analysis (solid mechanics) ![Python](media/icon/python.png)

## Physics-Informed Neural Networks

- [pinns_for_comp_mech](https://github.com/imcs-compsim/pinns_for_comp_mech) – Implementation of Physics-Informed Neural Networks for Computational Mechanics based on the DeepXDE package.

## Tutorial

- [comet-fenicsx](https://bleyerj.github.io/comet-fenicsx/) – COmputational MEchanics numerical Tours.
- [fenics-sz](https://github.com/cianwilson/fenics-sz) – Jupyter Book and computational repository for modeling subduction zones using FEniCSx.
- [The DOLFINx tutorial](https://github.com/jorgensd/dolfinx-tutorial) – This is the source code for the dolfinx-tutorial webpage.

## Visualization

- [PyVista](https://docs.pyvista.org/version/stable/) – 3D plotting and mesh analysis through a streamlined interface for VTK
- [vedo](https://github.com/marcomusy/vedo) – A python module for scientific analysis of 3D data based on VTK and Numpy
