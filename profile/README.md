# Klyroo

Independent, composable .NET libraries for Blazor and .NET MAUI Blazor Hybrid. *Build better. Compose freely.*

Each library solves one problem, ships its own NuGet packages and versions, and works alone or with the others. Most
of them split into a `.Core` package with no UI dependency (usable in APIs, workers and NativeAOT apps) and a Blazor
package, which for the visual libraries is built on [Klyroo.UI](https://github.com/klyroo/klyroo-ui).

## Libraries

| Library | Description |
| :--- | :--- |
| [Klyroo.UI](https://github.com/klyroo/klyroo-ui) | Accessible Blazor components for the web and .NET MAUI Blazor Hybrid, styled with Tailwind CSS v4 |
| [Klyroo.Query](https://github.com/klyroo/klyroo-query) | Typed query model, URL state sync, and IQueryable / EF Core execution |
| [Klyroo.Table](https://github.com/klyroo/klyroo-table) | Data lists with table and card-grid layouts, filters, selection and actions |
| [Klyroo.Form](https://github.com/klyroo/klyroo-form) | Schema-driven forms, validation and wizards |
| [Klyroo.Dashboard](https://github.com/klyroo/klyroo-dashboard) | Dashboard controller, filters and Blazor blocks: stats, gauges, charts, tables and feeds |
| [Klyroo.Display](https://github.com/klyroo/klyroo-display) | Read-only display blocks, media player controls and file preview |
| [Klyroo.Spreadsheet](https://github.com/klyroo/klyroo-spreadsheet) | Import wizard for CSV, TSV and pasted data, with column and value mapping |
| [Klyroo.Agent](https://github.com/klyroo/klyroo-agent) | Bridge that lets AI agents read and act on Klyroo forms, dashboards and imports |
| [Klyroo.Stack](https://github.com/klyroo/klyroo-stack) | Meta-package, MCP documentation server and `dotnet new` templates |

## Get started

Install the libraries you need, for example:

```bash
dotnet add package Klyroo.Form --prerelease
```

or everything at once with the meta-package:

```bash
dotnet add package Klyroo.Stack --prerelease
```

Each repository's README has a quick start, and its `docs/` folder has the getting-started tutorial, guides, concepts
and the API reference.

## Contributing

Issues and pull requests are welcome in each repository. Read its `CONTRIBUTING.md` first, and report security
issues privately through the repository's security advisories, never in a public issue.

All Klyroo libraries are released under the [MIT License](https://opensource.org/license/mit).
