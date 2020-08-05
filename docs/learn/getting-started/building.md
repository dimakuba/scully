---
title: Building a Scully app
published: true
lang: en
navlist_position: 300
---

# Building a Scully app

## Overview

Running Scully for the first time is exciting. Congrats on making it here!

Before Scully can run you need to build your Angular project. Most projects' built is:

```bash
ng build
```

Now that the Angular project is built, Scully can do its work. Run Scully with the following command:

```bash
npm run scully
```

You did it! You have turned your Angular app into a wicked fast pre-rendered static site thanks to Scully.

The Scully-built version of the project is located in the `./dist/static` folder. It contains all the static pages in the project.

## Troubleshooting

**NOTE**: In case of any errors or warnings during the build process, please follow the instructions in the errors/warnings section or [submit an issue](https://github.com/scullyio/scully/issues/new/choose).

**NOTE**: The following is a common error when building with Scully for the first time:

```bash
No configuration for route `/user/:userId` found. Skipping
```

This message indicates that Scully has skipped any unconfigured routes. Read more about [Route Parameters & Scully](/docs/learn/faq#route-parameters).

<div class="docs-prev_next">
  <a class="prev" href="/docs/learn/getting-started/installation">Installing Scully</a>
  <a class="next" href="/docs/learn/getting-started/serving">Serving a Scully app</a>
</div>