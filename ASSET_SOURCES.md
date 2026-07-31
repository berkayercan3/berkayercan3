# Asset sources

- `assets/hero-light.svg` and `assets/hero-dark.svg` are original, repository-local SVG compositions based on Picksyu's location, city and connection concepts.
- `assets/picksyu-showcase-light.png` and `assets/picksyu-showcase-dark.png` use the exact product artwork from the Picksyu application repository's `assets/images/1.png` and `assets/images/3.png`; the app screens were not regenerated or altered.
- The light showcase backdrop was generated with the built-in image generation tool from a text-only brief for a sparse connected-city map. The dark backdrop is a palette-only edit of that composition. Exact Picksyu product screenshots were composited afterwards with ImageMagick.
- `assets/metrics-light.svg` and `assets/metrics-dark.svg` are initial public-data snapshots. The repository workflow replaces them with current GitHub metrics after `METRICS_TOKEN` is configured.
- No animated demo was added because the available static marketing screens do not form a truthful interaction sequence.
