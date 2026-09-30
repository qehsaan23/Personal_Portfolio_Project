# Personal_Portfolio_Project
My Portfolio Project
A clean, modern, and fully responsive Personal Portfolio Website designed to showcase skills, experiences, and past work. This project features a built-in style switcher that allows users to seamlessly toggle between multiple accent colors and light/dark modes.
🚀 Features
• Fully Responsive Design: Optimised for desktop, tablet, and mobile displays.
• Dynamic Style Switcher: Allows visitors to change the theme's accent color dynamically.
• Multiple Color Skins: Includes 5 distinct color templates (color-1.css to color-5.css).
• Interactive Components: Smooth transitions, filtering portfolio pieces, and dynamic content handling powered by custom JavaScript.
• Clean Architecture: Modulised CSS stylesheet separation (style.css and style-switcher.css).
📁 Project Structure
Based on the repository contents, the project is structured as follows:
text
My-Portfolio-project-main/
│
├── index.html                  # Main layout and content file
├── icon.jpg                    # Website favicon/icon asset
│
├── css/                        # Stylesheets directory
│   ├── style.css               # Core website styling
│   ├── style-switcher.css      # Styling for the interactive theme toggle widget
│   └── skin/                   # Preset theme accent colors
│       ├── color-1.css         
│       ├── color-2.css         
│       ├── color-3.css         
│       ├── color-4.css         
│       └── color-5.css         
│
├── js/                         # Logic and functionality directory
│   ├── script.js               # Main script managing page actions and navigation
│   └── style-switcher.js       # Configuration file managing color changes
│
└── images/                     # Visual assets directory
    ├── me.png                  # Main profile photo display
    └── portfolio/              # Folder containing project preview screenshots
Use code with caution.
🛠️ Tech Stack
• HTML5: Structured semantic markup.
• CSS3: Custom layouts, transitions, animations, and skin presets.
• JavaScript (ES6+): Scripting logic for project interactions and dynamic style customisations.
💻 Getting Started
Follow these instructions to get a local copy of this portfolio website up and running:
1. Clone the repository:bash
git clone https://github.com
Use code with caution.
2. Navigate into the directory:bash
cd My-Portfolio-project-main
Use code with caution.
3. Open the project:
	• Simply double-click the index.html file to view it in any modern browser.
	• Alternatively, open it via a local development server like Live Server in VS Code for live refreshing capabilities.
⚙️ Customisation Instructions
1. Updating Profile Data
Open the index.html file and change the placeholder headers, paragraphs, and list items to map your specific credentials, bios, and links.
2. Changing the Profile Image
Replace the default picture saved under images/me.png with your preferred profile image. For best results, use a transparent square aspect ratio image (.png format).
3. Modifying Style Options
• To edit primary layout sizes, fonts, or base colors, update css/style.css.
• To tweak theme variations, alter the HEX color values located in the files under the css/skin/ directory.
