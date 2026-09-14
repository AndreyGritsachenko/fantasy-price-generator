\# Architecture



The system is implemented as reusable .NET libraries.



\## Projects



\### FantasyPriceGenerator.Core



Contains:



\- domain entities;

\- value objects;

\- price calculation rules;

\- domain services.



Must not depend on infrastructure or UI.



\### FantasyPriceGenerator.Application



Contains:



\- application services;

\- use cases;

\- repository abstractions;

\- product search;

\- category operations.



Depends on Core.



\### FantasyPriceGenerator.Infrastructure



Contains implementations of persistence and external integrations.



Depends on Application and Core.



\## Dependency direction



Core

↑

Application

↑

Infrastructure



Core must not reference Application or Infrastructure.



\## UI



UI applications will be implemented later.



Possible future consumers:



\- WPF;

\- ASP.NET Core;

\- mobile application.



No UI project should be created during Phase 1.

