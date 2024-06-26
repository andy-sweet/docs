(explanations)=
# In-depth explanations

```{note}
These pages describe advanced usage and how napari works internally. If you are
just getting started, check out our [tutorials](tutorials) or
[how-to guides](how-tos) instead.
```

## Advanced usage

If you use napari to view and interact with the results of long-running
computations, and would like to avoid having the viewer become unresponsive
while you wait for a computation to finish, you may benefit from reading about
{ref}`multithreading-in-napari`.

If you are interested in using napari to explore 3D objects, see {ref}`3d-interactivity`.

To understand how napari produces a 2- or 3-dimensional render in the canvas
from layers’ n-dimensional array-like data, check out the {ref}`dedicated guide on rendering in napari <rendering>`.

To understand how to test and measure performance in napari, see {ref}`napari-performance`.

## Architecture documents

See {ref}`napari-preferences` for the list of preferences that can be set via
the preferences dialog.

If you are writing a plugin manifest, or are interested in contributing to
napari, you can also read about the concept of {ref}`context-expressions`.

For a full list of events you may connect to, see {ref}`events-reference`.
