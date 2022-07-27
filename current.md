---
title: Latest Release Notes
description: Learn about the latest release notes, new features, and new documentation for [!DNL Experience Cloud] products and services. Find new help and tutorials about [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
---
# Adobe Experience Cloud Release Notes - July 2022

![Banner](assets/experience-cloud-banner-3.png)

As an Experience Maker, your path to success starts with [Experience League](https://experienceleague.adobe.com/?lang=en#home). Find a vast how-to documentation library, self-guided tutorials, how-to videos, and courses for all levels and roles, an online community of peers, and expert sup  port when you need it. 

>[!NOTE]
>
>To receive a monthly email notification about updates to this page, subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html). Check back frequently to stay on top of what's happening on Experience League.

Latest update: **July 27, 2022**

* [[!DNL Experience League] events](#events) 
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - central interface components & administration](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo) (**Updated July 27**)
* [[!DNL Adobe Workfront]](#workfront) (**Updated July 27**)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience Blueprints - tutorials](#blueprints)

Need help? Visit [Experience League](https://experienceleague.adobe.com/#home) for product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/experience-league.png) [!DNL Experience League] events {#events}

Experience League events are a great place to learn, interact, and get answers from product experts at Adobe! See [Events](https://experienceleague.adobe.com/events/?lang=en) on Experience League to stay updated for July 2022.

Updated **July 17, 2022**

|Event |Type|Description |
| -----------|---------- | ----|
|[Ask the Experts: Datastreams and data prep](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |Experience League LIVE |In this final of three sessions regarding data collection for the Adobe Experience Cloud, our experts will provide a deeper dive into Adobe’s advanced data collection capabilities, including functions like data prep for data collection. At the end of this session, attendees will feel confident with the latest and most powerful features for collecting data from digital experiences<br>**Date:** July 21 @ 9 a.m. PDT - [Details](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en)|

{style="table-layout:auto"}

See [Events](https://experienceleague.adobe.com/events/?lang=en) on Experience League to stay updated on upcoming events and past episodes.

## ![Icon](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

For the latest release information, see Adobe System Status [release notes](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud - central interface components & administration {#ecloud}

Experience Cloud [central UI components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) include features available on the home page and the persistent product header. These features include user profile settings, preferences, and search. You can also find help on user and product management, Customer Attributes, and Experience Cloud Audiences.

### Provisioning update

>[!IMPORTANT]
>
>Please review the following notice regarding Experience Cloud provisioning.

Adobe is updating its provisioning to provide all Experience Cloud customers access to foundational capabilities that aid interoperability between some Experience Cloud products. Users will have Adobe Experience Platform as a new entitlement added to their Experience Cloud organizations, with [!UICONTROL Data Collection] as an included service. 

Adobe Experience Platform [!UICONTROL Data Collection] includes [tags](https://experienceleague.adobe.com/docs/tags.html?lang=en) for simplified universal tag management, and offers a trusted, robust, and complete, streaming data infrastructure. Tags simplify customer experience data collection and streamlines experience delivery. 

**Changes in Admin Console**

Administrators could see changes or additions to the Admin Console as follows:

* The Adobe Experience Platform product card in the Admin Console will include:

  * Places
  * Assurance
  * Identity Namespace
  * Sandboxes
  * Experience Data Model
  * Schemas
  * Datastreams
  * Visitor ID

   For organizations that are not currently using Experience Platform, you will now see the _Adobe Experience Platform_ product in the Admin Console, including the capabilities listed above.

   For organizations currently using Experience Platform, _Places_ will now be consolidated into the Experience Platform card.

* Adobe Experience Platform Data Collection (formerly, Launch) and Privacy will continue to appear as separate product cards from the other Experience Platform capabilities.

For more details about the new capabilities, please visit their respective pages on Experience League: 

* [Data Collection](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [Places](https://experienceleague.adobe.com/docs/places/using/home.html?lang=en)
* [Assurance](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html)
* [Identity Namespace](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=en)
* [Sandboxes](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=en)
* [Experience Data Model](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html)
* [Schemas](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html)
* [Datastreams](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=en)
* [Visitor ID](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=en#section_3C9F6DF37C654D939625BB4D485E4354)
* [Privacy](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=en)

### Feature update

Feature released: **July 11, 2022**

| Feature | Description |
| ------- | ------- |
| Unified Home - Quick Access Widget | **Navigate faster:** You can now further personalize your home experience and decide which applications are at your fingertips. Use the new pinning feature to select which applications appear front and center on your [!UICONTROL Quick Access]. <br>**Stay informed with smart pinning:** Your new applications are now easier to find. Newly assigned applications display a _New_ badge and auto-pin to [!UICONTROL Quick Access]. |

{style="table-layout:auto"}

**More help resources on [!DNL Experience Cloud Central UI Components] & Administration**

* [Release notes](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) for Experience Cloud Central UI Components
* [User and product management](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) for Experience Cloud (administration)
* Places Service [release notes](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Product documentation for [People - Customer Attributes and Audience Library](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
* [Unified Search for objects and entities](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Latest release information and new documentation for [!DNL Experience Platform] and [!UICONTROL Mobile SDK]:

Planned release: **July 27, 2022**

* [Experience Platform release notes](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)

### New [!DNL Experience Platform] tutorials and courses {#tutorials-platform}

New video tutorials, articles, and courses published for [!DNL Experience Platform].

|Published|Name|Type|Description |Application|
| -----------| ---------- | ---------- | ---------- |---------- |
| July 2022| [Monitor event forwarding](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html) | Video | Learn how to monitor event forwarding in the Data Collection interface. |Data Collection |
| July 2022| [Monitor data ingestion](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html) | Video | Learn how to monitor and track data that gets ingested into Adobe Experience Platform using the monitoring dashboard.  |Data Collection |
| July 2022| [Import sample data to Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html) | Article | Learn how to set up an Experience Platform sandbox environment with sample data. Using a Postman collection, you can create field groups, schemas, datasets and then import sample data into Experience Platform. |Experience Platform |
|July 2022|[Segment Match receiving data](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html)|Video |With Segment Match, data can be shared to you by your strategic partners. In this video, learn how to approve and receive the data, and where you can see it and add it to your own segments.| Experience Platform - Segments|
|July 2022|[Ask the experts: Real-Time CDP Connections](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=en)|Experience League LIVE video |In this second of three livestream sessions regarding data collection, our favorite experts provide an extensive look at Adobe RTCDP [!UICONTROL Connections], where customers can forward events to non-Adobe destinations using a server-side tag management system.|Data Collection |

{style="table-layout:auto"}

### [!DNL Adobe Mobile] SDK

See [Release notes and change logs](https://aep-sdks.gitbook.io/docs/release-notes) for the Adobe Experience Platform Mobile SDKs.

## ![Icon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Next release: **July 20, 2022**

Last update: **July 13, 2022**

* Adobe Analytics [release notes](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en)
* Adobe Analytics [product documentation and tutorials](https://experienceleague.adobe.com/docs/analytics.html)

### AppMeasurement {#appm}

Release version: **2.22.4**

* [AppMeasurement for JavaScript release notes](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)

### New [!DNL Analytics] tutorials and courses {#tutorials-analytics}

New video tutorials, articles, and courses published for Adobe Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 2022|[2022 Flow improvements](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html)|Video |Learn about some of the great improvements to the [!UICONTROL Flow] visualization. Improvements include letting you configure the start or end of the path you are interested in, filtering a column to include or exclude a specific item, and pre-configurable advanced settings.|

{style="table-layout:auto"}

## ![Icon](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Latest update: **July 12, 2022**

* Customer Journey Analytics [release notes](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en) 
* Customer Journey Analytics [product documentation and tutorials](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### New Customer Journey Analytics tutorials and courses {#tutorials-cja}

New videos, tutorials, or courses published for CJA.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 2022|[Configure the next and previous item panel](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html)|Video |Learn how to configure the next and previous item panel in [!DNL Customer Journey Analytics]. This panel generates tables and visualizations to identify the next or previous item for a specific dimension value.|
|July 2022|[Create an annotation](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=en)|Video |Learn to create an annotation in your [!DNL Customer Journey Analytics] projects when events like campaign launches, data issues, and holidays occur. This feature informs your users about metric variances on these dates or date ranges.|
|July 2022|[Create a quick filter](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html)|Video |Create quick filters directly in your [!DNL Customer Journey Analytics] projects and bypass the complexity of the full filter builder.|

{style="table-layout:auto"}

## ![Icon](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Last update: **March 23, 2022**

* [!DNL Streaming Media Analytics] [release notes](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=en) 
* [!DNL Streaming Media Analytics] [product documentation and tutorials](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Fixes and improvements in Audience Manager:

| Improvement    | Description  |
| -----------| ---------- |  
|Validator for target data sources belonging to other companies| Audience Manager released an improvement to the [batch data onboarding process](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en). To prevent accidental file and data onboarding into target data sources owned by other partners, Audience Manager has added a mapping requirement between partner ID (PID) and the data sources (DPID) owned by other partners. <ul><li>See also the __DPID_TARGET_DATA_OWNER_ field in [Amazon S3 name and file size requirements for inbound data files](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements).</li><li>Adobe-internal consultants and customer care should read [Manage onboarding access for second-party data](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) for information about the new mapping require improvement and how to request a new mapping</li><li>It is _not_ required to request a mapping for existing data sharing relationships. The mapping is also _not_ required when onboarding data into target data sources that belong to your PID.</li></ul>|

{style="table-layout:auto"}

For self-help resources, see [Audience Manager documentation and tutorials](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) on Experience League.

## ![Icon](/assets/aem.png) Adobe Experience Manager {#aem}

New features, fixes, and updates in Experience Manager. Adobe recommends customers with On-Premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

Adobe recommends visiting the [Experience Manager release updates and roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) page to stay current on release information.

### Product update videos

* [June 2022 Release Overview video](https://video.tv.adobe.com/v/344308/?quality=12) for a summary of the 2022.6 release.

Older product update videos:

* [May 2022 Release Overview video](https://video.tv.adobe.com/v/343321/?quality=12) for a summary of the features added in the 2022.5.0 (May 2022) release. 
* [April 2022 Release Overview video](https://video.tv.adobe.com/v/342612?quality=12)
* [March 2022 Release Overview video](https://video.tv.adobe.com/v/341465)
* [January 2022 Release Overview video](https://video.tv.adobe.com/v/340120)
* [December 2021 Release Overview video](https://video.tv.adobe.com/v/339278)
* [October 2021 Release Overview video](https://video.tv.adobe.com/v/338253)
* [September 2021 Release Overview video](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

New features in [!DNL Sites]:

* A [new user interface](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=en) is now available for content admins and content authors to efficiently manage (take actions such as publish, unpublish, copy, and move), search/filter, and create content fragments for Headless use-cases.

* The new [Table of Contents Component](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=en) works not only with the [!UICONTROL Core Components] but with all components, automatically rendering table of contents on content pages. And, because it is rendered server-side and fully cached by the dispatcher, it is also efficient to load.

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

New features in [!DNL Assets]:

* Experience Manager [!DNL Assets] uses Adobe Sensei AI capabilities to now [distinguish between colors in an image and apply those as tags automatically on ingestion](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=en). These tags enable enhanced Search experience, based on image color composition. You can configure the number of colors, within a range of one to forty, that are tagged to an image so that you can search for images based on those colors later.

### Experience Manager Forms as a Cloud Service

New features in [!DNL Forms]:

* [Integrate [!UICONTROL Adaptive Forms] with Microsoft® Power Automate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=en): You can now configure an Adaptive Form to run a Microsoft® Power Automate Cloud Flow on submission. The configured Adaptive Form sends captured data, attachments, and Document Of Record to Power Automate Cloud Flow for processing. It helps you build custom data capture experience while harnessing the power of Microsoft® Power Automate to build business logics around captured data and automate customer workflows.

**Wizard to create an Adaptive Form:** You can use business user friendly wizard to quickly author [!UICONTROL Adaptive Forms]. The wizard provides a quick tab navigation to easily select pre-configured template, styling, fields, and submission options to create an adaptive form.

### Experience Manager as a Cloud Service Foundation

What's new:

As mentioned in the May (2022.5.0) release notes, the "Add tree” option under the replication agent admin screen’s Distribute tab was removed. Packages with a tree hierarchy of content should instead be replicated using Manage Publication or the Publish Content Tree workflow.

### [!DNL Cloud Manager]

What’s New:

* [!DNL Cloud Manager] users can now access useful video tutorials from the [!UICONTROL Welcome] card on the landing page at any time.

* The popover on the [Restore Content](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=en) tab of the environments details page now displays a handy list of git commands allowing the user to view changes locally.

### New Experience Manager courses and tutorials {#tutorials-aem}

New videos, tutorials, and courses published over the past month.

|Published|Name|Type|Description |Applications|
| -----------| ---------- | ---------- | ---------- |---------- |
|July 2022|[Get the most out of the Enterprise Workflow Management](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=en)|Video |Learn the benefits of using workflows for your assets management and how to quickly create them.|AEM - Experience Workflow Management |
|July 2022|[Deliver Headless Experiences with Adobe Experience Manager](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=en)|Video |Learn about headless experience management using the latest Experience Manager [!UICONTROL Content Fragment] enhancements and the new GraphQL API for headless content delivery.|Experience Manager [!DNL Sites] |
|July 2022|[Make Metadata work for your business in Adobe Experience Manager Assets](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=en)|Video |Learn how to make the most out of your metadata in AEM Assets by reducing the workload to tag assets and by making your assets more searchable.|Experience Manager [!DNL Assets] |
|July 2022|[iOS app](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html)|Video |Example applications are a great way to explore the headless capabilities of Adobe Experience Manager. This iOS application demonstrates how to query content using AEM’s [!UICONTROL GraphQL APIs] using persisted queries.|Experience Manager [!DNL Assets], [!DNL Sites]|
|July 2022|[Android™ App](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html)|Video |This Android™ application demonstrates how to query content using the [!UICONTROL GraphQL APIs] of AEM.|Experience Manager [!DNL Assets], [!DNL Sites] |
|July 2022|[Configuring OSGi for Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=en )|Video |Learn how to configure OSGI for AEM CS. For example, learn about management of OSGi bundles and managing the configuration settings for OSGi components through configuration files that are part of an AEM code project.|AEM as a Cloud Service |
|July 2022|[Override Form Data Model Properties](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=en)|Video |Learn how to override form data model properties to make it easier to test one form data model against different endpoints.|AEM [!DNL Forms] |

{style="table-layout:auto"}

### Experience Manager release information

All Experience Manager release notes are maintained at the following pages:

* [Experience Manager as a Cloud Service release information](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager release notes](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=en)
* [Automated Forms Conversion Service release notes](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Service Pack release notes](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack release notes](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
* [Experience Manager Assets Dynamic Media release notes](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=en)
* [Experience Manager Brand Portal release notes](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Experience Manager desktop app release notes](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Experience Manager Dispatcher release notes](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=en)
* [Adobe Primetime release notes](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Livefyre release notes](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html)

### Other Help resources for Experience Manager

* [Experience Manager as a Cloud Service Guides](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Cloud Manager User Guide](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=en)
* [Experience Manager 6.5 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Older Versions of Experience Manager Documentation](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic Help Home](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Experience Manager Documentation: Recent Updates](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Icon](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] is an application deployed onto AEM. It is a powerful, enterprise-grade component content management solution (CCMS) which enables native DITA support in Adobe Experience Manager, empowering AEM to handle DITA-based content creation and delivery.

Learn more about [[!DNL Experience Manager Guides]](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html).

### Additional resources

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - tutorials on Experience League
* [[!DNL Experience Manager Guides] Learn & Support](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - product documentation

## ![Icon](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

See the following links for Adobe Commerce release notes:

* [Adobe Commerce and Magento Open Source 2.4.x release notes](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Release notes for Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### New Adobe Commerce tutorials and documentation {#tutorials-commerce}

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 2022|[Adobe Commerce Getting Started guide](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html)|Product documentation |A guide intended for merchants and system administrators that are new to Adobe Commerce and Magento Open Source. Get an overview of the platform from their perspective and some detailed information about basic features that enable a functional store.|
|July 2022|[Page Builder user guide](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html)|Product documentation |Learn about Page Builder features, including a three-part walkthrough for building basic content components. This guide is for administrators. It assumes a basic understanding of the core Adobe Commerce configuration and functionality.|
|July 2022|[B2B for Adobe Commerce Guide](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html)|Administration guide |Get detailed information about installing and enabling this module, including configuration and management of its features.|
|July 2022|[B2B for Adobe Commerce - tutorials](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=en)|Video (multiple) |Learn about the [!UICONTROL Companies] page in Adobe Commerce. You can manage your company accounts and any pending requests for approval appear at the top of the list. |
|July 2022|[Use the Quality Patch Tool](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html)|Video |Learn about the [!UICONTROL Quality Patch Tool], which is a command-line tool that delivers quality patches for Adobe Commerce and Magento Open Source.|
|July 2022|[The Site-Wide Analysis Tool Dashboard](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html)|Video |Learn about the Site-Wide Analysis Tool. This feature is proactive, self-service tool and central repository that includes detailed system insights and recommendations to ensure the security and operability of your Adobe Commerce installation.|
|July 2022|[Use Payment Services](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html)|Video |Learn how to use [!UICONTROL Payment Services] to reduce operational overhead, increase revenue.|
|July 2022|[Manage Order Status](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html)|Video |Learn how to check order status and its details, and how to change the status of an order, if necessary. |
|July 2022|[Marketing Tools](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=en)|Video (multiple) |Learn about creating a catalog price rule, cart price rules, manage related product rules, live search, and more.|
|July 2022|[Innovations in content personalization that deliver business value](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=en)|Video|View Skill Builder presentations and learn about recent innovations in Adobe's Content solution that help you democratize content authoring, make omni-channel delivery a breeze, and scale personalization. |
|July 2022|[Catalog Management](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html)|Videos |Learn about catalog management in Adobe Commerce. create a category, manage products in a category, manage inventory, and more.|

{style="table-layout:auto"}

## ![Icon](/assets/target.png) [!DNL Adobe Target] {#target}

Last Updated: **June 30, 2022**

* For pre-release information, see [Adobe Target prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en)
* For current information, see [Adobe Target release notes](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

### New Adobe Target courses and tutorials {#tutorials-target}

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 2022|[Create audiences](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html)|Video |Learn to create and save custom audiences in [!DNL Target] to use in your activities.|
|July 2022|[Personalize and automate with Adobe Target](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=en)|Video |Learn the core concepts of automating and optimizing Adobe Target capabilities using [!UICONTROL Auto Target] and [!UICONTROL Auto Personalizations].|

{style="table-layout:auto"}

## ![Icon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Latest Campaign product releases

* [Campaign v7.3 release](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)
* [Control Panel June release](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)
* [tutorials and courses](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) on Experience League

### New [!DNL Campaign] tutorials and courses {#tutorials-campaign}

New videos, tutorials, or courses published for Adobe Campaign.

|Published|Name|Type|Description |Applications|
| -----------| ---------- | ---------- | ---------- |---------- |
|July 2022|[Control Panel for hybrid hosting models](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html)|Video |Learn how to enable Control Panel for Adobe Campaign hybrid hosting models, access Control Panel, and unlock key features.|Control Panel|
|July 2022|[Monitor through-puts and latency](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html)|Video |Learn how to monitor delivery through-puts and transactional message latencies of your campaign instance.|Control Panel|
|July 2022|[Monitor workflows to optimize resource usage](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html)|Video |Learn how to monitor your workflows’ temporary storage usage and where to configure workflow settings to avoid database or workflow issues on your instance.|Control Panel|
|July 2022|[Develop and customize data models in Adobe Campaign Classic](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en)|Video (Skill Builder events) |Join this session with our Campaign trainer to learn how to develop a data schema inside a data model within Campaign Classic.|Campaign Classic v7|
|July 2022|[Deliverability best practices and strategies that drive results](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html)|Video |Learn how to minimize the countless hours that go into the planning and production of your email campaigns.|Campaign Classic v7|
|July 2022|[Level up Your Cross-channel Marketing with Adobe Campaign Classic](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en)|Video |Watch this deep-dive webinar focusing on workflows, automation, personalization, and measurement for Adobe Campaign Classic customers.|Campaign Classic v7|
|July 2022|[Time saving tips from a pro!](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en)|Video |Start your new year with tips and tricks from an Adobe Campaign pro! Learn to be more efficient with creating and launching campaigns and how to deliver more meaningful and tailored cross-channel experiences.|Campaign Classic v7|
|July 2022|[Adobe Campaign integrations with a marketing ecosystem](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en)|Video |Learn about Adobe Campaign integrations with a marketing ecosystem. Cross-channel marketing solutions like Adobe Campaign should not sit in isolation from other technologies or teams. Don't let disparate systems impede a complete understanding of a customer and disrupt cross-channel strategies.|Campaign Classic v7|
|July 2022|[Adobe Campaign Standard Customer Spotlight - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en)|Video |Hear from the marketing team at Microsoft® to share how they use Adobe Campaign Standard, their architecture and guiding principles, and best practices. |Campaign Standard|
|July 2022|[Adobe Campaign Customer Spotlight - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en)|Video |Hear Adobe Campaign customers share how they overcome challenges, adjust to the new normal, become more efficient with managing campaigns, and drive meaningful value through Adobe Campaign.|Campaign Classic v7|
|July 2022|[Adobe Campaign Classic V7 vs V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en)|Video |Hear about the latest Product updates and understand differences between V7 and V8 from our Product Managers.|Campaign Classic v7, Campaign v8|
|July 2022|[Keynote - Customer Journey trends and innovation across B2B & B2C](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en)|Video |Learn about the latest trends in Customer Journey Management across B2B and B2C. See the most recent innovations in key journey applications and the broader Adobe Experience Cloud and Platform.|Marketo, Campaign Classic v7, Campaign v8|
|July 2022|[Top Tips and Tricks for Adobe Campaign Standard](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en)|Video |Plug in to your Adobe Campaign Standard instance and discover best practices around targeting, personalization, and marketing fatigue to have a better usage of ACS.|Campaign Standard|
|July 2022|[Team, skills, and organizational design required to support cross-channel marketing](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html)|Video |Learn how to be empowered to engage wherever, whenever, and however you want. Learn the importance of having a marketing organization that supports planning, execution, and measurement.|Campaign Classic v7, Campaign v8, Campaign Standard|

{style="table-layout:auto"}

### Campaign help resources

* Adobe Campaign v8: [Documentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Implementation Guides](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard Documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [Release Planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7 Documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign Control Panel: [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - How-to-videos for [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html)

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

With Journey Optimizer, you can manage scheduled omnichannel campaigns and one-to-one moments for millions of customers from a single application--and the entire journey is optimized with intelligent decisioning and insights.

### Latest Journey Optimizer product releases

Find out more about the latest capabilities, improvements, and fixes in the [Journey Optimizer Release Notes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=en).

### New Journey Optimizer tutorials and courses {#tutorials-ajo}

New videos, tutorials, or courses published for Adobe Journey Optimizer.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 2022|[Configure message frequency rules](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html)|Video |Learn how to create, activate, test, and report on frequency rules. Understand how to determine which frequency rules will be inherited for a message.|
|July 2022|[Configure, author, and deliver SMS messages](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html)|Video |Learn how to configure, author, and include SMS messaging into your customer journeys.|
|July 2022|[Inbound keyword support for SMS](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html)|Video |Understand how native inbound keyword support (start, stop, unstop) for SMS works.|

{style="table-layout:auto"}

### More resources for [!DNL Journey Optimizer]

* [Journey Optimizer documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [Release rotes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)
* [Decision Management documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) - [Release notes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Icon](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Use Experience Platform to orchestrate a customer’s journey at scale across experience channels, by intelligently anticipating every individual’s needs in real time.

### Latest [!DNL Journey Orchestration] product releases

Find out more about the latest capabilities, improvements, and fixes in the [[!DNL Journey Orchestration] release notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html).

#### More resources for [!DNL Journey Orchestration]

* [Journey Orchestration documentation](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html) - [Release notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![Icon](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] is a complete application for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo Engage] [release schedule](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) for the latest release schedule information and release notes.

### New Marketo tutorials and courses {#tutorials-marketo}

New videos, tutorials, or courses published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 27, 2022 |[Marketo Engage tutorials](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en)|Videos |Visit the [Marketo Engage tutorial home](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) on Experience League for all past and new tutorials.|
|July 2022|[B2B experiences with Marketo Engage and Adobe Experience Cloud](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=en)|Video |Get a walkthrough of the integrations between Marketo Engage and Adobe Experience Cloud application, and what pain points will be solved.|Marketo Engage |
|July 2022|[Better together - Adobe Marketo Engage and Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=en)|Video |Learn how to orchestrate B2B campaigns with Marketo Engage and RT-CDP (B2B edition) and what are the top use cases and advantages unlocked.|Marketo, Real-time Customer Data Platform |

{style="table-layout:auto"}

## ![Icon](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] is a unified work management application for sharing ideas, creating content, managing complex processes, and doing their best work.

**Workfront tutorial home**

**July 27, 2022**: Visit Workfront's new [tutorial home on Experience League](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/home.html?lang=en) for all training and tutorial videos and articles.

See the [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) page for a round-up of the latest information for all products.

## ![Icon](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Release notes for [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [New features in [!DNL Advertising Cloud Search]](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **July 27, 2022**

| Feature | Description |
| ------- | ----------- |
| [!UICONTROL Inventory] | (July 27 release) [!UICONTROL Auction Insights] is a new troubleshooting tool that allows you to analyze the deal composition of both guaranteed and non-guaranteed private deals. Using data visualizations, this tool shows the trend and relative proportions of values received for key auction attributes within a specific time period. |

{style="table-layout:auto"}

### New features in [!DNL Advertising Cloud Search] {#adcloud-search}

Last updated: **July 27, 2022**

| Feature | Description |
| ------- | ----------- |
| [!UICONTROL Campaigns] | (Opt-in beta feature for all advertisers; July 16 release) You can now create and manage [!DNL Google Ads] performance max campaigns, including manually creating asset groups and uploading assets. Links to [!DNL Google Merchant Center] product feeds aren’t supported.<br><br>Once you opt in for the beta, you can create campaigns with the [!UICONTROL Campaign Type] "[!UICONTROL Performance Max]" and set up asset groups within the campaign settings. You can also view your existing performance max campaigns, with performance data in table and trend chart format, in the [!UICONTROL Campaigns] view. Campaign-level performance data is also available in reports and in Adobe Analytics (for advertisers with an [!DNL Analytics] integration).<br><br>To opt in for the beta, contact your [!DNL Adobe] account team. |
|  |  [!DNL Google Ads] no longer provides ad-level performance data for standard shopping campaigns, dynamic search ads, or placements. |
| [!UICONTROL Campaigns], [!DNL Advanced Campaign Management], [!UICONTROL Reports] | (July 16 release) ([!DNL Google Ads] and [!DNL Microsoft Advertising] campaigns) The following support is now available for responsive search ads:<ul><li>The [!UICONTROL Ads] view now shows previews of responsive search ads.</li><li> (Since June 20) You can now create dynamic responsive search ad variations using a search engine-specific ad template, based on the contents of your inventory, from [!UICONTROL Campaigns] > [!UICONTROL Advanced (ACM)].</li><li>The [!UICONTROL Ad Variation Report] includes two new custom columns:  "[!UICONTROL Creative Titles]," which is a comma-separated list of the ad's title rows, and "[!UICONTROL Descriptions]," which is a comma-separated list of the ad's description rows.</li></ul> |

{style="table-layout:auto"}

## ![Icon](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

New tutorials and courses published for Adobe Document Cloud.

|Published|Name|Type|Description |Application|
| -----------| ---------- | ---------- | ---------- |---------- |
|July 2022|[Using the approver role](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=en)|Video (updated) |Learn how to send a document through an approval process. |Adobe Sign|
|July 2022|[Set up a Web Form](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html)|Video (updated)|Learn how to create a document that can be signed electronically directly on your website. |Adobe Sign|
|July 2022|[Using the delegator role](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en)|Video (updated) |Description|Adobe Sign|
|July 2022|[Electronically signing a document](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=en)|Video (updated) |Learn how easy it is to sign a document that is sent to you with Acrobat Sign.|Adobe Sign|
|July 2022|[Up & running for Acrobat Sign administrators](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=en)|Video (updated) |Learn the seven key areas that administrators should focus on to get up & running quickly in Acrobat Sign.|Adobe Sign|
|July 2022|[Send for Signature in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=en#)|Video (updated) |Learn how to streamline document workflows by sending a document for signature directly within Microsoft® Outlook.|Adobe Sign|
|July 2022|[Filling and signing in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=en)|Video (updated) |Learn how to streamline document workflows by filling out and signing a form directly within Microsoft Outlook.|Adobe Sign|
|July 2022|[Creating and managing groups](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=en)|Video (updated) |Learn how to create groups, add users to groups, and edit group settings. |Adobe Sign|
|July 2022|[Delegate signing to someone else](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=en)|Video (updated) |Learn how to delegate the signing of a document to someone else.|Adobe Sign|

{style="table-layout:auto"}

For Document Cloud help, see:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud Learn & Support](https://helpx.adobe.com/support/document-cloud.html)

## ![Icon](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

See [Creative Cloud for enterprise tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.

## ![Icon](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) is your destination as a customer data management technical and marketing practice leader and specialist. This collection of tutorials is your one-stop-shop to hear from your peers, get inspired, and learn about developments in MarTech. No registration required, simply click and watch.

## ![Icon](/assets/experience-league.png) Digital Experience Blueprints {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) are repeatable implementations that let you address strategy and quickly solve established business problems. Each Blueprint provides a series of artifacts that explain the high-value business problem, architectures, implementation steps, technical considerations, and links to the relevant documentation.

[Top](#events)
