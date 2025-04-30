# Discord Clone

This project is a clone of the Discord landing page, built using HTML, CSS, and TailwindCSS. It replicates the design and layout of the official Discord website, providing a responsive and visually appealing user interface.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [How to Run](#how-to-run)
- [License](#license)

## Features
- Responsive design for desktop, tablet, and mobile devices.
- Custom fonts and icons to match the Discord branding.
- Multiple sections including Hero, Features, and Footer.
- TailwindCSS for efficient styling.

## Technologies Used
- **HTML5**: For structuring the content.
- **CSS3**: For additional styling.
- **TailwindCSS**: For utility-first CSS framework.
- **FontAwesome**: For icons.

## Folder Structure
```
/Discord
│
├── Index.html          # Main HTML file
├── main.css            # Compiled CSS file
├── package.json        # Node.js dependencies
├── postcss.config.js   # PostCSS configuration
├── tailwind.config.js  # TailwindCSS configuration
├── fonts/              # Custom fonts used in the project
│   ├── gg-sans/        # ggSans font files
│   ├── Ginto/          # Ginto font files
│   ├── Ginto-Nord/     # Ginto-Nord font files
│   └── Whitney/        # Whitney font files
├── images/             # Image assets
│   ├── favicon.ico     # Favicon
│   ├── logo.svg        # Logo
│   ├── section*.svg    # Section images
│   └── other images
└── README.md           # Project documentation
```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Discord
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Build the CSS using TailwindCSS:
   ```bash
   npm run build
   ```
5. Start Script:
   ```bash
   npm run start
   ```   
6. Open `Index.html` in your browser to view the project.

## License
This project is licensed under the Prashant Mishra. Feel free to use and modify it as per your needs.