---
name: Azure Recovery Services
x-slug: azure-recovery-services
description: Learn how to use Site Recovery for business continuity and disaster recovery
  strategy for private clouds. Tutorials and other documentation show you how to plan,
  deploy, and manage the orchestration of replicating on-premises physical servers
  and virtual machines to the cloud or to a secondary datacenter.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Entities
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/azure-recovery-services/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Recovery Service API Registered Identities Delete
  x-api-slug: azure-recovery-service-api
  description: Unregisters the given container from your Recovery Services vault.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
  humanURL: https://azure.microsoft.com/en-us/services/site-recovery/
  baseURL: ://management.azure.com////Subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.RecoveryServices/vaults/{vaultName}/registeredIdentities/{identityName}
  tags: Registered Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/azure-recovery-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnameregisteredidentitiesidentityname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/azure-recovery-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnameregisteredidentitiesidentityname-delete-openapi.md
- name: Azure Recovery Service API
  x-api-slug: azure-recovery-service-api
  description: Learn how to use Site Recovery for business continuity and disaster
    recovery strategy for private clouds. Tutorials and other documentation show you
    how to plan, deploy, and manage the orchestration of replicating on-premises physical
    servers and virtual machines to the cloud or to a secondary datacenter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
  humanURL: https://azure.microsoft.com/en-us/services/site-recovery/
  baseURL: ://management.azure.com//
  tags: Entities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/azure-recovery-services/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/site-recovery/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/site-recovery/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/site-recovery/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/site-recovery/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---