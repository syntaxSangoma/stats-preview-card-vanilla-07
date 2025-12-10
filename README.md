# NFT Preview Card (Vanilla Web)

A clean, responsive NFT Preview Card component built using vanilla HTML and CSS.

![NFT Preview Card](./images/desktop-design.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS for a lightweight, dependency-free component.
- **Responsive Design:** Mobile-first approach with optimized layouts for both mobile and desktop viewports.
- **Smooth Interactions:** GPU-accelerated hover animations with opacity and transform effects for a polished feel.
- **Accessible:** Semantic HTML structure and keyboard-navigable links.
- **Easy to Integrate:** Drop the `index.html`, `style.css`, and the `images/` folder into any project—no build step required.
- **Customizable:** Simple class structure lets you change copy, images, and styles quickly.

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