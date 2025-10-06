<!-- 
SPDX-FileCopyrightText: German Aerospace Center (DLR) <cosmoscout@dlr.de>
SPDX-License-Identifier: CC-BY-4.0
 -->

# Rings for CosmoScout VR

A CosmoScout VR plugin which can draw simple rings around celestial bodies. The rings can be configured with a inner and a outer radius and a texture.

## Configuration

This plugin can be enabled with the following configuration in your `settings.json`:

```javascript
{
  ...
  "plugins": {
    ...
    "csp-rings": {
      "rings": {
        <anchor name>: {
          "texture": <path to the texture>,   // The texture should be a cross section
                                              // of the ring.
          "innerRadius": <meters from planet center>,
          "outerRadius": <meters from planet center>
        },
        ... <more rings> ...
      }
    }
  }
}
```

**More in-depth information and some tutorials will be provided soon.**

<!-- Auto-update: 2025-10-07T05:06:24.219917 -->
