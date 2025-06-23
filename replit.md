# Protein Structure Explorer

## Overview

A web-based 3D protein structure visualization application built with React and Vite. The application allows users to input PDB (Protein Data Bank) IDs and visualize protein structures interactively using the NGL Viewer library. Users can switch between different molecular representations (cartoon, surface, stick) and view detailed structure information.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite for fast development and optimized builds
- **UI Library**: Shadcn/ui components built on Radix UI primitives
- **Styling**: Tailwind CSS with custom design tokens
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: React Query (TanStack Query) for server state management

### Backend Architecture
- **Runtime**: Node.js with Express.js
- **Language**: TypeScript with ES modules
- **Development**: tsx for TypeScript execution in development
- **Production**: esbuild for server bundling

## Key Components

### Frontend Components
1. **ProteinViewer**: Main component handling 3D visualization
   - Integrates NGL Viewer for molecular rendering
   - Manages PDB loading and representation switching
   - Handles error states and loading indicators

2. **UI Components**: Comprehensive set of reusable components
   - Input fields, buttons, labels for user interaction
   - Toast notifications for user feedback
   - Cards and layout components for structure

### Backend Components
1. **Storage Layer**: 
   - In-memory storage implementation (`MemStorage`)
   - Interface-based design for future database integration
   - User management with basic CRUD operations

2. **Route System**: Express.js route registration system with middleware support

### 3D Visualization
- **NGL Viewer**: Integrated via CDN for protein structure rendering
- **Representation Types**: Cartoon, surface, and stick representations
- **Interactive Controls**: Zoom, rotate, and pan capabilities
- **Structure Information**: Display of PDB metadata including resolution and atom counts

## Data Flow

1. **User Input**: PDB ID entered through input field
2. **Validation**: Client-side validation of PDB ID format
3. **Data Fetching**: NGL Viewer fetches structure from RCSB PDB
4. **Rendering**: 3D structure rendered with default cartoon representation
5. **Interaction**: Users can switch representations and view structure details
6. **Error Handling**: Invalid IDs trigger user-friendly error messages

## External Dependencies

### Core Libraries
- **NGL**: 3D molecular visualization library
- **React Query**: Server state management and caching
- **Drizzle ORM**: Database toolkit with PostgreSQL support
- **Zod**: TypeScript-first schema validation

### UI Dependencies
- **Radix UI**: Unstyled, accessible UI primitives
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Icon library for consistent iconography

### Development Tools
- **TypeScript**: Type safety and enhanced developer experience
- **ESLint/Prettier**: Code formatting and linting
- **Vite**: Fast build tool with HMR support

## Deployment Strategy

### Environment Configuration
- **Development**: Hot module replacement with Vite dev server
- **Production**: Optimized builds with static asset serving
- **Database**: PostgreSQL with connection pooling via Neon

### Build Process
1. Client build via Vite (React app bundling)
2. Server build via esbuild (Node.js server bundling)
3. Static asset optimization and compression
4. Environment-specific configuration injection

### Hosting
- **Platform**: Replit with autoscale deployment
- **Port Configuration**: Internal port 5000, external port 80
- **Process Management**: npm scripts for development and production

## Recent Changes

- June 23, 2025: ✓ Full protein structure explorer implementation complete
- ✓ NGL Viewer integration working with RCSB PDB loading
- ✓ Interactive 3D visualization with cartoon, surface, stick representations
- ✓ Error handling and validation for invalid PDB IDs
- ✓ Structure information display (resolution, chains, atoms)
- ✓ Screenshot capture and fullscreen capabilities
- ✓ Responsive design with gradient backgrounds and animations

## Changelog

- June 23, 2025: Initial setup and complete implementation

## User Preferences

Preferred communication style: Simple, everyday language.