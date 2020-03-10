---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: March 2020
author: mfrei

---

# Early Access - Adobe Experience Cloud Release Notes - March 2020

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE] 
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

**Release date: March 2020**

(Specific product release dates my vary)

* [Adobe System Status](#status)
* [Experience Cloud interface and core services](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey)
* [Mobile Services and Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [New documentation and tutorials](#selfhelp)

Looking for the help home? See [Adobe Experience Cloud Documentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

**What's new**

* Using your Adobe ID, you can subscribe to event notifications with more granularity, down to the product offering and add-on level. Look for this new capability in Experience Cloud products, where the self-subscription process displays sub-offerings for the products and services to which you want to subscribe. This enhancement should significantly reduce the volume of notifications you receive, and make the notifications more relevant to the products and features you use.  Get started at [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**New features and enhancements available today**

| Feature    | Description  |
| -----------| ---------- |
|Personalized self-subscription by product sub-offerings | <ul><li>Self-subscription by product offering or add-ons for Experience Cloud products.</li><li>Event notifications received are relevant to your product and product offerings preferences.</li></ul> |
|Personalized experience based on user preferences| <ul><li>Timezone preference based on browser setting is used in email notifications.</li><li>Email confirmation sent on subscribe/unsubscribe with all selected preferences.</li></ul> |
|Better delivery of event messages | <ul><li>Event history sorted based on chronological event updates.</li><li>Timestamp of event resolution added to Major/Minor closed issues.</li></ul> |

## Experience Cloud interface and core services {#ecloud}

New features and fixes in the Experience Cloud interface, including administration and core services (customer attributes, audiences, triggers, cookies, and so on).

| Feature    |Release date | Description  |
| ----|----|---- |
|Admin Tool - view user details |February 26, 2020 |Administrators can view a sortable and filterable list of all Experience Cloud users and their details in the new Admin Tool. User details include a user’s product access, roles, and last accessed information. See [Experience Cloud Admin Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) help for details.|

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

**Note:** The [!UICONTROL Feed] page was deprecated in January, 2020. Look for an in-product deprecation notice.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.  

* [Experience Platform Release Notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## Journey Orchestration {#journey}

Using Adobe Experience Platform, orchestrate individual customer journeys at scale across experience channels by intelligently anticipating every individual’s needs in real time, wherever their journey takes them.

Q1 release has been published. [Read more](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

### Additional resources

[Documentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## Mobile Services and Mobile SDKs {#mobile}

**iOS v4.19.1**

* General – Resolved a potential crash when [!UICONTROL Swift] enums are included in context data for track calls.
* [!DNL Target] – [!DNL Target] Session ID will now be added as a context data parameter `a.target.sessionId` in the internal [!UICONTROL Analytics-for-Target] hit sent to Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] – [!DNL Target] Session ID will now be added as a context data parameter “a.target.sessionId” in the internal [!UICONTROL Analytics-for-Target] hit sent to Adobe Analytics.

## [!DNL Analytics] {#analytics}

Release date: **March 12, 2020**

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

* **Multiple report suites in [!UICONTROL Analysis Workspace]**: You can now bring in data from multiple report suites into a single [!UICONTROL Analysis Workspace] project to view in side-by-side panels. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**: This feature enables you to publish segments to the Experience Cloud within 8 hours (instead of the previous 48-hour processing time). [Learn more...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - Training Tutorial template**: This new standard template walks you through common terminology and steps for building your first analysis in Workspace. It is available as a standard template in the [!UICONTROL New Project] modal and replaces the sample project that exists today for new users that do not have other projects in their list.

#### Fixes

* Fixed an issue in [!UICONTROL Reports & Analytics] that prevented downloading `.xls` reports. This issue affected customers using currencies other than US Dollar and Euro. (AN-206541, AN-204008)
* The rollout of a new shell fixed several customer issues related to switching Experience Cloud organizations.(AN-200844, AN-186920)
* Fixed an issue where doing a breakdown on the _Unspecified_ line item (or some other reporting line items) while not including _Unspecified (None)_ in the search filters of the breakdown would return no results in the breakdown.
* Fixed an issue occurring when using a classified dimension, the entry or exit metric totals would not match the line item total on a breakdown.
* Fixed an issue where first touch and last touch models in Attribution IQ were not calculating credit correctly for some line items in some out of the box dimensions.
* Fixed an issue where breaking down one date dimension by another date dimension would return incorrect results.
* Fixed an issue where sometimes entry or exit metrics would be counted incorrectly when applied to “Unspecified” in a classified dimension report.

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|EOL of **[!UICONTROL Conversion Level]** setting|March 3, 2020|The non-functioning [Conversion Level](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools] > [!UICONTROL Report Suites] > [!UICONTROL General Account Settings]** will be removed from the UI on March 12, 2020.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 3, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of March 12, 2020.|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics began moving to a new domain - `https://experience.adobe.com/analytics.`<br>**Note:** This change applies to all users accessing Analytics with their Adobe ID or Enterprise ID. <ul><li>The domain change may cause cookie issues when loading Analytics in Safari. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul>|
|End of Life - Analytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 was released on March 5, 2020.

## Audience Manager {#aam}

New features and updates to Audience Manager:

### Fixes and improvements {#aam-fixes-and-improvements}

* Fixed a bug where customers could not update segment name because of a missing RBAC permission [!UICONTROL VIEW_ALL_DESTINATIONS]. The [!UICONTROL VIEW_ALL_DESTINATIONS] permission should not be required to update a segment. For more information about RBAC permissions, see [Administration (RBAC Controls)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Fixed a bug in [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) where some customers could not see content in the basic information section and operators in the expression builder, when creating traits based off of [!UICONTROL Data Explorer] signals. (AAM-53130)
* Fixed a bug where some customers could not load the [!UICONTROL Audience Marketplace] interface. (AAM-52070)
* Fixed a bug in the [!UICONTROL Segments API] where, because of some segments with no description, the interface would freeze when users tried to access those segments and users had to navigate away from that page. (AAM-53071)
* Multiple accessibility improvements throughout the interface. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058,AAM-49392)

## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product Updates

* **AEM 6.5.4.0**
    AEM 6.5, Service Pack 4.0 (6.5.4.0 released March 5, 2020) is an important update that includes new features, key customer enhancements, improved performance, stability, and security, released since the general availability of AEM 6.5, April 2019.
  * [What's new in Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
  * [Release notes](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
  * [AEM Forms release deliverables](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

  AEM 6.4, Service Pack 8.0 (6.4.8.0 released March 5, 2020) is an important update that includes key customer fixes released since the general availability of AEM 6.4, April 2018.
  * [Release notes](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
  * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

  AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 released March 5, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.3, April 2017.
  * [Release notes](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
  * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

  AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 released March 5, 2020) changes the way AEM Assets is configured with [!UICONTROL Brand Portal.] In addition, the release includes other enhancements and bug fixes.
  * [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Self-Help

* **AEM as a Cloud Service &ndash; Role Based Permissions**

  Cloud Manager has pre-configured roles with appropriate permissions. Each of the roles have specific permissions, pre-configured tasks, or permissions, associated with each role. The [Role Based Permissions](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) Help topic identifies available functions and the roles who can run them.

* **AEM as a Cloud Service &ndash; Dispatcher**

  The [Dispatcher and CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) and [Explicit Dispatcher cache invalidation](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) sections were updated to clarify the options that are available and how they work.

* **Configure AEM Assets with Brand Portal**

  AEM Assets is now configured with [!UICONTROL Brand Portal] through Adobe I/O, which procures an IMS token for authorization of the Brand Portal tenant. Earlier, it was configured in Classic interface by way of the [!UICONTROL Legacy OAuth Gateway.]
  See [Configure AEM Assets with Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM as a Cloud Service - Smart Crop in Dynamic Media**

  A new option is available in AEM as a Cloud Service when you work with Smart Crop in the Dynamic Media component:

  **Enable Aspect Ratio match** - Select this option to let Dynamic Media pick a smart crop rendition that best matches the aspect ratio of the original image.
  See [When working with Smart Crop](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Community

* **AEM Skill Builder webinars**

  * AEM Sites &ndash; Starting March 17, 2020 learn the building blocks of content authoring and the fundamental concepts and operations of AEM Sites. [Register now](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
  * AEM Assets &ndash; Starting March 19, 2020 hone your digital asset management expertise, plus learn the basics of brand portal, [!UICONTROL Dynamic Media,] [!UICONTROL Asset Link,] and more. [Register now](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

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

### Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Additional resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign Control Panel: [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Updated February 10, 2020, for February 8 release:

| View | Feature |
|------|---------|
| [!UICONTROL Portfolios] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. The same bid is applied to all ads in an ad group. Data for Japan Display Network campaigns is included in the simulations for the portfolio. |
| [!UICONTROL Search] > [!UICONTROL Bulksheets]  | You can now create, edit, and delete Google responsive search ads (RSAs) using bulksheets. Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| [!UICONTROL Search] > [!UICONTROL Campaigns, Reports] | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

For Magento release notes, see:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] is a complete solution for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

Release date: February 21, 2020

* **Microsoft Dynamics _Change Owner in Microsoft_ Flow Action:** Change a lead or contact owner directly from Marketo Engage.
* **Enhancements to API calls:**
  * User management APIs
  * Custom object schema APIs
  * Landing page redirect rules APIs
* **Form Descriptor Caching:** Improvements to Landing Pages & Forms.

See [!DNL Marketo] release notes for [February 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) for more information.

### Upcoming features

The following features are releasing throughout the quarter:

| Feature | Description |
|------|---------|
| [!DNL Bizible] |<ul><li>New account-based segmentation</li><li>Save dashboard-specific filters</li><li>Export Bizible dashboards as PDFs</li></ul> |
| Sales Connect |Compose Window and Command Center updates/enhancements |

### Announcements

**Marketo Engage Success Center:** Launching in February 2020. The Success Center is an in-product help center that enables you to search Product Docs and the Community, launch how-to guides, access adoption content, and more. Note: This feature will be launched as a beta in ANZ and will roll out to North America later in the quarter.

### Deprecations

* **Asset API "_method" Parameter:** After September 2020, Asset API Endpoints will no longer accept "_method" to pass Query Parameters in a POST body to bypass URI length limitations.
* **Internet Explorer Support Deprecation:** Beginning with the July release on July 31, 2020, the Marketo Engage user interface will no longer be supported on Internet Explorer.

For cumulative and historical release notes, see [Marketo release notes](https://docs.marketo.com/x/CgA6Ag).

## New documentation and tutorials {#selfhelp}

New and recent self-help articles and videos. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

|Solution |Content | Description |
|----------| -----------| ---------- |  
|[!UICONTROL AEM Commerce] |Video - [Creating Multiple Category and Product Pages](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md)  |Learn how to create a minimal Adobe Experience Manager (AEM) CIF project as a starting point for customer projects using CIF Core Components. Apply theme and CSS styling to components and inspect a new AEM CIF project, generated by the archetype. Also, learn how CSS and JavaScript used by CIF core components are organized. |  
| [!UICONTROL AEM Forms]  |Article - [Authenticate to AEM Author using OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Learn how to configure your app on OKTA portal and about the settings that you typically use in registering new application. |
| [!UICONTROL AEM Commerce]  |Tutorial - [Customize CIF Core Components](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md)  | Review several different extension points provided by CIF Core Components and AEM in general. CIF Core Components provides a standard set of Commerce components that can be used to accelerate a project that integrates Adobe Experience Manager (AEM) and Magento solutions.|
|[!DNL Adobe Campaign] - Audience Destinations|Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Create an audience in Campaign Standard using the Adobe [!UICONTROL Experience Platform Segment Builder]. You can access this feature directly within Adobe Campaign Standard via the [!UICONTROL Audiences] modules. |
|[!DNL Adobe Campaign] - Audience Destinations |Video - [Activating Adobe Experience Platform Audiences in a Marketing Workflow](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Learn how to activate the [!UICONTROL Data Services Query Audience] within a workflow by using the [!UICONTROL Read Audience] activity.|
|[!DNL Adobe Campaign] |Tutorial - [Push Notification with Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) |Send personalized and segmented push notifications to iOS and Android mobile devices. This tutorial will walk you through the steps involved in sending push notifications from Adobe Campaign and receiving these notifications in your Android app.|
|[!DNL Adobe Campaign] |Video - [Create a Push Notification](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Create a push notification in Adobe Campaign Standard. You can send personalized and segmented push notifications to iOS and Android mobile devices. |
|[!DNL Adobe Campaign] - AEP Data Connector |Video - [Check the status of a data ingestion job](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) |Learn how to check the status of a data ingestion job and if the data has been ingested from Adobe Campaign Standard into Adobe Experience Platform. |
|[!DNL Adobe Campaign] - AEP Data Connector |Video - [Modify data mapping](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) |Learn how to check the status and modify the data mapping. |
|[!DNL Adobe Campaign] - AEP Data Connector |Video - [Map experience events](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Learn how to map Experience Events in Adobe Experience Platform. |
|[!DNL Adobe Campaign] - AEP Data Connector |Video - [Map custom resources](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) |Learn how to map different data types between Adobe Campaign Standard and Adobe Experience Platform. |
|[!DNL Adobe Campaign] - AEP Data Connector |Video - [Understand the Adobe Experience Platform Data Connector](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) |Learn how to make your data available on Adobe Experience Platform by mapping XTK data (data ingested in Campaign) to Experience Data Model (XDM) data on Adobe Experience Platform. |
|[!DNL Adobe Campaign] - AEP Data Connector|Video - [Map seed table data](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html)  |Learn how to map you seed data / test profiles with the Adobe Experience Platform.|
|[!DNL Adobe Campaign]- Audience Destinations |Video - [Change the targeting dimension of a delivery for a Platform Audience](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html)  |Learn how to change the targeting dimension of a delivery for a Platform Audience outside of the primary profile table in Adobe Campaign Standard.|
|[!DNL Adobe Campaign] |Video - [Big data management on Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) |Leverage the Snowflake connector in Adobe Campaign Classic.|
|[!DNL Adobe Campaign] - Audience Destinations |Article - [Audience Destinations (BETA)- Overview](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) |Learn how to leverage centralized and consolidated profile data from the Adobe Experience Platform for marketing campaigns in Adobe Campaign Standard. |
|[!DNL Adobe Target] - Mobile SDK |Tutorial - [Personalize app experiences with Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) |Implement Adobe Target in your own Android app. Validate the Mobile Services SDK setup and implement [!DNL Target] requests like pre-fetching content, blocking requests, and more. |
|Adobe Analytics |Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) |Watch curated clips from the high tech "super session" at Summit 2019. |
|Adobe Analytics |Video - [Introduction to Calculated Metrics in Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) |Walk through the basics of creating [!UICONTROL Calculated Metrics] in [!UICONTROL Customer Journey Analytics]. |
|Adobe Analytics |Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html)|View curated clips from the travel and hospitality session at Summit 2019. |
|Adobe Analytics |Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) |See curated clips from the retail session at Summit 2019. |
|Adobe Analytics |Video - [Customer Use Case: Accent Group Invests in Customer Experience to Drive Sales](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) |Watch how the Accent Group uses the Adobe Experience Cloud to create seamless digital experiences. |
|Adobe Analytics |Video - [Customer Use Case: ServiceNow gets the right insights to connect with prospects](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) |Find out how [!DNL ServiceNow] gets actionable data from its marketing channels and boosts ROI on paid search advertising with Adobe Advertising Cloud and Adobe Analytics. |
|Adobe Analytics |Video - [Adobe Analytics - It's More Than Data It's Customer Intelligence](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html)|Learn about data-driven marketing and how to take your analytics maturity to from data to insights to action. |
|Adobe Analytics |Video - [Adobe Sensei and Adobe Analytics - Extended Version](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html)|View key features in Adobe Analytics powered by Adobe [!DNL Sensei,] including [!UICONTROL Anomaly Detection,] [!UICONTROL Contribution Analysis,] [!UICONTROL Intelligent Alerts,] [!UICONTROL Clustering,] [!UICONTROL Segment IQ,] and [!UICONTROL Propensity Modeling.] |
|Adobe Analytics |Video - [How Adobe Analysis Workspace Can Change Your Business](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Learn how you can perform ad hoc analysis, flexible analysis, cohort analysis, and fallout analysis using [!UICONTROL Analysis Workspace]. You can also share the analysis working environment with everyone in your company, and its drag and drop function allows everyone to analyze the data easily and get insights quickly.|
|Adobe Analytics |Video - [Customer Use Case: The Home Depot Innovates with Customer Experience Management](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) |Learn how [!DNL Home Depot] uses Adobe solutions to create brand loyalty and customer satisfaction with a personalized, customized shopping experience. |
|Adobe Analytics |Presentation - [Understanding Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html)  |Learn how Adobe’s [!UICONTROL Customer Journey Analytics], an application service built on [!DNL Adobe Experience Platform], brings [!UICONTROL Analysis Workspace] into the Experience Platform. This feature enables multi-channel analysis on any of your [!DNL Adobe Experience Platform] data sets.|
|Adobe Analytics |Video - [Cross-Channel Attribution in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html)  |Learn how you can use visualizations to show attribution (give credit) across channels in [!UICONTROL Customer Journey Analytics]. |
|Adobe Analytics |Article - [Customer Tips for Continuing your Adobe Analytics Learning Journey](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) |Meet three Adobe customers who have tips and tricks for you regarding how to get the most value from Adobe Analytics. |
|Adobe Analytics |Video - [Create Cross-Channel Visualizations in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html)|Discover how [!UICONTROL Customer Journey Analytics] allows you to create visualizations that include data from multiple data sets across multiple channels, including merging the data per visitor. |
|Adobe Analytics |Video - [Move your Calculated Metrics from Adobe Analytics to Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) |Find tips for re-creating your Analytics [!UICONTROLCalculated Metrics] in [!UICONTROL Customer Journey Analytics]. |
