# AspNetCoreApiStarter UPDATED (3.1)
ASP.NET Core Web API with Identity, JWT authentication w/ refresh tokens.

# Setup
- <code>Web.Api.Infrastructure>**dotnet ef database update --context AppDbContext**</code>
- <code>Web.Api.Infrastructure>**dotnet ef database update --context AppIdentityDbContext**</code>

# Swagger Enabled
To explore and test the available APIs simply run the project and use the Swagger UI.

The available APIs include:
- POST `/api/accounts` - Creates a new user.
- POST `/api/auth/login` - Authenticates a user.
- POST `/api/auth/refreshtoken` - Refreshes expired access tokens.
- GET `/api/protected` - Protected controller for testing role-based authorization.


[Original Repository](https://github.com/mmacneil/AspNetCoreApiStarter)
 
