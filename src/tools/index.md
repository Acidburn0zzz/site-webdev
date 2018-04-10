---
title: Dart Tools for the Web
short-title: Tools
description: The tools that support web development using Dart.
show_breadcrumbs: false
---

This page lists specialized tools for developing web apps.
For information about general tools for Dart apps, see
[Dart Tools.]({{site.dartlang}}/tools)

## Recommended IDE {#ides}

{% include webstorm-not-ready.md %}

If you don't already have a favorite IDE,
we recommend WebStorm, which comes with Dart support.

<a href="/tools/webstorm">
<img src="{% asset_path 'webstorm.svg' %}" alt="WebStorm icon" width="48"><br>
<b>WebStorm</b>
</a>

See [Dart Tools]({{site.dartlang}}/tools) for a list of other IDEs.

## SDK

Although [DartPad][]{: target="_blank"} is a great way to learn how to write a
simple web app, once you're ready to develop real apps, you need to
[install the Dart SDK.](/tools/sdk)

## Command-line tools

In addition to the [other Dart tools]({{site.dartlang}}/tools)
included in the SDK, the following tools
offer specialized support for web programming.

[dart2js](/tools/dart2js)
: The original Dart-to-JavaScript compiler, with tree shaking

[dartdevc](/tools/dartdevc)
: The Dart dev compiler, a modular Dart-to-JavaScript compiler

[build_runner](/tools/build_runner)
: A package for building and serving web apps

[DartPad]: {{site.custom.dartpad.direct-link}}
