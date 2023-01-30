---
date: 2022-11-22T12:46:47+02:00
weight: 1
version:
---

#### Scraper

- {{% tag added %}} Provide custom formatting for emitting metrics using StatsD sink in Geneva format
- {{% tag added %}} Provide capability to read Azure AD service principal secret from a file
- {{% tag added %}} Provide Azure Log Analytics scraper ([docs](https://docs.promitor.io/v2.9/scraping/providers/log-analytics/)
| [#2132](https://github.com/tomkerkhove/promitor/pull/2132))
- {{% tag fixed %}} Fixed a bug where startup throws scheduling exception due to metric misconfiguration
- {{% tag added %}} Provide capability to read Azure ClientId for UserAssignedManagedIdentity from environment to support Azure Workload Identity

#### Resource Discovery

- {{% tag added %}} Provide path to read app secret key from file
- {{% tag added %}} Provide capability to read Azure ClientId for UserAssignedManagedIdentity from environment to support Azure Workload Identity

