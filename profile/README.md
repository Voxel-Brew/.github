# VoxelBrew

## CAD for 3D printers

Create precise, editable objects, slice them, and print them from one open-source
desktop app. Change your CAD design and the slicer updates automatically—no
manual re-export required.

- **Design:** Build parts from editable sketches, dimensions, and solid geometry.
- **Slice:** Arrange objects and choose print settings while the slice stays in
  sync with the design.
- **Print:** Review the result and send it to a configured printer from VoxelBrew.

Save editable `.vxb` designs and return to their feature history, or export STL,
3MF, OBJ, and STEP for the rest of your workflow. The desktop workbench and CLI
share the same modeling engine, making repeatable operations scriptable.

> VoxelBrew is in active development. Get the source, follow the build guide,
> and help shape what comes next.

## Explore the project

- [VoxelBrew](https://github.com/Voxel-Brew/VoxelBrew) — desktop application,
  CLI, CAD engine, slicer, and printer implementations
- [voxelbrew.dev](https://voxelbrew.dev) — project website and product overview
- [BOM](https://github.com/Voxel-Brew/BOM) — dependency and API version alignment

## Visit voxelbrew.dev

[voxelbrew.dev](https://voxelbrew.dev) is the best place for a visual tour of
VoxelBrew. Explore the Designer and Slicer through genuine application
screenshots, see how the connected design-to-print workflow works, and download
the editable bearing-mount `.vxb` demo to try in the application. The site also
links directly to the source, build guide, documentation, and issue tracker.

The desktop workflow targets Windows and Ubuntu Linux. macOS Intel CLI support
is available; macOS GUI qualification remains deferred. VoxelBrew works with
local design files and does not require a cloud account for modeling.

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

The VoxelBrew application is licensed under AGPL-3.0. The standalone public API
libraries are licensed under MIT; see each repository for its complete terms.
