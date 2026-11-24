# DPC6 Desktop (WPF, .NET 10, Windows x64)

    dotnet build -c Release
    dotnet test -c Release
    dotnet run --project DPC6Desktop -c Release
    dotnet publish DPC6Desktop\DPC6Desktop.csproj -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true

Passwords: minimum 12 characters, exact (never trimmed). Text screens update live (key derivation takes a moment).
Format and key schedule: docs/CONTAINER_FORMAT.md. Not independently audited.
