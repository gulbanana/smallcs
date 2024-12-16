Demo of a C# program configured to compile to smallish native binaries. You'll need [the .NET SDK](https://dotnet.microsoft.com/en-us/download).

To compile on windows, run:
```
dotnet publish -c Release -r win-x64
```
Or on Linux (glibc distributions):
```
dotnet publish -c Release -r linux-x64
```