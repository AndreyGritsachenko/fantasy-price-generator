\# Domain



\## Product



Represents a tradeable item.



Properties:



\- Id

\- Name

\- Description

\- CategoryId

\- BasePrice

\- Tags



\## Category



Represents a group of products.



Properties:



\- Id

\- Name

\- ParentCategoryId



Categories may be hierarchical.



\## PriceModifier



Represents a factor affecting product price.



Examples:



\- environment modifier;

\- merchant attitude modifier;

\- scarcity modifier;

\- location modifier.



\## Price calculation



Initial concept:



FinalPrice =

BasePrice

× EnvironmentModifier

× MerchantAttitudeModifier

× AdditionalModifiers



The calculation model should be extensible.



\## Important rule



Price calculation logic belongs to the domain and must not depend on persistence or UI.

