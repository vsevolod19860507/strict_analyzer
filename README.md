# strict_analyzer

The Dart analyzer settings with stricter linter rules that allow you to write more maintainable code and improve performance.

## Getting Started

- Add a dev dependency in your pubspec.yaml

```yaml
dev_dependencies:
  strict_analyzer: ^0.1.0
```

- Place an `analysis_options.yaml` at the root of your package.

- Include the next line in your `analysis_options.yaml`:

```yaml
include: package:strict_analyzer/analysis_options.yaml
```

In addition, you can always change the severity of lints or ignore individual lint rule. You can find information on how to do this at the link below.

[Static analysis details](https://dart.dev/guides/language/analysis-options)

