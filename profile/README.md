# VoxelBrew

VoxelBrew is an open-source desktop CAD environment for designing mechanical
parts and preparing them for FDM 3D printing.

The project brings parametric modeling, an editable feature history, slicing,
and printer workflows together in one application. It is built with Java 21,
JavaFX, and Open CASCADE Technology, with a CLI backed by the same modeling
engine as the desktop workbench.

> VoxelBrew is actively being developed. Source code and build instructions are
> available today; release downloads will appear as they become available.

## Explore the project

- [VoxelBrew](https://github.com/Voxel-Brew/VoxelBrew) — desktop application,
  CLI, CAD engine, slicer, and printer implementations
- [voxelbrew.dev](https://voxelbrew.dev) — project website and product overview
- [BOM](https://github.com/Voxel-Brew/BOM) — dependency and API version alignment

## Build on VoxelBrew

Public contracts are maintained as small, independently versioned modules so
plugins can integrate without depending on application internals:

- [Model API](https://github.com/Voxel-Brew/api-model)
- [Import API](https://github.com/Voxel-Brew/api-import)
- [Export API](https://github.com/Voxel-Brew/api-export)
- [Slicer API](https://github.com/Voxel-Brew/api-slicer)
- [Printer API](https://github.com/Voxel-Brew/api-printer)

Start with the main repository's
[README](https://github.com/Voxel-Brew/VoxelBrew#readme) for prerequisites,
build commands, architecture, and contribution guidance.
