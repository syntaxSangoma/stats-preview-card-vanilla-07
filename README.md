# Stats Preview Card (Vanilla Web)

A clean, responsive Stats Preview Card component built using vanilla HTML and CSS.

![Alt text](./images/desktop-design.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS, making it lightweight and easy to understand.
- **Responsive Design:** Adapts to different screen sizes, ensuring optimal viewing on various devices.
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

The component is static and intended as a visual stats preview card. To modify content, edit `index.html`:

- Replace the hero images at `images/image-header-mobile.jpg` and `images/image-header-desktop.jpg` with other images.
- Update the statistics values (10k+, 314, 12M+) and categories (Companies, Templates, Queries) directly in `index.html`.
- Change the title and description text to customize the card message.

Example: Replace `images/image-header-desktop.jpg` with a different image file (keep filename or update the `src`).

## Configuration Options

Most visual changes are done in `style.css` using CSS variables defined in the `:root` selector. Common customizations:

- **Colors:** Modify `--MAIN-BG`, `--MULTIPLY-BG`, `--CARD-BG`, `--TITLE-CLR`, `--TITLE-SPAN-CLR`, and other color variables in `style.css`.
- **Shadow:** Tweak `--CARD-SHADOW` to change the card elevation effect.
- **Font:** The project uses the `Inter` and `Lexend Deca` fonts via Google Fonts. Change or replace the font import in `style.css` to use other fonts.
- **Card Dimensions:** Adjust `.stats-card` width and padding in `style.css` to change card sizing.
- **Image behavior:** The hero image can be controlled with `object-fit` and `mix-blend-mode` on `.stats-card__hero-image img`.
- **Responsive Breakpoints:** Modify the `@media screen and (min-width: 992px)` query to adjust when the layout switches from mobile to desktop.

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
