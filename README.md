# .NET-Web-Application # Microsoft Azure DevOps # CI/CD Pipeline

* Setup Instructions
* Clone the repository:
git clone https://github.com/VamsiKrishnaYadavLoya/.NET-Web-Application.git
cd .NET-Web-Application

* Build the Solution:
dotnet build
* Run the Application:
dotnet run --project VamsiWebApplication
* Run Unit Tests:
dotnet test

The project includes a CI/CD pipeline defined in the azure-pipelines.yml file, which automates the following steps:

Build Stage
* Restore NuGet Packages: Ensures all dependencies are available.
* Build Solution: Compiles the application.
* Run Unit Tests: Executes unit tests to validate code quality.
* Publish Artifacts: Packages the application and prepares for deployment.
Deployment Stages
Staging Environment
* Deploy to Staging: Deploys the built application to the staging environment.
* Verification: Ensures the application is running correctly in staging.
Production Environment
* Deploy to Production: Deploys the application to the production environment if staging deployment succeeds.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
