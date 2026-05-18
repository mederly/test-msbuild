# test-msbuild

Sample C# "Hello, World!" console app built with MSBuild.

## Build with MSBuild

```bash
dotnet msbuild HelloWorld.sln /t:Restore,Build /p:Configuration=Release
```

## Run locally

```bash
dotnet run --project src/HelloWorld/HelloWorld.csproj
```
