# Alexandria VA Library Dark Mode - Style Spec

## Sites

-   **alexlibraryva.org** — Main website (Bootstrap 3, Font Awesome 4, custom CSS)
-   **alexandria.na5.iiivega.com** — Vega catalog portal (Angular SPA, Bootstrap 4, Material)

## Light Mode Style Inventory

### alexlibraryva.org

| Role                    | Colors                                           |
| ----------------------- | ------------------------------------------------ |
| Page background         | `#ffffff`                                        |
| Body text               | `#5e6468`, `#333333`, `#555555`, `#1d1d1d`       |
| Links (primary)         | `#af2487` (purple), `#00aca0` (teal)             |
| Brand accent backgrounds| `#00aca0` (teal), `#ec332e` (red), `#fcb931` (yellow), `#af2487` (purple) |
| Nav/header text         | `#ffffff` on colored backgrounds                 |
| Form inputs             | `#ffffff` bg, `#555555` text                     |
| Footer                  | Colored accent backgrounds with white text       |
| Event headings          | `#2d3e4f`                                        |
| Event body text         | `#5b5b5b`                                        |
| Calendar active day bg  | `#286090`                                        |

### alexandria.na5.iiivega.com

| Role                    | Colors                                           |
| ----------------------- | ------------------------------------------------ |
| Page background         | `#ffffff`                                        |
| Section backgrounds     | `#f1f4f6`, `#f2f3f5`                             |
| Body text               | `#222222`, `#212529`, `#4a4b4c`                  |
| Links                   | `#1eaedb` (cyan), `#33475b` (slate), `#00778a` (deep teal) |
| Search button/accent    | `#e45d3f` (orange-red)                           |
| Header bar buttons      | `#425b76` (flint)                                |
| Availability: available | `#0c7e11` (green)                                |
| Availability: unavailable | `#c21414` (red)                                |
| Card borders            | `#babec5`, `#dee1e4`                             |
| Tab/facet text          | `#495057`, `#516f90`, `#666b74`                  |
| Book info text          | `#727272`                                        |
| Location links          | `#219d9d` (turquoise)                            |
| Detail page accents     | `#425b76` (flint), `#0fa0ce` (active tab)        |
| Reading level badges    | `#882b69` (lexile), `#2f8022` (book level), `#0c699b` (age) |
| Unbound widget borders  | `#eeeeee`                                        |

## Dark Mode Palette

Theme: **Pure dark / charcoal**. Brand accents lightened for dark background readability.

| Token                | Value     | Purpose                              |
| -------------------- | --------- | ------------------------------------ |
| `--dm-bg`            | `#1a1a1a` | Page background                      |
| `--dm-bg-surface`    | `#252525` | Cards, panels, sidebars              |
| `--dm-bg-elevated`   | `#2e2e2e` | Inputs, dropdowns, popovers          |
| `--dm-bg-hover`      | `#383838` | Hover states                         |
| `--dm-text`          | `#e0e0e0` | Primary text                         |
| `--dm-text-muted`    | `#a0a0a0` | Secondary/muted text                 |
| `--dm-link`          | `#7ec8e3` | Primary links                        |
| `--dm-link-hover`    | `#a8dcf0` | Link hover                           |
| `--dm-accent-teal`   | `#4dd9c8` | Teal accent (from `#00aca0`)         |
| `--dm-accent-purple` | `#c77dba` | Purple accent (from `#af2487`)       |
| `--dm-accent-red`    | `#e47272` | Red accent (from `#ec332e`)          |
| `--dm-accent-yellow` | `#f0d060` | Yellow accent (from `#fcb931`)       |
| `--dm-accent-orange` | `#e8855a` | Orange-red accent (from `#e45d3f`)   |
| `--dm-border`        | `#3a3a3a` | Borders and dividers                 |
| `--dm-available`     | `#5cbf5c` | Availability: yes                    |
| `--dm-unavailable`   | `#e06060` | Availability: no                     |
