\# Project Instructions



\## Project



This repository contains Fantasy Price Generator.



The goal is to build reusable business logic that can later be consumed by:



\- desktop application;

\- web application;

\- mobile application.



\## Documentation



Before implementing features, read:



\- docs/PRODUCT.md

\- docs/ARCHITECTURE.md

\- docs/DOMAIN.md

\- docs/plans/phase-1.md



Treat these files as project requirements.



\## Current phase



Only Phase 1 is currently being implemented.



Do not create:



\- WPF applications;

\- ASP.NET applications;

\- MAUI applications;

\- frontend code.



Unless explicitly requested.



\## Technology



Use:



\- .NET 10

\- C#

\- nullable reference types

\- implicit usings



\## Architecture



Keep business logic independent from:



\- UI;

\- persistence;

\- frameworks.



Core must not reference Infrastructure.



Do not introduce unnecessary frameworks or architectural patterns.



Do not add:



\- MediatR

\- AutoMapper

\- Entity Framework Core

\- CQRS frameworks



unless explicitly requested.



\## Development workflow



For non-trivial tasks:



1\. Inspect the existing repository.

2\. Read relevant documentation.

3\. Create a short implementation plan.

4\. Implement the requested change.

5\. Build the solution.

6\. Run tests.

7\. Fix failures.

8\. Review the resulting diff.



Do not consider the task complete while build or tests are failing.



\## Tests



Business rules should have unit tests.



Before completing a task run:



dotnet build



dotnet test



\## Git



Before completing a task:



\- inspect git status;

\- inspect git diff;

\- avoid unrelated changes.



Do not commit changes unless explicitly requested.

