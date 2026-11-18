<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shadehq-dev/.github/main/profile/shade-logo-white.svg">
    <img src="https://raw.githubusercontent.com/shadehq-dev/.github/main/profile/shade-logo-ink.svg" alt="SHADE" height="48">
  </picture>
</p>

<p align="center">
  <strong>The Self-Hosted Adaptive Data Engine.</strong><br>
  Content, data and client systems on your own server, with nothing to rent and no one to ask.
</p>

<p align="center">
  <a href="https://docs.shadehq.dev">Documentation</a> ·
  <a href="https://github.com/shadehq-dev/shade">Core</a> ·
  <a href="https://www.npmjs.com/org/shadestack">npm</a> ·
  <a href="https://github.com/shadehq-dev/shade/blob/main/SECURITY.md">Security</a>
</p>

---

SHADE runs underneath client systems. Each instance has its own server and its own database. Editors work in the admin
app, plugins add what a client needs (a shop, bookings, forms, their own records) and frontends in any framework read
it over the API: Astro, Next.js, Nuxt, SvelteKit or plain HTTP.

Whoever runs an instance owns it outright: no licence keys, no outside services, and any competent developer can take
it over.

> [!NOTE]
> SHADE is pre-release. Data formats, APIs and the plugin SDK may still change between versions.

## Repositories

| Repository | What it is |
| --- | --- |
| [`shade`](https://github.com/shadehq-dev/shade) | The core: API, admin app, plugin SDK and the `@shadestack/*` frontend packages |
| [`shade-docs`](https://github.com/shadehq-dev/shade-docs) | The documentation, published at [docs.shadehq.dev](https://docs.shadehq.dev) |
| [`shade-programs`](https://github.com/shadehq-dev/shade-programs) | Runs an instance's own services as containers, in any language, approved from the admin |
| [`shade-site`](https://github.com/shadehq-dev/shade-site) | SHADE's own website, an Astro frontend built on SHADE |

### Official plugins

| Plugin | What it adds |
| --- | --- |
| [`website`](https://github.com/shadehq-dev/shade-plugin-website) | Pages, navigation, posts, theme, redirects and deploys, with a visual editor |
| [`payments`](https://github.com/shadehq-dev/shade-plugin-payments) | Payment providers, and the base for building your own |
| [`forms`](https://github.com/shadehq-dev/shade-plugin-forms) | Forms on the site and their submissions in the admin |
| [`editorial`](https://github.com/shadehq-dev/shade-plugin-editorial) | Editorial workflow for content teams |
| [`import`](https://github.com/shadehq-dev/shade-plugin-import) | Bringing content in from other systems |

## Getting started

Start with [Getting started](https://docs.shadehq.dev) in the documentation. To work on SHADE itself, see the
[core README](https://github.com/shadehq-dev/shade#developing).

## Security

Please report vulnerabilities privately, as described in
[SECURITY.md](https://github.com/shadehq-dev/shade/blob/main/SECURITY.md), not in a public issue.

---

<sub>SHADE is built by RG Digital in the Netherlands and released under the Apache 2.0 licence.</sub>
