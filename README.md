1. Clone https://github.com/mpulukkinen/MauiApp2DoesNotStart
2. Run this command to build the project: dotnet publish .\MauiApp2.csproj -f net9.0-windows10.0.19041.0 -c Release /p:RuntimeIdentifierOverride=win-x86 -o ..\publish
3. Start MauiApp2.exe from publish folder
1. 
Comment <WindowsPackageType>MSIX</WindowsPackageType> to get the app running. Or change it to None
