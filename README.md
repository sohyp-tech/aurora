```markdown name=README.md
# Aurora CSS

Utility-first CSS framework for building fast, clean, and customizable interfaces with a tiny footprint.

Aurora CSS gives you a lightweight set of utility classes to design modern layouts without the overhead of a large framework. It is designed around simple naming conventions, CSS variables, and fast prototyping.

## Features

- Utility-first styling with expressive class names like `a-flex`, `a-p-4`, and `a-text-color`
- Ultra-lightweight and minimal by default
- Variable-driven design system using CSS custom properties
- Easy to learn and quick to use in static HTML or component-based projects
- Flexible layout, spacing, typography, and border utilities

## Quick Start

1. Download `aurora.css`
2. Include it in your HTML document

```html
<link rel="stylesheet" href="aurora.css" />
```

3. Start using Aurora utility classes in your markup.

## Usage Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Aurora Example</title>
    <link rel="stylesheet" href="aurora.css" />
    <style>
      :root {
        --background: #0f172a;
        --text-color: #f8fafc;
      }
    </style>
  </head>
  <body class="a-flex a-center a-p-4">
    <div class="a-p-4 radius-8 border-solid1">
      <h1 class="a-text-color a-text-weight-700">Hello, Aurora CSS</h1>
      <p class="a-text-color a-text-weight-400">Build modern interfaces with utility classes.</p>
    </div>
  </body>
</html>
```

This example uses:
- `a-flex` for layout
- `a-p-4` for padding
- `a-text-color` for text color

## Customization

Aurora CSS is powered by CSS variables, making it easy to theme your project without editing the framework file itself.

Use the `:root` selector to override default values:

```css
:root {
  --background: #f8fafc;
  --text-color: #111827;
  --font-family: "Inter", "Segoe UI", sans-serif;
  --border-color: #d1d5db;
  --bs: 0 10px 25px rgba(15, 23, 42, 0.1);
  --ts: 0 2px 6px rgba(15, 23, 42, 0.15);
}
```

Common variables you can customize:
- `--background`
- `--text-color`
- `--font-family`
- `--border-color`
- `--bs`
- `--ts`

You can also define custom widths and heights:

```css
:root {
  --width: 100%;
  --height: auto;
}
```

## Utility Classes

| Category | Examples | Purpose |
| --- | --- | --- |
| Layout | `a-flex`, `a-flex-col`, `a-center`, `a-content-between`, `a-flex-wrap` | Control display, alignment, and layout flow |
| Spacing | `a-p-4`, `a-px-8`, `a-mg-2`, `a-mg-top-10` | Add padding and margin consistently |
| Typography | `a-text-color`, `a-text-family`, `a-text-weight-700`, `a-text-shadow` | Style color, font, weight, and text effects |

## License

MIT License

Copyright (c) 2026 Aurora CSS

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

