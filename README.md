[![pub package](https://img.shields.io/pub/v/mgenware_dart_lints.svg)](https://pub.dev/packages/mgenware_dart_lints)
[![Status](https://github.com/mgenware/mgenware_dart_lints/workflows/Lint/badge.svg)](https://github.com/mgenware/mgenware_dart_lints/actions)

Dart lint rules used in Mgenware. It includes all official recommended Dart lint rules in `package:lints/recommended.yaml`.

## Usage

Install this package:

```sh
dart pub add --dev mgenware_dart_lints
```

Create a `analysis_options.yaml` and include this package.

Dart:

```yaml
include: package:mgenware_dart_lints/lints.yaml
```

Flutter:

```yaml
include: package:mgenware_dart_lints/flutter_lints.yaml
```
