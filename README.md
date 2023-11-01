# Introduction
A course on DevOps from Udemy

## Models in SDLC
- waterfall
- agile
- spiral
- big bang

### Waterfall Model
1. Requirement
2. Design
3. Implementation
4. Testing
5. Maintenance

#### Waterfall Disadvanatges
- cannot accomodate chaning requirements
- may take month to complete

### Agile SDLC
- each iteration 2-4 weeks
- demo given after every iteration

## DevOps 
- Development (AGILE): regular and quick changes
- Operations (ITIL): stability

## Automation application
- code build
- code testing
- software testing
- infrastructure changes
- deployments

## DevOps Lifecycle
- code: developers commits code
- deployable software: artifact
- code test: unit and integration test
- code analysis: vulnerability, best practices
- delivery: deploy changes to staging
- DB changes: operation changes
- software testing: QA/functional, load, performance tests
- deploy to prod
- go live: user traffic diverted to new changes
- user approval/feedback
- continous monitoring

## Continuous Integration (CI)
- version control system: centralized code repository
- artifact repo stored in
- software in test environment is loaded into build server
    * built
    * tested
    * evaluated
- when code is built in pipeline, stored as artifact repository in formats:
    * WAR/JAR
    * DLL/EXE/MSI
    * ZIP/TAR
- code can be merged into repository but NOT integrated, can lead to many bugs, errors, deploy problems
- SOLUTION: for every commit build and test
    * defects caught as soon as code is merged
    * goal is to detect defects at early stages

## Tools for CI
- IDEs for coding
    * ecplise
    * visual studio
    * atom
    * pycharm
- version control
    * git
    * svn
    * tfs
    * perforce
- build tools (based on programming language)
    * maven, ant, gradle
    * msbuild, visual build
    * IBM urban code
    * make
    * grunt
- software repository to store artifacts
    * sonatype nexus
    * jfrog artifactory
    * archiva
    * cloudsmith package
    * grunt
- CI tools
    * jenkins
    * circleci
    * teamcity
    * bamboo ci
    * cruise control

## Continuous Delivery (CD)
- operations and development solve issues with code deployment
- code deployment entails:
    * server provisioning
    * dependencies
    * conf changes
    * network
    * artifact deploy

## Automation Tools for DevOps SDLC
- system: ansible, puppet, chef
- cloud infrastructure: terraform, cformation
- CI/CD automation: jenkins, octopus deploy
- helm charts
- code deploy
- Test Automation
    * functional
    * load
    * performance
    * db
    * security
    