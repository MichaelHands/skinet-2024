To apply/remove migration use these commands from the terminal "../skinet"

dotnet ef migrations add InitialCreate -s API -p Infrastructure

dotnet ef migrations remove -s API -p Infrastructure

dotnet ef database update -s API -p Infrastructure

 dotnet ef database drop -s API -p Infrastructure