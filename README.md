# Motivational Quote Generator

Motivational Quote Generator built using React and Tailwind CSS — a small, responsive app that shows a fresh motivational quote with the click of a button.

---

## Screenshot

![Motivational Quote Generator screenshot](https://raw.githubusercontent.com/BinaryVortex/Motivational-Quote-Generator/main/Screenshot%202025-08-15%20134335.png)

---

## Features

- Clean, minimal UI built with Tailwind CSS
- Generates and displays motivating quotes
- Responsive layout that works on mobile and desktop
- Single-file static build included (index.html)


## Quick start

Two easy ways to run the app locally:

1. Open the static file
   - Clone the repository and open `index.html` in your browser.
     ```bash
     git clone https://github.com/BinaryVortex/Motivational-Quote-Generator.git
     # open index.html in your browser
     ```

2. Serve with a simple HTTP server (recommended for correct fetch/asset behavior):
   - Using Python 3:
     ```bash
     # from the project directory
     python -m http.server 8000
     # then open http://localhost:8000 in your browser
     ```
   - Or using Node's http-server:
     ```bash
     npx http-server . -p 8000
     ```


## Development

This repository currently contains a static build (index.html). If you have the original React source or want to convert this back into a full React development setup, you'll generally:

1. Initialize a new React project (e.g., using Vite or Create React App).
2. Install Tailwind CSS and configure it per the Tailwind docs.
3. Copy the UI and logic from the static build into the React components.


## Contributing

Contributions, suggestions and improvements are welcome. If you'd like to contribute:

1. Open an issue describing the change or feature.
2. Create a branch from `main` and submit a pull request with a clear description and testing steps.


## License

No license file detected in this repository. If you are the repository owner, consider adding a LICENSE file (for example, the MIT license) to make reuse terms clear.


## Author

BinaryVortex

---

If you'd like, I can:
- Add a short demo GIF instead of the static screenshot,
- Add contribution templates, or
- Convert the static build back into a full React source scaffold (Vite/CRA) with scripts and dependencies.
