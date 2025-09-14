Introduction to xunit
ci/cd pipelines with jenkins , githubactions, devops, docker, kubernetes
hand on with SonarQube
Case Study:
    Library application need to be referenced in xunit application
    xunit application need to be referenced in API application

Case Study 1:
`               Through GitHubActions : 

Connection_string : "Server=tcp:githubcicdserver.database.windows.net,1433;Initial Catalog=GitHubCICDDB;Persist Security Info=False;
User ID=githubAdmin@githubcicdserver;Password=Kanuj@6583;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30"

Case Study 2:

1. Concept of Deployment Centre(Authenticate and Authorize b/w Azure Subscription) 
   and Deployment group(Own Agent IIS and Azure acts as a bridge).

2. CI/CD(Multistage YAML either separate the build and release) 
   service connection: CI/CD by service connection is best way to work.              


-> DotNet Core + GitHub = pipeline = Agent = release(Deployment) + VM or agent by Deployment group
-> Now eligible to deploys on IIS Server
-> Troubleshooting
