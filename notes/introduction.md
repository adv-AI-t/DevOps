# Introduction to DevOps Fundamentals

## Index

1. [CI/CD](#cicd-pipeline)
2. [IaC](#infrastructure-as-code)
3. [Monitoring and Logging](#monitoring-and-logging)
4. [Containerization and Microservices](#containerization-and-microservices)
5. [Configuration management](#configuration-management)

## What is DevOps

Combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity.

- Dev - Develop code that needs to be pushed into production.
- Ops - Orchestrate the process of putting the updated code to production.

## Dev v/s Ops

### "it is working on my machine!" problem

- Developer and Operation team work separately
- Slow release cycles
- Manual processing of deployment, testing. Rollbacks are not automated.
- Environment mismatches
- Poor monitoring and feedback
- Blame game - no shared responsibility for software development

## DevOps lifecycle

![DevOps 7 'C's Cycle](https://cms-cdn.katalon.com/7cs_of_devops_lifecycle_09484f6808.png)

Responsibility of Dev team: PLAN - CODE - BUILD - TEST

Responsibility of Ops team: DEPLOY - OPERATE - MONITOR

## DevOps tools

- Version Control - Git, GitHub, GitTab
- CI/CD - GitHub Actions, Jenkins, GitLab CI/CD
- IaC (Infrastructure as Code) - Terraform, Ansible, CloudFormation
- Containers - Docker, Podman
- Orchestration - Kubernetes, OpenShift
- Monitoring - Promethus, Grafana, ELK stack (ElasticSearch, LogStash, Kibana)


Refer to learn tools: [DevOps Tools](https://github.com/techiescamp/devops-tools)

# CI/CD Pipeline

### Continuous Integration

It is the practice of regularly merging code changes from multiple developers. Tools like GitHub are used to continuously push the changes in the form of commits.

### Continuous Development

It means the code is always in a deployable state. Once changes are tested, they are approved for deployment.

CI/CD pipeline is a set of automated steps that take your code from development to deployment.

Code -> Built -> Test -> Release -> Deploy -> Monitor

![CI/CD Pipeline](https://zd-brightspot.s3.us-east-1.amazonaws.com/wp-content/uploads/2022/04/01113503/74-1.png)


# Infrastructure as Code

Settinf up servers, databases and networking using code instead of clicking buttons manually.

Basically, we don't have to use the AWS GUI to provision resources. Instead, write a code to do the same.

This makes setups faster, consistent, and repeatable - perfect for large team and cloud environments.

# Monitoring and Logging

Montoring shows the current health of the application.
We can use Kibana dashboards for montoring.

Logging keeps on recording the activity, what is happening begind the scenes, errors, usage and behaviour.
We can use Logstash for logging.

# Containerization and Microservices

Containerization - Pachaging the app and all the dependencies into a neat, portable box, called container.

Microservices - Break a big appliacation into smakker, independent services, each focusing one specific task.

# Configuration Management

Keeping the environment consistant. Write code that sets up servers, databases and settings - no need for manual configuration everytime we spin up a new instance, or port it somewhere else.

