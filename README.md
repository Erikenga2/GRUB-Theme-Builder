# GRUB Theme Builder

### Visual GRUB 2 Theme Design Studio for Windows and Linux

**GRUB Theme Builder** is a visual **GRUB 2 theme design studio and builder** that allows you to create, customize, preview, import, and export GRUB 2 themes through a graphical interface.

Instead of designing a GRUB theme entirely by manually editing `theme.txt` and managing every graphical resource separately, GRUB Theme Builder provides a visual canvas where the theme can be designed directly.

With **v1.1**, the project evolves beyond a basic GRUB theme editor by introducing dedicated design tools such as **Background Studio** and **Boot Menu Studio**, integrated font management, visual effects, and expanded graphical customization.

---

# ✨ Features

## 🎨 Visual GRUB Theme Editor

Design GRUB themes directly on a graphical canvas.

You can:

- Drag and position elements
- Resize elements
- Add text labels
- Add images
- Add boxes
- Add progress bars
- Add circular progress indicators
- Add a boot menu
- Customize colors
- Customize transparency
- Zoom the canvas
- Preview the design while working
- Save projects
- Open existing projects
- Import GRUB themes
- Export GRUB themes

The goal is to make GRUB theme creation a visual design process rather than a configuration-only workflow.

---

# 🖼️ Background System

GRUB Theme Builder provides **three background modes**.

### 1. Simple Color

Use a single custom color as the background.

### 2. Background Studio

Create a complete graphical background directly inside GRUB Theme Builder.

### 3. External Image

Load an existing image and use it as the GRUB background.

---

# 🎨 Background Studio

**Background Studio** is a dedicated environment for creating custom GRUB backgrounds.

It allows you to build graphical compositions directly on the canvas instead of relying on a single external image.

You can combine different visual elements to create complex backgrounds.

### Supported visual elements include:

- Multi-color gradients
- Custom colors
- Transparency
- Circles
- Squares
- Cubes
- Lines
- Waves
- Arrows
- Decorative elements
- Layered graphical compositions

Colors and transparency can be combined to create different visual styles.

This makes it possible to create simple backgrounds, modern interfaces, abstract designs, decorative backgrounds, and more complex graphical compositions directly inside the application.

---

# 📋 Boot Menu Studio

GRUB Theme Builder v1.1 includes a dedicated **Boot Menu Studio** for designing the visual appearance of the GRUB boot menu.

The boot menu is treated as a complete visual component of the theme rather than simply a configuration entry.

## 💡 Visual Effects

Boot Menu Studio provides controls for:

- Shadows
- Light behind the menu
- Glow effects
- Transparency
- Glass-style effects
- Custom borders
- Border radius
- Custom colors
- Menu text
- Visual styling
- Menu positioning
- Menu sizing

### 🪟 Glass Effects

The menu can be designed with a glass-style appearance by combining:

- Transparency
- Background visibility
- Light effects
- Shadows
- Borders
- Rounded corners
- Custom colors

This allows the menu to become visually integrated with the background instead of appearing as a simple standard GRUB menu.

---

# 🔤 Font Management

GRUB Theme Builder v1.1 includes integrated font selection and GRUB font conversion.

You can select supported font files and automatically convert them into the **PF2** format required by GRUB.

### Supported source formats

- `.ttf`
- `.otf`

### Automatic conversion

The workflow is:

```text
TTF / OTF
      ↓
GRUB Theme Builder
      ↓
grub-mkfont
      ↓
PF2
      ↓
GRUB Theme Export
```

The converted PF2 font is then included in the exported theme.

---

# 🪟 Windows Font Conversion

On Windows, GRUB Theme Builder uses the GRUB font conversion tools bundled with the application.

The application handles the conversion process automatically so the user does not need to manually install or configure `grub-mkfont`.

---

# 🐧 Linux Font Conversion

On Linux, GRUB Theme Builder uses the **system-installed `grub-mkfont` command**.

The application does not depend on a bundled Linux `grub-mkfont` binary.

Instead, it uses the GRUB tools provided by the user's Linux distribution.

This avoids distributing a Linux executable compiled against a specific system library environment.

---

# 📊 Progress Bars

GRUB Theme Builder supports graphical progress bars that can be positioned and customized directly on the canvas.

You can customize:

- Position
- Size
- Color
- Transparency
- Visual appearance

Progress bars can therefore be integrated into the overall design of the theme.

---

# 🔄 Circular Progress Indicators

The editor also supports circular progress indicators.

Circular progress elements can be customized through:

- Position
- Size
- Colors
- Visual appearance
- Transparency

They can be used as decorative or functional graphical components within the theme.

---

# 📝 Text Labels

Text labels can be placed directly on the canvas.

You can customize:

- Text
- Font
- Font size
- Color
- Position
- Transparency
- Appearance

This can be used for titles, descriptions, system information, decorative text, and other graphical elements.

---

# 🖼️ Images

Images can be added directly to the theme design.

You can:

- Import images
- Position images
- Resize images
- Include multiple images
- Integrate images with other graphical elements

Images are included in the exported GRUB theme.

---

# 📦 Boxes

Boxes can be used to create panels, containers, decorations, and interface elements.

Supported customization includes:

- Custom colors
- Transparency
- Borders
- Rounded corners
- Rounded borders
- Position
- Size

Boxes can also be combined with other visual elements to create more complex interfaces.

---

# ✨ Visual Effects

GRUB Theme Builder provides multiple visual effects that can be combined to create different interface styles.

Depending on the component, available effects include:

- Transparency
- Shadows
- Light
- Glow
- Glass effects
- Rounded corners
- Borders
- Custom colors

These effects are particularly useful for creating modern boot interfaces.

---

# 🖥️ Visual Canvas

The main workspace is a graphical canvas where the theme is designed visually.

The canvas can contain:

- Background
- Images
- Labels
- Boxes
- Progress bars
- Circular progress indicators
- Boot menu
- Graphical decorations

Elements can be positioned directly on the canvas.

The visual canvas is the central part of the design workflow.

---

# 🎯 From Design to GRUB

The basic workflow is:

```text
Create Project
      ↓
Choose Background
      ↓
Design Background
      ↓
Design Boot Menu
      ↓
Add Images / Text / Boxes
      ↓
Add Progress Indicators
      ↓
Choose Font
      ↓
Apply Visual Effects
      ↓
Preview
      ↓
Export GRUB Theme
```

The exported theme contains the resources required by the GRUB theme structure.

---

# 📥 Import Existing GRUB Themes

GRUB Theme Builder can import existing GRUB themes for editing.

Depending on the structure and features of the original theme, supported resources can be brought into the visual editor.

Imported themes can then be modified through the graphical interface.

You can change supported:

- Positions
- Colors
- Images
- Text
- Graphical elements
- Menu appearance
- Other supported visual properties

Import compatibility depends on the structure and features used by the original GRUB theme.

---

# 📤 Export GRUB Themes

When the design is complete, GRUB Theme Builder can export the project as a GRUB 2 theme.

The export process can generate resources such as:

```text
theme.txt
fonts/
images/
icons/
menu resources
progress resources
```

Font conversion is integrated into the export workflow.

The resulting theme can then be copied to a compatible GRUB installation and activated through the appropriate GRUB configuration.

---

# 💾 Project Files

GRUB Theme Builder uses its own project format.

Project files use:

```text
.GthEri
```

Projects can be saved and reopened later.

This allows a complete design to be preserved without having to rebuild the theme from the beginning.

---

# 🚀 Getting Started

## 1. Download

Download the latest release from GitHub:

**[Download GRUB Theme Builder](https://github.com/Erikenga2/GRUB-Theme-Builder/releases)**

Available platforms:

- Windows
- Linux

---

## 2. Create a Project

Open GRUB Theme Builder and create a new project.

Choose the background method you want to use:

- Simple Color
- Background Studio
- External Image

---

## 3. Design the Background

Use Background Studio to create the visual foundation of the theme.

Add gradients, shapes, lines, waves, transparency, and other graphical elements as required.

---

## 4. Design the Boot Menu

Open **Boot Menu Studio** and customize the menu.

Configure:

- Transparency
- Shadow
- Light
- Glow
- Glass effect
- Border
- Border radius
- Colors
- Text
- Position
- Size

---

## 5. Add Theme Elements

Add:

- Images
- Text
- Boxes
- Progress bars
- Circular progress indicators
- Other supported graphical elements

---

## 6. Choose a Font

Select a TTF or OTF font.

GRUB Theme Builder automatically converts the selected font to PF2 during the appropriate export process.

---

## 7. Export

Export the finished project as a GRUB 2 theme.

The required graphical resources and fonts are included in the exported theme.

---

# 🖥️ Supported Platforms

GRUB Theme Builder currently targets:

### Windows

Windows packages include the required application runtime and bundled GRUB font conversion tools.

### Linux

Linux uses the system's own `grub-mkfont` installation for font conversion.

Linux distributions may differ in package names and GRUB tool availability.

---

# 👤 Who Is It For?

GRUB Theme Builder is designed for:

- Linux users
- GRUB users
- GRUB theme designers
- Linux distribution developers
- System customization enthusiasts
- Developers
- Hobbyists
- Users who prefer visual design tools
- Users who want to create GRUB themes without manually designing everything through `theme.txt`

---

# 💡 Why GRUB Theme Builder?

Traditional GRUB theme development often requires working directly with:

- `theme.txt`
- Image files
- Font files
- PF2 fonts
- Coordinates
- Sizes
- Colors
- Transparency values
- GRUB-specific configuration

GRUB Theme Builder provides a graphical workflow for these tasks.

Instead of starting with configuration files, you can start with the visual design.

### The idea is simple:

> **Design your GRUB theme visually.**

---

# 🆕 What's New in v1.1

Version **1.1** significantly expands the visual design capabilities of GRUB Theme Builder.

### Background

- Three background modes
- Background Studio
- Multi-color gradients
- Custom colors
- Circles
- Squares
- Cubes
- Waves
- Lines
- Arrows
- Decorative elements
- Transparency

### Boot Menu

- Dedicated Boot Menu Studio
- Shadows
- Light behind the menu
- Glow
- Transparency
- Glass-style effects
- Borders
- Border radius
- Custom colors
- Custom menu text
- Menu positioning and sizing

### Fonts

- Integrated font selection
- TTF support
- OTF support
- Automatic TTF/OTF → PF2 conversion
- Windows bundled GRUB font tools
- Linux system `grub-mkfont` support

### Progress Indicators

- Custom progress bar colors
- Circular progress indicators
- Custom circular progress colors

### General

- Expanded visual customization
- More graphical effects
- More control over the boot menu
- More control over backgrounds
- Improved GRUB theme design workflow

---

# 🔄 Update System

GRUB Theme Builder includes an update checking system.

The application can check GitHub releases for newer versions.

### Automatic Update Check

The application can automatically check for available updates.

### Manual Check

Users can also manually check for updates from inside the application.

---

# 🛠️ Built With

GRUB Theme Builder is built using:

- **Java**
- **Java Swing**
- **NetBeans**
- **GitHub Releases API**

---

# 📌 Current Version

**Version: 1.1.0**

---

# 🐛 Bug Reports

If you find a bug, please open an issue on GitHub.

When reporting a problem, include:

- GRUB Theme Builder version
- Operating system
- Linux distribution and version, if applicable
- Steps to reproduce the problem
- Expected behavior
- Actual behavior
- Error messages
- Screenshots when possible

This information helps reproduce and fix problems more quickly.

---

# 💡 Feature Requests

Feature suggestions are welcome.

If you have an idea for improving the visual design workflow, open a GitHub Issue and describe:

- What you would like to add
- Why it would be useful
- How you would expect it to work

---

# 🤝 Contributing

Contributions are welcome.

You can contribute by:

- Reporting bugs
- Suggesting features
- Improving documentation
- Submitting pull requests
- Testing releases
- Providing feedback

---

# 📜 License

License information will be provided with the applicable release.

---

# 👤 Author

**Ermir Kenga**

---

# 🔗 Links

**Repository:**  
https://github.com/Erikenga2/GRUB-Theme-Builder

**Releases:**  
https://github.com/Erikenga2/GRUB-Theme-Builder/releases

**Issues:**  
https://github.com/Erikenga2/GRUB-Theme-Builder/issues

---

# ⭐ Support the Project

If you find GRUB Theme Builder useful, consider giving the project a **Star on GitHub**.

You can also help by:

- Reporting bugs
- Testing releases
- Suggesting improvements
- Contributing code
- Sharing the project with other GRUB and Linux users

---

# 🎨 GRUB Theme Builder v1.1

GRUB Theme Builder v1.1 is designed as a complete visual environment for creating GRUB 2 themes.

With dedicated tools for:

**Background Design**  
**Boot Menu Design**  
**Fonts**  
**Images**  
**Text**  
**Boxes**  
**Progress Indicators**  
**Transparency**  
**Shadows**  
**Light and Glow**  
**Glass Effects**  
**Gradients**  
**Graphical Decorations**

the application provides a visual workflow for designing the appearance of the GRUB bootloader.

Instead of designing a theme only through configuration files, you can build the visual interface directly on the canvas and export it as a GRUB 2 theme.

## **Design. Customize. Export.**

### **GRUB Theme Builder**
### *Visual GRUB 2 Theme Design Studio*
