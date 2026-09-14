\# Phase 1 — Core Library



\## Goal



Create the reusable backend/business library for the Fantasy Price Generator.



No UI should be implemented.



\## Milestone 1



Create solution structure:



\- FantasyPriceGenerator.Core

\- FantasyPriceGenerator.Application

\- FantasyPriceGenerator.Infrastructure

\- FantasyPriceGenerator.Core.Tests

\- FantasyPriceGenerator.Application.Tests



Target:



.NET 10



\## Milestone 2



Implement initial domain model:



\- Product

\- Category

\- Price

\- PriceModifier



\## Milestone 3



Implement product catalogue operations:



\- Add product

\- Update product

\- Delete product

\- Get product

\- Search products

\- Get products by category



\## Milestone 4



Implement price calculation engine.



Initial modifiers:



\- Environment

\- Merchant attitude



\## Milestone 5



Add simple replaceable persistence.



Initial persistence may be file-based.



Persistence must not leak into Core.

