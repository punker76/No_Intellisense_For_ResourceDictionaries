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
