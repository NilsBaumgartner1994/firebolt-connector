# CI/CD-Configuration

## Used Pipelines

- SonarCloud
- Travis-CI
- Coveralls
- Fossa

### README.md
- Change all Badges to correct url

### SondarCloud
- Checks any Code-Smells and Code-Quality metrics
    - Activate account and connect with GitHub
        - https://sonarcloud.io/projects
    - Add the project
        - https://sonarcloud.io/projects/create
    - Add .github/workflows/build.yml to the repo
        - Check correct branch: master-->main

### Travis-CI
- Check GitHub integration
    - https://travis-ci.com/dashboard

#### Coveralls
- Checks the coverage tests
- Add the Repo
    - https://coveralls.io/repos/new

### Fossa
- Check the if any license problems are found
- Add the Repo
  - https://app.fossa.com/projects