---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: September 2019
author: mfrei

---

# Early Access - September 2019 - Experience Cloud Release Notes

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>
>This page contains pre-release content and is subject to change prior to the September 12, 2019 release.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

## Release date: September 12, 2019

* [Experience Cloud interface](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Release notes for the Experience Platform, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Platform Launch](#launch)
* [Mobile Services and Mobile SDK](#mobile)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services and Mobile SDK {#mobile}

Release Date: **September 26th**
 
**iOS (4.18.8)**

* Fixed a bug where SDK data is synchronized to the paired watchOS app on every Analytics call.
* Fixed a bug where push click-through payload could not be used as traits for in-app messaging.
* Updated to user notification framework APIs instead of UILocalNotification API, which has been deprecated from iOS 10 onwards.
* Updated to WKWebView instead of UIWebView, which has been deprecated for iOS 12 onwards.
 
**Android 4.17.10**

* Added support for BCP 47 language tags.
 
**Unity**

* Plug-in updated to 4.18.7 for iOS and 4.17.9 for Android

## [!DNL Analytics] {#analytics}

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |  
|**Journey IQ: Cross-Device Analytics** | In September 2019, Adobe Analytics is introducing a powerful new feature called Journey IQ: Cross-Device Analytics. (Please note that this feature is available only to Analytics Ultimate customers.) Cross-Device Analytics (CDA) transforms Adobe Analytics from a device centric to a person-centric analysis tool. Using CDA you can answer questions such as: <ul><li>How many people are interacting with my brand? How many and what types of devices do they use? How do they overlap?</li><li>How often do people begin a task on a mobile device and then later move to a desktop PC to complete the task? Do campaign click-throughs that land on one device lead to conversion somewhere else?</li><li>How does my understanding of campaign effectiveness change if I take into account cross-device journeys? How does my funnel analysis change?</li><li>What are the most common paths users take from one device to another? Where do they drop out? Where do they succeed?</li><li>How does the behavior of users with multiple devices differ from the users with a single device?</li></ul><br/>To learn more, visit [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/).|
|**Updated Classifications architecture**|Starting in September, an update to the Classifications architecture will be migrated to customers over a period of several months. The September release includes migration for a small number of early adopters.<br/>The update significantly reduces the time it takes for uploads (including rule logic) to be imported/ingested and made available for reporting.|

#### Fixes

* Fixed an issue with the [!UICONTROL People] and [!UICONTROL Offers] core services not being accessible from the main Experience Cloud menu. (AN-184294)
* Fixed an issue with the left rail in [!UICONTROL Analysis Workspace] oscillating between having a scrollbar and having no scrollbar, which caused a fluttering effect. (AN-183904)
* Fixed issues with error reporting. You will start to see more specific error messages instead of just the red error indicator. More specifically, it should help you understand when the issue is caused by heavy load, by an error , or by creating a report request that is too complex. (AN-184135) [More…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* Fixed an issue that prevented the successful download of fallout reports in `.pdf/.xls/.rtf` formats. (AN-183165)
* Fixed issues with logging in through the Experience Cloud and switching to different Experience Cloud solutions or switching to another login company. (AN-183376)
* Fixed an issue with assets transfer of scheduled projects not working properly. Groups are managed in the [!UICONTROL Admin Console] now so we do not copy them between users when transferring assets anymore. (AN-183751)
* Fixed an issue with deleting scheduled reports whose owners have been deleted. From now on, a notification will go to the Admin (who performed the delete operation) when the schedule owner no longer exists. (AN-181000)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
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
| Update Adobe [!DNL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | 
|End of Support for TLS 1.0 | Updated January 10, 2019 | TLS 1.0 is no longer supported in |

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

New features, enhancements, and fixes in Audience Manager.

### New features and enhancements {#aam-features}

| Feature    | Description  |
| -----------| ---------- |  
|**[[!DNL People-Based Destinations]](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** |[!DNL People-Based Destinations] is a paid Audience Manager add-on that helps you activate first-party audience segments across people-based environments, like Facebook, using hashed identifiers, such as email addresses.|
|**[Configuring Twitter Tailored Audiences as a Self-Service Device-Based Destination](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)**|We're migrating Twitter destinations to a self-service configuration model. This article explains what you need to do for existing Twitter integrations to continue working after the migration.|
|**[Audience Marketplace Billing Examples](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)**|We added a new example, Case 3, where we detail how billing works for segments with activation and modeling use cases.|

**Fixes and Improvements**

* We fixed a bug where users were unable to edit Adobe Analytics destinations to map segments manually. (AAM-49323)
* We fixed a bug where duplicate Audience Marketplace feeds were originating from a single data source ID. There must be a 1:1 mapping between data sources and [!DNL Marketplace] feeds. (AAM-48504)
* We made an enhancement to the trait and segment creation workflow. Now, you can filter the data source to store the trait or segment, to exclude any non-Audience Manager data sources (for example, report suite data sources from Adobe Analytics). (AAM-35899)
* We fixed an issue in the Data Sources API where setting the query parameter `ExcludeReportSuites=true` did not exclude report suite data sources from Adobe Analytics. (AAM-48545)
* We made several improvements related to the accessibility of the Audience Manager User Interface. (AAM-49024) and (AAM-49031)
  
## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product release

**Cloud Manager 2019.8.0**

Cloud Manager release 2019.8.0 fixes a variety of minor bugs, improves build performance, and adds support for selective built content packages.

* [Release Notes for Cloud Manager 2019.8.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Product maintenance

**AEM maintenance release roadmap**

See the AEM maintenance release roadmap as published [here](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html).

### Self-Help

**Asset Link 1.1 prerelease**

* [About Adobe Asset Link Prerelease](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [Configuring AEM for Adobe Asset Link for prerelease](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

AEM Desktop App 2.0 for MAC was released 30 August 2019. AEM Desktop App 2.0 for Windows will release in early September.

Access documentation and downloads [here](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html).

**Assets Smart Tags**

Learn how to update a certificate after it has expired [here](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate).

**AEM 6.5 Screens User Guide**

New documentation on _Network Deployment Guidelines_ is now available. See the [User Guide](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html).

**Automated Forms Conversion Service**

Documentation for AEM Forms automated forms conversion service is now available. See [Introduction to Automated Forms Conversion service](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### Community

**AEM Skill Builder Webinars**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

    | Webinar    | Date  |
    | -----------| ---------- |  
    |_Authoring Web Experiences_ |27 August 2019|
    |_Search and Navigate Content_ |03 September 2019|
    |_Manage Every-Evolving Content Easily_ |10 September 2019|
    |_Fluid Experiences_ |17 September 2019|
    |_Create and Manage Multi-Lingual, Multi-National to Design a Global Website Structure_ |24 September 2019|

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

    | Webinar    | Date  |
    | -----------| ---------- |  
    |_Folder Structure and Search_ |29 August 2019|
    |_Metadata_ |05 September 2019|
    |_Brand Portal_ |12 September 2019|
    |_Dynamic Media_ |19 September 2019|
    |_Asset Link_ |26 September 2019|

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

    | Webinar    | Date  |
    | -----------| ---------- |  
    |Forms 101_|04 September 2019|
    |_Connect Forms to Databases, Build Workflows, and Integrate Forms with E-Signatures_|11 September 2019|
    |_Create Mobile-Responsive Web and Print-Ready Interactive Communications_|25 September 2019|

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

    | Webinar    | Date  |
    | -----------| ---------- |  
    |_Testing Best Practices &ndash; Build execution, monitoring, audit, and insights with Cloud Manager_ |18 September 2019|
    |_Dispatcher Configurations with Cloud Manager_|16 October 2019|
    |_Creating Workflows with Cloud Manager and Third-Party Tools_|13 November 2019|

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

### Product end-of-life

[!DNL Digital Publishing Suite Classic] (DPSC) will end-of-life on August 31, 2019. For more information, see the [[!DNL Digital Publishing Suite Classic] End-of-Life FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

### Additional resources

* [AEM 6.5 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older versions of AEM documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System release notes](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre release notes](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.5 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) – build 9033

### Adobe Campaign [!UICONTROL Control Panel]

We’ve added new capabilities for Admin users to receive notifications before SSL certificates for their domains expire. For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html).

Additionally, Admin users can now delete SSH keys that were added to access SFTP servers.

Please note that [!UICONTROL Control Panel] is available for both Adobe Campaign Classic and Adobe Campaign Standard customers hosted on AWS. No upgrades are required to access [!UICONTROL Control Panel].

### Additional resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
