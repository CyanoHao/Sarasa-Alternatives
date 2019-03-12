# Sarasa Gothic Slab

Mono-slab variants for [Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic).

## To build

Same as [Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic).

### Boost building process

Since v0.7.0, ideohint cache files are available. With existing cache files, building time will be reduced by up to 80%.

To make use of cache file, just download `sarasa-ideohint-cache-<version>.7z`, then extract it and move `hint-_sg{1,2}.hgc` to `Sarasa-Gothic-Slab/hint/build/`.

Note: These cache files were built on Windows. If you are to build on Linux or macOS, backslashes (`\\`) in filenames should be replaced to slashes (`/`). Run `head hint-_sg1.hgc` to learn more about the schema.

## What are the names?

- Style dimension
  - Latin/Greek/Cyrillic character set being Iosevka Slab
    - Have ligature, Em dashes (`——`) are full width —— Mono Type Slab
    - Have ligature, Em dashes (`——`) are half width —— Mono Slab
    - No ligature, Em dashes (`——`) are half width —— Term Slab
- Orthography dimension
  - `CL`: Classical orthography
  - `SC`, `TC`, `J`, `HC`: Regional orthography, following [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) notations.
