<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shadehq-dev/.github/main/profile/shade-logo-white.svg">
    <img src="https://raw.githubusercontent.com/shadehq-dev/.github/main/profile/shade-logo-ink.svg" alt="SHADE" height="48">
  </picture>
</p>

<p align="center">
  <strong>The Self-Hosted Adaptive Data Engine.</strong><br>
  Free, open-source software for small European businesses to run their own systems on, owned outright and never locked in.
</p>

<p align="center">
  <a href="https://docs.shadehq.dev">Documentation</a> ·
  <a href="https://github.com/shadehq-dev/shade">Core</a> ·
  <a href="https://www.npmjs.com/org/shadestack">npm</a> ·
  <a href="https://github.com/shadehq-dev/shade/blob/main/SECURITY.md">Security</a>
</p>

---

SHADE is open source under Apache-2.0. Anyone may host it, run it and change it. A business runs its own site, shop,
bookings and forms on SHADE, on a server it chooses, with its own database. Editors work in the admin app and plugins
add what the business needs. Frontends in any framework read the content over the API: Astro, Next.js, Nuxt, SvelteKit
or plain HTTP.

Whoever runs an instance owns it outright: no licence keys, no outside services, and you can move to another host or
supplier at any time, with a full export.

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

Every official plugin is free and public under Apache-2.0.

| Plugin | What it adds |
| --- | --- |
| [`website`](https://github.com/shadehq-dev/shade-plugin-website) | Pages, navigation, posts, theme, redirects and deploys, with a visual editor |
| [`appointments`](https://github.com/shadehq-dev/shade-plugin-appointments) | Opening hours, free times on the site and bookings in the admin |
| [`commerce`](https://github.com/shadehq-dev/shade-plugin-commerce) | Products, orders, stock and hosted checkout |
| [`analytics`](https://github.com/shadehq-dev/shade-plugin-analytics) | Page views without cookies, of the site and of other sites |
| [`error-forwarding`](https://github.com/shadehq-dev/shade-plugin-error-forwarding) | Sends the errors SHADE stores to a GlitchTip or Sentry the business picks |
| [`nl`](https://github.com/shadehq-dev/shade-plugin-nl) | PDOK address lookup and KvK company lookup, each opt-in |
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

<sub>RG Digital built SHADE. It is open source under Apache-2.0: anyone may host it, run it and change it. For help with SHADE itself, use GitHub Discussions on the shade repo.</sub>
