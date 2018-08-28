---
name: IBM Financial Crimes Insight for Insurance
x-slug: ibm-financial-crimes-insight-for-insurance
description: IBM&reg; Financial Crimes Insight&reg; for Insurance V3.0, formerly known
  as IBM Counter Fraud Management for Insurance, is now being offered as a cloud service
  offering. It helps organizations analyze data to determine the fraud risk of claims,
  medical providers, and other business entities, manage the full investigation lifecycle,
  and report on outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
x-kinRank: "7"
x-alexaRank: ""
tags: Entities
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/apis.md
specificationVersion: "0.14"
apis:
- name: Financial Crimes Insight for Insurance public REST APIs - Get a list of resolved
    objects from resolved entities for a given object.
  x-api-slug: ibmfciplatformfactentitymatch-get
  description: Get a list of resolved objects from resolved entities for a given object.
    Using the provided object ID, produce a list of all objects of the same business
    object type that have been determined to be 'matches'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentitymatch-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - This method is used
    to retrieve the set of explicitly related parties and implicitly related entities
    for the supplied externally sourced reference party
  x-api-slug: ibmfciplatformfactentityrelatedpartiessystemidremotereference-get
  description: |-
    A data source must be configured in the appropriate server.xml to use ISII. Ensure that the following has been included:

    &lt;dataSource beginTranForResultSetScrollingAPIs="false" id="ISIIDB" isolationLevel="TRANSACTION_READ_COMMITTED" jndiName="jdbc/isii"&gt;

    &lt;jdbcDriver javax.sql.DataSource="com.ibm.db2.jcc.DB2XADataSource" libraryRef="DB2_LIB"/&gt;

    &lt;properties.db2.jcc databaseName="ISII" password="${isii_db_pass}" portNumber="${isii_db_port}" serverName="${isii_host}" user="${isii_db_user}"/&gt;

    &lt;connectionManager connectionTimeout="60s" maxIdleTime="3m" maxPoolSize="200" minPoolSize="0"/&gt;

    &lt;/dataSource&gt;

    Where password, portNumber, serverName, and user values are replaced with the appropriate properties or environment variables for your configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityrelatedpartiessystemidremotereference-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityrelatedpartiessystemidremotereference-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Retrieve set of
    identities considered to be the same entity
  x-api-slug: ibmfciplatformfactentityremote-system-idexternal-remote-reference-get
  description: This method is used to retrieve the set of individuals (or organizations)
    that are considered the same as the provided party reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityremote-system-idexternal-remote-reference-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Get the data for
    the resolved entity id.
  x-api-slug: ibmfciplatformfactentityid-get
  description: Using the provided party id, obtain the entity id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityid-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Get a list of resolved
    objects from resolved entities for a given object.
  x-api-slug: ibmfciplatformfactentitymatch-get
  description: Get a list of resolved objects from resolved entities for a given object.
    Using the provided object ID, produce a list of all objects of the same business
    object type that have been determined to be 'matches'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentitymatch-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - This method is used
    to retrieve the set of explicitly related parties and implicitly related entities
    for the supplied externally sourced reference party
  x-api-slug: ibmfciplatformfactentityrelatedpartiessystemidremotereference-get
  description: |-
    A data source must be configured in the appropriate server.xml to use ISII. Ensure that the following has been included:

    &lt;dataSource beginTranForResultSetScrollingAPIs="false" id="ISIIDB" isolationLevel="TRANSACTION_READ_COMMITTED" jndiName="jdbc/isii"&gt;

    &lt;jdbcDriver javax.sql.DataSource="com.ibm.db2.jcc.DB2XADataSource" libraryRef="DB2_LIB"/&gt;

    &lt;properties.db2.jcc databaseName="ISII" password="${isii_db_pass}" portNumber="${isii_db_port}" serverName="${isii_host}" user="${isii_db_user}"/&gt;

    &lt;connectionManager connectionTimeout="60s" maxIdleTime="3m" maxPoolSize="200" minPoolSize="0"/&gt;

    &lt;/dataSource&gt;

    Where password, portNumber, serverName, and user values are replaced with the appropriate properties or environment variables for your configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityrelatedpartiessystemidremotereference-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityrelatedpartiessystemidremotereference-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Retrieve set of
    identities considered to be the same entity
  x-api-slug: ibmfciplatformfactentityremote-system-idexternal-remote-reference-get
  description: This method is used to retrieve the set of individuals (or organizations)
    that are considered the same as the provided party reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityremote-system-idexternal-remote-reference-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Get the data for
    the resolved entity id.
  x-api-slug: ibmfciplatformfactentityid-get
  description: Using the provided party id, obtain the entity id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityid-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Get a list of resolved
    objects from resolved entities for a given object.
  x-api-slug: ibmfciplatformfactentitymatch-get
  description: Get a list of resolved objects from resolved entities for a given object.
    Using the provided object ID, produce a list of all objects of the same business
    object type that have been determined to be 'matches'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentitymatch-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - This method is used
    to retrieve the set of explicitly related parties and implicitly related entities
    for the supplied externally sourced reference party
  x-api-slug: ibmfciplatformfactentityrelatedpartiessystemidremotereference-get
  description: |-
    A data source must be configured in the appropriate server.xml to use ISII. Ensure that the following has been included:

    &lt;dataSource beginTranForResultSetScrollingAPIs="false" id="ISIIDB" isolationLevel="TRANSACTION_READ_COMMITTED" jndiName="jdbc/isii"&gt;

    &lt;jdbcDriver javax.sql.DataSource="com.ibm.db2.jcc.DB2XADataSource" libraryRef="DB2_LIB"/&gt;

    &lt;properties.db2.jcc databaseName="ISII" password="${isii_db_pass}" portNumber="${isii_db_port}" serverName="${isii_host}" user="${isii_db_user}"/&gt;

    &lt;connectionManager connectionTimeout="60s" maxIdleTime="3m" maxPoolSize="200" minPoolSize="0"/&gt;

    &lt;/dataSource&gt;

    Where password, portNumber, serverName, and user values are replaced with the appropriate properties or environment variables for your configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityrelatedpartiessystemidremotereference-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityrelatedpartiessystemidremotereference-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Get the data for
    the resolved entity id.
  x-api-slug: ibmfciplatformfactentityid-get
  description: Using the provided party id, obtain the entity id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityid-get-openapi.md
- name: Financial Crimes Insight for Insurance public REST APIs - Retrieve set of
    identities considered to be the same entity
  x-api-slug: ibmfciplatformfactentityremote-system-idexternal-remote-reference-get
  description: This method is used to retrieve the set of individuals (or organizations)
    that are considered the same as the provided party reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/WFS-Counter-Fraud-Technical-Level-3.png
  humanURL: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
  baseURL: https://fcihost.ibm.com:9443//
  tags: Policing, Financial, Insurance, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/ibm-financial-crimes-insight-for-insurance/ibmfciplatformfactentityremote-system-idexternal-remote-reference-get-openapi.md
x-common:
- type: x-openapi
  url: https://www.ibm.com/support/knowledgecenter/SSC2HF_3.0.0/api/fcii-insurance-v3.0.0.yaml?origin=swagger-ui
- type: x-pricing
  url: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN#echargex
- type: x-website
  url: https://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=AN&subtype=CA&htmlfid=897/ENUS218-305&appname=USN
- type: x-api-gallery
  url: http://ibm.cloud.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ibm.financial.crimes.insight.for.insurance.stack.network
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---