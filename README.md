# Scream CSS Framework

A lightweight Sass-based CSS framework built for custom theming, reusable styles, and consistent UI design across standard HTML elements.

---
## Authors

- **Abdul-Ahad, Maya**
- **Alifa Manzanilla, Laura Vanesa**
- **Hinojos, Kristen**
- **Willmersdorf Franco Filho, Carlos Augusto** (Team leader)

## Professor

Leighton Rodney

## Features

- Built with Sass and partials architecture
- Fully customizable theme using Sass maps
- Styled standard HTML elements (typography, buttons, forms, tables, lists)
- Modular SCSS structure (variables, base, components, utilities)
- Reusable design system foundation

## Installation

Install Sass globally if you do not already have it:

```bash
npm install -g sass
```

Clone the repository:

```bash
git clone https://github.com/will1166/scream-css-framework
cd scream-css-framework
```

## Usage

Compile the main Sass file into CSS:

```bash
sass src/scream.scss dist/style.css --watch
```

Then link the generated CSS file in your HTML:

```bash
<link rel="stylesheet" href="dist/style.css">
````

Use the framework’s default styles in your HTML markup, and add your own classes or component styles as needed.

## Customization

You can customize the framework by editing the Sass partials inside `src/variables/`.

Common customization options include:

- Primary, secondary, and accent colors.
- Background, text, and border colors.
- Font family and typography settings.
- Spacing values and border radius.
- Table border and shared component values.

After changing variables, recompile the Sass file to generate updated CSS.

Example:

```scss
// src/variables/_colors.scss
$primary-color: #111827;
$secondary-color: #6B7280;
$accent-color: #006D77;
```

## Components

The framework is organized into reusable Sass partials for different style groups:

- `variables/` — design tokens and shared values.
- `base/` — global element styling.
- `components/` — reusable UI pieces like buttons, cards, and alerts.
- `utilities/` — helper classes for spacing, colors, and layout.
- `icons/` — optional icon styling and helpers.

Typical component styles may include:

- Buttons.
- Forms.
- Tables.
- Cards.
- Alerts.
- Badges.
- Navigation.

