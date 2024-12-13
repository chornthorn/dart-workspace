# Dart Pub Workspace Demo

This is a demo project showing how to set up a Dart pub workspace for managing multiple packages.

## Project Structure

```
workspace/
├── packages/         # Contains all package projects
│   ├── package_a/    # Package A
│   └── package_b/    # Package B  
├── pubspec.yaml      # Workspace root pubspec
└── README.md         # This file
```

## Getting Started

1. Clone this repository
2. Run `dart pub get` in the workspace root directory
3. Run `dart pub get` in each package directory under `packages/`

## Features

- Demonstrates multi-package workspace setup
- Shows package dependencies management
- Includes example of package-to-package references

## Requirements

- Dart SDK >= 3.6.0
- pub package manager

## Development

To work on packages in this workspace:

1. Make changes in the package directories under `packages/`
2. Run tests: `dart test` in package directories
3. Build/run as needed

## License

MIT

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request