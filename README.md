# Alga Config UIKit

A simple Flutter package for a clean and consistent configuration UI.

## Features

- **Documentation Page:**  
  A filterable list of categorized facts with expandable details.

- **Configuration Page:**  
  Navigate to a configuration view via the settings icon.

## Getting Started

### Installation

Add this to your `pubspec.yaml`:

```yaml
dependencies:
  alga_configui:
    path: ../alga_configui
```

## Usage
Import the package and set DocumentationPage as your home widget:

```dart
import 'package:alga_configui/alga_configui.dart';

void main() {
  runApp(const MaterialApp(home: DocumentationPage()));
}
```
Tap the settings icon in the app bar to navigate to the configuration page.

