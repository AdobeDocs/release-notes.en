---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: January 2020
author: mfrei

---

# INTERNAL REVIEW - Adobe Experience Cloud Release Notes - January 2020

New features and fixes in the Adobe Experience Cloud.

> [!NOTE] Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

**Release date: January, 2020**

* [Experience Cloud interface](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)
* [!DNL Advertising Cloud](#adcloud) (Updated 11/8)

Looking for the help home? See [Adobe Experience Cloud Documentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status.adobe.com

Using your Adobe ID, you can subscribe to status event notifcations, based on your produts, region, and event preferences.

| Feature    | Description  |
| -----------| ---------- |
|Subscribe to real-time email notifications | <ul><li>Support for Experience Cloud, Creative Cloud, Document Cloud, AEP, and Adobe Services</li><li>Support for region and event type preferences</li><li>UX support for Web, mobile, and tablet surfaces</li></ul> |
|Notifications preferences management | <ul><li>Edit and save notification preferences at any time</li><li>Unsubscribe from notifications at any time</li><li>Item</li></ul> |
|Personalized and faster email delivery | <ul><li>Event notifications are sent as soon as CSOs and CMRs are opened, updated or closed</li><li>Receive only the relevant event notifications matching your configured preferences</li><li>Received localized notifications based on the language configured in in your account preferences</li></ul> |
|Personalized in-product notifications | Events matching your notification preferences and product entitlements appear in the Announcement panel.|

## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Item
* Item

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Release notes for the Experience Platform, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Platform Release Notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices) (**Updated Dec. 18, 2019**)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- | 
| | |

#### Fixes

* Fix
* Fix

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics will move to new domain - https://experience.adobe.com/analytics. This change may cause cookie issues when loading Analytics in Safari. Unchecking "Prevent cross-site tracking" in the Safari Privacy Preferences will enable cookies across domains (and all cross-site experiences), and allow Analytics to function on this new Adobe Experience Cloud domain. Users can use other browsers without issue, since this only affects Safari users.|
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
| Change to _Report Total_ calculations | Updated July 9, 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. This resulted in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 18, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API.<br>**Note**: This _Report Total_ calculation is now called _Grand Total_. See "Analysis Workspace: Update to Freeform table totals" above. |
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

### New features, enhancements, and fixes in Audience Manager {#aam-new-features}

| Feature | Description |
|--- |----|
| | |

### Enhancements {#aam-enhancements}

For more information, please contact your Audience Manager consultant or Customer Care.

### Fixes and Improvements {#aam-fixes-and-improvements}

* Fix
* Fix
  
## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

### Self-help

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

| View | Feature |
|------|---------|
| | |
