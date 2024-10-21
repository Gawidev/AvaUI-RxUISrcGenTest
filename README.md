Reproducible bug test.
When attempting to build a project containing ReactiveUI.SourceGenerators with preview .Net9 sdk, the process stalls and never completes.
This project is comprised of the AvaloniaUI-MVVM template using Avalonia.ReactiveUI, and the aforementionned ReactiveUI.SourceGenerators.
All that should be required to reproduce the issue is to ensure usage of the preview sdk.
