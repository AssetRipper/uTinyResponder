## Hello
uTinyRipper has been abandoned, but [AssetRipper](https://github.com/AssetRipper/AssetRipper) is actively being developed with the intent to recover Unity games as best as possible. I encourage you to help out if you're able and willing. Code contributions can be submitted via [pull requests](https://github.com/AssetRipper/AssetRipper/pulls).

## Development Progress
These are some of the notable things I've implemented since taking over development.

* 2020 - 6 support
* APK, XAPK, and IPA reading with [SharpZipLib](https://github.com/icsharpcode/SharpZipLib)
* Dummy shaders (so everything isn't pink when you open the project)
* Il2Cpp support via an integration of [Cpp2IL](https://github.com/SamboyCoding/Cpp2IL)
* Better game platform support
* Full script decompilation using the [ILSpy](https://github.com/icsharpcode/ILSpy) decompiler with custom preprocessors to improve C# decompilation
* Cross-platform support
* Multiple configuration options
* Numerous performance improvements
* Support for all asset types
* Lightmap Recovery
* High-quality 3D model export with [SharpGltf](https://github.com/vpenades/SharpGLTF)
* Prefab Outlining
* Hybrid Script Export
* Mesh Preview
* 2 export modes (Primary Content and Unity Project)
* Child State Machines

This is not (at all) a comprehensive list. There are so many other things that could not be included here. They have all been made possible with the support of my generous sponsors.

## Future Plans
This is a list of notable improvements planned for the future.

* Rewrite Sprite Support
* Dynamic Zip File Loading
* Addressable Guid Parsing
* Shader Decompilation
* C# Decompilation Improvements

## Sponsorship
If you like the work I've done and want to see it continue, please consider sponsoring me.

* [GitHub Sponsors](https://github.com/sponsors/ds5678)
* [Patreon](https://patreon.com/ds5678)
* [Paypal](https://paypal.me/ds5678)

A [Patreon](https://patreon.com/ds5678) subscription gives access to AssetRipper Premium, which has [additional features](https://assetripper.github.io/AssetRipper/articles/PremiumFeatures.html).