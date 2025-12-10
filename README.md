# Stats Preview Card (Vanilla Web)

A clean, responsive Stats Preview Card component built using vanilla HTML and CSS.

![Alt text](./images/image-header-desktop.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS, making it lightweight and easy to understand.
- **Responsive Design:** Adapts seamlessly from mobile to desktop, ensuring optimal viewing on various devices.
- **Easy to Integrate:** Can be dropped into any web project without external dependencies.
- **Customizable:** Uses CSS variables and simple class structure so you can quickly adapt styles.

## Prerequisites & Dependencies

- A web browser (e.g., Chrome, Firefox, Safari) to view the component.
- A text editor or IDE to edit the HTML and CSS files (e.g., VS Code, Sublime Text).

## Installation & Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/syntaxSangoma/stats-preview-card-vanilla-07.git
```

2. **Navigate to the project directory:**

```bash
cd stats-preview-card-vanilla-07
```

3. **Open `index.html` in your web browser:**
   - Double-click `index.html` or open it from your editor.
   - Or serve the folder using a simple local server (recommended for consistent image and font loading):

## Usage Examples

The component is static and intended as a visual preview card. To modify content, edit `index.html`:

- Replace the hero images at `images/image-header-mobile.jpg` and `images/image-header-desktop.jpg` with other images.
- Update the stats values and categories directly in `index.html` (10k+, 314, 12M+, etc.).
- Change the title and description text in the `stats-card__title` and `stats-card__description` elements.

Example: Replace `images/image-header-desktop.jpg` with a different image file (keep filename or update the `src`).

## Configuration Options

Most visual changes are done in `style.css` using CSS variables defined in the `:root` selector. Common customizations:

- **Colors:** Modify `--MAIN-BG`, `--CARD-BG`, `--MULTIPLY-BG`, and `--TITLE-CLR` in `style.css`.
- **Shadow:** Tweak `--CARD-SHADOW` to change the card elevation effect.
- **Font:** The project uses the `Inter` and `Lexend Deca` fonts via Google Fonts. Change or replace the font import in `style.css` to use another font.
- **Card Dimensions:** Adjust `.stats-card` width, padding and `.stats-card__hero-image` dimensions in `style.css` to change card sizing.
- **Image behavior:** The hero image can be controlled with `mix-blend-mode: multiply` on `.stats-card__hero-image img`.
- **Responsive Breakpoint:** The desktop layout activates at `min-width: 992px`. Adjust this value in the media query to change the breakpoint.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/fix-styles`).
3. Make changes with clear commit messages.
4. Push to your fork and open a pull request.

## License

License not specified.

## Acknowledgments

- Google Fonts for the `Inter` and `Lexend Deca` fonts used in this project.
