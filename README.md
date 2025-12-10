
# Stats Preview Card (Vanilla Web)

A clean, responsive Stats Preview Card component built using vanilla HTML and CSS. This repository contains a small, dependency-free component you can drop into any project.

![Stats Preview Card](./images/image-header-desktop.jpg)

## Key Features & Benefits

- **Lightweight:** Built with plain HTML and CSS — no JS or build step required.
- **Mobile-First Responsive:** Optimized layout for mobile, with desktop styles at `992px` and above.
- **Semantic & Accessible:** Uses semantic markup and sensible image alt text for better accessibility.
- **Customizable:** Easy-to-edit class structure (`.stats-card`, `.stats-card__title`, `.stats-card__stat-value`, etc.).
- **Ready-to-Use:** Drop `index.html`, `style.css`, and the `images/` folder into your project.

## Files

- `index.html`: Markup for the stats card component.
- `style.css`: All styles including CSS variables at `:root` for quick theming.
- `images/`: Hero images and favicon used by the component.

## Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari).
- A text editor or IDE (e.g., `VS Code`) to edit `index.html` and `style.css`.
- (Optional) A local static server for consistent asset loading.

## Quick Start

1. Clone this repository:

```bash
git clone https://github.com/syntaxSangoma/stats-preview-card-vanilla-07.git
cd stats-preview-card-vanilla-07
```

2. Open `index.html` directly in your browser, or serve the folder for consistent results:

```bash
# using Python 3
python -m http.server 8000

# or using Node.js serve
npx serve .
```

Then open `http://localhost:8000` in your browser.

## How to Customize

- **Change the hero images:** Replace `./images/image-header-mobile.jpg` and `./images/image-header-desktop.jpg` with your own images.
- **Update the title and description:** Edit the markup in `index.html` inside the elements with classes `stats-card__title` and `stats-card__description`.
- **Update the stats values:** Edit the three `.stats-card__stat-value` elements to change numbers (e.g., `10k+`, `314`, `12M+`).
- **Colors & Theme:** Open `style.css` and update CSS variables in `:root` such as `--MAIN-BG`, `--CARD-BG`, and `--MULTIPLY-BG` to change palette.
- **Typography:** Fonts are imported at the top of `style.css` (`Inter` and `Lexend Deca`). Swap or edit the `@import` line to use different Google Fonts.
- **Layout Breakpoint:** Desktop layout is applied at `@media (min-width: 992px)` — adjust that media query if you need different breakpoints.

Example — change the first stat value in `index.html`:

```html
<div class="stats-card__stats-item">
	<h2 class="stats-card__stat-value center">10k+</h2>
	<p class="stats-card__stat-category center">Companies</p>
</div>
```

## Configuration Options (CSS variables)

Edit `:root` in `style.css` to configure colors, fonts, and shared typography values. Useful variables include:

- `--MAIN-BG`, `--CARD-BG`, `--MULTIPLY-BG` — background and card colors.
- `--TITLE-CLR`, `--TITLE-SPAN-CLR` — title and accent color.
- `--DESCRIPTION-SHARED`, `--STATS-VALUE-SHARED` — typography shorthand for shared styles.

## Contributing

- Fork the repo and create a branch for your changes.
- Open a clear pull request describing your change.
- Keep changes focused to one concern per PR (styles, content, accessibility fixes).

## License

No license specified. If you plan to reuse this in public projects, consider adding an open-source license.

## Acknowledgments

- Google Fonts: `Inter` and `Lexend Deca` used in `style.css`.
- Design inspired by small UI component patterns and accessible card layouts.

## Prerequisites & Dependencies

- A web browser (Chrome, Firefox, Safari, Edge) to view the component.
- A text editor or IDE to edit `index.html` and `style.css` (e.g., VS Code).
- (Optional) A local server for consistent asset loading (VS Code Live Server).

## Installation & Setup Instructions

1. **Clone or download the repository** (or copy the project folder locally):

```bash
git clone https://github.com/syntaxSangoma/nft-preview-card-vanilla-05
```

```bash
cd nft-preview-card-vanilla-05
```

2. **Open the project** in your editor and open `index.html` in the browser:

- Double-click `index.html` or open it from your editor.
- Or serve the folder using a simple local server (recommended for consistent image loading)

## Usage Examples

The component is a product card template. To customize, edit `index.html`:

- Replace the NFT image at `./images/image-equilibrium.jpg` with your own artwork.
- Update the NFT title, description, and pricing in the `.nft-card__title` and `.nft-card__description` markup.
- Change the avatar image at `./images/image-avatar.png` and author name in `.nft-card__author-name`.
- Update the ETH price and time remaining in the `.nft-card__currency` and `.nft-card__time` sections.

Example: to update the NFT price, find the `.nft-card__currency` section and replace the value:

```html
<div class="nft-card__currency">
	<img src="./images/icon-ethereum.svg" alt="" class="nft-card__eth-icon">
	<span>0.405 ETH</span>  <!-- Update this value -->
</div>
```

## Configuration Options

Most visual changes live in `style.css`. Typical customizations:

- **Colors & Palette:** Edit CSS custom properties (variables) at the top of `style.css` under `:root`:
	- `--CYAN` for accent/hover color
	- `--SOFT-BLUE` for secondary text
	- `--MAIN-BG` for background
  
- **Typography:** Change the `--FF` font import or replace with a different Google Font in the `@import` statement.

- **Card Size & Spacing:** Adjust `.nft-card` width, padding, and inner element dimensions to fit your layout.

- **Animations & Hover Effects:** Modify transition durations and transform scales in the `@media (min-width: 992px)` section:
	- Change `250ms` to adjust animation speed
	- Replace `ease` with `cubic-bezier(...)` for custom easing curves
	- Adjust `scale(0.98)` and `scale(0.9)` for different grow/shrink effects

- **Responsive Breakpoints:** The mobile design applies by default; desktop styles activate at `992px` and above. Adjust this breakpoint to match your needs.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/dark-mode`, `feature/animation-speed`).
3. Make changes with focused commits.
4. Push to your fork and open a pull request describing your changes.

## License

License not specified.

## Acknowledgments

- Google Fonts for the `Outfit` font family used in this project.