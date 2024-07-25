
## To list global tool
dotnet tool list -g

## To install dotnet ef
dotnet tool install dotnet-ef -g

## To update dotnet tool
dotnet tool update dotnet-ef -g

## To execute a new migration
dotnet ef migrations add "InitialCreate" -o Data/Migrations

## To execute migration update
dotnet ef database update

### Run docker
docker compose up -d

### Drop database
dotnet ef database drop
