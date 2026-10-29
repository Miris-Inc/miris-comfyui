# Miris for ComfyUI

A ComfyUI custom node pack that publishes meshes and 3D files from a ComfyUI
workflow to Miris and returns a link that streams them.

> **Beta:** The plugin is in beta, so expect changes between releases.

**Requires** ComfyUI 0.7 or later, Python 3.10 or later, and a Miris account.
Publishing has Miris make every asset streamable, which uses one generation
credit per asset.

## Install

Releases will be published here soon.

In ComfyUI Manager, search for **Miris** and install `comfyui-miris`, or open a
workflow that uses a Miris node and let Manager install what it is missing.
Then restart ComfyUI.

Without Manager, download `comfyui-miris-<version>.zip` from this repository's
releases, stop ComfyUI, unzip it into `ComfyUI/custom_nodes/`, and start
ComfyUI again. Install instructions ship inside the package as `INSTALL.md`.

## Support

Report bugs in [GitHub issues](https://github.com/Miris-Inc/miris-comfyui/issues).
For anything else, email [support@miris.com](mailto:support@miris.com).

We don't accept pull requests.

## License

Apache License 2.0. See [LICENSE](LICENSE).
