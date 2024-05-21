# What

- UPM for https://github.com/Cysharp/R3 (alternative to using nuget)
- netstandard2.1


# How To Install Package

Add the lines below to `Packages/manifest.json`

for version `1.1.11`
```csharp
"com.pancake.r3": "https://github.com/pancake-llc/R3.git#1.1.11",
```

dependencies
```csharp
"com.pancake.unsafe": "https://github.com/pancake-llc/system-unsafe.git#6.0.0",
"com.pancake.threading.channels": "https://github.com/pancake-llc/system.threading.channels.git#8.0.0",
"com.pancake.component.annotations": "https://github.com/pancake-llc/system-componentmodel-annotations.git#5.0.0",
"com.pancake.bcl.timeprovider": "https://github.com/pancake-llc/microsoft-bcl-time-provider.git#8.0.0",
"com.pancake.bcl.asyncinterfaces": "https://github.com/pancake-llc/microsoft-bcl-async-interfaces.git#6.0.0",
```
