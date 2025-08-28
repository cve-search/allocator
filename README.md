**ALPHA DRAFT**

# shvi-allocation

Software and procedure supporting the allocation of SHVI number (software and hardware vulnerability identifier) via a community portal.

This software was a precursor of [vulnerability-lookup](https://vulnerability-lookup.org) and the [GCVE](https://gcve.eu/) implementation and it's now archived.

# Procedure of Allocation

Anyone can request a SHVI identifier as long as they register to the interface and validate their email address.

The request of an identifier is bound to a time limit publication where the requester need to renew the expiration period.

The requester must enter a title, a reference URL, CVSS when the security vulnerability is published. The information must be present for the publication.

Additional fields like description, CPE and cross-references values should be enter by the requester. The requester can also
add his/her PGP key in order to verify the signature of security vulnerability documents.

## Format of SHVI identifier

~~~~
SHVI-2016-<N>
~~~~

where N is an incrementing numerical value.

# FAQ

## Why don't you require to add details about the vulnerability before publication?

shvi-allocation is an identifier allocation system supporting security researchers to uniquely identify software
and hardware vulnerabilities. The shvi-allocation system doesn't store any information about the security vulnerability
before that the requester decided to publish the vulnerability.
