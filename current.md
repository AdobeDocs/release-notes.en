---
description: New features and fixes in the Adobe Experience Cloud.
seo-description: New features and fixes in the Adobe Experience Cloud.
seo-title: Adobe Experience Cloud Release Notes
solution: Release Notes,Marketing Cloud,Analytics,Social,Target,Media Optimizer
title: Adobe Experience Cloud Release Notes
topic: Release notes
uuid: c56a1064-0f2c-4241-93c6-ca4b1f267763
---

# [!DNL Adobe Experience Cloud] release notes

New features and fixes in the [!DNL Adobe Experience Cloud]. 

<!--
>[!IMPORTANT]
>This page contains pre-release content and is subject to change prior to the November release.
-->

>[!NOTE]
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

**November 2018**

Latest update: **December 4, 2018**

+ [Adobe Cloud Platform](#acp)
+ [Analytics Cloud](#analytics-cloud)
+ [Marketing Cloud](#marketing-cloud)
+ [Advertising Cloud](#advertising-cloud)

## [!DNL Adobe Cloud Platform]{#acp}

Release notes for the Experience Cloud interface and [!UICONTROL platform] core services. Includes Mobile Services, Launch, by Adobe, Dynamic Tag Management, GDPR API, and Experience Cloud ID Service.

### [!UICONTROL Dynamic Tag Management]

[!DNL Adobe] plans to sunset [!UICONTROL Dynamic Tag Management] by the end of 2020. For more information and scheduling, see [DTM Plans for a Sunst](https://forums.adobe.com/community/experience-cloud/platform/launch/blog/2018/10/05/dtm-plans-for-a-sunset).

## [!DNL Analytics Cloud]{#analytics-cloud}

+ [Analytics](#analytics-update)
+ [Audience Manager](#audience-manager)

### [!DNL Analytics]{#analytics-update}

New features and fixes in [!DNL Adobe Analytics]:

+ [Analysis Workspace](#analysis-workspace)
+ [Media Analytics SDK for iOS & Android (formerly VHL SDK)](#media-analytics-sdk)
+ [Analytics fixes and updates](#analytics-fixes)
+ [Important notices for Analytics administrators](#analytics-admins)

For product documentation, see [Analytics Help Home](https://marketing.adobe.com/resources/help/en_US/reference/).

#### [!UICONTROL Analysis Workspace]{#analysis-workspace}

|Feature|Description|
| -----------| ---------- |  
| [Changes to VRS/project curation](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/curate-projects-vrs.html) | (Implemented September 2018.) Changes were made to which components administrators and non-administrators can see in curated Workspace projects and curated virtual reports suites (VRSs). Previously, anyone could see non-curated components when clicking **[!UICONTROL Show all Components]**. The updated curation experience allows for more fine-grained control over which components are visible. |  
| Adobe [!DNL Analytics] and General Data Protection Regulation (GDPR) | [!DNL Analytics] supports a new method for passing the legacy [!DNL Analytics] visitor ID to a GDPR request (see [AAID](https://marketing.adobe.com/resources/help/en_US/analytics/gdpr/gdpr_namespaces.html)). Also, [!DNL Analytics] now supports [deleting (anonymizing) the Purchase ID value](https://marketing.adobe.com/resources/help/en_US/analytics/gdpr/gdpr_labels.html) as part of a delete request. |
| [GDPR/ePrivacy enhancements to server-side forwarding](https://marketing.adobe.com/resources/help/en_US/analytics/audiences/ssf-gdpr.html) | Prompted by the [EU cookie compliance regulation](http://ec.europa.eu/ipg/basics/legal/cookies/index_en.htm), data controllers ([!DNL Analytics] customers) now have the option to restrict pre-consent data to Adobe [!DNL Analytics], and prevent it from being server-side forwarded to Adobe Audience Manager (AAM). A new implementation context variable lets you flag hits where consent has not been received. The variable, when set, prevents these hits from being sent to AAM until consent has been received. | 

### [!UICONTROL Media Analytics SDK] for [!DNL iOS] & [!DNL Android] (formerly VHL SDK){#media-analytics-sdk}

| Feature    | Description  |
| -----------| ---------- |  
| [!UICONTROL Adobe Analytics for Audio] | Connects a listener's streaming audio engagement with their full digital behavior. You can understand who's listening where, when, and how often, and evaluate user behavior in a commonly fragmented audio marketplace. This feature enables businesses to measure the reach of their listeners, measure the popularity of their content, and provides insight into how to keep users engaged based on their behaviors and look-alike modeling. Measure 10-second audio content and 1-second streaming ads with our best-in-class SDKs, to evaluate both quality of experience (stall, errors, time to start) and content plus ad KPIs. |  
| Maintaining Ad Breaks  | Enhanced Ad tracking in scenarios where if a player has entered an ad break, and no calls are sent for a certain period of time, the SDK logic will default back to content playback, even if the player is still in an ad break state. During a pre-roll ad, this may result in a content start firing before the ad break is complete. In Media 2.2 SDK, buffer calls will be sent between ads within an ad break when there is a long delay between ads. | 
| SDK Name Change  | Starting with the 2.2 release, the Video Heartbeat Library (VHL) SDKs are renamed to Media SDK. The Media 2.2 SDK is fully backwards compatible with the VHL 2.X SDK series. The name change does not represent a functional break, simply a change in naming convention. | 

#### [!DNL Analytics] Fixes and Updates{#analytics-fixes}

**[!UICONTROL Analysis Workspace]**

+ Fixed an issue where in **[!UICONTROL Create metric from selection]** and **[!UICONTROL Compare attribution models]**, the [!UICONTROL Percent Change] calculated metric was incorrect. (AN-170471)

**Other [!DNL Analytics] Fixes**

+ [!UICONTROL Calculated Metrics]: Fixed an issue related to copying calculated metric parameters. (AN-169648)
+ [!UICONTROL Calculated Metrics]: Fixed a localization issue in the calculated metric preview. (AN-165086)

#### [!UICONTROL Data Workbench]{#data-workbench}

See [Data Workbench release notes](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/) for the latest information.

#### Important Notices for [!DNL Analytics] administrators{#analytics-admins}

| Notice | Description |
| -----------| ---------- | 
| Dallas FTP server migration (ftp2.omniture.com)<br></br>October 19, 2018 | On October 23, 2018, if you connect to ftp2.omniture.com via the SFTP protocol, you might be required to re-accept the SJ1 site's host identifier. This issue applies only to October 23.<br></br>See [Upgrading Adobe FTP Servers](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/ftp_upgrade.html). |
| Update to Mobile Device dimension<br></br>October 16, 2018 | On September 26, Adobe updated its device lookup to Device Atlas's 2.1 API. This caused more detailed devices (e.g. Apple iPhone 7, Apple iPhone 8 Plus, etc.) to appear in the Mobile Device dimension for some browsers. This new level of device detail should be used directionally as is does not extend to all devices and browser types at this time. | 
| End of support for Internet Explorer 11<br></br>Sept. 12, 2018 | Adobe will end support for Internet Explorer 11 within Adobe [!DNL Analytics] on November 13, 2018. Please switch to Microsoft Edge or another supported browser as soon as possible. |
| Data Feed: post_product_list column - size change<br></br>Sept. 12, 2018 | In January 2019, Adobe plans to expand the size of the post_product_list column from 64 KB to 16 MB. This change is intended to ensure that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values.<br></br>If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| End of life for Ad Hoc Analysis<br></br>August 9, 2018 | On August 6, 2018, Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).<br></br>We will not modify Ad Hoc Analysis to support Java 9+ from this point forward. If you upgrade to Java 9+, Ad Hoc Analysis will cease to function. Only Java 8 will be supported. |
| End of Support for TLS 1.0<br></br>Sept. 7, 2018 | To minimize customer impact, we are delaying Adobe [!DNL Analytics] Reporting’s end of support for TLS 1.0 encryption. Starting in February, 2019, Adobe [!DNL Analytics] Reporting will no longer support TLS (Transport Layer Security) 1.0 encryption. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. Because the [!DNL Analytics] reporting interface already requires a modern web browser, we do not anticipate issues. If you are unable to connect to **Adobe [!DNL Analytics] reporting** after February 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br></br>Starting February 2019, **Adobe [!DNL Analytics] Reporting API** will no longer support TLS 1.0 encryption. Customers who access the API should verify that they will not be impacted.<ul><li>API clients using Java 7 with default settings will need [modifications to support TLS 1.2](https://www.java.com/en/configure_crypto.html). (Refer to “Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2”.)</li><li>API clients using Java 8 should not be impacted because the default setting is TLS 1.2.</li><li>API clients using other frameworks will need to contact their vendors for details on TLS 1.2 support.</li></ul><br>Starting February 2019, Adobe [!DNL Analytics] Data Collection will no longer support TLS 1.0. With this change, we will no longer collect [!DNL Analytics] data from end users with older devices or web browsers that do not support TLS 1.1 or later.<br></br>**Note:** If your web site does not support TLS 1.0, you will not be impacted by the collection change. |
| Update Adobe [!UICONTROL Report Builder] due to end of support for TLS 1.0<br></br>Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that Adobe [!UICONTROL Report Builder] (ARB) users download ARB v5.6.21 prior to February 2019. After that date, prior versions of ARB will no longer function. |
| New help for the [!DNL Analytics] user migration<br></br>May 10, 2018 | We updated the [!DNL Analytics] user ID migration help with information about migrating Enterprise and Federated IDs to the Admin Console.<br></br>See [Migrate [!DNL Analytics] user accounts for Enterprise and Federated IDs.](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html) |
| Upcoming removal of Account Activity Report<br></br>May 10, 2018 | The Account Activity Report will be replaced by the Server Call Usage feature in the Adobe [!DNL Analytics] Summer Release. The Account Activity Report will be permanently removed on August 9, 2018. To view summary data about report suite traffic after August 9, 2018, use the Server Call Usage feature. |
| Changes to linear allocation models in [!UICONTROL Calculated Metrics]<br></br>May 10, 2018 (Effective July 19, 2018) | On July 19th, Adobe [!DNL Analytics] will revise the way allocation models in calculated metrics are evaluated. As part of this change, calculated metrics that use a non-default allocation model will be migrated to new and improved attribution models.<br></br>Marketing Channel Last Touch and Marketing Channel First Touch allocation models will be migrated to new Last Touch and First Touch attribution models respectively. (Marketing Channels are not being deprecated, only the two allocation models that appear in calculated metrics).<br></br>Additionally, we will correct the way linear allocation is calculated. If you use calculated metrics with linear allocation models, the reports may change slightly to reflect the new, corrected attribution model.<br></br>This change to calculated metrics will be reflected in [!UICONTROL Analysis Workspace], [!UICONTROL Reports & Analytics], the Reporting API, [!UICONTROL Report Builder], and Ad Hoc Analysis.<br></br>See the [Calculated Metrics documentation](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html) for more information about this change. |
| Anomaly Detection and Contribution Analysis functionality removed from [!UICONTROL Reports & Analytics]<br></br>April 10, 2018 | Anomaly Detection and Contribution Analysis have been removed from the [!UICONTROL Reports & Analytics] feature set and are now available only via [Analysis Workspace](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/virtual-analyst.html).<br></br>Adobe [!DNL Analytics] Select and Foundation customers have access only to “daily-granularity” [Anomaly Detection](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/anomaly_detection.html) in [!UICONTROL Analysis Workspace] help. |
| Adobe no longer issuing 3rd-party s_vi cookies for Safari<br></br>April 05, 2018 | On March 20, 2018, Adobe stopped issuing third-party s_vi cookies for the Safari browser. This change does not impact customers using first-party data collection cookies. This change also removes the visit and visitor inflation experienced by some customers, resulting from Safari ITP. |
| Update [!UICONTROL Report Builder] before you migrate user IDs to the Admin Console<br></br>March 17, 2018 | Update your installation of [!UICONTROL Report Builder] to the latest version. This update is a pre-requisite for running the [!DNL Analytics] user ID migration to the Admin Console, beginning in April 2018.<br></br>See [Analytics User Migration to the Admin Console](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/) for migration information. |
| Back-end changes that affect reporting<br></br>April 11, 2018 | A change to the (back-end) lookup mechanism is going to impact reporting in several ways. Please be aware that these changes went into effect around the end of February, 2018:<ul><li>Page renaming will no longer be allowed. Going forward, you will need to use classifications to rename pages. Until the May 10, 2018 release, the system will continue to process the renamed pages as they are currently configured. Adobe is asking all customers to migrate to classifications by that date. After the May release, existing renames will no longer be honored and can change, retroactively, without notice.</li><li>The URL replacement methodology is different. Previously, Adobe [!DNL Analytics] would store (mostly) the first URL associated with each page name each month. Going forward, we will store the most recent URL for each page name.</li><li>(Updated April 11, 2018) Category reports for roll-ups and current data in [!UICONTROL Reports & Analytics] are no longer provided. Deprecating category roll-up reports in the Web Service API is effective with the May 10, 2018, Adobe [!DNL Analytics] maintenance release.</li><li>There is no longer any support for page/prop data from before approximately January 2007 (in some cases, 2006). This only impacts pages, props and page events (i.e. custom links, exit links, download links). (This change does not impact reporting in [!UICONTROL Analysis Workspace] or Data Warehouse.)</li></ul><br></br>If you have data preceding these dates, data will not combine correctly across the pre/post January 2007 boundary, and searches will not work against data before approximately January, 2007. |
| Upcoming support changes for Date-Enabled and Numeric Classifications<br></br>May 7, 2018 | In the May 10, 2018 Maintenance release, we will begin limiting the functionality of date-enabled and numeric classifications. These classification types will be removed from the Admin and Classification Importer interfaces.<br></br>From that date on, no new date-enabled and numeric classifications can be added. Existing classifications can still be managed (uploaded to, deleted) through the standard classification workflow, and will continue to be available in reporting. |
| Upcoming support changes for Marketing Channel Cost and Budget<br></br>February 28, 2018 | In the April maintenance release, we will remove Marketing Channel Cost and Budget from the **Admin** > **Marketing Channel** menu. No new cost and budget data can be added. Existing cost and budget data will continue to be available in reporting, but cannot be updated. |
| Code Manager - Legacy H Code<br></br>February 8, 2018 | Downloading legacy JavaScript (H code) from the Code Manager is no longer supported. |
| Data retention: Check and set your data retention policy for Adobe [!DNL Analytics]<br></br>February 1, 2018 | **Background**<br></br>The European Union’s General Data Protection Regulation (GDPR), which applies as from May 25, 2018, provides that Adobe, in its role as your data processor, must take appropriate measures to assist its customers in fulfilling access, deletion, and other requests from individuals. Applying appropriate, secure, and timely deletion policies is an important part of complying with this obligation. As a result, Adobe would like to work with you to implement a data retention policy before GDPR takes effect on May 25, 2018.<br></br>**What to expect**<br></br>Unless you already have an Adobe [!DNL Analytics] data retention policy in place, Adobe will begin applying data retention as currently specified in customer contracts for Adobe [!DNL Analytics], unless other arrangements are made.<br></br>Most Adobe [!DNL Analytics] contracts state that Adobe may delete data after 25 months. Once a data retention policy is in place for your organization, it is enforced on a rolling monthly basis. Data retention for longer periods than 25 months is available for an additional fee. Data retention periods for shorter periods can also be configured by contacting Customer Care.<br></br>You will soon receive an email with additional details for your organization.<br></br>Data retention impacts all methods for accessing historical Adobe [!DNL Analytics] data, including but not limited to [!UICONTROL Reports & Analytics], [!UICONTROL Analysis Workspace], [!UICONTROL Report Builder], the Web Services Reporting APIs, data warehouse, and data feeds.<br></br>**Next steps**<br></br>Identify stakeholders within your organization responsible for making decisions about data retention. Your organization is best placed to know the appropriate period for which Adobe [!DNL Analytics] data should be retained.<br></br>Contact your Adobe Customer Success Manager if you have questions regarding data retention for Adobe [!DNL Analytics]. |
| User account linking<br></br>October 26, 2017 | [!DNL Analytics] users no longer need to manually link their accounts between the Experience Cloud and [!DNL Analytics]. Users can contact their Admin Console administrator to request [!DNL Analytics] access.<br></br>The [!DNL Analytics] user ID migration enables administrators to easily migrate user accounts from [!DNL Analytics] User Management to the Adobe Admin Console. After your users are migrated, they will have access to the purchased solutions and core services available in the Experience Cloud.<br></br>[Learn more about the [!DNL Analytics] User ID migration](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/). |

### [!DNL Audience Manager]{#audience-manager}

New features and fixes in Adobe Audience Manager.

| Feature    | Description  |
| -----------| ---------- |  
| [IRIS Optimizations](https://marketing.adobe.com/resources/help/en_US/aam/c_compact.html)  | See **Segment Mapping Rules** for more information on the set of rules that IRIS follows when sending segments to destinations. Go to [IRIS > Segment Mapping Rules](https://marketing.adobe.com/resources/help/en_US/aam/c_compact.html). |  
| [Trait Exclusions in Algorithmic Modeling](https://marketing.adobe.com/resources/help/en_US/aam/trait-exclusion-algo-models.html)  | With Trait Exclusions, you can remove traits from modeling. This way, extremely common traits such as site visitor traits don't bias your model. This new capability also enables you to remove traits from third-party data feeds. |
| [Audience Lab Advanced Functionality](https://marketing.adobe.com/resources/help/en_US/aam/audience-lab-advanced.html) - **Duplicate Allocation Template** and **Test Segment Holdout** | We released two features to increase your productivity when using Audience Lab. Learn how to get started with them in [Audience Lab Advanced Functionality](https://marketing.adobe.com/resources/help/en_US/aam/audience-lab-advanced.html). |

**Fixes, enhancements, and deprecations**

+ We updated the name of the Outbound History Report to Outbound File History Report. The previous name caused some customers to think the report would show outbound data for HTTP destinations. In fact, the report covers files delivered to S3 or FTP locations.

**Known issues**

+ The latest version of Safari includes Intelligent Tracking Prevention (ITP) 2.0 tools. This affects Addressable Audience metrics for your Safari users and data collection using the h_referer signal. Read about Safari traffic as a [Cause of Low Match Rates for Addressable Audiences](https://marketing.adobe.com/resources/help/en_US/aam/addressable-audiences-match-rates.html) and [data collection using the h_ prefix](https://marketing.adobe.com/resources/help/en_US/aam/r_tb_variable_prefixes.html).
+ The release of [Trait Exclusions in Algorithmic Modeling](https://marketing.adobe.com/resources/help/en_US/aam/trait-exclusion-algo-models.html) introduced an issue for customers using [Role-Based Access Controls](https://marketing.adobe.com/resources/help/en_US/aam/c_administration.html) . When creating a new model, if you only select data sources that you have access to, you can see their corresponding traits in the **Exclusions** window. However, if you select any other data sources than the ones you have access to, in addition to the ones that you have access to, you will see a blank list. Unselect the data sources that you don't have access to in order to see the traits. (AAM-42380)

**Documentation Updates**

+ We added definitions and examples for all the metrics in the General Reports. Read our [General Reports documentation](https://marketing.adobe.com/resources/help/en_US/aam/c_general_reports.html).
+ We updated the Addressable Audience documentation to clarify the difference between customer-level and segment-level metrics. Read our [Addressable Audience documentation](https://marketing.adobe.com/resources/help/en_US/aam/addressable-audience-metrics.html).

## [!DNL Marketing Cloud]{#marketing-cloud}

+ [Experience Manager](#aem)
+ [Target](#target)
+ [Campaign](#ac)

### [!DNL Experience Manager]{#experience-manager}

New features, fixes, and updates in [!DNL Adobe Experience Manager]. Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

#### Product releases

+ AEM Dispatcher 4.3.1

Adobe strongly recommends using the latest version of AEM Dispatcher to avail the latest functionality, the most recent bug fixes, and the best possible performance.

See the [AEM Dispatcher Release Notes](https://helpx.adobe.com/experience-manager/dispatcher/release-notes.html).

#### Self help

+ Configuring AEM Assets integration with Experience Cloud and Creative Cloud

The documentation for configuring the AEM Assets integration with Experience Cloud and Creative Cloud has been updated. If you use this integration, Adobe recommends that you update the configuration to point to experiencecloud.adobe.com instead.

See also: [Configure AEM Assets integration with Experience Cloud](https://helpx.adobe.com/experience-manager/6-4/sites/administering/using/configure-assets-cc-integration.html) and [Creative Cloud and AEM and Creative Cloud Integration Best Practices](https://helpx.adobe.com/experience-manager/6-4/assets/using/aem-cc-integration-best-practices.html).

#### Community

+ Experience League: Fast-track your Adobe Experience Cloud Expertise

Learning any new software can be challenging. Even after the initial training, there may be a lot to learn and you may not know where to start or who to ask for help.

When it comes to learning [Adobe Experience Cloud](https://www.adobe.com/experience-cloud.html), you can expect a different experience. Unlike any other guided learning program out there, our [Experience League](https://landing.adobe.com/experience-league/) enablement program is uniquely tailored to your individual needs—and it's free for everyone. Experience League just launched Business Essentials for most of the solutions in Experience Cloud (two for AEM). It is also coming up with Implementation essentials very soon.

For more information see the following: [https://adobe.ly/2AmFaUT](https://adobe.ly/2AmFaUT).

#### Additional resources

+ [AEM 6.4 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-4.html)
+ [AEM 6.3 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-3.html)
+ [AEM 6.2 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-2.html)
+ [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
+ [Older versions of AEM documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
+ [Scene7 Publishing System release notes](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
+ [Livefyre release notes](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### [!DNL Target]{#target}

Refer to the [Adobe Target Release Notes](https://marketing.adobe.com/resources/help/en_US/target/rn/target_release_notes.html) for the latest release information about the following products:

+ [!DNL Target] Standard
+ [!DNL Target] Premium
+ [!DNL Recommendations] Classic

### [!DNL Campaign]{#campaign}

[!DNL Adobe Campaign] provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

#### [!DNL Adobe Campaign] Classic 18.10

Availability: November 5, 2018

| Feature    | Description  |
| -----------| ---------- |  
| Push notification improvements  | A number of enhancements has been implemented for push notifications in Adobe Campaign:<ul><li>Track silent notifications in iOS</li><li>Implement feedback on registration calls in [!DNL iOS]</li><li>Improve [!DNL iOS] delivery preparation speed</li></ul><br></br>As a part of GCM depreciation by [!DNL Google], [!DNL Android] V2 connector now allows connections only to the FCM server. |  
| SQL Data Management activity  | A new data management workflow activity has been added. The SQL Data Management activity lets you write or copy-paste your own SQL scripts to create and populate work tables (FDA only). | 
| Workflow monitoring  | With the new Adobe Campaign Workflow HeatMap, the platform administrators have a quick graphical representation of all the concurrent workflows, which allows them to monitor the load on the instance and plan workflows accordingly. | 

For product documentation, see:

+ [Adobe Campaign Classic Release Notes](http://docs.campaign.adobe.com/doc/AC/en/RN.html)
+ [Adobe Campaign Classic Learn & Support](https://helpx.adobe.com/support/campaign/classic.html)
+ [Adobe Campaign Standard Release Notes](https://helpx.adobe.com/campaign/standard/rn/rn.html)
+ [Adobe Campaign Standard Learn & Support](https://helpx.adobe.com/support/campaign/standard.html)
