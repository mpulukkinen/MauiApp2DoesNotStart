Publish: dotnet publish .\MauiApp2.csproj -f net9.0-windows10.0.19041.0 -c Release /p:RuntimeIdentifierOverride=win-x86 -o publish
Comment <WindowsPackageType>MSIX</WindowsPackageType> to get the app running
