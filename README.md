# No_Intellisense_For_ResourceDictionaries
Demo for Intellisense bug with targeting .Net Core 3.0 and .Net 4.x

```
<Project Sdk="Microsoft.NET.Sdk.WindowsDesktop">

  <PropertyGroup>
    <OutputType>WinExe</OutputType>
    <!-- with more then one framework, the intellisense for resource dictionaries doesn't work -->
    <TargetFrameworks>net47;netcoreapp3.0</TargetFrameworks>
    <UseWPF>true</UseWPF>
  </PropertyGroup>

</Project>
```

### Environment
```
.Net 3.0.100-preview-010157
Microsoft Visual Studio Enterprise 2019 Preview
Version 16.0.0 Preview 2.0
VisualStudio.16.Preview/16.0.0-pre.2.0+28522.59
```
