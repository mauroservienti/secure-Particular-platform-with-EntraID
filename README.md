# secure-Particular-platform-with-EntraID

Shows how to secure a container-based installation of the Particular Platform using a reverse proxy and Microsoft Entra ID

To run the sample:

- Using the Azure Portal, create a new Microsoft EntraID Application
- Copy the "TenantId", "ClientId", and "ClientSecret"
- Update the `appsettings.json` file with the above values
- run the `docker-compose.yml` file

When trying to access ServicePulse, the browser will redirect to the Azure Portal for authentication.
