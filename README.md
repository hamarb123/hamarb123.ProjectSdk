# hamarb123.ProjectSdk

The core custom project sdk used by many of hamarb123's projects.

NuGet link:
[![NuGet version (hamarb123.ProjectSdk)](https://img.shields.io/nuget/v/hamarb123.ProjectSdk.svg?style=flat-square)](https://www.nuget.org/packages/hamarb123.ProjectSdk/)

# hamarb123.ProjectSdk versions known to work:

- 1.0.45 - Initial public release
- 1.0.46 - C# 13, add `CS0197` to `NoWarn` on applicable runtimes, add `<Features>strict</Features>`, remove legacy code, and set CsWinRT generation mode to opt-in by default (not working)
- 1.0.47 - Upgrade `hamarb123.Analyzers` to `1.2.1`, add `CS8500` to `NoWarn`, fix `CsWinRTAotOptimizerEnabled` setting
- 1.0.48 - Upgrade `hamarb123.Analyzers` to `1.2.2`, and C# version to 14
- 1.0.49 - Upgrade `hamarb123.Analyzers` to `1.3.3`, and support non-git projects with default configuration
- 1.0.50 - Upgrade `hamarb123.Analyzers` to `1.3.4`

# Build Instructions

Run `nuget pack hamarb123.ProjectSdk.nuspec` in `hamarb123.ProjectSdk`.
