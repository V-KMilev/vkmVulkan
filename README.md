# vkmVulkan

The Vulkan counterpart of [vkmOpenGL](https://github.com/V-KMilev/vkmOpenGL): the layer vkmEngine's
renderer will draw through on Vulkan, as it draws through vkmOpenGL on OpenGL today. It is not
started: this repository holds no code yet.

## What it will be

A library of its own, in the shape every vkm library has: it knows no engine and no window library,
a consumer adds it as a submodule, it carries its own suite, and this README says how to build and
use it, its conventions and its entry points.

## Version

Nothing is released yet. Each release will be tagged `vX.Y.Z` on `master` and listed in
[CHANGELOG.md](CHANGELOG.md); work lands on `vkm/dev` first.

## In vkmEngine

vkmEngine draws through vkmOpenGL today, and Vulkan is on its roadmap. Once this library has code,
the engine pins it at `modules/vkmVulkan`, as it pins its other libraries: a change is a commit here,
then an engine commit that moves the pin.

## License

vkmVulkan is source-available under the [vkmEngine License](LICENSE), the engine's own, which holds
for each vkm library used alone. Changes are shared only as contributions to this repository or in a
fork of it on GitHub.
