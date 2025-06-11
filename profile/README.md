## COMPAS

COMPAS is an open source toolbox for developing computational solutions in AEC.
It provides a base framework and a collection of extensions related to specific AEC-related tasks, problems, processes...

The base framework consists of

* a main library;
* bindings for CGAL, libigl, OCC, gmsh, and ShapeOp;
* UI and visualisation packages;
* CAD integrations for Rhino/GH and Blender; and
* a collection of developer tools.

COMPAS is Python-based and platform and CAD-software independent.
The simplest way to get started with COMPAS is to install the "meta package" `compas_framework` in a virtual environment with `pip`.

```bash
pip install compas_framework
```

This will install all of the packages of the base framework, except for the binding for OCC (`compas_occ`).
If you are planning to work with Nurbs and Breps outside of Rhino, you should install `compas_occ` as well.

```bash
conda create -n comaps-dev -c conda-forge compas_occ
conda activate compas_dev
pip install compas_framework
```

For more information about the packages of the base framework, check out the documentation of `compas_framework`.
