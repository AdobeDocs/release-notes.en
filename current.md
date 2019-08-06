---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: August 2019
author: mfrei

---

# Early Access - Adobe Experience Cloud Release Notes

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>
>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE]
>
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

**Release date: August 2019**

* [Experience Platform and administration](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

## [!UICONTROL Experience Platform] and administration {#platform}

Release notes for the [!UICONTROL Experience Platform], Experience Cloud interface, product administration, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Cloud interface](#core-services)
* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Cloud interface {#core-services}

* Fixed a critical issue in Experience Cloud login that led to session logout for some users. (MCUI-6908)
* Updated Experience Cloud login to improve performance and reduce latency. (MCUI-6854, MCUI-6869, MCUI-6883)
* Updated interface cosmetically. (MCUI-6861, MCUI-6911, MCUI-6862)
* Fixed an issue with Experience Cloud [!UICONTROL Triggers] that led to incorrect interpretation of _Like_ clause in the [!UICONTROL Trigger] definition. (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

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
| Support for SameSite cookie settings  | The SameSite cookie setting will be added to all cookies sets by Analytics. This change allows you to be compliant with the Chrome changes requiring the SameSite cookie field. These changes are done server side, you will not need to update AppMeasurement to have the SameSite setting added. |
| Workspace: Increase item limit for dropdown filter from 50 to 200  | We increased the limit of items that can be placed in a dropdown filter from 50 to 200. This enhancement accommodates a variety of use cases, such as adding all countries (195) to a filter, or all US states and provinces (52). |

#### Fixes

* Fixed an issue with the text display in real-time reports when in full-screen mode. (AN-183168)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
| Classification rule builder limits | Added June 5, 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html).|
| New segment operator limits | Added May 31, 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. The limit will be applied to all new and modified segments after this date. Existing segments that exceed the limit will continue to be supported, but cannot be modified or saved until the input field is reduced. These limits are being applied as part of a continued effort to improve query performance. |
| Upcoming support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Updated May 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change will take effect with the July 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
| Upcoming change to _Report Total_ calculations | Updated July 9, 2019 | On **June 18, 2019**, Adobe Analytics will make _Report Total_ calculations consistent across all dimensions and metrics. This will result in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 18, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API. |
| Update to CSV downloads from [!DNL Analysis Workspace]| April 10, 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from [!DNL Analysis Workspace] to remove formatting from exported data.  <ul><li>The thousands separator is no longer included. The decimal separator will continue to be included, and will adhere to the format defined under **[!UICONTROL Components > Report Settings > Thousands Separator]**. Note: Numeric values that use a comma as the decimal separator will continue to be quoted in the exported CSV.</li><li>No currency symbols will be shown.</li><li>No percent symbols will be shown. Percentages will be in decimal form. E.g., 75% will be represented as 0.75.</li><li>Time will be shown in seconds.</li><li>Cohort tables will show raw values only; percentages will be removed.</li><li>If a number is invalid, an empty cell will be displayed.</li></ul>|
| Upcoming change to the [!DNL Analysis Workspace] Debugger command | April 4, 2019 | The Console command to turn on the [!DNL Analysis Workspace] Debugger is changing to adobeTools.debug.includeOberonXml on **June 13, 2019**. adobe.tools.debug.includeOberonXml will cease to function after that date. |
| Mobile browser version numbers | February 7, 2019 | Starting January 8, 2019, we changed the truncation level for mobile browser version numbers from 2 to 1. From that date forward, versions only display the first two levels (e.g. _Firefox 64.0.2_ is now reported as _Firefox 64.0_). |
| End of life for [!DNL Ad Hoc Analysis] | January 29, 2019 | On August 6, 2018, Adobe announced the intention to end-of-life [!DNL Ad Hoc Analysis]. An end-of-life date will be shared once available.<br/>For more information, including which versions of Java will be compatible during this period, visit [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | January 14, 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| End of Support for TLS 1.0 | Updated January 10, 2019 | As of February 11, 2019 Adobe Analytics reporting no longer supports TLS (Transport Layer Security) 1.0 encryption. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> As of February 20, 2019 Adobe Analytics data collection no longer supports TLS 1.0. With this change, Adobe no longer collects [!DNL Analytics] data from end users with older devices or web browsers that do not support TLS 1.1 or later. We do not expect this to have a significant impact on customer data or reporting. (If your website already does not support TLS 1.0, you will not be affected.) <br/>Beginning April 11, 2019, the Adobe Analytics Reporting API no longer supports TLS 1.0 encryption. Customers who access the API should verify that they will not be impacted. <ul><li>API clients using Java 7 with default settings will need [modifications to support TLS 1.2](https://www.java.com/en/configure_crypto.html). (Refer to _Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_.) </li><li>API clients using Java 8 should not be impacted, because the default setting is TLS 1.2.</li><li> API clients using other frameworks will need to contact their vendors for details on TLS 1.2 support.</li></ul>|
| Data Feed: post_product_list column - size change | January 9, 2019 | On February 7, 2019, Adobe expanded the size of the post_product_list column from 64 KB to 16 MB. This change ensures that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values. If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| Management changes affecting inactive [!DNL Analytics Live Stream] endpoints | December 20, 2018 | Starting on February 1, 2019, [!DNL Live Stream] endpoints with no active consumer connections for 90 days may be disabled. You can reach out to Customer Care to inquire about your [!DNL Live Stream] endpoints and, if necessary, have them re-enabled. In addition, please ensure your consumer processes maintain a persistent connection, as intended by the design of the service, and that they are implemented to reconnect when the connection is disconnected or interrupted. |
| Update Adobe [!DNL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that [!DNL Report Builder] users download version v5.6.21 prior to February 2019. After that date, prior versions of [!DNL Report Builder] will no longer function. |

### AppMeasurement {#appm}

[!UICONTROL AppMeasurement] 2.16.0 releases on August 8, 2019.

| Feature    | Description  |
| -----------| ---------- |
| `sendBeacon` support for exit links  | Implemented `sendBeacon` support in [!UICONTROL AppMeasurement] for exit links. This will improve exit link tracking and will likely result in increased traffic. |  
| ECID/fid values | ECID/fid values are now cached on the first hit even though OptIn settings change. |
| DIL 9.3  | Updated  Audience Management Module to DIL 9.3 |
| Scroll reach tracking  | Exposed switch in s.ActivityMap.trackScrollReach to turn scroll reach tracking on or off. |
| Visitor ID Service 4.4.0 | Upgraded AppMeasurement to use Visitor ID Service 4.4.0. |

#### Fixes

* Fixed a bug in AppMeasurement queuing that occurred before isReadyToTrack was true.

See [AppMeasurement release history](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) for a release history of AppMeasurement on the following platforms:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight, and .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**Fixes and Improvements**

* The Administration tab now only appears to user accounts with administrative privileges (AAM-48557).
* The List Users API now returns full user details (AAM-48662).
* You can now resize the trait folder list (AAM-48800).
* Multiple UI accessibility optimizations (AAM-48865, AAM-48933).
* Loading optimizations for the Administration and Data Sources pages (AAM-48514).

## [!DNL Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Adobe Campaign Standard

[Campaign Standard 19.3 Release](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Feature    | Description  |
| -----------| ---------- |  
| External API Activity (Public Beta)  | For deeper personalization, External API Activity allows you to bring data from external systems into a workflow via a REST API call. The REST endpoints can be a customer management system, Adobe I/O Runtime or Adobe Experience Cloud REST endpoint (e.g. Data Platform, Target, Analytics, Campaign). This capability is currently in public beta. For more information, refer to the [detailed documentation](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) and the [how-to video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html).|  
| Report on workflow segment  | This feature allows marketers to break down their delivery performance by segment code. When you create a workflow and use a segmentation activity to assign segments to the delivery population, these segments can now go into the same delivery. This allows you to display the opens/clicks statistics based on multiple segments within a single delivery. For more information, refer to the [detailed documentation](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) and the [how-to video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html).|

### Adobe Campaign Classic

[Campaign Classic 19.1.3 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9031

### Adobe Campaign Control Panel

[New Control Panel capabilities](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) include the ability to add URLs that Campaign Classic connects to for data/file transfers.

Please note that [!UICONTROL Control Panel] is available for both Adobe Campaign Classic and Adobe Campaign Standard customers hosted on AWS. No upgrades are required to access Control Panel.

### Additional resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
