---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: February 2020
author: mfrei

---

# INTERNAL REVIEW - Adobe Experience Cloud Release Notes - February 2020

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE] 
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

**Release date: February 20, 2020**

(Specific product release dates my vary)

* [Adobe System Status](#status)
* [Experience Cloud interface and core services](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services and Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics)<!-- * [Audience Manager](#aam) -->
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

Looking for the help home? See [Adobe Experience Cloud Documentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

**What's new**

* Using your Adobe ID, you can subscribe to event notifications based on your product, region, event, and language preferences. Users who configure their subscription preferences are notified of relevant product incident and maintenance events as soon as they are opened, updated, or closed. Get started at [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**New features and enhancements available today**

| Feature    | Description  |
| -----------| ---------- |
|Faster awareness of product events | <ul><li>Get informed 30 days in advance of upcoming service maintenance. This feature provides more lead time to assess the potential impact on your business operations, enabling you to implement a mitigation plan if necessary.</li><li>Advanced notifications are available on Web/mobile/tablet surfaces and via email notifications.</li></ul> |
|Personalize your experience based on preferred language | <ul><li>Choose a preferred language for email notifications. The Self-subscription feature is now available in nineteen languages.</li></ul> |
|Improved subscription and notification user experience | <ul><li>Specify the region and event preferences in just one click for all products to which you want to subscribe.</li><li>Get notified when _Potential_ issues are promoted to _Minor_ or _Major_ ones.</li><li>The browser page automatically refreshes when any product or event status is updated.</li></ul> |

## Experience Cloud interface and core services {#ecloud}

New features and fixes in the Experience Cloud interface, including administration and core services (customer attributes, audiences, triggers, cookies, and so on).

### Unified product domain

Adobe is updating the domain and interface header to unify and improve your experience across all Experience Cloud applications. These enhancements are designed to simplify your experience in small but important ways. These enhancements will not change your current workflows.

Updates include:

* New solution URLs: `experience.adobe.com/<application name>`:
  * All products will eventually adopt this URL pattern. Look for new URLs to become effective throughout the month.
  * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Note:** Although the Experience Cloud interface supports these browsers, individual solutions might not support every browser. (For example, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) does not support [!DNL Opera], and [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) does not support [!DNL Safari].)
  * ([!DNL Safari] only) The domain change may cause cookie issues in [!DNL Safari]. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Easier switching between your organizations or to a different application.
* Improved product help: [!UICONTROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. This change simplifies access to more content and helps you get the most out of Experience Cloud. Additionally, click **[!UICONTROL Help]** > **[!UICONTROL Feedback]** to report issues or share your ideas with Adobe.  
* Improved notifications: The [!UICONTROL Notifications] drop-down menu now has two tabs, one for your own product notifications and one for global product announcements.

**Note:** The [!UICONTROL Feed] page is being deprecated in January, 2020. Look for an in-product deprecation notice.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Release notes for the Experience Platform, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Platform Release Notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## Mobile Services and Mobile SDKs {#mobile}

**Feburary 4, 2020: Version 4.19.0**

The following update was made in this release:

**Lifecycle:** Added a new API, `pauseCollectingLifecycleData`, to mitigate the abnormal session length data that was reported from some old iOS devices.

## [!DNL Analytics] {#analytics}

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* New **Workspace template for organizations using Cross-Device Analytics:** This template shows how effective CDA is at stitching visits together and educates you on CDA-exclusive dimensions and metrics. A report suite using CDA is required. See [Setting up Cross-Device Analytics](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) for more information.
* **CDA stitching latency for organizations using the Private Graph is reduced to one day:** Private Graph functionality has been enhanced to reduce graph generation latency from a weekly batch process to a daily refreshed graph, allowing CDA customers to access more up to date identity graphs and linkages.
* **New hotkeys in Workspace:**<ul><li>Collapse/Expand All panels: `alt + m`</li><li>Collapse/Expand Active panel: `alt + ctrl + m`</li><li>Search left rail: `ctrl + /`</li><li>Move to next panel: `alt + Right Key`</li><li>Move to previous panel: `alt + Left Key`</li></ul>[Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **Other Workspace enhancements:**<ul><li>When a panel or visualization is dropped into [!UICONTROL Workspace], the left rail auto-switches to components for a more seamless workflow.</li><li>Template components can now be actioned upon (e.g. tagged, marked as favorite, approved).</li><li>Filtered metric and segment lists offer the `+` button to add a new component if you don't find what you need.</li></ul>

#### Fixes

* Fixed an issue with Segment UI saying that [!UICONTROL Marketing Channel] dimensions were compatible with [!UICONTROL Data Warehouse], when in reality they are not. In the future, the [!UICONTROL Segment Builder] will no longer show these dimensions as being [!UICONTROL Data Warehouse] compatible. (AN-202297)
* Fixed an issue with the name of a published segment that was updated in Analytics not getting updated in Audience Manager within 24 hours. (AN-199974)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics began moving to a new domain - `https://experience.adobe.com/analytics.`<br>**Note:** This change applies to all users accessing Analytics with their Adobe ID or Enterprise ID. <ul><li>The domain change may cause cookie issues when loading Analytics in Safari. Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. You can use other browsers without issue because this affects only Safari users.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul>|
|End of Life - Analytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs.|
|EOL of **[!UICONTROL View Archive]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the **[!UICONTROL View Archive]** option in the Dashboard Manager (**[!UICONTROL Components > Dashboards]**).|
|EOL of **[!UICONTROL Enforce IP Login Restrictions]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the IP login whitelisting (**[!UICONTROL Enforce IP Login Restrictions]**) functionality under the **[!UICONTROL Admin > Company Settings > Security]** menu.|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|Upcoming change regarding `createDate` field for Analytics users|August 30, 2019|In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468)|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.18.0 was released on February 13, 2020.

## Audience Manager {#aam}

Fixes and features added to Audience Manager.

### New features, enhancements, and fixes in Audience Manager {#aam-features}

|Feature|Description|
|----|----|
|[Activity Usage Reporting](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html)|The [!UICONTROL Activity Usage Report] helps you view and track the activity usage of your Audience Manager instance, giving you a clear idea of how your activity usage compares to your contractual commitment.|

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixes
* Fixes -->

## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

* **Cloud Manager 2020.2.0**

    Cloud Manager 2020.2.0 simplifies the self-service management of sandboxes for Adobe Experience Manager as a Cloud Service.

    See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Self-Help

* **AEM Forms interactive communication Batch API**

    Batch API of AEM Forms interactive communication lets customers produce multiple interactive communications, automatically or on-demand. Customers can generate Print and Web outputs simultaneously.
    See [Generate multiple interactive communications using Batch API](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html).

* **Supported Platforms for AEM Forms on JEE**

    Added support for Oracle 19c for AEM Forms on JEE customers.
    See [Supported Platforms for AEM Forms on JEE](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html).

### Additional resources

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### Campaign Classic 19.2.3

See [Adobe Campaign Classic Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) for fixes and improvements.

### Campaign Standard 20.1

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Additional resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign Control Panel: [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Updated February 10, 2020, for February 8 release

| View | Feature |
|------|---------|
| Portfolios | You can now add Yahoo! Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. The same bid is applied to all ads in an ad group. Data for YDN campaigns is included in the simulations for the portfolio. |
| Search > Bulksheets  | You can now create, edit, and delete Google responsive search ads (RSAs) using bulksheets. Previously, support was available only through the standard campaign management interface at Search > Campaigns |
| Search > Campaigns, Reports | The Google Ads prominence metrics “Impr. (Abs. Top) %” and “Impr. (Top) %” are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the Campaign Daily Impression Share and Keyword Daily Impression Share reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

For Magento release notes, see:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
