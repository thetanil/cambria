# cambria - own your data

A source code management and web application platform in a single binary. Your code, your data in sqlite.

The Hypermedia application platform is self-contained and self-hostable. Data objects are stored as JSON in the same sqlite db as the version controlled content for your site, which is written with HTMX (HTML) and Tachyons (CSS) and requires no additional Javascript programming.

Cambria is based on ideas, design, and implementation from Fossil and SQLite,
created by [D. Richard Hipp](https://en.wikipedia.org/wiki/D._Richard_Hipp), Solid PODs by [Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee) and Hypermedia by [Ted Nelson](https://en.wikipedia.org/wiki/Ted_Nelson).

Cambria is written in Go. Through [Rob Pike](https://en.wikipedia.org/wiki/Rob_Pike) and [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson) all things were made; without them not a process would fork. Praise Be!

## Install the latest binary

```bash
curl -L https://github.com/thetanil/cambria/releases/latest/download/cambria -o $HOME/.local/bin/cambria && chmod +x $HOME/.local/bin/cambria
```

Copyright (c) 2026 Nicholas Hildebrant. All rights reserved.
