# Awesome Finite Element Method (FEM) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<h3 align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/FAE_visualization.jpg" width="30%">
</h3>

> A curated list of awesome stuff related to Finite Element Analysis (FEA) Software for Structural Engineering.
> The finite element method (FEM) is a numerical method for solving problems in engineering and mathematical physics.
> Typical problem areas of interest include structural analysis, heat transfer, fluid flow, mass transport, and electromagnetic potential.

This list is a collection of tools, projects, images, and resources conforming to the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)

Contributions _very welcome_ but first see [Contributing](CONTRIBUTING.md).

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [CAD](#cad)
- [FEniCSx](#fenicsx)
- [High Performance Computing](#high-performance-computing)
- [Julia](#julia)
- [Mesh](#mesh)
- [PDE Solver](#pde-solver)
- [Parallel Computing](#parallel-computing)
- [Python](#python)
- [Tutorial](#tutorial)
- [Others](#others)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## CAD

- [CadQuery](https://cadquery.readthedocs.io/en/latest/) - A python parametric CAD scripting framework based on OCCT ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [FreeCAD](https://www.freecad.org/) - A free and opensource multiplatform 3D parametric modeler. ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![macOS](https://img.shields.io/badge/mac%20os-000000?logo=macos&logoColor=F0F0F0) ![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)

## FEniCSx

- [dolfinx](https://github.com/FEniCS/dolfinx) - Next generation FEniCS problem solving environment ![C++](https://img.shields.io/badge/c++-%2300599C.svg?logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)

## High Performance Computing

- [MFEM](https://mfem.org/) - Lightweight, general, scalable C++ library for finite element methods ![C++](https://img.shields.io/badge/c++-%2300599C.svg?logo=c%2B%2B&logoColor=white)

## Julia

- [Gridap.jl](https://github.com/gridap/Gridap.jl) - Grid-based approximation of partial differential equations in Julia ![Julia](https://img.shields.io/badge/-Julia-9558B2?logo=julia&logoColor=white)

## Mesh

- [pygmsh](https://github.com/nschloe/pygmsh) - pygmsh combines the power of Gmsh with the versatility of Python. It provides useful abstractions from Gmsh's own Python interface so you can create complex geometries more easily. ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [t8code](https://github.com/DLR-AMR/t8code) - Parallel algorithms and data structures for tree-based AMR with arbitrary element shapes. ![C++](https://img.shields.io/badge/c++-%2300599C.svg?logo=c%2B%2B&logoColor=white)

## PDE Solver

- [FeenoX](https://github.com/seamplex/feenox) - Cloud-first free no-fee no-X uniX-like finite-element(ish) computational engineering tool. ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)

## Parallel Computing

- [Netgen/NGSolve](https://ngsolve.org/) - Netgen/NGSolve is a high performance multiphysics finite element software. It is widely used to analyze models from solid mechanics, fluid dynamics and electromagnetics. Due to its flexible Python interface new physical equations and solution algorithms can be implemented easily. ![C++](https://img.shields.io/badge/c++-%2300599C.svg?logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54) [![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://ngsolve.github.io/jupyterlite_ngsolve/lab?path=poisson.ipynb)

## Python

- [FElupe](https://felupe.readthedocs.io/en/latest/) - 🔍 finite element analysis for continuum mechanics of solid bodies ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)
- [GetFEM](https://getfem.org) - Framework for solving systems of coupled nonlinear PDEs. ![C++](https://img.shields.io/badge/c++-%2300599C.svg?logo=c%2B%2B&logoColor=white) ![Octave](https://img.shields.io/badge/OCTAVE-darkblue?logo=octave&logoColor=fcd683) ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [PyMAPDL](https://github.com/ansys/pymapdl) - The PyMAPDL project supports Pythonic access to MAPDL. ![pyansys](https://img.shields.io/badge/Py-Ansys-ffc107.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAIAAACQkWg2AAABDklEQVQ4jWNgoDfg5mD8vE7q/3bpVyskbW0sMRUwofHD7Dh5OBkZGBgW7/3W2tZpa2tLQEOyOzeEsfumlK2tbVpaGj4N6jIs1lpsDAwMJ278sveMY2BgCA0NFRISwqkhyQ1q/Nyd3zg4OBgYGNjZ2ePi4rB5loGBhZnhxTLJ/9ulv26Q4uVk1NXV/f///////69du4Zdg78lx//t0v+3S88rFISInD59GqIH2esIJ8G9O2/XVwhjzpw5EAam1xkkBJn/bJX+v1365hxxuCAfH9+3b9/+////48cPuNehNsS7cDEzMTAwMMzb+Q2u4dOnT2vWrMHu9ZtzxP9vl/69RVpCkBlZ3N7enoDXBwEAAA+YYitOilMVAAAAAElFTkSuQmCC) ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [PyVista](https://docs.pyvista.org/version/stable/) - 3D plotting and mesh analysis through a streamlined interface for VTK ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [Symfem](https://symfem.readthedocs.io/en/latest/) - A symbolic finite element definition library ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [pyelmer](https://github.com/nemocrys/pyelmer) - A python interface to Elmer. ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [pyGIMLi](https://github.com/gimli-org/gimli) - Geophysical Inversion and Modeling Library 🌍 ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)
- [scikit-fem](https://scikit-fem.readthedocs.io/en/latest/) - Simple finite element assemblers ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)

## Tutorial

- [The DOLFINx tutorial](https://github.com/jorgensd/dolfinx-tutorial) - This is the source code for the dolfinx-tutorial webpage. ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
- [comet-fenicsx](https://bleyerj.github.io/comet-fenicsx/) - COmputational MEchanics numerical Tours. ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)

## Others

- [DefElement](https://defelement.com/) - an encyclopedia of finite element definitions ![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
