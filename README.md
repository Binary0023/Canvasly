
# Website Builder - Figma & Framer Combined

A powerful design and prototyping platform combining the best features of Figma and Framer.

## Features

### Core Editor Features
- **Canvas / Frame Editor**: Infinite canvas with zoom/pan, frames, groups, components, layers
- **Shapes & Elements**: Rectangle, Ellipse, Line, Text, Pen tool
- **Keyboard Shortcuts**: Figma-style shortcuts (R for rectangle, F for frame, T for text, etc.)
- **Right-click Menus**: Context menus for frames/components
- **Resizing & Constraints**: Resize with constraints, auto-layout, responsive resizing
- **Property Inspector**: Size, color, gradient, opacity, shadows, stroke, corner radius, blending

### Typography & Fonts
- **Font Library**: Google Fonts integration
- **Style Controls**: Font size, weight, letter spacing, line height, color, alignment
- **Auto-resize**: Text auto-resize options

### Icons & Assets
- **Icon Packs**: Material Icons, Feather Icons, Heroicons
- **Asset Management**: Upload custom SVG/PNG assets

### Components Library
- **Pre-built UI Elements**: Navigation bars, buttons, forms, modals, tables, etc.
- **Component Variants**: Support for hover, active, disabled states
- **Drag & Drop**: Intuitive drag-and-drop interface

### Prototype & Preview
- **Interactive Links**: Create links between frames
- **Animations**: Add transitions and animations
- **Device Previews**: Desktop, tablet, phone mockups
- **Responsive Breakpoints**: Design for multiple screen sizes

### Export Features
- **Image Export**: PNG, JPG, SVG, PDF
- **Code Export**: HTML/CSS/React code generation
- **Figma Integration**: "Copy as Figma" functionality
- **Direct Deployment**: Vercel/Netlify integration

### User & Project Management
- **Dashboard**: Recent projects, drafts, templates
- **Project Organization**: Grid/list view, search, filter
- **Team Collaboration**: Invite members, assign permissions
- **Drafts & Trash**: Autosave drafts, restore deleted projects

### Collaboration Features
- **Real-time Editing**: Multi-user collaboration with WebSockets
- **Live Cursors**: See other users' cursors with names/colors
- **Commenting**: Sticky notes on frames
- **Version History**: Undo/redo functionality

### Advanced Features
- **Animation Panel**: Drag-and-drop animations
- **Auto-layout**: Smart alignment and spacing
- **Dark/Light Mode**: Theme toggle
- **Keyboard Shortcuts**: Comprehensive shortcut system

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Heroicons
- **Canvas**: Fabric.js / Konva.js
- **State Management**: React Context API
- **Drag & Drop**: React DnD
- **Database**: Firebase Realtime Database
- **Authentication**: Firebase Auth
- **Collaboration**: Socket.io (planned)
- **Animations**: Framer Motion

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd website-builder
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open your browser to `http://localhost:3000`

## Project Structure

```
src/
├── app/                 # Next.js app directory
│   ├── api/             # API routes
│   ├── components/      # React components
│   ├── context/         # React context providers
│   ├── lib/             # Library files (Firebase config)
│   ├── types/           # TypeScript types
│   ├── utils/           # Utility functions
│   ├── auth/            # Authentication pages
│   ├── dashboard/       # Dashboard pages
│   ├── profile/         # Profile settings
│   ├── projects/        # Projects management
│   ├── teams/           # Team collaboration
│   └── trash/           # Deleted projects
├── public/              # Static assets
└── styles/              # Global styles
```

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Deployment

The application can be deployed to any platform that supports Next.js, such as:
- Vercel (recommended)
- Netlify
- AWS Amplify
- Google Cloud Run

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a pull request

## License

This project is licensed under the MIT License.

## Acknowledgments

- Inspired by Figma and Framer
- Built with Next.js and Firebase
- UI components from Heroicons
