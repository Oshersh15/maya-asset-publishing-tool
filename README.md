# Maya Asset Publishing Tool

A Python-based pipeline tool for Autodesk Maya that validates, fixes, and publishes scene assets through a structured workflow.

## Features

- Type-aware validation using Maya scene data
- Regex-based naming validation
- Automatic naming fixes for models, cameras, and lights
- Versioned publishing
- OBJ export for model assets
- USD export for models, cameras, and lights
- Metadata generation per published version
- Viewport preview generation for model assets
- PySide asset browser with tabs, version selection, search, and folder access

## Workflow

1. Select assets or a scene group in Maya
2. Validate naming and object types
3. Fix invalid names automatically
4. Publish versioned assets
5. Browse published models, cameras, and lights in the UI

## Technologies

- Python
- Autodesk Maya cmds
- PySide
- USD export
- JSON metadata
