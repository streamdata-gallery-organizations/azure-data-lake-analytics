---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Catalog List Table Valued Functions By Database
  description: Retrieves the list of all table valued functions in a database from
    the Data Lake Analytics catalog.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/firewallRules/{firewallRuleName}
  : put:
      summary: Firewall Rules Create Or Update
      description: Creates or updates the specified firewall rule. During update,
        the firewall rule with the specified name will be replaced with this new firewall
        rule.
      operationId: FirewallRules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to add or replace
          the firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to create or update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to create or update the firewall rule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
    patch:
      summary: Firewall Rules Update
      description: Updates the specified firewall rule.
      operationId: FirewallRules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to which to update
          the firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to update the firewall rule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
    delete:
      summary: Firewall Rules Delete
      description: Deletes the specified firewall rule from the specified Data Lake
        Analytics account
      operationId: FirewallRules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to delete
          the firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to delete
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
    get:
      summary: Firewall Rules Get
      description: Gets the specified Data Lake Analytics firewall rule.
      operationId: FirewallRules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrulesfirewallrulename-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to get
          the firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/firewallRules
  : get:
      summary: Firewall Rules List By Account
      description: Lists the Data Lake Analytics firewall rules within the specified
        Data Lake Analytics account.
      operationId: FirewallRules_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrules-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to get
          the firewall rules
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}
  : get:
      summary: Storage Accounts Get
      description: Gets the specified Azure Storage account linked to the given Data
        Lake Analytics account.
      operationId: StorageAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to retrieve
          Azure storage account details
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure Storage account for which to retrieve the
          details
      responses:
        200:
          description: OK
      tags:
      - Stage Account
    delete:
      summary: Storage Accounts Delete
      description: Updates the specified Data Lake Analytics account to remove an
        Azure Storage account.
      operationId: StorageAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to remove
          the Azure Storage account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure Storage account to remove
      responses:
        200:
          description: OK
      tags:
      - Stage Account
    patch:
      summary: Storage Accounts Update
      description: Updates the Data Lake Analytics account to replace Azure Storage
        blob account details, such as the access key and/or suffix.
      operationId: StorageAccounts_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to modify storage
          accounts in
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters containing the access key and suffix to update
          the storage account with, if any
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The Azure Storage account to modify
      responses:
        200:
          description: OK
      tags:
      - Stage Account
    put:
      summary: Storage Accounts Add
      description: Updates the specified Data Lake Analytics account to add an Azure
        Storage account.
      operationId: StorageAccounts_Add
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to which to add the
          Azure Storage account
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters containing the access key and optional suffix
          for the Azure Storage Account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure Storage account to add
      responses:
        200:
          description: OK
      tags:
      - Stage Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers/{containerName}
  : get:
      summary: Storage Accounts Get Storage Container
      description: Gets the specified Azure Storage container associated with the
        given Data Lake Analytics and Azure Storage accounts.
      operationId: StorageAccounts_GetStorageContainer
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainername-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to retrieve
          blob container
      - in: path
        name: containerName
        description: The name of the Azure storage container to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account from which to retrieve
          the blob container
      responses:
        200:
          description: OK
      tags:
      - Containers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers
  : get:
      summary: Storage Accounts List Storage Containers
      description: Lists the Azure Storage containers, if any, associated with the
        specified Data Lake Analytics and Azure Storage account combination. The response
        includes a link to the next page of results, if any.
      operationId: StorageAccounts_ListStorageContainers
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainers-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to list
          Azure Storage blob containers
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account from which to list blob
          containers
      responses:
        200:
          description: OK
      tags:
      - Stage Account Stage Containers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers/{containerName}/listSasTokens
  : post:
      summary: Storage Accounts List Sas Tokens
      description: Gets the SAS token associated with the specified Data Lake Analytics
        and Azure Storage account and container combination.
      operationId: StorageAccounts_ListSasTokens
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainernamelistsastokens-post
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which an Azure
          Storage accounts SAS token is being requested
      - in: path
        name: containerName
        description: The name of the Azure storage container for which the SAS token
          is being requested
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account for which the SAS token
          is being requested
      responses:
        200:
          description: OK
      tags:
      - Stage Account Satokens
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  : get:
      summary: Data Lake Store Accounts Get
      description: Gets the specified Data Lake Store account details in the specified
        Data Lake Analytics account.
      operationId: DataLakeStoreAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to retrieve
          the Data Lake Store account details
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
    delete:
      summary: Data Lake Store Accounts Delete
      description: Updates the Data Lake Analytics account specified to remove the
        specified Data Lake Store account.
      operationId: DataLakeStoreAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to remove
          the Data Lake Store account
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to remove
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
    put:
      summary: Data Lake Store Accounts Add
      description: Updates the specified Data Lake Analytics account to include the
        additional Data Lake Store account.
      operationId: DataLakeStoreAccounts_Add
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to which to add the
          Data Lake Store account
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to add
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The details of the Data Lake Store account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/
  : get:
      summary: Storage Accounts List By Account
      description: Gets the first page of Azure Storage accounts, if any, linked to
        the specified Data Lake Analytics account. The response includes a link to
        the next page, if any.
      operationId: StorageAccounts_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccounts-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: The OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to list
          Azure Storage accounts
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Stage Account Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/
  : get:
      summary: Data Lake Store Accounts List By Account
      description: Gets the first page of Data Lake Store accounts linked to the specified
        Data Lake Analytics account. The response includes a link to the next page,
        if any.
      operationId: DataLakeStoreAccounts_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to list
          Data Lake Store accounts
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account Account
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts:
    get:
      summary: Account List By Resource Group
      description: Gets the first page of Data Lake Analytics accounts, if any, within
        a specific resource group. This includes a link to the next page, if any.
      operationId: Account_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccounts-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Account  Resource Group
  /subscriptions/{subscriptionId}/providers/Microsoft.DataLakeAnalytics/accounts:
    get:
      summary: Account List
      description: Gets the first page of Data Lake Analytics accounts, if any, within
        the current subscription. This includes a link to the next page, if any.
      operationId: Account_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-datalakeanalyticsaccounts-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Account
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}:
    get:
      summary: Account Get
      description: Gets details of the specified Data Lake Analytics account.
      operationId: Account_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Account
    delete:
      summary: Account Delete
      description: Begins the delete delete process for the Data Lake Analytics account
        object specified by the account name.
      operationId: Account_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to delete
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Account
    put:
      summary: Account Create
      description: Creates the specified Data Lake Analytics account. This supplies
        the user with computation services for Data Lake Analytics workloads
      operationId: Account_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to create
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create Data Lake Analytics account
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Account
    patch:
      summary: Account Update
      description: Updates the Data Lake Analytics account object specified by the
        accountName with the contents of the account object.
      operationId: Account_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountname-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the update Data Lake Analytics account
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Account
  /catalog/usql/databases/{databaseName}/secrets/{secretName}:
    put:
      summary: Catalog Create Secret
      description: Creates the specified secret for use with external data sources
        in the specified database. This is deprecated and will be removed in the next
        release. Please use CreateCredential instead.
      operationId: Catalog_CreateSecret
      x-api-path-slug: catalogusqldatabasesdatabasenamesecretssecretname-put
      parameters:
      - in: path
        name: databaseName
        description: The name of the database in which to create the secret
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters required to create the secret (name and password)
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: secretName
        description: The name of the secret
      responses:
        200:
          description: OK
      tags:
      - Catalog Secret
    patch:
      summary: Catalog Update Secret
      description: Modifies the specified secret for use with external data sources
        in the specified database. This is deprecated and will be removed in the next
        release. Please use UpdateCredential instead.
      operationId: Catalog_UpdateSecret
      x-api-path-slug: catalogusqldatabasesdatabasenamesecretssecretname-patch
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the secret
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters required to modify the secret (name and password)
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: secretName
        description: The name of the secret
      responses:
        200:
          description: OK
      tags:
      - Catalog Secret
    get:
      summary: Catalog Get Secret
      description: Gets the specified secret in the specified database. This is deprecated
        and will be removed in the next release. Please use GetCredential instead.
      operationId: Catalog_GetSecret
      x-api-path-slug: catalogusqldatabasesdatabasenamesecretssecretname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the secret
      - in: query
        name: No Name
      - in: path
        name: secretName
        description: The name of the secret to get
      responses:
        200:
          description: OK
      tags:
      - Catalog Secret
    delete:
      summary: Catalog Delete Secret
      description: Deletes the specified secret in the specified database. This is
        deprecated and will be removed in the next release. Please use DeleteCredential
        instead.
      operationId: Catalog_DeleteSecret
      x-api-path-slug: catalogusqldatabasesdatabasenamesecretssecretname-delete
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the secret
      - in: query
        name: No Name
      - in: path
        name: secretName
        description: The name of the secret to delete
      responses:
        200:
          description: OK
      tags:
      - Catalog Secret
  /catalog/usql/databases/{databaseName}/secrets:
    delete:
      summary: Catalog Delete All Secrets
      description: Deletes all secrets in the specified database. This is deprecated
        and will be removed in the next release. In the future, please only drop individual
        credentials using DeleteCredential
      operationId: Catalog_DeleteAllSecrets
      x-api-path-slug: catalogusqldatabasesdatabasenamesecrets-delete
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the secret
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog All Secrets
  /catalog/usql/databases/{databaseName}/credentials/{credentialName}:
    put:
      summary: Catalog Create Credential
      description: Creates the specified credential for use with external data sources
        in the specified database.
      operationId: Catalog_CreateCredential
      x-api-path-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-put
      parameters:
      - in: path
        name: credentialName
        description: The name of the credential
      - in: path
        name: databaseName
        description: The name of the database in which to create the credential
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters required to create the credential (name and password)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Catalog Credential
    patch:
      summary: Catalog Update Credential
      description: Modifies the specified credential for use with external data sources
        in the specified database
      operationId: Catalog_UpdateCredential
      x-api-path-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-patch
      parameters:
      - in: path
        name: credentialName
        description: The name of the credential
      - in: path
        name: databaseName
        description: The name of the database containing the credential
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters required to modify the credential (name and password)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Catalog Credential
    get:
      summary: Catalog Get Credential
      description: Retrieves the specified credential from the Data Lake Analytics
        catalog.
      operationId: Catalog_GetCredential
      x-api-path-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-get
      parameters:
      - in: path
        name: credentialName
        description: The name of the credential
      - in: path
        name: databaseName
        description: The name of the database containing the schema
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Credential
    post:
      summary: Catalog Delete Credential
      description: Deletes the specified credential in the specified database
      operationId: Catalog_DeleteCredential
      x-api-path-slug: catalogusqldatabasesdatabasenamecredentialscredentialname-post
      parameters:
      - in: query
        name: cascade
        description: Indicates if the delete should be a cascading delete (which deletes
          all resources dependent on the credential as well as the credential) or
          not
      - in: path
        name: credentialName
        description: The name of the credential to delete
      - in: path
        name: databaseName
        description: The name of the database containing the credential
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters to delete a credential if the current user is
          not the account owner
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Catalog Credential
  /catalog/usql/databases/{databaseName}/credentials:
    get:
      summary: Catalog List Credentials
      description: Retrieves the list of credentials from the Data Lake Analytics
        catalog.
      operationId: Catalog_ListCredentials
      x-api-path-slug: catalogusqldatabasesdatabasenamecredentials-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the schema
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Credentials
  /catalog/usql/databases/{databaseName}/externaldatasources/{externalDataSourceName}:
    get:
      summary: Catalog Get External Data Source
      description: Retrieves the specified external data source from the Data Lake
        Analytics catalog.
      operationId: Catalog_GetExternalDataSource
      x-api-path-slug: catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the external data source
      - in: path
        name: externalDataSourceName
        description: The name of the external data source
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog External Data Source
  /catalog/usql/databases/{databaseName}/externaldatasources:
    get:
      summary: Catalog List External Data Sources
      description: Retrieves the list of external data sources from the Data Lake
        Analytics catalog.
      operationId: Catalog_ListExternalDataSources
      x-api-path-slug: catalogusqldatabasesdatabasenameexternaldatasources-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the external data sources
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog External Data Sources
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/procedures/{procedureName}:
    get:
      summary: Catalog Get Procedure
      description: Retrieves the specified procedure from the Data Lake Analytics
        catalog.
      operationId: Catalog_GetProcedure
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanameproceduresprocedurename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the procedure
      - in: query
        name: No Name
      - in: path
        name: procedureName
        description: The name of the procedure
      - in: path
        name: schemaName
        description: The name of the schema containing the procedure
      responses:
        200:
          description: OK
      tags:
      - Catalog Procedure
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/procedures:
    get:
      summary: Catalog List Procedures
      description: Retrieves the list of procedures from the Data Lake Analytics catalog.
      operationId: Catalog_ListProcedures
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanameprocedures-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the procedures
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the procedures
      responses:
        200:
          description: OK
      tags:
      - Catalog Procedures
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tables/{tableName}:
    get:
      summary: Catalog Get Table
      description: Retrieves the specified table from the Data Lake Analytics catalog.
      operationId: Catalog_GetTable
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the table
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table
      - in: path
        name: tableName
        description: The name of the table
      responses:
        200:
          description: OK
      tags:
      - Catalog Table
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tables:
    get:
      summary: Catalog List Tables
      description: Retrieves the list of tables from the Data Lake Analytics catalog.
      operationId: Catalog_ListTables
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametables-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the tables
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the tables
      responses:
        200:
          description: OK
      tags:
      - Catalog Tables
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/statistics:
    get:
      summary: Catalog List Table Statistics By Database And Schema
      description: Retrieves the list of all table statistics within the specified
        schema from the Data Lake Analytics catalog.
      operationId: Catalog_ListTableStatisticsByDatabaseAndSchema
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanamestatistics-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the statistics
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the statistics
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Statistic Database Schema
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tabletypes/{tableTypeName}:
    get:
      summary: Catalog Get Table Type
      description: Retrieves the specified table type from the Data Lake Analytics
        catalog.
      operationId: Catalog_GetTableType
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametabletypestabletypename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the table type
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table type
      - in: path
        name: tableTypeName
        description: The name of the table type to retrieve
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Type
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tabletypes:
    get:
      summary: Catalog List Table Types
      description: Retrieves the list of table types from the Data Lake Analytics
        catalog.
      operationId: Catalog_ListTableTypes
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametabletypes-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table types
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table types
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Types
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/packages/{packageName}:
    get:
      summary: Catalog Get Package
      description: Retrieves the specified package from the Data Lake Analytics catalog.
      operationId: Catalog_GetPackage
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanamepackagespackagename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the package
      - in: query
        name: No Name
      - in: path
        name: packageName
        description: The name of the package
      - in: path
        name: schemaName
        description: The name of the schema containing the package
      responses:
        200:
          description: OK
      tags:
      - Catalog Package
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/packages:
    get:
      summary: Catalog List Packages
      description: Retrieves the list of packages from the Data Lake Analytics catalog.
      operationId: Catalog_ListPackages
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanamepackages-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the packages
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the packages
      responses:
        200:
          description: OK
      tags:
      - Catalog Packages
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/views/{viewName}:
    get:
      summary: Catalog Get View
      description: Retrieves the specified view from the Data Lake Analytics catalog.
      operationId: Catalog_GetView
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanameviewsviewname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the view
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the view
      - in: path
        name: viewName
        description: The name of the view
      responses:
        200:
          description: OK
      tags:
      - Catalog View
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/views:
    get:
      summary: Catalog List Views
      description: Retrieves the list of views from the Data Lake Analytics catalog.
      operationId: Catalog_ListViews
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanameviews-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the views
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the views
      responses:
        200:
          description: OK
      tags:
      - Catalog Views
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tables/{tableName}/statistics/{statisticsName}:
    get:
      summary: Catalog Get Table Statistic
      description: Retrieves the specified table statistics from the Data Lake Analytics
        catalog.
      operationId: Catalog_GetTableStatistic
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamestatisticsstatisticsname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the statistics
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the statistics
      - in: path
        name: statisticsName
        description: The name of the table statistics
      - in: path
        name: tableName
        description: The name of the table containing the statistics
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Statistic
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tables/{tableName}/statistics:
    get:
      summary: Catalog List Table Statistics
      description: Retrieves the list of table statistics from the Data Lake Analytics
        catalog.
      operationId: Catalog_ListTableStatistics
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamestatistics-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the statistics
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the statistics
      - in: path
        name: tableName
        description: The name of the table containing the statistics
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Statistics
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tables/{tableName}/partitions/{partitionName}:
    get:
      summary: Catalog Get Table Partition
      description: Retrieves the specified table partition from the Data Lake Analytics
        catalog.
      operationId: Catalog_GetTablePartition
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamepartitionspartitionname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the partition
      - in: query
        name: No Name
      - in: path
        name: partitionName
        description: The name of the table partition
      - in: path
        name: schemaName
        description: The name of the schema containing the partition
      - in: path
        name: tableName
        description: The name of the table containing the partition
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Partition
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tables/{tableName}/partitions:
    get:
      summary: Catalog List Table Partitions
      description: Retrieves the list of table partitions from the Data Lake Analytics
        catalog.
      operationId: Catalog_ListTablePartitions
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablestablenamepartitions-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the partitions
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the partitions
      - in: path
        name: tableName
        description: The name of the table containing the partitions
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Partitions
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/types:
    get:
      summary: Catalog List Types
      description: Retrieves the list of types within the specified database and schema
        from the Data Lake Analytics catalog.
      operationId: Catalog_ListTypes
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametypes-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the types
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the types
      responses:
        200:
          description: OK
      tags:
      - Catalog Types
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tablevaluedfunctions/{tableValuedFunctionName}:
    get:
      summary: Catalog Get Table Valued Function
      description: Retrieves the specified table valued function from the Data Lake
        Analytics catalog.
      operationId: Catalog_GetTableValuedFunction
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctionstablevaluedfunctionname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the table valued function
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table valued function
      - in: path
        name: tableValuedFunctionName
        description: The name of the tableValuedFunction
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Valued Function
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/tablevaluedfunctions:
    get:
      summary: Catalog List Table Valued Functions
      description: Retrieves the list of table valued functions from the Data Lake
        Analytics catalog.
      operationId: Catalog_ListTableValuedFunctions
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanametablevaluedfunctions-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table valued functions
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the table valued functions
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Valued Functions
  /catalog/usql/databases/{databaseName}/assemblies/{assemblyName}:
    get:
      summary: Catalog Get Assembly
      description: Retrieves the specified assembly from the Data Lake Analytics catalog.
      operationId: Catalog_GetAssembly
      x-api-path-slug: catalogusqldatabasesdatabasenameassembliesassemblyname-get
      parameters:
      - in: path
        name: assemblyName
        description: The name of the assembly
      - in: path
        name: databaseName
        description: The name of the database containing the assembly
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Assembly
  /catalog/usql/databases/{databaseName}/assemblies:
    get:
      summary: Catalog List Assemblies
      description: Retrieves the list of assemblies from the Data Lake Analytics catalog.
      operationId: Catalog_ListAssemblies
      x-api-path-slug: catalogusqldatabasesdatabasenameassemblies-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the assembly
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Assemblies
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}:
    get:
      summary: Catalog Get Schema
      description: Retrieves the specified schema from the Data Lake Analytics catalog.
      operationId: Catalog_GetSchema
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemaname-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database containing the schema
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema
      responses:
        200:
          description: OK
      tags:
      - Catalog Schema
  /catalog/usql/databases/{databaseName}/schemas:
    get:
      summary: Catalog List Schemas
      description: Retrieves the list of schemas from the Data Lake Analytics catalog.
      operationId: Catalog_ListSchemas
      x-api-path-slug: catalogusqldatabasesdatabasenameschemas-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the schema
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Schemas
  /catalog/usql/databases/{databaseName}/statistics:
    get:
      summary: Catalog List Table Statistics By Database
      description: Retrieves the list of all statistics in a database from the Data
        Lake Analytics catalog.
      operationId: Catalog_ListTableStatisticsByDatabase
      x-api-path-slug: catalogusqldatabasesdatabasenamestatistics-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table statistics
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Statistic Database
  /catalog/usql/databases/{databaseName}/tables:
    get:
      summary: Catalog List Tables By Database
      description: Retrieves the list of all tables in a database from the Data Lake
        Analytics catalog.
      operationId: Catalog_ListTablesByDatabase
      x-api-path-slug: catalogusqldatabasesdatabasenametables-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the tables
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Database
  /catalog/usql/databases/{databaseName}/tablevaluedfunctions:
    get:
      summary: Catalog List Table Valued Functions By Database
      description: Retrieves the list of all table valued functions in a database
        from the Data Lake Analytics catalog.
      operationId: Catalog_ListTableValuedFunctionsByDatabase
      x-api-path-slug: catalogusqldatabasesdatabasenametablevaluedfunctions-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the table valued functions
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Catalog Table Valued Function Database
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---