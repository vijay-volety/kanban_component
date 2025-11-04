# Kanban Board Component

A reusable, accessible Kanban board component built with React, TypeScript, and Tailwind CSS.

## Features

- Drag-and-drop functionality
- Keyboard navigation support
- Responsive design
- Customizable priority levels
- Task assignment
- Due date tracking
- Tagging system

## Installation

```bash
npm install
```

## Usage

```bash
# Development
npm run dev

# Build
npm run build

# Storybook
npm run storybook
```

## Component Structure

```
src/components/KanbanBoard/
├── KanbanBoard.tsx
├── KanbanColumn.tsx
├── KanbanCard.tsx
├── KanbanBoard.types.ts
├── hooks/
│   └── useDragAndDrop.ts
└── utils/
    └── task.utils.ts
```

## Storybook Stories

- Default
- Empty
- Large Dataset
- Mobile Responsive
- Interactive Playground
- Accessibility

## Accessibility

- Keyboard navigation (Arrow keys, Space, Enter)
- ARIA attributes
- Focus-visible styles
- Color contrast compliance