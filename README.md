# cambria

A web application platform in a single binary. Version controlled in sqlite. Own your data.

Cambria is based on ideas, design, and implementation from Fossil and SQLite,
created by [D. Richard Hipp](https://en.wikipedia.org/wiki/D._Richard_Hipp).

The HyperMedia application platform is self-contained and self-hostable. Data objects are stored as JSON in the same sqlite db as the version controlled content for your site, which is written with HTMX (HTML) and Tachyons (CSS) and requires no additional Javascript programming.

## Install the latest binary

```bash
curl -L https://github.com/thetanil/cambria/releases/latest/download/cambria -o $HOME/.local/bin/cambria && chmod +x $HOME/.local/bin/cambria
```

Copyright (c) 2026 Nicholas Hildebrant. All rights reserved.