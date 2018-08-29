---
name: Azure Data Lake Analytics
x-slug: azure-data-lake-analytics
description: The Data Lake analytics service is a new distributed analytics service
  built on Apache YARN that dynamically scales so you can focus on your business goals,
  not on distributed infrastructure. Instead of deploying, configuring and tuning
  hardware, you write queries to transform your data and extract valuable insights.
  The analytics service can handle jobs of any scale instantly by simply setting the
  dial for how much power you need. You only pay for your job when it is running making
  it cost-effective. The analytics service supports Azure Active Directory letting
  you simply manage access and roles, integrated with your on-premises identity system.
  It also includes U-SQL, a language that unifies the benefits of SQL with the expressive
  power of user code. U-SQL&rsquo;s scalable distributed runtime enables you to efficiently
  analyze data in the store and across SQL Servers in Azure, Azure SQL Database and
  Azure SQL Data Warehouse.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Data Lake Analytics
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: DataLakeAnalyticsJobManagementClient - Firewall Rules Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-put
  description: Creates or updates the specified firewall rule. During update, the
    firewall rule with the specified name will be replaced with this new firewall
    rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Firewall Rules Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-patch
  description: Updates the specified firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-patch-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Firewall Rules Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-delete
  description: Deletes the specified firewall rule from the specified Data Lake Analytics
    account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-delete-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Firewall Rules Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-get
  description: Gets the specified Data Lake Analytics firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Firewall Rules List By Account
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrules-get
  description: Lists the Data Lake Analytics firewall rules within the specified Data
    Lake Analytics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrules-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-get
  description: Gets the specified Azure Storage account linked to the given Data Lake
    Analytics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-delete
  description: Updates the specified Data Lake Analytics account to remove an Azure
    Storage account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-delete-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-patch
  description: Updates the Data Lake Analytics account to replace Azure Storage blob
    account details, such as the access key and/or suffix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-patch-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts Add
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-put
  description: Updates the specified Data Lake Analytics account to add an Azure Storage
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts Get Storage Container
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainername-get
  description: Gets the specified Azure Storage container associated with the given
    Data Lake Analytics and Azure Storage accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainername-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts List Storage Containers
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainers-get
  description: Lists the Azure Storage containers, if any, associated with the specified
    Data Lake Analytics and Azure Storage account combination. The response includes
    a link to the next page of results, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainers-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts List Sas Tokens
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainernamelistsastokens-post
  description: Gets the SAS token associated with the specified Data Lake Analytics
    and Azure Storage account and container combination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainernamelistsastokens-post-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Data Lake Store Accounts Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get
  description: Gets the specified Data Lake Store account details in the specified
    Data Lake Analytics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Data Lake Store Accounts Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete
  description: Updates the Data Lake Analytics account specified to remove the specified
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Data Lake Store Accounts Add
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-put
  description: Updates the specified Data Lake Analytics account to include the additional
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Storage Accounts List By Account
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccounts-get
  description: Gets the first page of Azure Storage accounts, if any, linked to the
    specified Data Lake Analytics account. The response includes a link to the next
    page, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccounts-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Data Lake Store Accounts List By Account
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get
  description: Gets the first page of Data Lake Store accounts linked to the specified
    Data Lake Analytics account. The response includes a link to the next page, if
    any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Account List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccounts-get
  description: Gets the first page of Data Lake Analytics accounts, if any, within
    a specific resource group. This includes a link to the next page, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccounts-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Account List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-datalakeanalyticsaccounts-get
  description: Gets the first page of Data Lake Analytics accounts, if any, within
    the current subscription. This includes a link to the next page, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidprovidersmicrosoft-datalakeanalyticsaccounts-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Account Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-get
  description: Gets details of the specified Data Lake Analytics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Account Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-delete
  description: Begins the delete delete process for the Data Lake Analytics account
    object specified by the account name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-delete-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Account Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-put
  description: Creates the specified Data Lake Analytics account. This supplies the
    user with computation services for Data Lake Analytics workloads
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Account Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-patch
  description: Updates the Data Lake Analytics account object specified by the accountName
    with the contents of the account object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-patch-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Create Secret
  x-api-slug: catalogusqldatabasesdatabasenamesecretssecretname-put
  description: Creates the specified secret for use with external data sources in
    the specified database. This is deprecated and will be removed in the next release.
    Please use CreateCredential instead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamesecretssecretname-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Update Secret
  x-api-slug: catalogusqldatabasesdatabasenamesecretssecretname-patch
  description: Modifies the specified secret for use with external data sources in
    the specified database. This is deprecated and will be removed in the next release.
    Please use UpdateCredential instead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamesecretssecretname-patch-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Secret
  x-api-slug: catalogusqldatabasesdatabasenamesecretssecretname-get
  description: Gets the specified secret in the specified database. This is deprecated
    and will be removed in the next release. Please use GetCredential instead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamesecretssecretname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Delete Secret
  x-api-slug: catalogusqldatabasesdatabasenamesecretssecretname-delete
  description: Deletes the specified secret in the specified database. This is deprecated
    and will be removed in the next release. Please use DeleteCredential instead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamesecretssecretname-delete-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Delete All Secrets
  x-api-slug: catalogusqldatabasesdatabasenamesecrets-delete
  description: Deletes all secrets in the specified database. This is deprecated and
    will be removed in the next release. In the future, please only drop individual
    credentials using DeleteCredential
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamesecrets-delete-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Create Credential
  x-api-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-put
  description: Creates the specified credential for use with external data sources
    in the specified database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamecredentialscredentialname-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Update Credential
  x-api-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-patch
  description: Modifies the specified credential for use with external data sources
    in the specified database
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamecredentialscredentialname-patch-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Credential
  x-api-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-get
  description: Retrieves the specified credential from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamecredentialscredentialname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Delete Credential
  x-api-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-post
  description: Deletes the specified credential in the specified database
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamecredentialscredentialname-post-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Credentials
  x-api-slug: catalogusqldatabasesdatabasenamecredentials-get
  description: Retrieves the list of credentials from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamecredentials-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get External Data Source
  x-api-slug: catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get
  description: Retrieves the specified external data source from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List External Data Sources
  x-api-slug: catalogusqldatabasesdatabasenameexternaldatasources-get
  description: Retrieves the list of external data sources from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasources-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Procedure
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanameproceduresprocedurename-get
  description: Retrieves the specified procedure from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanameproceduresprocedurename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Procedures
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanameprocedures-get
  description: Retrieves the list of procedures from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanameprocedures-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Table
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablename-get
  description: Retrieves the specified table from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablestablename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Tables
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametables-get
  description: Retrieves the list of tables from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametables-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Statistics By Database
    And Schema
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanamestatistics-get
  description: Retrieves the list of all table statistics within the specified schema
    from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanamestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanamestatistics-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Table Type
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametabletypestabletypename-get
  description: Retrieves the specified table type from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametabletypestabletypename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Types
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametabletypes-get
  description: Retrieves the list of table types from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametabletypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametabletypes-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Package
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanamepackagespackagename-get
  description: Retrieves the specified package from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanamepackagespackagename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Packages
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanamepackages-get
  description: Retrieves the list of packages from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanamepackages-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get View
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanameviewsviewname-get
  description: Retrieves the specified view from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanameviewsviewname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Views
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanameviews-get
  description: Retrieves the list of views from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanameviews-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Table Statistic
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamestatisticsstatisticsname-get
  description: Retrieves the specified table statistics from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablestablenamestatisticsstatisticsname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Statistics
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamestatistics-get
  description: Retrieves the list of table statistics from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablestablenamestatistics-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Table Partition
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamepartitionspartitionname-get
  description: Retrieves the specified table partition from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablestablenamepartitionspartitionname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Partitions
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamepartitions-get
  description: Retrieves the list of table partitions from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablestablenamepartitions-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Types
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametypes-get
  description: Retrieves the list of types within the specified database and schema
    from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametypes-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Table Valued Function
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctionstablevaluedfunctionname-get
  description: Retrieves the specified table valued function from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctionstablevaluedfunctionname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Valued Functions
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get
  description: Retrieves the list of table valued functions from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Assembly
  x-api-slug: catalogusqldatabasesdatabasenameassembliesassemblyname-get
  description: Retrieves the specified assembly from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameassembliesassemblyname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Assemblies
  x-api-slug: catalogusqldatabasesdatabasenameassemblies-get
  description: Retrieves the list of assemblies from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameassemblies-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Schema
  x-api-slug: catalogusqldatabasesdatabasenameschemasschemaname-get
  description: Retrieves the specified schema from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemaname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemaname-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Schemas
  x-api-slug: catalogusqldatabasesdatabasenameschemas-get
  description: Retrieves the list of schemas from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemas-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemas-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Statistics By Database
  x-api-slug: catalogusqldatabasesdatabasenamestatistics-get
  description: Retrieves the list of all statistics in a database from the Data Lake
    Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamestatistics-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Tables By Database
  x-api-slug: catalogusqldatabasesdatabasenametables-get
  description: Retrieves the list of all tables in a database from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametables-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Table Valued Functions
    By Database
  x-api-slug: catalogusqldatabasesdatabasenametablevaluedfunctions-get
  description: Retrieves the list of all table valued functions in a database from
    the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametablevaluedfunctions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametablevaluedfunctions-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Views By Database
  x-api-slug: catalogusqldatabasesdatabasenameviews-get
  description: Retrieves the list of all views in a database from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameviews-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog Get Database
  x-api-slug: catalogusqldatabasesdatabasename-get
  description: Retrieves the specified database from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasename-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Catalog List Databases
  x-api-slug: catalogusqldatabases-get
  description: Retrieves the list of databases from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/catalogusqldatabases-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job Get Statistics
  x-api-slug: jobsjobidentitygetstatistics-get
  description: Gets statistics of the specified job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentitygetstatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentitygetstatistics-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job Get Debug Data Path
  x-api-slug: jobsjobidentitygetdebugdatapath-get
  description: Gets the job debug data information specified by the job ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentitygetdebugdatapath-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentitygetdebugdatapath-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job Build
  x-api-slug: buildjob-post
  description: Builds (compiles) the specified job in the specified Data Lake Analytics
    account for job correctness and validation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/buildjob-post-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job Cancel
  x-api-slug: jobsjobidentitycanceljob-post
  description: Cancels the running job specified by the job ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentitycanceljob-post-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job Get
  x-api-slug: jobsjobidentity-get
  description: Gets the job information for the specified job ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentity-get-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job Create
  x-api-slug: jobsjobidentity-put
  description: Submits a job to the specified Data Lake Analytics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobsjobidentity-put-openapi.md
- name: DataLakeAnalyticsJobManagementClient - Job List
  x-api-slug: jobs-get
  description: Lists the jobs, if any, associated with the specified Data Lake Analytics
    account. The response includes a link to the next page of results, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Analysis, Microsoft, Data, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-analytics/master/_listings/azure-data-lake-analytics/jobs-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.container.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.data.lake.analytics.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/data-lake-analytics/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/data-lake-analytics/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/data-lake-analytics/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/data-lake-analytics/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---