# SITMUN

**SITMUN** is an open-source platform, licensed under the [EUPL 1.2](https://github.com/sitmun/sitmun/blob/main/LICENSE), that lets supramunicipal organisations offer map viewers and territorial information tools to the municipalities they serve. It is developed by the [SITMUN network](https://sitmun.org). The documentation, in Spanish, is at [sitmun.github.io](https://sitmun.github.io).

**SITMUN** es una plataforma de código abierto, con licencia [EUPL 1.2](https://github.com/sitmun/sitmun/blob/main/LICENSE), que permite a las organizaciones supramunicipales ofrecer visores de mapas y herramientas de información territorial a los municipios a los que dan servicio. La desarrolla la [Red SITMUN](https://sitmun.org). La documentación, en castellano, está en [sitmun.github.io](https://sitmun.github.io).

## Where to start

| | |
| --- | --- |
| **Code** | [sitmun/sitmun](https://github.com/sitmun/sitmun): all the components in one repository (backend, proxy, administration app, map viewer, MBTiles service and mobile apps) |
| **Current release** | [SITMUN 1.3.0](https://github.com/sitmun/sitmun/releases/tag/v1.3.0) |
| **Documentation** | [sitmun.github.io](https://sitmun.github.io) (in Spanish): installation, administrator manual, guides and architecture |
| **Contributing** | [CONTRIBUTING.md](https://github.com/sitmun/sitmun/blob/main/CONTRIBUTING.md) |
| **Bugs and questions** | [Issues in sitmun/sitmun](https://github.com/sitmun/sitmun/issues); for the documentation, [issues in sitmun.github.io](https://github.com/sitmun/sitmun.github.io/issues) |
| **Network and brand** | [The SITMUN network](https://sitmun.github.io/que-es-sitmun/red-sitmun/), its [governing bodies](https://sitmun.github.io/que-es-sitmun/red-sitmun/contacto/) and the [corporate identity](https://sitmun.github.io/que-es-sitmun/red-sitmun/identidad-corporativa/) (logos and manual) |

## Active repositories

- [sitmun](https://github.com/sitmun/sitmun): the SITMUN platform.
- [sitmun.github.io](https://github.com/sitmun/sitmun.github.io): source of the documentation site.
- [sitna-ats](https://github.com/sitmun/sitna-ats) and [sitna-npm-test](https://github.com/sitmun/sitna-npm-test): test projects for the [SITNA map API](https://github.com/sitna/api-sitna) that the viewer uses.

[All active repositories](https://github.com/orgs/sitmun/repositories?q=archived:false)

## Archived repositories

Until version 1.2.9, each component lived in its own repository (`sitmun-shared`, with the common libraries, was created after 1.2.9 and imported before 1.3.0). Since 1.3.0 they are part of [sitmun/sitmun](https://github.com/sitmun/sitmun), which imported their history:

| Old repository | Now in sitmun/sitmun |
| --- | --- |
| `sitmun-application-stack` | repository root |
| `sitmun-backend-core` | `sitmun-backend` |
| `sitmun-proxy-middleware` | `sitmun-proxy` |
| `sitmun-admin-app` | `sitmun-admin` |
| `sitmun-viewer-app` | `sitmun-viewer` |
| `sitmun-mbtiles` | `sitmun-addons/sitmun-mbtiles` |
| `sitmun-shared` | `sitmun-common` |
| `edition-mobile-app` | `sitmun-mobile/sitmun-edition` |
| `touristic-mobile-app` | `sitmun-mobile/sitmun-touristic` |

The old repositories, and other earlier ones that are no longer maintained, are archived: they stay public and read-only, and receive no further changes. This includes `sitmun-community`: its corporate identity material is now on the [documentation site](https://sitmun.github.io/que-es-sitmun/red-sitmun/identidad-corporativa/).

