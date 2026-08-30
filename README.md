[![](https://img.shields.io/nuget/v/soenneker.extensions.spans.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.extensions.spans/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.extensions.spans/publish-package.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.extensions.spans/actions/workflows/publish-package.yml)
[![](https://img.shields.io/nuget/dt/soenneker.extensions.spans.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.extensions.spans/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.extensions.spans/codeql.yml?label=CodeQL&style=for-the-badge)](https://github.com/soenneker/soenneker.extensions.spans/actions/workflows/codeql.yml)

# ![](https://user-images.githubusercontent.com/4441470/224455560-91ed3ee7-f510-4041-a8d2-3fc093025112.png) Soenneker.Extensions.Spans
The namespace anchor for Soenneker's type-specific `Span<T>` extension packages.

## Installation

```bash
dotnet add package Soenneker.Extensions.Spans
```

## Usage

This package exposes the empty `SpanExtension` type and no extension methods. Install the package that matches the span element type and operation you need, such as:

- [`Soenneker.Extensions.Spans.Bytes`](https://www.nuget.org/packages/Soenneker.Extensions.Spans.Bytes/) for mutable byte spans.
- [`Soenneker.Extensions.Spans.Chars`](https://www.nuget.org/packages/Soenneker.Extensions.Spans.Chars/) for mutable character spans.
- [`Soenneker.Extensions.Spans.Generics`](https://www.nuget.org/packages/Soenneker.Extensions.Spans.Generics/) for generic span helpers.

Installing this package by itself does not add runtime behavior.
