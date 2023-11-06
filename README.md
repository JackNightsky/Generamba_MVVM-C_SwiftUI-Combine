# generamba-templates

This repository contains a list of [Generamba](https://github.com/rambler-digital-solutions/Generamba) templates.

The detailed information about a template structure is available in [Generamba Wiki](https://github.com/rambler-digital-solutions/Generamba/wiki/Template-Structure).

## Requirements

[Generamba](https://github.com/rambler-digital-solutions/Generamba) 1.3.0 or later.

## List of templates

* [Stinsen MVVM+C SwiftUI+Combine](https://github.com/JackNightsky/generamba-templates/tree/main/stinsen_mvvm%2Bc_swiftui%2Bcombine) - generates a new module of **Stinsen MVVM+C SwiftUI+Combine** architecture

## Installation

To install a template just put these strings in your `Rambafile` and run `generamba template install` in Terminal

```
### Catalogs
catalogs:
- 'https://github.com/JackNightsky/generamba-templates'

### Templates
templates:
- {name: needed_template_name}
```

### As an example: 
```
### Catalogs
catalogs:
- 'https://github.com/JackNightsky/generamba-templates'

### Templates
templates:
- {name: stinsen_mvvm+c_swiftui+combine}
```