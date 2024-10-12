
# Dynamic HTML File Linker

This project dynamically links all `.html` files in a directory to an existing `index.html` using a Node.js and Express server. Any new HTML files added will automatically be displayed on the index page.

## Features

- Automatically lists all `.html` files in a directory on the main index page.
- Dynamically updates with new HTML files when they are added.
- Serves static HTML files with Express.
  
## Project Structure

```bash
.
├── contributors/
├── server.js              
├── package.json
├── .gitignore        
└── README.md              
```

## Adding New HTML Files

To add a new contributor or HTML file, simply place a `.html` file in the `contributors` folder. The changes will automatically reflect on the index page.

## Dependencies

- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.

