# DevOps Brief

## Objective

To develop a system for ingesting and storing National Grid consumption data every hour and providing access to the data through a public API. We expect the API to increase in load linearly over the next three years

## Requirements

- Infrastructure must be managed by IaC (In house we use Terraform)
- You must use the https://api.carbonintensity.org.uk API to ingest the data
  - Example usage of the above API - https://api.carbonintensity.org.uk/intensity/2023-01-01T10:00/2023-01-01T11:00
- You can use any programming language or framework for the API (In house we use Typescript and NodeJS)

## Deliverables

- A system for ingesting National Grid consumption data every hour
- A persistent data store for storing the ingested data
- A public API for accessing the stored data
- A deployed API and infrastructure
- Example usage of the API using CURL or Postman

## Bonus points

- Implement monitoring and logging capabilities
- CI/CD pipeline that deploys the infra and code
- Documentation on how to use the API
