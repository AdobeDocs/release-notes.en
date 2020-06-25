---
title: Adobe Experience Cloud Release Notes
description: Adobe Experience Cloud release notes
doc-type: release notes
last-update: June 2020
author: mfrei
---

# Adobe Experience Cloud Release Notes - June 2020 

![Banner](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. It also highlights new documentation, training courses, and video tutorials to help you get the most out of Experience Cloud.

>[!NOTE]
>
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases.

**Release date: June 18, 2020**

Product release dates may vary. Check back frequently for updates.

Latest update: **June 18, 2020**

* [Adobe System Status](#status)
* [Experience Cloud interface](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) (and [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to Primetime's help page)

Need help? Visit [Adobe Experience League](https://experienceleague.adobe.com/#home) to find product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/adobe.png) Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

Released: **May 21, 2020**

**What's new**

* Using your Adobe ID, you can subscribe to event notifications with more granularity, down to the product offering and add-on level. To help you setup your subscription faster, the self-subscription process now recommends a selection of products and offerings based on your product entitlements. This should reduce the number of emails you receive, and deliver more relevant notifications in your inbox. Get started at [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**New features and enhancements available today**

| Feature    | Description  |
| -----------| ---------- |
|Improved subscription and notification user experience | <ul><li>[!DNL Marketo Engage] regional locations are now filtered based on the list of product offerings selected.</li><li>[!DNL Marketo Engage] email notifications are relevant to the user's region, location, and environment preferences.</li></ul> |
|Event subscription confirmation| <ul><li>You can now get an email confirmation when subscribing to on-going single event updates.</li></ul> |
|Global navigation usability enhancements | <ul><li>Consistent user experience with `Adobe.com` at the top level navigation menu.</li></ul>|

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud interface {#ecloud}

General updates to Experience Cloud interface.

**Unified product domain**

Adobe has been updating the domain and interface header to unify and improve your experience across all Experience Cloud applications. These enhancements are designed to simplify your experience in small but important ways. These enhancements do not change your current workflows.

Updates include:

* New application URLs: `experience.adobe.com/<application name>`:
  * All products will eventually adopt this URL pattern. Look for new URLs to become effective throughout the month.
  * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Note:** Although Experience Cloud interface supports these browsers, individual applications might not support every browser. (For example, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) does not support [!DNL Opera], and [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) does not support [!DNL Safari].)
  * ([!DNL Safari] only) The domain change may cause cookie issues in [!DNL Safari]. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Easier switching between your organizations or to a different application.
* Improved product help: [!UICONTROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. This change simplifies access to more content and helps you get the most out of Experience Cloud. Additionally, click **[!UICONTROL Help]** > **[!UICONTROL Feedback]** to report issues or share your ideas with Adobe.

The following apps use the new experience.adobe.com domain:

| App or Service    | Domain  |
| -----------| ---------- |
|Experience Cloud home page | `experience.adobe.com/home`|
|Adobe Target |`experience.adobe.com/target` |
|Adobe Audience Manager |`experience.adobe.com/audience-manager` |
|Adobe Launch |`experience.adobe.com/launch` |
|Adobe Experience Platform |`experience.adobe.com/platform` |
|Journey Management |`experience.adobe.com/journeys` |
|Adobe Analytics|`experience.adobe.com/analytics`|
|Customer Journey Analytics |`experience.adobe.com/platform/analytics` |
|Adobe Campaign Control Panel |`experience.adobe.com/controlpanel` |
|Cloud Manager |`experience.adobe.com/cloud-manager` |
|Places Service |`experience.adobe.com/places` |
|Software Distribution |`experience.adobe.com/downloads` |
|Admin Tool (beta)  |`experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board & Collections]**, a legacy filter in [!UICONTROL Marketing Cloud Assets] selector, is being decommissioned.

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.  

Release date: **June 10, 2020**

[!DNL Adobe Experience Platform] includes the following new features:

* **Data Science Workspace:** The [!DNL JupyterLab Launcher] now includes a [!DNL Python] notebook starter for Real-time Machine Learning (Alpha).
* **Segmentation:** An Anniversary date field for date functions has been added, allowing users to evaluate dates without the year.
* **Sources:** New source connectors for [!DNL Apache HDFS] and [!DNL Couchbase].

For more information about these features, see [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md).

### Additional Experience Platform release information

* [Experience Platform Launch release notes](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### New Experience Platform courses and tutorials {#tutorials-plat}

|Content |Content Type |Description |
| -----------| ---------- | ---------- |
|[Introduction to Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1)|Course |Learn how Adobe Experience Platform helps you deliver the right experience by transforming your data into robust real-time customer profiles and AI-driven insights that you can activate in every channel. This introductory-level course gives you an overview of Experience Platform's capabilities, use cases, relationship with Adobe Experience Cloud, basic architecture, interface, and project roles. |
|[Introduction to Web SDK and Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html)|Video tutorial |An overview of Adobe Experience Platform SDK and Edge Network. Experience Platform Web SDK is a client-side JavaScript library that allows customers to use one JavaScript library, one beacon type, one data stream, one and server-side destination to send data to all Adobe applications and to third-party destinations.|
|[Demo of Web SDK and Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html)|Video tutorial |Watch the Adobe Experience Platform Web SDK and Edge Network in action, with a single call to Adobe sending data to Experience Platform, Analytics, Audience Manager and Target.|
|[Demo of Real-time Customer Data Platform](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html)|Video tutorial |Learn how Real-time CDP is used to collect data from multiple sources. You can merge that data into a single real-time customer profile, and activate that data to create personalized customer experiences. |

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Using Adobe Experience Platform, orchestrate individual customer journeys at scale across experience channels by intelligently anticipating every individual’s needs in real time, wherever their journey takes them.

### Latest release

For the latest release updates, see [Journey Orchestration release notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)

### New Journey Orchestration courses and tutorials {#jo-tutorials}

|Content |Content Type | Description |
| -----------| ---------- | ---------- |
|[Getting Started with Journey Orchestration for Administrators](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2)|Course |Learn how to configure and use Journey Orchestration. This course covers the key concepts, and the configuration steps required to enable the orchestration of a journey. Learn how to create, publish, and how to report and analyze your orchestrated journeys. |
|[Getting started with Journey Orchestration for business users](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1)|Course  |Learn how to configure and use Journey Orchestration. This course covers the key concepts. You will learn how to create, publish, report on and analyze your orchestrated Journeys. |  

### Additional resources for Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Release date: **June 18, 2020**

* [New features in Adobe Analytics](#aa-features)
* [New features in Customer Journey Analytics](#cust-journey)
* [New features in Media Analytics](#media-aa)
* [Fixes in Adobe Analytics](#aa-fixes)
* [Important notices for Analytics administrators](#aa-notices)
* [New Adobe Analytics courses and tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### New features in Adobe Analytics {#aa-features}

| Feature    | [General Availability](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html)- Target Date |Description  |
| -----------| ---------- |-------|
| Attribution IQ: Algorithmic Attribution |June 18, 2020| The [!UICONTROL Algorithmic Attribution] model in Analysis Workspace uses statistical techniques to dynamically determine the optimal allocation of credit for the selected metric. Available to Adobe Analytics Ultimate customers. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Attribution IQ: Custom lookback windows |June 18, 2020| You can now configure any attribution model in [!UICONTROL Attribution IQ] to include touchpoints from up to 90 days before the reporting time period. This will typically increase the attribution accuracy for events that happen early in the reporting period by accounting for interactions that occurred in the prior month(s). Available to Adobe Analytics Foundation, Select, Prime, Premium, Premium Attribution, Premium Complete, and Ultimate customers. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows)|
| Project roles for shared Workspace projects | June 18, 2020 |When sharing a Workspace project, you can now place recipients in one of three project roles, depending on the project experience you want them to have: Edit, Duplicate and View. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html)|
|View-only Workspace projects|June 18, 2020|Workspace projects can be shared to users as “Can view” only. When a View recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html)|
|Ability to co-edit Workspace projects|June 18, 2020|Recipients added to the “Can edit” role can save over a project that has been shared to them. This extends to both admins and non-admins. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html)|
|Updated Blank panel in Workspace|June 18, 2020|The blank panel in Workspace now includes panels and visualizations, giving you a more seamless way to pick the analysis workflow that works best for you.|
| First-party domains available in China RDC | June 18, 2020 |Enables customers with a `.cn` domain to request a 1st-party domain for use inside of Mainland China. (Documentation available with the purchase of "China Performance Optimization" SKU.)|
|Quick Insights panel in Workspace|June 25, 2020|Quick Insights provides guidance for non-analysts and new users of Analysis Workspace to learn how to answer business questions quickly and easily. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html)|
|Analytics for Target panel in Workspace|June 25, 2020|The Analytics for Target (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html)|
|[!UICONTROL About Workspace] page|June 18,2020|The [!UICONTROL About Workspace] page provides information about your Analysis Workspace environment, about your Adobe Analytics administrators (if you need support), and a way to provide in-product feedback. It can be found under **[!UICONTROL Workspace]** > **[!UICONTROL Help]** > **[!UICONTROL About Workspace]**.|

### New features in Customer Journey Analytics {#cust-journey}

| Feature    | [General Availability](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html)- Target Date |Description  |
| -----------| ---------- |-----|
|Support for Object arrays|June 18, 2020|CJA customers can now report on dimensions and metrics that appear in Object arrays within their Adobe Experience Platform dataset schemas. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html)|
| Attribution IQ: [!UICONTROL Algorithmic Attribution] |June 18, 2020| The [!UICONTROL Algorithmic Attribution] model in [!UICONTROL Analysis Workspace] uses statistical techniques to dynamically determine the optimal allocation of credit for the selected metric. Available to Adobe Analytics Ultimate customers. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| Attribution IQ: Custom lookback windows |June 18, 2020| You can now configure any attribution model in [!UICONTROL Attribution IQ] to include touch-points from up to 90 days before the reporting time period. This will typically increase the attribution accuracy for events that happen early in the reporting period by accounting for interactions that occurred in the prior month(s). [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/models.html)|
|Support for [!UICONTROL Anomaly Detection]|June 18, 2020|[!UICONTROL Anomaly Detection] provides a statistical method to determine how a given metric has changed in relation to previous data. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html)|
|Project roles for shared [!UICONTROL Workspace] projects | June 18, 2020 |When sharing a [!UICONTROL Workspace] project, you can now place recipients in one of three project roles, depending on the project experience you want them to have: Edit, Duplicate and View. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html)|
|View-only [!UICONTROL Workspace] projects|June 18, 2020|[!UICONTROL Workspace] projects can be shared to users as _[!UICONTROL Can View]_ only. When a View recipient opens the shared project, they receive a more restrictive project experience with no left rail and limited interactions. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html)|
|Ability to co-edit [!UICONTROL Workspace] projects|June 18, 2020|Recipients added to the _[!UICONTROL Can Edit]_ role can save over a project that has been shared to them. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html)|
|Quick Insights panel in [!UICONTROL Workspace]|June 25, 2020|Quick Insights provides guidance for non-analysts and new users of [!UICONTROL Analysis Workspace] to learn how to answer business questions quickly and easily. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/panels/quickinsight.html)|
|[!UICONTROL About Workspace] page|June 18,2020|The [!UICONTROL About Workspace] page provides information about your Analysis Workspace environment, about your Adobe Analytics administrators (if you need support), and a way to provide in-product feedback. It can be found under **[!UICONTROL Workspace]** > **[!UICONTROL Help]** > **[!UICONTROL About Workspace]**.|

### New features in [!UICONTROL Media Analytics] {#media-aa}

Date updated: **June 18, 2020**

|Feature |[General Availability](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html)- Target Date | Description |
| -----------| ---------- | ---------- |
|[Supported devices and platforms](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html)|June 18, 2020  |The Media Launch Extension w/ AEP SDK now supports the following OTT devices:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul>||[Supported devices and platforms](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html)|June 18, 2020  |The Media Launch Extension w/ AEP SDK now supports the following OTT devices:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul>|
|[Player State Tracking](https://docs.adobe.com/content/help/en/media-analytics/using/player-state-tracking/player-state-overview.html)|May 29, 2020 |[!UICONTROL Media Analytics] customers can capture viewer interaction during playback using a standard set of solution variables for full screen, closed captioning, mute, picture-in-picture, and in-focus. You also have the flexibility to create custom player states. Player State Tracking variables are now available for reporting in [!UICONTROL Analysis Workspace]. This feature requires one of the following: <ul><li>Media [!DNL JavaScript] SDK 3.0 or higher</li><li>For use with the [!DNL Adobe Experience Platform] (AEP) SDK:</li><li>[!UICONTROL Media Analytics Extension] (for web): [!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 or higher</li><li>[!UICONTROL Media Analytics Extension] (for mobile): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 or higher</li><li>[!UICONTROL Media Collection]</li></ul>|

### Fixes in Adobe Analytics {#aa-fixes}

* Fixed an issue that caused segments with multi-byte searches for certain report suites to match nothing. They will now match the correct strings. (AN-220043)
* Fixed an issue with the [!UICONTROL Item Filter] in [!UICONTROL Reports & Analytics] not working. (AN-206132)
* Fixed slow response time in [!UICONTROL Scheduled Projects] interface. (AN-214837)
* Fixed an issue with the Analytics Reporting API 2.0 throwing a date range error. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn't being counted in the denominator for the [!UICONTROL Time Spent] metrics. This would happen when a hit with no value for the dimension (e.g. Pagename) followed in the same second. (AN-211074)
* Fixed an issue with users unable to access [!UICONTROL Workspace] projects shared with them. (AN-217561)
* Fixed issue with keys not being classified by [!UICONTROL Classification Rule Builder]. (AN-221538)
* Fixed an issue with the [!UICONTROL Server Call Usage] not reporting any usage data. (AN-210452)
* Fixed issues with published Adobe Analytics segments missing data in Audience Manager. (AN-220208, AN-220659)
* Fixed an issue with reports showing data but [!UICONTROL Data Feeds] logs saying "No Data Warehouse data". (AN-220784, AN-220858)
* Fixed issues that prevented the launch of [!UICONTROL Ad Hoc Analysis] from the `experiencecloud.com` domain. (AN-219680, AN-221629)
* Fixed issues with using the "Ctrl (or Command) + C" hotkey. (AN-221101, AN-221537)
* Fixed an issue with the [!UICONTROL Activity Map] enablement page. (AN-222029, AN-221242)
* Fixed an issue with not being able to add a touch-point in the middle of a [!UICONTROL Fallout] visualization. (AN-221648)

#### Additional Adobe Analytics fixes

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|Migration to unified product domain|Effective date: May 28, 2020|The migration to a unified product domain for Adobe Analytics, which began in January 2020, completed on May 28, 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. When the full architecture migration is (soon) completed, we will notify you via the release notes and this allowlist step will no longer be needed. [Here](https://helpx.adobe.com/analytics/kb/adobe-ip-addresses.html) is a full list of recommended IP addresses and domains that you should allowlist.<br>If your organization blocks third-party cookies, please reach out to Customer Care to regain your access to Adobe Analytics.|
|New Adobe Analytics default landing page|Effective Date: June 18, 2020|On June 18, 2020, the default landing page for Adobe Analytics will change from [!UICONTROL Reports] to [!UICONTROL Workspace]. This change will occur for any users who have not previously set a custom landing page.|
|Third-party technology allowlist|March 12, 2020 (effective date)|Adobe Analytics has begun leveraging third-party technologies for feature rollout management and in-product support. The following URLs should be added to any necessary network firewall allowlists to ensure full feature access:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul>|
|Improved redundancy for [!UICONTROL Analysis Workspace] availability|May 21, 2020|In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. The following URLs should be added to any necessary network firewall allowlists:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
|Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace]|April 7, 2020|In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. For example, assume that the first hit of a visit has no value for eVars, but the second hit does. In [!UICONTROL Reports & Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of October, 2020.|
|End of Life - Analytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL of Ad Hoc Analysis|Aug 6, 2018|Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

#### New Analytics courses and tutorials {#tutorials-analytics}

New courses, tutorial videos, and articles in Analytics and Customer Journey Analytics.

|Content |Content Type | Description |
| -----------| ---------- | ---------- |
|[Getting Started with Customer Journey Analytics for Users](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1)|Course  |In this course, you will learn how to use Customer Journey Analytics (CJA) to analyze data from many different data sources. You will learn about the differences between Adobe Analytics and Customer Journey Analytics, and how the data is handled in CJA. After taking this course, you should be able to create and customize cross channel visualizations for increased understanding of your customers. |
|[Getting Started with Customer Journey Analytics for Administrators](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1)|Course |Learn how to configure and use [!UICONTROL Journey Orchestration]. This course covers the key concepts and the configuration steps required to enable the orchestration of a Journey. You will learn how to create, publish and how to report and analyze your orchestrated Journeys. |
|[Getting Started with Customer Journey Analytics for Data Engineers](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1)|Course |In this course, you will learn about the data coming into Customer Journey Analytics and how it affects the reports for the analyst. This course builds upon your general knowledge of the Adobe Experience Platform.|
|[Getting Started with Customer Journey Analytics for Administrators](https://video.tv.adobe.com/v/34349)|Video tutorial |An introductory video to Customer Journey Analytics for Administrators. |
|[Guided Analytics Implementation](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1)|Course |In this course, you learn how to get started implementing Adobe Analytics, understand Analytics concepts, create a plan, and implement Adobe Analytics using Experience Platform Launch. |
|[Adobe Analytics Fundamentals for Leaders](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1)|Course |In this course, learn about the Analytics fundamentals and how Analysis Workspace can change your business. Learn how you can uncover insights with Adobe Sensei, hear customer testimonials, and watch highlights from industry experts at Summit 2019. |
|[Getting Started with Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace)|Course  |Learn how to get started using Analysis Workspace. Build your first project, learn how to define date ranges, apply segments, and share and collaborate on projects. |
|[Adobe Analytics dashboards Scorecard Builder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html)|Video tutorial  |In this video, learn how to create and share [!UICONTROL Scorecards] in [!UICONTROL Analysis Workspace] to be viewed on Adobe Analytics dashboards (mobile app).|
|[Adobe Analytics dashboards In-App Experience](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html)|Video tutorial  |In this video, learn how to use Adobe Analytics dashboards (mobile app) to access and view [!UICONTROL Scorecards] created by or shared with you.|

#### Analytics help resources

* [Adobe Analytics Tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics Product Documentation](https://docs.adobe.com/content/help/en/analytics/landing/home.html)

## ![Icon](/assets/audience-manager.png) Adobe Audience Manager {#aam}

New features, fixes, documentation and tutorials in Audience Manager.

Updated **June 10, 2020**

### User interface updates

Audience Manager is releasing updates to the domain and header bar to improve your experience and unify with other Experience Cloud applications.

* Easier switching between your organizations or to a different application.
* Improved user help, including featured articles and context-relevant videos in the Help menu.
* Ability to give feedback about Experience Platform and file support tickets.
* A new easier URL pattern. Update your bookmarks to the new url: `experience.adobe.com/audience-manager`.

These updates are available only to users logging in using Adobe ID. To switch to an Adobe ID login, see [Manage Experience Cloud users and products](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-getting-started.html).

### New features and fixes in Adobe Audience Manager

| Feature    | Description  |
| -----------| ---------- |  
|[Audience Manager Plug-in for IAB TCF v2.0 ](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html)| Continuing Adobe’s focus on Privacy by Design, we are upgrading the Audience Manager Plug-in for IAB TCF to the IAB Transparency & Consent Framework (TCF) version 2.0, starting June 10th, 2020. Customers who have implemented the Audience Manager Plug-in for IAB TCF must upgrade to version 2.0 by August 15, 2020, in order to continue using the feature. After August 15th, 2020, version 1.1 will be deprecated and no longer supported.|

**Fixes**

* Updated the [!UICONTROL Audience Marketplace Terms & Conditions] to reflect legal requirements in specific geographies. (AAM-54518)
* Fixed an issue where accessing the [!UICONTROL Traits] page from bookmarks would result in a 404 error. (AAM-54768)
* Fixed an issue where the Destination Update API would time out while retrieving [!UICONTROL Algorithmic Models]. (AAM-54342)
* Users can now see a model classification accuracy indicator for [!UICONTROL Smart Personas]. (AAM-54847)
* Fixed an issue where pressing Enter after adding a trait expression would remove the expression instead of saving it. (AAM-54210)
* Fixed an issue where calls to the GET method of the [!UICONTROL Traits] API would fail for users who did not have the VIEW_MODELS permission. (AAM-53104)
* Fixed an issue where users could not delete [!UICONTROL Algorithmic Models] that contained [!UICONTROL Folder Traits]. (AAM-50192)
* Long trait expressions now wrap across multiple lines. (AAM-54972)
* Fixed an issue where users with read-only permissions could see the [!UICONTROL Create New] button in the algorithmic models pages. (AAM-54889)
* Fixed an issue causing the [!UICONTROL General] and [!UICONTROL Trend] reports loading indicator to keep spinning after CSV download was finished. (AAM-54571)
* Fixed an issue where users could not add bulk traits to segments in the [!UICONTROL Segment Builder]. (AAM-55033)
* Multiple accessibility improvements across the interface. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### New Audience Manager courses and tutorials {#tutorials-aam}

|Content |Content Type | Description |
| -----------| ---------- | ---------- |  
|[Introduction to Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1)|Course  |This course teaches you the basics of Audience Manager and the problems you can solve using it. Learn about common use cases and key Audience Manager terms and concepts.|
|[Introduction to Identity in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html)|Video tutorial |Learn how Adobe Audience Manager manages identity, including internal profiles and profile merging as well as ID syncing with partners. |
|[Understanding and Configuring the LinkedIn People-Based Destination](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html)|Course|This video walks you through the concepts and steps to create a People-Based Destination to LinkedIn. It builds on the additional videos and documentation regarding People-Based Destinations. |
|[Creating Rule-based Traits](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html)|Video tutorial |Learn how to use the [!UICONTROL Trait Builder] in the Audience Manager interface to create a rule-based trait, allowing you to capture real-time activity into Audience Manager profiles. |
|[Enabling the Audience Manager Plug-in for IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf)|Video tutorial |Learn how to enabling the Audience Manager Plug-in for IAB TCF. Enabling this plug-in is easy if you are using Adobe Experience Platform Launch. |
|[Demo of the Audience Manager Plugin for IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo)|Video tutorial|In this video, see how cookies and beacons from Experience Cloud ID Service and solutions are affected by the IAB user choice selections. |

## ![Icon](/assets/aem.png) Adobe Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product Updates

* **AEM 6.5.5.0**

    AEM 6.5, Service Pack 5 (6.5.5.0 released June 04, 2020) is an important update that includes new features, key customer-requested enhancements, and performance, stability, security improvements, released since the general availability of AEM 6.5 in April 2019.

    * [Release Notes](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
    * [AEM Forms release deliverables](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

    AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 released June 04, 2020) is an important update that includes several internal and customer fixes since the general availability of AEM 6.4, Service Pack 8 (6.4.8.0) in March 2020.

    * [Release Notes](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
    * [AEM Forms release deliverables](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Self-Help

* **AEM as a Cloud Service**

    What's new on AEM as a Cloud Service?

    Highlights include:

    * AEM Sites Commerce Integration Framework.
    * Enhanced Smart Tags and new in UI guided training experience.
    * Adobe Asset Link support for Adobe Xd.
    * AEM Assets Dynamic Media 3D support.
    * New Self Service improvements reduce dependencies on Adobe for sandbox operations.
        * Enhanced self-service sandbox support in Cloud Manager allows entitled users to delete all environments within a sandbox and receive credits.
        * Auto-Hibernation sandbox environments automatically "hibernates" sandboxes after a period of inactivity. Customers can actively trigger "de-hibernation".
    * Transition tooling to support cloud acceleration

    With the goal of reducing time and cost to transition from on-premise to Cloud Service, two transition tools were launched this month. These tools are designed to automate some of the key tasks during transition process and hence, reducing the overall effort. .

    1. [Using Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) (available on SD)  streamlines the content transfer activity and makes it scalable. With a user-friendly UI, the tool is self-service for existing customers and partners (on-prem/AMS) that are transitioning to AEM as a Cloud Service.
    1. [AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-source) tool to automate converting AMS Dispatcher configurations to Cloud Service Dispatcher configurations.

    [Release notes for AEM as a Cloud Service 2020.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

    Transition tooling:

    https://github.com/adobe/aem-cloud-service-dispatcher-converter

    https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Core Components**

    Core Components 2.9.0 introduces integration with the [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) and a new Progress Bar Component and is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Moving to AEM as a Cloud Service**

    [Moving to AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/home.html) describes the recommended transition journey for an existing AEM customer moving to Cloud Service. The goal of this documentation is to provide customers with information, guidance and best practices to help them prepare for this transition and to make this journey structured and predictable.

    One of the Cloud Transition Tools - Content Transfer Tool was released. [Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) is developed by Adobe that can be used to move existing content over from a source AEM instance (on-premise or AMS) to the target AEM Cloud Service instance.

    One of the Code Refactoring Tools - AEM Dispatcher Converter was released. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) is a tool for converting existing AEM Dispatcher configurations to AEM as a Cloud Service Dispatcher configurations and is available.

* **Accessibility and the WCAG 2.1 Guidelines**

    Updates in relation to the WCAG 2.1 Guidelines:

    * [Adobe Experience Manager as a Cloud Service and the Web Accessibility Guidelines](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
    * [A Quick Guide to WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
    * [Creating Accessible Content (WCAG 2.1 Conformance)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM newsletters**

    The AEM Newsletter by Experience League is designed to help you get up to speed with AEM so that you can start realizing value right away. Here is the most current newsletter:

    * [Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager is now available as a cloud service.
    * [Subscribe](https://adobeeventsonline.com/AEM/2017/NL/Optin/) to the Experience Insider Newsletter.
    * View newsletter archives in the [AEM resources](https://helpx.adobe.com/support/experience-manager/6-5.html) section of the Adobe Experience Manager 6.5 Learn & Support page.

### **Community**

* **AEM Community Discussion**

    Now you can look at all the AEM announcements and interesting references to internal and external bloggers in one place. See the AEM Community's [Discussion section.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### New Experience Manager courses and tutorials

|Content |Content Type | Description |
| -----------| ---------- | ---------- |
|[Getting Started with Adobe Asset Link for Business Users](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link)|Course|In this course, learn how to use Adobe Asset Link's features and capabilities to fuel your creative design with content stored in Adobe Experience Manager Assets. The course covers everything from how to launch adobe asset link,  basic asset operations, search and browse options, and how to efficiently collaborate with other users. |
|[Getting Started with AEM Assets for Business Users](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets)|Course|Learn how to get started with AEM Assets for business users. Explore the basics of AEM Assets, collaboration features, searching, organizing assets, and downloading assets and their renditions. |
|[Getting started with AEM Sites for business users](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites)|Course | Learn how to use AEM Sites' core features and capabilities to manage your organization's webpages. The course covers everything from an introduction to AEM Sites, basic concepts of authoring, advanced authoring features, and page management capabilities. |
|[AEM Project Structure](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html)|Article|Describes the changes required to Adobe Experience Manager Maven projects so that they are AEM Cloud Service compatible. |
|[Sling Models](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models)|Video tutorial|Learn about debugging AEM as a Cloud Service SDK’s local quickstart using the Sling Models web console.|
|[AEM Web Console Components](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components)|Video tutorial|Learn about debugging AEM as a Cloud Service SDK’s local quickstart using the Components web console. |
|[Debugging AEM SDK’s local quickstart using logs](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html)|Video tutorial|Learn about debugging AEM as a Cloud Service SDK’s local quickstart using the Bundles web console.|
|[Remote debugging the AEM as a Cloud Service SDK’s local quickstart](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html)|Video tutorial|Learn bout remote Java debugging from your IDE, allowing you to step through live code execution in AEM to understand the exact execution flow.|
|[Smart Tag Setup](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html)|Video tutorial|Step-by-step instructions to integrate Adobe Experience Manager (AEM) with the Smart Content Service using Adobe I/O. |
|[Batch generation of documents](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html)|Article|Learn about using the Batch API to produce multiple interactive communications from a template. |
|[Creating Print channel document in AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html)|Article|Learn the steps needed to create an interactive communication for the print channel. |
|[Access Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html)|Video tutorial|Learn about accessing content stored in Adobe Experience Manager Assets (AEM Assets), without leaving the Creative Cloud desktop apps you are most familiar with. |
|[Asset Link Panel Overview](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html)|Video tutorial|Adobe Asset Link provides creative users with the ability to browse, search, check out, and check in assets stored in AEM Assets using the in-app panel in InDesign, Photoshop, and Illustrator. Get introduced to Adobe Asset Link panel's UI and its capabilities. |
|[Asset Search](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html)|Video tutorial|Creative users can search for assets stored in AEM Assets using keywords, or perform a search under a specific location.|
|[File Versioning and Comments](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html)|Video tutorial|Using the Adobe Asset Link panel, you can access file details for assets in AEM Assets, such as thumbnail, basic metadata, and versions from within the panel.  |
|[Check-In Check-Out](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html)|Video tutorial|Adobe Asset lets you check out AEM Assets directly from the creative app you are working on, and can immediately begin making edits.|
|[For Placement Only Rendition for AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html)|Video tutorial|Explore how to create and use a For Placement Only (FPO) rendition for AEM assets. |
|[Place Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html)|Video tutorial|Learn how to use assets from AEM Assets using the Place Copy operation. |
|[Download and Upload](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html)|Video tutorial|Learn how to download and upload asset files from and to AEM Assets using the Asset Link panel. |
|[Files and Collections](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html)|Video tutorial|Learn how to quickly and easily access AEM Assets Files and Collections from within the Asset Link panel. |
|[Download](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html)|Video tutorial|Learn how to download assets and their renditions to your local machine for use and sharing. |

### Additional resources

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of AEM Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help Home](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media release notes](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre release notes](https://docs.adobe.com/content/help/en/livefyre/using/release-notes/c-rn.html)

## ![Icon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### New product releases

[Adobe Campaign Classic 20.2 release](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) incldues:

* _Support of Emoticon_ – _Azure Synapse FDA Connector_ – _New privacy regulations_
* Campaign Control Panel: [Active profile monitoring](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### New Campaign courses and tutorials

|Content |Content Type | Description |
| -----------| ---------- | ---------- |  
|[Getting Started with Adobe Campaign Standard for Business Users](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard)|Course|Learn how to navigate the interface, work with deliveries, and create and manage recipient data. |
|[Install and setup the Adobe Campaign Client](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard)|Video|Learn how to download and install the Adobe Campaign Client console, create and manage your connections to multiple environments, and verify access to the Adobe Campaign Client console |

### Help resources

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/en/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [Latest documentation updates](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Latest documentation updates](https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Adobe Campaign Control Panel: [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html) - How-to-videos for [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [New features in Advertising Cloud DSP](#adcloud-dsp)
* [New features in Advertising Cloud Search](#adcloud-search)

### New features in Advertising Cloud DSP {#adcloud-dsp}

Updated **June 23, 2020**

| Feature    | Description  |
| -----------| ---------- |
| Domain Migration | (June 22 release) The Advertising Cloud DSP has migrated from https://www.tubemogul.com to [https://advertising.adobe.com](https://advertising.adobe.com). |
| Adobe Analytics integration | (June 18 release) DSP can now optionally suppress the AMO Cost metric from the data it sends to Analytics. To suppress the metric, contact your Adobe account manager. |
| People Based Device Graph | (June 22 release) Self-serve DSP customers can now leverage a device graph (either Adobe Experience Cloud Device Co-op
 or LiveRamp) for people-based targeting and frequency management across any new campaigns. This will ensure that you reach your audiences across their owned devices, and can limit their ad exposure. |
| CCPA Opt-Out-of-Sale | (June 22 release) You can now communicate CCPA opt-out-of-sale requests to Advertising Cloud using a new CCPA opt-out-of-sale segment, which you can create from [!UICONTROL Audiences > Segments]. You can also retrieve monthly reports of IDs customers have submitted for opt-out-of-sale requests for the account a) from [!UICONTROL Audiences > Segments] or b) using the Advertising Cloud Trafficking API. For more information, see https://docs.adobe.com/content/help/en/advertising-cloud/all/privacy/ad-cloud-ccpa-opt-out-of-sale.html. |
| DoubleVerify Authentic Brand Safety | (June 22 release) Advertisers can now target a single DoubleVerify segment ID pre-bid, with comprehensive brand safety filters to mimic their post-bid blocking rules with DoubleVerify. You can now do so in the Media Quality targeting section of the advertiser settings at [!UICONTROL Settings > Advertiser]. To learn more about the service, contact programmaticsales@doubleverify.com. Additional fees apply for this feature. |
| CPA/ROAS Optimization | (May 20 release) Campaign managers no longer need to cap new placements within packages to prevent overallocation of budget. Placements now receive a dynamic budget allocation based on their CPM or CPA/ROAS performance. |
| [!UICONTROL Campaign] Home | (June 3 release) New campaign-level pacing metrics based on the provided campaign budget and time elapsed are available. |
| [!UICONTROL Placements] | (June 22 release) The Site Diversity and Player Size filters were removed to simplify placement setup. |
| Placement Forecasting | (June 3 release) For CTV and video placements with placement-level optimization, the placement settings now include forecasting for multiple ad lengths (15 sec and 30 sec). They also include forecasting for both VAST and VPAID inventory. |
| [!UICONTROL Inventory] | (June 22 beta release) A new deal ID form allows you to quickly set up a private deal you’ve already negotiated.|
| | (June 22 beta release)  Interactive pre-roll is now available for VAST inventory. You can set up a single interactive pre-roll ad and placement, reducing the number of your ads and placements. |
| ACTV Audience Lens | (June 18 release) Audience Lenses allows users to create and apply secondary audience reads to their planning, ordering and reporting workflows. This enables them to (1) gain quick insights into secondary audiences, (2) have flexibility to transact on preferred audiences and (3) measure a campaign’s execution through the “lens” of multiple audiences. |

### New features in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Feature    | Description  |
| -----------| ---------- |
|[!UICONTROL Campaigns]| Microsoft Advertising (formerly Bing Ads) is deprecating average position metrics after 30 September 2020. In preparation for this, beginning on July 11, position-based constraints will be ignored and position-based conditions in any type of constraint will also be ignored. |
|[!UICONTROL Advertising Insights]| (June 13 release) The following insights were removed:<br/><br/><ul><li>Audience Target Performance (the newer version)</li><li>Historic Performance (the newer version)</li><li>Match Type (the newer version)</li><li>Settings Audit (the newer version)</li><li>Portfolio Pre-Post (Legacy)</li></ul><br/>The remaining insights are legacy versions, and the _Legacy_ label was removed from the names. In addition, the Live/Edit modes were removed. |

## ![Icon](/assets/magento.png) [!DNL Magento] {#magento}

For Magento release notes, see:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is a complete applications for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo] [release notes](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) for the latest release information.

### Upcoming features

The following features are releasing throughout the quarter:

| Feature | Description |
|------|---------|
| [!DNL Bizible] |<ul><li>New account-based segmentation</li><li>Save dashboard-specific filters</li><li>Export Bizible dashboards as PDFs</li></ul> |
| Sales Connect |Compose Window and Command Center updates/enhancements |

### Announcements

**Marketo Engage Success Center:** Launching in February 2020. The Success Center is an in-product help center that enables you to search Product Docs and the Community, launch how-to guides, access adoption content, and more. Note: This feature will be launched as a beta in ANZ and will roll out to North America later in the quarter.

### Deprecations

* **Asset API "_method" Parameter:** After September 2020, Asset API Endpoints will no longer accept `_method` to pass Query Parameters in a POST body to bypass URI length limitations.
* **Internet Explorer Support Deprecation:** Beginning with the July release on July 31, 2020, the Marketo Engage user interface will no longer be supported on Internet Explorer.

For cumulative and historical release notes, see [Marketo release notes](https://docs.marketo.com/x/CgA6Ag).
