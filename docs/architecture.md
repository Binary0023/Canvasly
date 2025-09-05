# 🏗️ Architecture Overview

This document explains the internal architecture of **Canvasly** so that contributors and advanced users can understand how the system works under the hood.

---

## 📦 Core Components

1. **Renderer**
   - Responsible for drawing shapes, text, and images on the HTML5 canvas.
   - Uses optimized rendering techniques to keep performance smooth.

2. **UI Layer**
   - Handles toolbars, menus, and user interactions.
   - Communicates with the renderer to update visuals in real-time.

3. **State Management**
   - Keeps track of the canvas state, including:
     - Current shapes
     - Undo/redo history
     - Layers and groups

4. **Export/Import Engine**
   - Allows saving projects in multiple formats (e.g., PNG, JPEG, SVG).
   - Supports loading existing files for further editing.

---

## 🔄 Data Flow

```text
User Action → UI Layer → State Management → Renderer → Canvas
