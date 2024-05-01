# docfx-assets

Common assets used for package documentation.

## How to use

To use these assets in a docfx website, first clone this repository as a submodule:

```
git submodule add https://github.com/bonsai-rx/docfx-assets assets
```

Then modify `docfx.json` to include the asset files under the `"resource"` section:

```json
      {
        "files": [
          "logo.svg",
          "favicon.ico"
        ],
        "src": "assets"
      }
```

## Licensing

Copyright (c) 2024 Bonsai Foundation CIC and Contributors

You may use, copy, modify and redistribute all assets included in this repository
according to the terms and conditions of the Creative Commons Attribution 4.0
International License.  See the `LICENSE` file for details.