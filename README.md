# Markdown Viewer

This is a simple, single-page web application designed to render Markdown content from an `input.md` file into a responsive HTML page using `marked.js` and styled with Tailwind CSS.

## Features

*   **Markdown to HTML Conversion:** Automatically fetches `input.md` and converts its content to HTML.
*   **Responsive Design:** Styled with Tailwind CSS for optimal viewing on various screen sizes.
*   **Single-File Application:** All necessary HTML, CSS (via CDN), and JavaScript (via CDN) are contained within `index.html`.

## Getting Started

To use this application:

1.  **Save the files:** Ensure `index.html` and `input.md` are in the same directory.
2.  **Open `index.html`:** Open `index.html` in your web browser.

The page will automatically load, parse, and display the content of `input.md`.

## Project Structure

```
.
├── index.html      // The main application page
├── input.md        // Your markdown content goes here
└── README.md       // This file
└── LICENSE         // Project license
```

## Technologies Used

*   **HTML5**
*   **Tailwind CSS:** For utility-first styling and responsive design.
*   **Marked.js:** A markdown parser and compiler for the web.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
