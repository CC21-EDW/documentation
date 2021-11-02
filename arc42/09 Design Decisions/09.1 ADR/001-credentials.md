# We use a central vault to store all credentials.

## Description
As we have several systems, especially used during development time, that are secured, 
we need a centralized vault that can be used to store all credentials. 

## Rationale
* we do not store credentials somewhere as plain text
* we have all relevant credentials stored in a central location.

## Consequences
* we do not use different stores, files etc.
* new team members can be onboarded easily

##References
* [tbd](link to vault impl.)