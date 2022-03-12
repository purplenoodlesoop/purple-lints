# purple_metrics_lints

## Overview

This package contains set of custom rules that can be used both in pure Dart and Flutter projects with additional Dart Code Metrics integration.

This package contains all the rules from the [purple_lints](https://pub.dev/packages/purple_lints) plus additional `dart_code_metrics` specific ones.

It is built upon the thought of strictness. Strictness helps to unify the code, avoid runtime problems that are derived from type and mutability-related issues and avoid common pitfalls that developers that came from other languages can stumble upon.

## Installation

Create `analysis_options.yaml` file

```yaml
include: package:purple_metrics_lints/purple_metrics_lints.yaml
```