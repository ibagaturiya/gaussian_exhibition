# gaussian_exhibition

A browser-based virtual exhibition for 3D scans. Drop gaussian splats, point clouds and meshes into the page and walk through them laid out as an exhibition.

**Open it:** https://ibagaturiya.github.io/gaussian_exhibition/

Supported files: `.ply` `.splat` `.ksplat` `.spz` · `.glb` `.gltf` `.obj` (+`.mtl`) `.fbx` `.stl` `.3dm` `.pcd` `.xyz` `.pts`

Drop, paste (⌘V / Ctrl+V) or choose files. On phones and tablets: one finger orbits, pinch flies in and out, twist rotates, double-tap flies to a model. The Paste button next to + Add loads a copied link to a model file (phones only let web pages paste links, not files).

Everything runs locally in your browser; files are not uploaded anywhere. Press **H** in the viewer for controls.

## License

- **Code:** © 2026 Ivan Bagaturiya, licensed under the [GNU Affero General Public License v3.0 or later](LICENSE). You may use, study, change and host it. If you run a modified version for others, e.g. on a website, you must make your source code available under the same license.
- **Demo scan** (`demo/demo_model.ply`): © 2026 Ivan Bagaturiya, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Free to reuse with credit.
- **Libraries** loaded from jsDelivr (three.js, Spark, meshoptimizer, rhino3dm) are under their own MIT licenses.
