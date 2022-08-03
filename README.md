# OpenFOAM Templated RunTime Selection

> This branch is compatible with Foam-Extend 4.1; compile with `wmakeLnInclude . && wmake`

The default macros from OpenFOAM which handle the declaration
and definition of different variables and member methods can only support
a single-parameter template to participate in RunTime selection:

This repository attempts to implement and test enhanced versions of these macros
using variadic macros to allow templates with multiple arguments to have
RunTime-selection capabilities.
