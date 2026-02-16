# css-empty-cells

Functional CSS for empty-cells

## Filesize

| File | Size |
|------|------|
| `dist/empty-cells.css` | 665 bytes |
| `dist/empty-cells.min.css` | 489 bytes (148 Gzipped) |

## Install

```sh
npm install css-empty-cells
```

## Usage

### Import

```css
@import "css-empty-cells";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-empty-cells/dist/empty-cells.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-empty-cells/dist/empty-cells.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.empty-show` | `empty-cells: show;` |
| `.empty-hide` | `empty-cells: hide;` |
| `.empty-inherit` | `empty-cells: inherit;` |
| `.empty-show-s` | `empty-cells: show;` |
| `.empty-hide-s` | `empty-cells: hide;` |
| `.empty-inherit-s` | `empty-cells: inherit;` |
| `.empty-show-m` | `empty-cells: show;` |
| `.empty-hide-m` | `empty-cells: hide;` |
| `.empty-inherit-m` | `empty-cells: inherit;` |
| `.empty-show-l` | `empty-cells: show;` |
| `.empty-hide-l` | `empty-cells: hide;` |
| `.empty-inherit-l` | `empty-cells: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.empty-show-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/empty-cells.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/empty-cells.css` — formatted
- `dist/empty-cells.min.css` — minified

## License

MIT
