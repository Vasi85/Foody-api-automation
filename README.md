# Foody — Back-End API Automation

This project contains automated REST API tests for the "Foody" system.

The test suite validates the main API functionalities including authentication, food management and negative scenarios.

## Project Scope

The following scenarios are covered:

- User Authentication
- Create Food (valid data)
- Edit Food (PATCH request)
- Get All Foods
- Delete Food
- Create Food with missing required fields (400 validation)
- Edit non-existing Food (404 validation)
- Delete non-existing Food (400 validation)

## Tech Stack

- C#
- .NET
- NUnit
- RestSharp
- GitHub Actions (CI)

## Architecture

- RestClient base configuration
- JWT token authentication
- DTO classes for request and response handling
- Ordered test execution using [Order()]
- Reusable setup configuration

## Continuous Integration

A GitHub Actions workflow is configured to:

- Restore dependencies
- Build the solution
- Run all tests on push to main branch

## How to Run

1. Clone the repository
2. Open the solution in Visual Studio
3. Restore NuGet packages
4. Run tests from Test Explorer

---

Developed as part of Back-End Test Automation training.
