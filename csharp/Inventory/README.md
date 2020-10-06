## Generate a certificate

From `Inventory.API` folder execute:

```
dotnet dev-certs https -v -ep ./cert-aspnetcore.pfx -p 1234
```

This will generate a certificate with the password `1234`

## Build

From `csharp` folder: 

```
docker-compose build
```

## Run

From `csharp` folder:

```
docker-compose up
```

Then, navigate to `http://localhost`