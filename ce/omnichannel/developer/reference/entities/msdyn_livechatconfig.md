---
title: "msdyn_livechatconfig Entity Reference (Developer Guide for Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_livechatconfig entity."
ms.date: 08/29/2019
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "susikka"
ms.author: "susikka"
manager: "shujoshi"
---
# msdyn_livechatconfig Entity Reference

[!INCLUDE[cc-use-with-omnichannel](../../../../includes/cc-use-with-omnichannel.md)]

Stores chat widget customizations

**Added by**: Omnichannel – Chat Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.1/msdyn_livechatconfigs(*msdyn_livechatconfigid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.1/msdyn_livechatconfigs<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.1/msdyn_livechatconfigs(*msdyn_livechatconfigid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Retrieve|GET [*org URI*]/api/data/v9.1/msdyn_livechatconfigs(*msdyn_livechatconfigid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.1/msdyn_livechatconfigs<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.1/msdyn_livechatconfigs(*msdyn_livechatconfigid*)<br />[Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.1/msdyn_livechatconfigs(*msdyn_livechatconfigid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_livechatconfigs|
|DisplayCollectionName|Chat Widgets|
|DisplayName|Chat Widget|
|EntitySetName|msdyn_livechatconfigs|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_livechatconfigs|
|LogicalName|msdyn_livechatconfig|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_livechatconfigid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_livechatconfig|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_agentDisplayName](#BKMK_msdyn_agentDisplayName)
- [msdyn_AuthsettingsId](#BKMK_msdyn_AuthsettingsId)
- [msdyn_AutoDetectLanguage](#BKMK_msdyn_AutoDetectLanguage)
- [msdyn_avatarUrl](#BKMK_msdyn_avatarUrl)
- [msdyn_Duringnonoperatinghours](#BKMK_msdyn_Duringnonoperatinghours)
- [msdyn_Enablefileattachmentsforagents](#BKMK_msdyn_Enablefileattachmentsforagents)
- [msdyn_Enablefileattachmentsforcustomers](#BKMK_msdyn_Enablefileattachmentsforcustomers)
- [msdyn_genericagentdisplayname](#BKMK_msdyn_genericagentdisplayname)
- [msdyn_infolabel](#BKMK_msdyn_infolabel)
- [msdyn_Language](#BKMK_msdyn_Language)
- [msdyn_livechatconfigId](#BKMK_msdyn_livechatconfigId)
- [msdyn_liveworkstreamid](#BKMK_msdyn_liveworkstreamid)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_oc_geolocationprovider](#BKMK_msdyn_oc_geolocationprovider)
- [msdyn_operatinghourid](#BKMK_msdyn_operatinghourid)
- [msdyn_postchatenabled](#BKMK_msdyn_postchatenabled)
- [msdyn_PrechatEnabled](#BKMK_msdyn_PrechatEnabled)
- [msdyn_PreChatQuestionnaireAuthenticated](#BKMK_msdyn_PreChatQuestionnaireAuthenticated)
- [msdyn_PreChatQuestionnaireUnauthenticated](#BKMK_msdyn_PreChatQuestionnaireUnauthenticated)
- [msdyn_requestvisitorlocation](#BKMK_msdyn_requestvisitorlocation)
- [msdyn_showagentname](#BKMK_msdyn_showagentname)
- [msdyn_widgetAppId](#BKMK_msdyn_widgetAppId)
- [msdyn_WidgetLocale](#BKMK_msdyn_WidgetLocale)
- [msdyn_widgetPosition](#BKMK_msdyn_widgetPosition)
- [msdyn_WidgetSnippet](#BKMK_msdyn_WidgetSnippet)
- [msdyn_widgetSubtitle](#BKMK_msdyn_widgetSubtitle)
- [msdyn_widgetThemeColor](#BKMK_msdyn_widgetThemeColor)
- [msdyn_widgetTitle](#BKMK_msdyn_widgetTitle)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_msdyn_agentDisplayName"></a> msdyn_agentDisplayName

|Property|Value|
|--------|-----|
|Description|Configure agent name to be displayed in the chat widget|
|DisplayName|Agent display name|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_agentdisplayname|
|RequiredLevel|None|
|Type|Picklist|

#### msdyn_agentDisplayName Options

|Value|Label|
|-----|-----|
|192350000|Full name|
|192350001|First name|
|192350002|Last name|
|192350003|Nick name|



### <a name="BKMK_msdyn_AuthsettingsId"></a> msdyn_AuthsettingsId

|Property|Value|
|--------|-----|
|Description|Unique identifier for Authentication settings associated with Chat widget.|
|DisplayName|Authentication settings|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_authsettingsid|
|RequiredLevel|None|
|Targets|msdyn_authenticationsettings|
|Type|Lookup|


### <a name="BKMK_msdyn_AutoDetectLanguage"></a> msdyn_AutoDetectLanguage

|Property|Value|
|--------|-----|
|Description|Indicates if the chat widget should automatically detect user locale.|
|DisplayName|Auto Detect Language|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_autodetectlanguage|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|

#### msdyn_AutoDetectLanguage Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_avatarUrl"></a> msdyn_avatarUrl

|Property|Value|
|--------|-----|
|Description|Chat logo|
|DisplayName|Logo|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_avatarurl|
|MaxLength|4000|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_Duringnonoperatinghours"></a> msdyn_Duringnonoperatinghours

|Property|Value|
|--------|-----|
|Description||
|DisplayName|During non-operating hours|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_duringnonoperatinghours|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Enablefileattachmentsforagents"></a> msdyn_Enablefileattachmentsforagents

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Enable file attachments for agents|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_enablefileattachmentsforagents|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_Enablefileattachmentsforagents Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: True



### <a name="BKMK_msdyn_Enablefileattachmentsforcustomers"></a> msdyn_Enablefileattachmentsforcustomers

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Enable file attachments for customers|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_enablefileattachmentsforcustomers|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_Enablefileattachmentsforcustomers Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_genericagentdisplayname"></a> msdyn_genericagentdisplayname

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Display Generic Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_genericagentdisplayname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_infolabel"></a> msdyn_infolabel

|Property|Value|
|--------|-----|
|Description||
|DisplayName|infolabel|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_infolabel|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_Language"></a> msdyn_Language

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Language|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_language|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|

#### msdyn_Language Options

|Value|Label|
|-----|-----|
|192350000|Auto-Detect|
|192360014|English|



### <a name="BKMK_msdyn_livechatconfigId"></a> msdyn_livechatconfigId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|Chat Widget|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_livechatconfigid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_liveworkstreamid"></a> msdyn_liveworkstreamid

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Work stream|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_liveworkstreamid|
|RequiredLevel|ApplicationRequired|
|Targets|msdyn_liveworkstream|
|Type|Lookup|


### <a name="BKMK_msdyn_name"></a> msdyn_name

|Property|Value|
|--------|-----|
|Description|The name of the custom entity.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_name|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_msdyn_oc_geolocationprovider"></a> msdyn_oc_geolocationprovider

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Provider API key|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_oc_geolocationprovider|
|RequiredLevel|None|
|Targets|msdyn_oc_geolocationprovider|
|Type|Lookup|


### <a name="BKMK_msdyn_operatinghourid"></a> msdyn_operatinghourid

|Property|Value|
|--------|-----|
|Description|Unique identifier for Operating hour associated with Chat widget.|
|DisplayName|Operating hours|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_operatinghourid|
|RequiredLevel|None|
|Targets|msdyn_operatinghour|
|Type|Lookup|


### <a name="BKMK_msdyn_postchatenabled"></a> msdyn_postchatenabled

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Post-chat Survey|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_postchatenabled|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|

#### msdyn_postchatenabled Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_PrechatEnabled"></a> msdyn_PrechatEnabled

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Pre-Chat Survey|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_prechatenabled|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|

#### msdyn_PrechatEnabled Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_PreChatQuestionnaireAuthenticated"></a> msdyn_PreChatQuestionnaireAuthenticated

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Question Set for Authenticated Users|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_prechatquestionnaireauthenticated|
|RequiredLevel|None|
|Targets||
|Type|Lookup|


### <a name="BKMK_msdyn_PreChatQuestionnaireUnauthenticated"></a> msdyn_PreChatQuestionnaireUnauthenticated

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Question Set for Unauthenticated Users|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_prechatquestionnaireunauthenticated|
|RequiredLevel|None|
|Targets||
|Type|Lookup|


### <a name="BKMK_msdyn_requestvisitorlocation"></a> msdyn_requestvisitorlocation

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Request visitor location|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_requestvisitorlocation|
|RequiredLevel|ApplicationRequired|
|Type|Boolean|

#### msdyn_requestvisitorlocation Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_showagentname"></a> msdyn_showagentname

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Anonymize Agent|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_showagentname|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_showagentname Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_msdyn_widgetAppId"></a> msdyn_widgetAppId

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Widget App Id|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgetappid|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_WidgetLocale"></a> msdyn_WidgetLocale

|Property|Value|
|--------|-----|
|Description|The language of the chat widget.|
|DisplayName|Language|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgetlocale|
|RequiredLevel|ApplicationRequired|
|Targets|msdyn_chatwidgetlanguage|
|Type|Lookup|


### <a name="BKMK_msdyn_widgetPosition"></a> msdyn_widgetPosition

|Property|Value|
|--------|-----|
|Description|Chat position relative to the page|
|DisplayName|Position|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgetposition|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|

#### msdyn_widgetPosition Options

|Value|Label|
|-----|-----|
|192236010|Bottom right|
|192236011|Bottom left|



### <a name="BKMK_msdyn_WidgetSnippet"></a> msdyn_WidgetSnippet

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Widget Snippet|
|Format|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgetsnippet|
|MaxLength|2000|
|RequiredLevel|None|
|Type|Memo|


### <a name="BKMK_msdyn_widgetSubtitle"></a> msdyn_widgetSubtitle

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Subtitle|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgetsubtitle|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_widgetThemeColor"></a> msdyn_widgetThemeColor

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Theme Color|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgetthemecolor|
|RequiredLevel|ApplicationRequired|
|Type|Picklist|

#### msdyn_widgetThemeColor Options

|Value|Label|
|-----|-----|
|19236001|Red|
|19236002|Blue|
|19236003|Green|
|19236004|Black|
|192350001|Orange|
|192350002|Pink|
|192350003|Grey|
|192350004|Violet|
|192350005|Brown|
|192350006|Clay|
|192350007|Purple|
|192360017|Teal|



### <a name="BKMK_msdyn_widgetTitle"></a> msdyn_widgetTitle

|Property|Value|
|--------|-----|
|Description||
|DisplayName|Title|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_widgettitle|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerId"></a> OwnerId

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id Type|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|--------|-----|
|Description|Status of the Chat widget|
|DisplayName|Status|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### statecode Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Active|1|Active|
|1|Inactive|2|Inactive|



### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the Chat widget|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### statuscode Options

|Value|Label|State|
|-----|-----|-----|
|1|Active|0|
|2|Inactive|1|



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_AuthsettingsIdName](#BKMK_msdyn_AuthsettingsIdName)
- [msdyn_liveworkstreamidName](#BKMK_msdyn_liveworkstreamidName)
- [msdyn_oc_geolocationproviderName](#BKMK_msdyn_oc_geolocationproviderName)
- [msdyn_operatinghouridName](#BKMK_msdyn_operatinghouridName)
- [msdyn_WidgetLocaleName](#BKMK_msdyn_WidgetLocaleName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the record.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the record.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who modified the record.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who modified the record.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_msdyn_AuthsettingsIdName"></a> msdyn_AuthsettingsIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_authsettingsidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_liveworkstreamidName"></a> msdyn_liveworkstreamidName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_liveworkstreamidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_oc_geolocationproviderName"></a> msdyn_oc_geolocationproviderName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_oc_geolocationprovidername|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_operatinghouridName"></a> msdyn_operatinghouridName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_operatinghouridname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_WidgetLocaleName"></a> msdyn_WidgetLocaleName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_widgetlocalename|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Yomi name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the business unit that owns the record|
|DisplayName|Owning Business Unit|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the team that owns the record.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the user that owns the record.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [msdyn_livechatconfig_msdyn_questionsequence](#BKMK_msdyn_livechatconfig_msdyn_questionsequence)
- [msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse](#BKMK_msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse)
- [msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid](#BKMK_msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid)


### <a name="BKMK_msdyn_livechatconfig_msdyn_questionsequence"></a> msdyn_livechatconfig_msdyn_questionsequence

Same as msdyn_questionsequence entity [msdyn_livechatconfig_msdyn_questionsequence](msdyn_questionsequence.md#BKMK_msdyn_livechatconfig_msdyn_questionsequence) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_questionsequence|
|ReferencingAttribute|msdyn_chatengagementtochatsequenceid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_livechatconfig_msdyn_questionsequence|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: RemoveLink<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse"></a> msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse

Same as msdyn_chatquestionnaireresponse entity [msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse](msdyn_chatquestionnaireresponse.md#BKMK_msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_chatquestionnaireresponse|
|ReferencingAttribute|msdyn_livechatconfigid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_msdyn_livechatconfig_msdyn_chatquestionnaireresponse|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: RemoveLink<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid"></a> msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid

Same as msdyn_livechatwidgetlocation entity [msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid](msdyn_livechatwidgetlocation.md#BKMK_msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_livechatwidgetlocation|
|ReferencingAttribute|msdyn_livechatconfigid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_msdyn_livechatconfig_msdyn_livechatwidgetlocation_livechatconfigid|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: RemoveLink<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [msdyn_msdyn_authsettings_msdyn_livechatconfig](#BKMK_msdyn_msdyn_authsettings_msdyn_livechatconfig)
- [msdyn_msdyn_chatwidgetlanguage_msdyn_livechatconfig_WidgetLocale](#BKMK_msdyn_msdyn_chatwidgetlanguage_msdyn_livechatconfig_WidgetLocale)
- [msdyn_msdyn_liveworkstream_msdyn_livechatconfig_liveworkstreamid](#BKMK_msdyn_msdyn_liveworkstream_msdyn_livechatconfig_liveworkstreamid)
- [msdyn_msdyn_operatinghour_msdyn_livechatconfig](#BKMK_msdyn_msdyn_operatinghour_msdyn_livechatconfig)
- [msdyn_msdyn_oc_geolocationprovider_msdyn_livechatconfig](#BKMK_msdyn_msdyn_oc_geolocationprovider_msdyn_livechatconfig)


### <a name="BKMK_msdyn_msdyn_authsettings_msdyn_livechatconfig"></a> msdyn_msdyn_authsettings_msdyn_livechatconfig

See msdyn_authenticationsettings Entity [msdyn_msdyn_authsettings_msdyn_livechatconfig](msdyn_authenticationsettings.md#BKMK_msdyn_msdyn_authsettings_msdyn_livechatconfig) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_chatwidgetlanguage_msdyn_livechatconfig_WidgetLocale"></a> msdyn_msdyn_chatwidgetlanguage_msdyn_livechatconfig_WidgetLocale

See msdyn_chatwidgetlanguage Entity [msdyn_msdyn_chatwidgetlanguage_msdyn_livechatconfig_WidgetLocale](msdyn_chatwidgetlanguage.md#BKMK_msdyn_msdyn_chatwidgetlanguage_msdyn_livechatconfig_WidgetLocale) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_liveworkstream_msdyn_livechatconfig_liveworkstreamid"></a> msdyn_msdyn_liveworkstream_msdyn_livechatconfig_liveworkstreamid

**Added by**: Omnichannel – Base Solution

See msdyn_liveworkstream Entity [msdyn_msdyn_liveworkstream_msdyn_livechatconfig_liveworkstreamid](msdyn_liveworkstream.md#BKMK_msdyn_msdyn_liveworkstream_msdyn_livechatconfig_liveworkstreamid) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_operatinghour_msdyn_livechatconfig"></a> msdyn_msdyn_operatinghour_msdyn_livechatconfig

**Added by**: Omnichannel – Base Solution

See msdyn_operatinghour Entity [msdyn_msdyn_operatinghour_msdyn_livechatconfig](msdyn_operatinghour.md#BKMK_msdyn_msdyn_operatinghour_msdyn_livechatconfig) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_oc_geolocationprovider_msdyn_livechatconfig"></a> msdyn_msdyn_oc_geolocationprovider_msdyn_livechatconfig

**Added by**: Omnichannel – Base Solution

See msdyn_oc_geolocationprovider Entity [msdyn_msdyn_oc_geolocationprovider_msdyn_livechatconfig](msdyn_oc_geolocationprovider.md#BKMK_msdyn_msdyn_oc_geolocationprovider_msdyn_livechatconfig) One-To-Many relationship.

### See also

[Introduction to Omnichannel for Customer Service](../../../introduction-omnichannel.md)<br />
[Developer guide for Omnichannel for Customer Service](../../omnichannel-developer.md)