# Protein Structure Explorer

A web-based 3D protein structure visualization application built with React and NGL Viewer. Load and explore protein structures from the Protein Data Bank (PDB) with interactive 3D visualization and multiple representation modes.

![Protein Structure Explorer](https://img.shields.io/badge/Status-Live-brightgreen) ![React](https://img.shields.io/badge/React-18-blue) ![TypeScript](https://img.shields.io/badge/TypeScript-Enabled-blue)

## Features

- **3D Protein Visualization**: Interactive 3D rendering using NGL Viewer
- **PDB Integration**: Direct loading from RCSB Protein Data Bank
- **Multiple Representations**: Switch between cartoon, surface, and stick modes
- **Structure Information**: Display resolution, chain count, and atom count
- **Error Handling**: User-friendly validation and error messages
- **Modern UI**: Gradient design with smooth animations
- **Responsive Design**: Works on desktop and mobile devices

## Quick Start

1. Enter a valid PDB ID (e.g., `7RSA`, `6LU7`, `1BNA`)
2. Click search or press Enter to load the structure
3. Use the representation buttons to switch between views
4. Interact with the 3D model (rotate, zoom, pan)

## Technology Stack

- **Frontend**: React 18 + TypeScript + Vite
- **3D Visualization**: NGL Viewer
- **UI Components**: Shadcn/ui + Radix UI
- **Styling**: Tailwind CSS
- **Backend**: Node.js + Express
- **State Management**: TanStack Query

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/protein-structure-explorer.git
cd protein-structure-explorer

# Install dependencies
npm install

# Start development server
npm run dev
```

## Usage Examples

### Popular Protein Structures to Try

- **7RSA** - Ribonuclease A
- **6LU7** - COVID-19 Main Protease
- **1BNA** - DNA Double Helix
- **6VXX** - SARS-CoV-2 Spike Protein
- **1REV** - HIV-1 Reverse Transcriptase

### Representation Modes

- **Cartoon**: Shows secondary structure (alpha helices, beta sheets)
- **Surface**: Displays molecular surface representation
- **Stick**: Shows atomic bonds and connections

## Development

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

### GitHub Pages (Recommended)

This project is configured for automatic deployment to GitHub Pages:

1. **Upload to GitHub** (follow instructions above)
2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "gh-pages" branch
   - Click "Save"

3. **Automatic Deployment**: Every push to main branch will automatically build and deploy your app

Your app will be live at: `https://yourusername.github.io/protein-structure-explorer/`

### Alternative: Replit Deployment

This project also works on Replit with the existing configuration running on port 5000.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [NGL Viewer](https://github.com/nglviewer/ngl) for 3D molecular visualization
- [RCSB Protein Data Bank](https://www.rcsb.org/) for protein structure data
- [Shadcn/ui](https://ui.shadcn.com/) for beautiful UI components

## Support

If you find this project helpful, please give it a ⭐ on GitHub!

---

Built with ❤️ using React and NGL Viewer
