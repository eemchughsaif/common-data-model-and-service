---
title: DealDeviceAddOn - Common Data Model | Microsoft Docs
description: Additional product or service offered with a given vehicle or device in a deal.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Deal Device Add On

Additional product or service offered with a given vehicle or device in a deal.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/DealDeviceAddOn.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/DealDeviceAddOn  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[actualCost](#actualCost)|Cost of the add-on added to the deal.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[actualCostBase](#actualCostBase)|Value of the actual cost in base currency.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[customerPrice](#customerPrice)|Price the customer was charged for the add-on.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[customerPriceBase](#customerPriceBase)|Value of the customer price in base currency.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[dealDeviceAddOnId](#dealDeviceAddOnId)|Unique identifier for entity instances|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[dealDeviceId](#dealDeviceId)|Parent deal for which the add-on is being added.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[description](#description)|Description of the deal device add-on.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[itemNumber](#itemNumber)|Unique number of the add-on.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[name](#name)|Name of the device add-on in this deal.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[retailPrice](#retailPrice)|Retail price of the add-on.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[retailPriceBase](#retailPriceBase)|Value of the Retail Price in base currency.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[stateCode](#stateCode)|Status of the Deal Device Add On|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[stateCode_display](#stateCode_display)||<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[statusCode](#statusCode)|Reason for the status of the Deal Device Add On|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[statusCode_display](#statusCode_display)||<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="DealDeviceAddOn.md" target="_blank">automotive/DealDeviceAddOn</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualCost name="actualCost">actualCost</a>

Cost of the add-on added to the deal.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost</td></tr><tr><td>description</td><td>Cost of the add-on added to the deal.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualcost</td></tr></table>

### <a href=#actualCostBase name="actualCostBase">actualCostBase</a>

Value of the actual cost in base currency.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost (Base)</td></tr><tr><td>description</td><td>Value of the actual cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualcost_base</td></tr></table>

### <a href=#customerPrice name="customerPrice">customerPrice</a>

Price the customer was charged for the add-on.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Price</td></tr><tr><td>description</td><td>Price the customer was charged for the add-on.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_customerprice</td></tr></table>

### <a href=#customerPriceBase name="customerPriceBase">customerPriceBase</a>

Value of the customer price in base currency.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Price (Base)</td></tr><tr><td>description</td><td>Value of the customer price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_customerprice_base</td></tr></table>

### <a href=#dealDeviceAddOnId name="dealDeviceAddOnId">dealDeviceAddOnId</a>

Unique identifier for entity instances  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal Device Add On</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_dealdeviceaddonid</td></tr></table>

### <a href=#dealDeviceId name="dealDeviceId">dealDeviceId</a>

Parent deal for which the add-on is being added.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal Device</td></tr><tr><td>description</td><td>Parent deal for which the add-on is being added.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_dealdeviceid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the deal device add-on.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the deal device add-on.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#itemNumber name="itemNumber">itemNumber</a>

Unique number of the add-on.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item Number</td></tr><tr><td>description</td><td>Unique number of the add-on.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_itemnumber</td></tr></table>

### <a href=#name name="name">name</a>

Name of the device add-on in this deal.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the device add-on in this deal.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#retailPrice name="retailPrice">retailPrice</a>

Retail price of the add-on.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retail Price</td></tr><tr><td>description</td><td>Retail price of the add-on.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_retailprice</td></tr></table>

### <a href=#retailPriceBase name="retailPriceBase">retailPriceBase</a>

Value of the Retail Price in base currency.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retail Price (Base)</td></tr><tr><td>description</td><td>Value of the Retail Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_retailprice_base</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Deal Device Add On  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Deal Device Add On</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Deal Device Add On  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Deal Device Add On</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/DealDeviceAddOn (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
