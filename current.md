---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: November 2019
author: mfrei

---

# Adobe Experience Cloud Release Notes - November 2019

New features and fixes in the Adobe Experience Cloud.

> [!NOTE] Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

**Release date: October 31, 2019**

* [Experience Cloud interface](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)
* [!DNL Advertising Cloud](#adcloud)

Looking for the help home? See [Experience Cloud Learn & Support](https://helpx.adobe.com/support/experience-cloud.html).

## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* The Feed page is being deprecated in December, 2019. Look for an in-product deprecation notice. (MCUI-10039)
* Updated the [Learn More](https://www.adobe.com/marketing/campaign.html) link for Adobe Campaign from the app selector. (MCUI-10034)
* Improved stability and responsiveness of the core platform for theExperience Cloud interface. (MCUI-6822)
* Fixed security vulnerabilities in Experience Cloud UI. (MCUI-9942)
* Fixed a critical issue in Customer Attributes that blocked schema validation for some customers. (MCUI-10024, MCUI-6479)
* Improved the Audience Library to remove dimensions that are not supported for real-time audience creation. (MCUI-10046)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Release notes for the Experience Platform, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- | 
|Customer Journey Analytics|On November 21, 2019, Adobe will make [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) available as an add-on to Adobe Analytics.<br><br/>Customer Journey Analytics allows you to bring all of your customer data from any channel — both online and offline — into Adobe Experience Platform, and then analyze this data just as you would your existing digital data using Analysis Workspace today. Customer Journey Analytics includes the ability for you to control how you connect your online and offline data in Analysis Workspace on any common customer ID, finally allowing you to do attribution, segmentation, flow, fallout, etc. across your entire customer data set in Adobe Analytics.<br><br/>Analytics Select, Prime, and Ultimate customers are eligible to purchase this add-on product. Please contact your Adobe account team for further details.|
|Privacy Service API: CCPA|The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br><br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br><br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out from the selling of personal data.<br><br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md)|
|Privacy Reporting: Analytics Admin Console|Enabling Privacy Reporting for Analytics adds a set of reserved variables to a report suite.  The variables are designed to assist in the collection of consumer consent data at a hit level.<br><br/>New Dimensions:<br/><ul><li>Consent Management Opt-Out</li><li>Consent Management Opt-In</li><li>[Consent Management Variables](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul>|
|Audio and Video Analytics: Privacy Support|Two new variables have been added to the Media Collection API:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>These are optional variables that can be used to capture the status of a consumer’s consent at the time of the hit.<br/><br/>[Media Collection API Documentation](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>The new Analytics Consent Management context data variables have been added to the Federated Analytics form. These variables are now available for use in flagging Opt Out of Sharing or Selling hits for federation.<br/><br/>[Download Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form)|

#### Fixes

* Fixed an issue that resulted in an error when trying to delete date ranges that were owned by “Unknown user.” (AN-185540)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|EOL of **[!UICONTROL View Archive]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the **[!UICONTROL View Archive]** option in the Dashboard Manager (**[!UICONTROL Components > Dashboards]**).|
|EOL of **[!UICONTROL Enforce IP Login Restrictions]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the IP login whitelisting (**[!UICONTROL Enforce IP Login Restrictions]**) functionality under the **[!UICONTROL Admin > Company Settings > Security]** menu.|
|Updated handling to SameSite attribute on cookies | October 15, 2019 | In August 2019, Adobe announced that it added the SameSite cookie setting to all cookies set by Analytics. An update in logic is applied where:<ul><li>All third-party cookies that are not based on Webkit have SameSite attribute set to `none`.</li><li>All other cookies do not have the SameSite attribute set.</li></ul>|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li>|
| Update to Analysis Workspace Freeform Table totals | September 12, 2019 | In October 2019, freeform table total rows will begin accounting for [report filters](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applied. To date, totals have accounted only for segmentation. With this change, dependent visualizations will update (e.g. linked [!UICONTROL Summary Number] visualizations), as well as exported CSV and PDF data.|
|Upcoming change regarding `createDate` field for Analytics users|August 30, 2019|In October or November 2019, the `createDate` field for Analytics users will be updated from US Pacific Time to a correctly formatted date/time value with time zone information. (AN-183468)|
| Support for Historical Timezone Offsets | August 8, 2019 | Analytics will now automatically handle timezone offsets for timestamped hits. Following this change on August 8, systems that load in data for historical processing will no longer need to adjust for timezone offsets before sending in the data. |
| Classification rule builder limits | Added June 5, 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html).|
| New segment operator limits | Added May 31, 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. The limit will be applied to all new and modified segments after this date. Existing segments that exceed the limit will continue to be supported, but cannot be modified or saved until the input field is reduced. These limits are being applied as part of a continued effort to improve query performance. |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Updated May 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change took effect with the July 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
| Change to _Report Total_ calculations | Updated July 9, 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. This resulted in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 18, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API. |
| Update to CSV downloads from Analysis Workspace | April 10, 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>The thousands separator is no longer included. The decimal separator will continue to be included, and will adhere to the format defined under **[!UICONTROL Components > Report Settings > Thousands Separator]**. Note: Numeric values that use a comma as the decimal separator will continue to be quoted in the exported CSV.</li><li>No currency symbols will be shown.</li><li>No percent symbols will be shown. Percentages will be in decimal form. E.g., 75% will be represented as 0.75.</li><li>Time will be shown in seconds.</li><li>Cohort tables will show raw values only; percentages will be removed.</li><li>If a number is invalid, an empty cell will be displayed.</li></ul>|
| Upcoming change to the Analysis Workspace Debugger command | April 4, 2019 | The Console command to turn on the Analysis Workspace Debugger is changing to adobeTools.debug.includeOberonXml on **June 13, 2019**. adobe.tools.debug.includeOberonXml will cease to function after that date. |
| Mobile browser version numbers | February 7, 2019 | Starting January 8, 2019, we changed the truncation level for mobile browser version numbers from 2 to 1. From that date forward, versions only display the first two levels (e.g. _Firefox 64.0.2_ is now reported as _Firefox 64.0_). |
| End of life for [!DNL Ad Hoc Analysis] | January 29, 2019 | On August 6, 2018, Adobe announced the intention to end-of-life [!DNL Ad Hoc Analysis]. An end-of-life date will be shared once available.<br/>For more information, including which versions of Java will be compatible during this period, visit [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | January 14, 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Data Feed: post_product_list column - size change | January 9, 2019 | On February 7, 2019, Adobe expanded the size of the post_product_list column from 64 KB to 16 MB. This change ensures that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values. If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| Management changes affecting inactive [!DNL Analytics Live Stream] endpoints | December 20, 2018 | Starting on February 1, 2019, [!DNL Live Stream] endpoints with no active consumer connections for 90 days may be disabled. You can reach out to Customer Care to inquire about your [!DNL Live Stream] endpoints and, if necessary, have them re-enabled. In addition, please ensure your consumer processes maintain a persistent connection, as intended by the design of the service, and that they are implemented to reconnect when the connection is disconnected or interrupted. |
| Update Adobe [!DNL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that [!DNL Report Builder] users download version v5.6.21 prior to February 2019. After that date, prior versions of [!DNL Report Builder] will no longer function. |

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

New features, enhancements, and fixes in Audience Manager.

| Feature | Description |
|--- |----|
|[Profile Merge Rules Enhancements](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | We released a series of enhancements for [!UICONTROL Profile Merge Rules]: <ul><li>Segment evaluation is now supported in batch, for up to 100 devices.</li><li>We improved the reporting accuracy for trait and segment populations.</li><li>We improved the accuracy of batch files generated using cross-device IDs.</li><li>We updated the documentation with more detailed use cases for each rule. See [General Use Cases for Profile Merge Rules](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html), [External Device Graph Use Cases](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html), and [Profile Link Device Graph Use Cases](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html).</li></ul> |
| [Bulk Management Tools](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | We released a new version of the Bulk Management worksheet that works on MacOS and Microsoft Windows operating systems and supports Experience Cloud login.|
|[HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | We added support for [!DNL HTTP Strict-Transport-Security], a web security policy that protects against cookie hijacking and protocol downgrade attacks.|

**Fixes and Improvements**

* We fixed a bug in Audience Marketplace, where the UI returned Error 409 when customers were submitting the monthly segment usage. (AAM-50825)
* We fixed a bug in Derived Signals, where for a short time customers were unable to create new derived signals. (AAM-50968) 
* We fixed a bug in People-Based Destinations, where customers were unable to change the name of a destination. (AAM-51025)
* We fixed a bug where some users had duplicate accounts to log in to the Audience Manager UI. Due to permissions associated to the duplicate accounts, these users were unable to access some parts of the UI and perform operations. (AAM-50818)
* We continued to make improvements to the accessibility of the Audience Manager UI. (AAM-48932, AAM-49043, AAM-49054, AAM-49371, AAM-49375)
  
## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

* **Brand Portal 6.4.5**

    Adobe Experience Manager Assets Brand Portal 6.4.5 is a feature release that focuses on providing Brand Portal users (external agencies/teams) with the ability to upload content to Brand Portal and publish to AEM Assets, without the need to access the author environment. This feature is called [Asset Sourcing in Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html), and improves customer experiences by providing a two-way mechanism for users to contribute and share assets with other globally distributed Brand Portal users.

    See [What is new in AEM Assets Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

    See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **AEM Forms Automated Conversion Service**

    Automated Forms Conversion service helps accelerate digitization and modernization of data capture experiences through automated conversion of PDF forms to adaptive forms. The service, powered by Adobe Sensei, automatically converts your PDF forms to device-friendly, responsive, and HTML5-based adaptive forms. While leveraging the existing investments in PDF Forms and XFA, the service also applies appropriate validations, styling, and layout to adaptive form fields during conversion.

    See [Adobe Experience Manager Forms Automated Conversion Service](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html).

* **Cloud Manager 2019.10.0**

    The general Release Notes for Cloud Manager 2019.10.0 are now available. The notes also lists updates to deployment steps and maven project version handling.

    See [Cloud Manager 2019.10.0 release notes](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Self-help

* **Activity map**

    Due to security changes within the Adobe Analytics API, it is no longer possible to use the version of Activity Map that is included within AEM. See [Configuring the connection to Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

    You should now use the [Activity Map browser plug-in](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) for either Chrome, Firefox, or Internet Explorer as provided by Adobe Analytics.

* **Best practices guide for AEM Screens projects**

    The new _Best Practices Guide for AEM Screens_ provides comprehensive insight and practical advice to imagine, design, and bring intentional customer experiences into your digital signage implementation. It also guides you in how to create a positive impact on your business using best practices, all while deploying a digital signage project in AEM Screens.

    See [Best Practices Guide for AEM Screens Projects](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html).

* **Headless Experience Management**

    Features of the [Remote Content Renderer](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) that is used for server side rendering of single page applications is now documented.

* **SPA and Server-side Rendering**

    You can extend and customize the remote content rendering service that your AEM-driven SPAs use for server-side rendering to meet your needs.

    See [SPA and Server-Side Rendering](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **AEM Project Archetype**

    The AEM Project Archetype creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. The properties that must be provided when using this archetype let you specify the names for all parts of this project as well as control certain optional features.

    See [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).
    
* **AEM Documentation Updates**

    Read about important documentation changes and updates for Adobe Experience Manager in the last three months.  
    
    See [AEM Documentation: Recent Documentation Updates](https://helpx.adobe.com/experience-manager/documentation-updates.html).

### Additional resources

* [AEM 6.5 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of AEM Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help Home](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media release notes](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre release notes](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Documentation resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Updated for October 12, 2019, release

| View | Feature |
|------|---------|
| Search Campaigns | Advertising Cloud can now sync and provide ad-level tracking for accounts on Yahoo! Japan Display Network. If you provide login details for an account, then all existing campaigns, ad groups, and ads in the account are available as read-only in the campaign management views. Click, cost, conversions, and other performance data are available within the campaign management views and in basic and advanced reports. |
| | (Advertisers with Google Analytics) Advertising Cloud Search can sync conversion metrics for a specific Google Analytics account, property, and view combination for optimization and reporting. Page views, Sessions, Bounce Rate (calculated as bounces/sessions), and Session Duration are automatically included. You can include up to 16 additional metrics per data source. |
| | (Existing Google Ads accounts for advertisers with an Advertising Cloud-Adobe Analytics integration) A new format is available for the s_kwcid tracking code, which allows Advertising Cloud to share data about the account with the Adobe Analytics reporting and analytics capability. The latest format includes parameters for campaign ID and ad group ID, which are necessary to accurately report at the campaign and ad group levels for Google Drafts and Experiments campaigns in Analytics. If your existing Google accounts includes Google Drafts and Experiments campaigns, edit the Account Tracking settings for each individual account to migrate to the new s_kwcid. If you don't have Google Drafts and Experiments campaigns, migrating to the new format is optional. Note: All new Google accounts automatically use the new  format. |
| Search Advanced Campaign Management (ACM) | (Google Ads campaigns) You can now configure campaign-level final URL suffixes for Google text ad and shopping ad templates. |
| | (Google Ads campaigns) Optional "Headline 3" and "Description 2" fields are available for Google expanded text ads. |
| Reports | The following Bing Ads impression share metrics, which were discontinued with the latest Bing Ads API, are not collected after October 11:  Search IS% Lost to Rank, Search IS% Lost to Bid (Bing), Search IS% Lost to Page Relevance (Bing), and Search IS% Lost to Keyword Relevance (Bing). Previously-collected metrics are still available for reporting. |
| Adobe Analytics Integration | (Advertisers with Adobe Analytics only) In Analysis Workspace, the “Device (AMO ID)” dimension, which has never collected data, is no longer available. To report on online Analytics data, use the dimension “Mobile Device Type.” To report on search engine traffic metrics (such as clicks, cost, and impressions) by device type, continue to use reporting in Advertising Cloud Search. |
