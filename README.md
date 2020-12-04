# Strict analyzer

The Dart analyzer settings with stricter linter rules that allow you to write more maintainable code and improve performance.

You can always change the severity of lints or ignore individual lint rule. If you need more information about the analyzer and linter rules, read this [static analysis details](https://dart.dev/guides/language/analysis-options).

Also you can read about [supported Lint Rules](https://dart-lang.github.io/linter/lints/).

## Getting Started

- Add a dev dependency in your pubspec.yaml

```yaml
dev_dependencies:
  strict_analyzer: ^0.6.0
```

- Place an `analysis_options.yaml` at the root of your package.

- Include the next line in your `analysis_options.yaml`:

```yaml
include: package:strict_analyzer/analysis_options.yaml
```