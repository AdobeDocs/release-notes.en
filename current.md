---
title: Latest Release Notes
description: Learn about the latest release notes, new features, and new documentation for Experience Cloud products and services. Find new help and tutorials about Experience Cloud, Creative Cloud for Enterprise, and Document Cloud.
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
---
# INTERNAL REVIEW - Adobe Experience Cloud Release Notes - October 2021

![Banner](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] applications and services are updated monthly. This page is your central location for finding the latest release updates, documentation, and tutorials for [!DNL Experience Cloud] and [!DNL Experience Platform]. You can also find new documentation for [!DNL Creative Cloud for Enterprise] and [!DNL Document Cloud].

>[!NOTE]
>
>Subscribe to the monthly [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to receive email notifications about updates to this page. This page is maintained throughout the month, so please check back regularly for updates to Adobe enterprise product and Experience League documentation.

Release month: **October 2021**

Latest update: **September 29, 2021**

* [[!DNL Experience League] Live Events](#events)
* [[!DNL Experience Cloud Central Interface Components] & Administration](#ecloud)
* [Adobe [!UICONTROL System Status]](#status)
* [[!DNL Adobe Analytics]](#analytics) and [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Need help? Visit [Adobe Experience League](https://experienceleague.adobe.com/#home) to find product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/experience-league.png) [!DNL Experience League] Live Events {#events}

[!DNL Experience League] Live Events are discussions with Adobe experts and special guests who are instrumental in bringing Adobe technology to you. See the following schedule and join us live or watch previously recorded events.

|Event Date|Event Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|September 23, 2021 |[Expert tips to make your holiday campaigns stand out](https://www.youtube.com/watch?v=bsU1lAv0xes)|Live video event |Just like it’s never too early to start your holiday shopping, it’s never too early to start planning for a wildly successful holiday marketing campaign. With Adobe Campaign, you can design, plan, and execute campaigns that make all your organization’s holiday wishes come true.<br>But do you know all the tips for running campaigns that finish the year out with a bang? Join Sandra for a live discussion featuring three Adobe experts who have eons of collective expertise in doing just that.|
|August 26, 2021|[Make Your Next Audience Segment Smarter than Ever](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=en)|Event recording|The success of every good marketing campaign hinges on precisely targeting your audience. With the new Adobe Experience Platform [!UICONTROL Segment Builder], you can build your next audience segment using profile data and time-based user behavior across channels. There’s no better way to ensure that your messages reach the people who need to hear them most.|
|July 29, 2021|[My Three Favorite Adobe Analytics Implementation Tips](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=en)|Event recording |You’ve seen him on-stage at Summit. You’ve heard him share expert advice at Adobe Insider Tours. You may have even had the benefit of working with him on your own Adobe Analytics implementation. Now, Eric Matisoff is bringing his three favorite Adobe Analytics implementation tips to this exclusive Experience League Live discussion.|

{style="table-layout:auto"}

For more videos, visit the [Adobe Experience League Channel](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) on YouTube.

## ![Icon](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] & Administration {#ecloud}

| Feature | Description |
| ------- | ------- |
|Unified Search |Unified Search continues to add objects types to the search index. In this update, global search now searches across Experience League content and the following Journey Optimizer object types: <ul><li>Datasets</li><li>Destinations</li><li>Queries</li><li>Schemas</li><li>Segments</li><li>Sources</li><li>Offers</li><li>Components</li><li>Messages</li><li>Journeys</li></ul> |
|Product usage data consent  |When you first sign in, you are asked to submit preferences for how Adobe can use Experience Cloud product usage data to enhance your experience. This request also includes an update to your preferences for collection and usage of these data at <https://experience.adobe.com/preferences>.|
|Experience Cloud [!UICONTROL Triggers] navigation  |[Experience Cloud Triggers](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) is available for direct navigation from the application switcher ("waffle icon") in the header for provisioned users. The [!UICONTROL Data Collection] / [!UICONTROL Launch] interstitial page (<https://experience.adobe.com/implement>) will be going away in November 2021.   |

{style="table-layout:auto"}

**More help resources on [!DNL Experience Cloud Central UI Components] & Administration**

* Administration help for [Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) and user management
* Help and release notes for [Places - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Help on [People - Customer Attributes and Audience Library](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icon](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

(Find the latest release information for [!DNL Adobe System Status] in the [May 21, 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=en) release notes.)

## ![Icon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Release date: **October 7, 2021**

* [New features in Adobe Analytics](#aa-features)
* [New features in Customer Journey Analytics](#cust-journey)
* [Fixes in Adobe Analytics](#aa-fixes)
* [Important notices for Analytics administrators](#aa-notices)
* [Analytics courses and tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### New features in Adobe Analytics {#aa-features}

| Feature | Description | [General Availability](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Target Date |
| ----------- | ---------- | ------- |
| Quick [!UICONTROL Segment Builder] | Allows business users to quickly apply basic segments in a simplified, in-line project workflow. No need to go to the [!UICONTROL Segment Builder]. [Learn more](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | October 7, 2021 |
| Visualizations for Analytics dashboards | Analytics dashboards is introducing three new visualizations to give executives and decision makers an even better at-a-glance understanding of their data. The new doughnut, line, and horizontal bar charts all make it easier to see data for individual dimension items, without having to open a details view. (Documentation link to follow) | October 7, 2021 |
| [!UICONTROL Media Playback Time Spent] | Adobe Streaming Media Playback [!UICONTROL Time Spent] provides valuable insight into viewer engagement and enables media organizations to derive deeper, more granular insights with minute-by-minute user engagement through advanced time spent analysis with day-parting capabilities. You can observe the amount of time spent viewing your media streams at a specific point in time and you can split the playback duration by different granularities, including new 5-minute, 15-minute, and 30-minute granularities. (Documentation link to follow) | October 7, 2021 |

{style="table-layout:auto"}

### New features in Customer Journey Analytics {#cust-journey}

| Feature | Description | [General Availability](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Target Date |
| ----------- | ---------- | ----- |
| Report Builder support | Report Builder is a Microsoft Excel Add-in that allows you to easily create, edit, and refresh custom reports using Customer Journey Analytics data. With Report Builder and Excel, you can use the simple but flexible drag-and-drop UI to easily build complex data requests. With Report Builder for Customer Journey Analytics, you can:<ul><li>Reference existing worksheet cells to get the perfect row order, date range, or filter</li><li>Create custom dates using calendar, cell references, or date math</li><li>Design your tables and visualizations with familiar Excel formatting tools</li></ul> | October 7, 2021 |
| Quick [!UICONTROL Filter Builder] | Allows business users to quickly apply basic segments in a simplified, in-line project workflow. No need to go to the [!UICONTROL Filter Builder]. [Learn more](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | October 7, 2021 |
| Visualizations for Analytics dashboards | Analytics dashboards is introducing three new visualizations to give executives and decision makers an even better at-a-glance understanding of their data. The new doughnut, line, and horizontal bar charts all make it easier to see data for individual dimension items, without having to open a details view. (Documentation link to follow)| October 7, 2021 |
| Customer Journey Analytics audit logs (API only) | Audit logs are an important part of security compliance as well as for auditing data and user actions.| October 7, 2021 |

{style="table-layout:auto"}

### Fixes in Adobe Analytics and CJA {#aa-fixes}

* Fixed a scheduled report error in Customer Journey Analytics. (AN-271721)
* Fixed issues with [!UICONTROL Search Components] in [!UICONTROL Workspace] not resulting in exact matches. (AN-253937; AN-271707)

#### Additional fixes in Adobe Analytics

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| ----------- | ---------- | ---------- |
| EOL for three Analytics API services | September 16, 2021| On **October 28, 2021**, the following Analytics Legacy API services will reach their end-of-life date and be shut down. Any current integrations built using these services will stop working on that day.<ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>Adobe has provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs. |

{style="table-layout:auto"}

### AppMeasurement {#appm}

For the latest updates on AppMeasurement releases (Version 2.22.2), please refer to [AppMeasurement for JavaScript release notes](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en).

### Analytics courses and tutorials {#tutorials-analytics}

Latest courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|September 2021|[Foundational Metrics in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/foundational-metrics-in-adobe-analytics.html)|Video |Get a conceptual description of basic visitor metrics in Adobe Analytics and how they relate to each other. Learn several use cases for when to use [!UICONTROL Page Views], [!UICONTROL Visits], and [!UICONTROL Unique Visitors] in reporting.|
|September 2021|[Table and Visualization [!UICONTROL Data Source] Settings](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/table-and-visualization-data-source-settings.html?lang=en)|Video |See how tables and visualizations are tied together through settings, and learn how to configure those settings for different analysis use cases.|
|September 2021|[Send Data Warehouse request via SFTP](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-warehouse/send-data-warehouse-request-via-sftp.html?lang=en)|Video |Learn how to send [!UICONTROL Data Warehouse] requests via SFTP. [!UICONTROL Data Warehouse] refers to the copy of Analytics data for storage and custom reports, which you can run by filtering the data. You can request reports to display advanced data relationships from raw data based on your unique questions.|
|September 2021|[Check Linked IMS ID to prevent login issues](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/user-management/check-linked-ims-id-to-prevent-login-issues.html?lang=en)|Video |Incorrect or missing Linked IMS IDs in Adobe Analytics can lead to login issues for users. Users can check the Linked IMS ID themselves and contact customer support for any issues, saving the hassle of performing common troubleshooting steps.|
|September 2021|[Rerun a Data Feed job](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-feeds/rerun-a-data-feed-job.html?lang=en)|Video |The [!UICONTROL Data Feed] UI in Adobe Analytics makes data feed management much easier. If you have the access to manage the data feed, you can rerun a data feed job on your own using the data feed interface without having the customer support team resending the recent data feed files.|
|September 2021|[Find your Data Feed ID](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-feeds/find-your-data-feed-id.html?lang=en)|Video |At times, you may need to contact Adobe if there is a failed data feed delivery or with a request to resend a data feed file. It becomes convenient for customer support team to handle such requests if the [!UICONTROL Data feed] ID is provided by the customer.|
|September 2021|[View your accounts available features](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/company-settings/view-your-accounts-available-features.html?lang=en)|Video | View [!UICONTROL Feature Access Levels] settings under [!UICONTROL Admin] section on [!DNL Analytics] allows you to view the level of access to [!DNL Analytics] packages and features that your company is entitled to. This view is available for Activity Map, Advertising Analytics, Anomaly detection in alerts, and so on.|
|September 2021|[Manage an upcoming traffic spike](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/traffic-management/manage-an-upcoming-traffic-spike.html?lang=en)|Video |Adobe attempts to partner with clients to ensure that a high-traffic event is successful. Scheduling traffic spikes is the starting point in that partnering process. The [!UICONTROL Schedule Spike] section lets you alert Adobe of temporary traffic spikes so that appropriate resources can be allocated to handle them.|
|September 2021|[Enforce Email Domain Restrictions - Technical Video](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/company-settings/enforce-email-domain-restrictions.html?lang=en)|Video |The [!UICONTROL Security Manager] lets you control access to reporting data. Options include strong passwords, password expiration, IP login restrictions, and email domain restrictions. [!UICONTROL Enforce Email Domain Restriction] filters the email addresses and domains where Analytics sends bookmarks, downloadable reports, and alerts. The email filter list supports up to 100 entries, and each entry can be an email address or an entire email domain.|
|September 2021|[Transfer user assets to a different user](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/user-management/transfer-user-assets-to-a-different-user.html?lang=en)|Video |The [!UICONTROL User Management] page lets you manage users and groups, and control access to reports, tools, and report suites. You can assign user account items like dashboards, calendar events, and bookmarks from one user account to another through [!UICONTROL User Management] in Adobe Analytics.|
|September 2021|[Configure [!UICONTROL bot rules] in Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-bot-rules-in-analytics.html?lang=en)|Video |[!UICONTROL Bot Rules] let you remove traffic from your report suite that is generated by known spiders and bots. Removing bot traffic can provide a more accurate measurement of user activity on your website. After bot rules are defined, all incoming traffic is compared against the defined rules. Traffic that matches any of these rules is not collected in the report suite and is not included in traffic metrics.|
|September 2021|[Overview of Analytics admin logs](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/logs/overview-of-analytics-admin-logs.html?lang=en)|Video |Log files help you see when users log in, their usage, access, report suites, and admin changes. The admin log reports all the changes made by administrators in [!UICONTROL Admin Tools]. The log provides a gateway to user-defined reports from any of the three logs.|
|September 2021|[View Analysis Workspace performance metrics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/view-analysis-workspace-performance-metrics.html?lang=en)|Video |Various factors can influence the performance of a project within Analysis Workspace. Using the [!UICONTROL Performance] option, you can see factors that impact your project’s performance, including network, browser, and project factors.|
|September 2021|[Enable the Timestamp Optional setting](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/enable-the-timestamp-optional-setting.html?lang=en)|Video |[!UICONTROL Timestamps Optional] allows you to mix timestamped and non-timestamped data in the same global report suite. You can send timestamped data from a mobile app to a global report suite and upgrade apps to use offline tracking without having to create a report suite.|
|September 2021|[Download the Data feed authentication key](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-feeds/download-the-data-feed-authentication-key.html?lang=en)|Video |Creating a data feed allows Adobe to know where to send raw data files, and what you would like to include in each file. SFTP support for data feeds is available in Analytics. It requires an SFTP host, username, and the destination site to contain a valid RSA or DSA public key. You can download the appropriate public key when creating the feed.|
|September 2021|[Customize visualization legends](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/customize-visualization-legends.html?lang=en)|Video |Customizing the legends in your visualizations, also known as series label editing, is a great way to make your visualizations more understandable for everyone looking at the reports.|
|September 2021|[Dimension-Graph Live Linking in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/dimension-graph-live-linking.html?lang=en)|Video |We don’t quite know what to call this, but it’s cool! When you create a line graph from a dimension value, you can now select different dimension values and change the graph dynamically. Watch the video to learn more!|

{style="table-layout:auto"}

### Analytics help resources

* [Adobe Analytics Product Documentation and Tutorials](https://experienceleague.adobe.com/docs/analytics.html)

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

New features in Audience Manager - updated **September 14, 2021**:

| Feature | Description |
| ------- | ------- |
| Mobile ID data collection consent | Added support for mobile ID data collection consent. To benefit from this update, customers must upgrade to [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) or later. |

## ![Icon](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Includes release update information and new documentation for Experience Platform and [!UICONTROL Mobile SDK]).

**September 29, 2021** release - See [Experience Platform release notes](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html) for all the details.

### Experience Platform tutorials and courses {#tutorials-platform}

Latest videos, tutorials, or courses published for Experience Platform and services.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|September 2021|[[!UICONTROL Alerts]](https://experienceleague.adobe.com/docs/platform-learn/tutorials/admin/use-alerts.html)|Video |Learn how to subscribe to and administer alerts in Adobe Experience Platform. [!UICONTROL Alerts] help you monitor various processes to make sure that your Platform implementation is running smoothly.|
|September 2021|[Product profiles](https://experienceleague.adobe.com/docs/platform-learn/tutorials/admin/managing-product-profiles.html)|Video |Learn how to create a product profile and assign users, developers, admins, and permissions.|
|September 2021|[Introduction to [!UICONTROL Admin Console]](https://experienceleague.adobe.com/docs/platform-learn/tutorials/admin/admin-console.html)|Video |A high-level overview of the access control hierarchy workflow for Experience Platform.|

{style="table-layout:auto"}

### Adobe Mobile SDK

See [Release notes and change logs](https://aep-sdks.gitbook.io/docs/release-notes) for the Adobe Experience Platform Mobile SDKs.

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

### Latest Journey Optimizer product releases

Find out more about the latest capabilities, improvements, and fixes in the [Journey Optimizer Release Notes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

### Journey Optimizer tutorials and courses {#tutorials-ajo}

Latest Journey Optimizer tutorials:

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|August 2021|[Introduction to building a journey](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/introduction-to-building-a-journey.html)|Video |Understand the basics of building a journey in the journey canvas.|
|August 2021|[Set up customer profile data - overview](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/data-configuration/set-up-data-overview.html)|Video |Learn about real-time customer profile data and the steps required to set up customer profile data for Journey Optimizer.|
|August 2021|[Map identities](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/data-configuration/map-identities.html)|Video |Learn how and when to label a schema field as an identity, how to create a namespace, when to make an identity primary, and how to ingest and verify identity data.|
|August 2021|[Use Case - Burst Message](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html)|Video |Understand the applicable use cases for burst messaging. Learn how to configure a journey for burst messages and which best practices to apply.|

{style="table-layout:auto"}

### More resources for Journey Optimizer

[Help Center](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use Experience Platform to orchestrate a customer’s journey at scale across experience channels, by intelligently anticipating every individual’s needs in real time.

### Latest Journey Orchestation product releases

Find out more about the latest capabilities, improvements, and fixes in the [Journey Orchestration Release Notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html).

#### More resources for Journey Orchestration

[Help Center](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![Icon](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] is an Application Service integrated with Adobe Experience Platform. Use [!UICONTROL Offer Decisioning] to deliver the best offer and experience to your customers across all touch points at the right time.

### Latest Offer Decisioning product releases

Find out more about the latest capabilities, improvements, and fixes in the [Offer Decisioning Release Notes](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html).

#### More resources for [!UICONTROL Offer Decisioning]

[Help Center](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html#new) - [How-to videos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/documentation-updates.html)

## ![Icon](/assets/aem.png) Experience Manager {#aem}

Adobe recommends visiting the [Experience Manager release updates and roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) page to stay current on release information.

### Community

* [Adobe Developers Live](https://adobe.ly/3A0yybp) | 4-5 October 2021, 7:00 PDT

    Adobe Developers Live brings together Adobe developers and experience builders with diverse backgrounds and a singular purpose – to create incredible end-to-end experiences. This two-day conference features important developer updates, technical sessions, and community networking opportunities.

    Adobe product teams across Adobe Experience Cloud, Document Cloud, and Creative Cloud will showcase the latest technological advances and developer tools powering design, content creation workflows, document services, and customer experience management across industries.

    Adobe has 20 Experience Manager sessions planned. Spread the word!

  * [Complete session list](https://adobe.ly/2VKuAVq)
  * [Free registration &ndash; Log in to RSVP](https://adobe.ly/3A0yybp)
  * [Adobe Developers Live Community](https://adobe.ly/3BVeK9V)

### New Experience Manager courses and tutorials {#tutorials-aem}

New videos, tutorials, and courses published over the past month.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|October 2021|[[!UICONTROL Content Transfer Tool]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en)|Video |Learn how [!UICONTROL Content Transfer Tool] helps you migrate content to AEM as a Cloud Service from AEM 6.3+.|
|October 2021|[[!UICONTROL Bulk Import Service]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en)|Video |Learn how AEM as a Cloud Services’ [!UICONTROL Bulk Import Service] can be used to import assets from non-AEM sources.|
|October 2021|[Communications (Output Service)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en)|Video |Learn how AEM Forms as a Cloud Service supports the Communication use case.|
|October 2021|[Digital Enrollment](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en)|Video |Learn about how AEM Forms as a Cloud Service supports the Digital Enrollment use case.|
|October 2021|[Using [!UICONTROL Cloud Acceleration Manager] tools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html)|Video |A narrated walk-through of using [!UICONTROL Cloud Acceleration Manager] tools.|
|October 2021|[Navigating [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html)|Video |Explore the navigation experience of [!UICONTROL Cloud Acceleration Manager] for Experience Manager as a Cloud Service.|
|October 2021|[[!UICONTROL Asset Workflow Migration] Tool](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html)|Video |Learn how the [!UICONTROL Asset Workflow Migration] tool helps migrate your existing AEM Assets Workflows to AEM as a Cloud Service.|
|October 2021|[[!UICONTROL Index Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html)|Video |Learn how the [!UICONTROL Index Converter] automatically converts existing AEM index definitions to be AEM as a Cloud Service compatible.|
|October 2021|[[!UICONTROL Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html)|Video |Learn how the [!UICONTROL Dispatcher Converter] automatically updates existing AEM Dispatcher configurations to be AEM as a Cloud Service compatible.|
|October 2021|[[!UICONTROL Code Repository Modernizer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html)|Video |Learn how the [!UICONTROL Core Repository Modernizer] automatically updates existing AEM Maven projects to be AEM as a Cloud Service compatible.|
|October 2021|[[!UICONTROL Code Refactoring Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html)|Video |Learn how the AEM [!UICONTROL Code Refactoring Tools] help automate the conversion of existing AEM projects to be AEM as a Cloud Service compatible.|
|October 2021|[[!UICONTROL Content Transfer Tool]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html)|Video |Learn how the [!UICONTROL Content Transfer Tool] lets you efficiently move content from AEM 6.5 to AEM as a Cloud Service.|
|October 2021|[The implementation phases of [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html)|Video |Review and understand the major implementation phases or moving to AEM as a Cloud Service using [!UICONTROL Cloud Acceleration Manager].|
|October 2021|[Readiness and [!UICONTROL Best Practice Analyzer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html)|Video |Learn how the [!UICONTROL Best Practice Analyzer] can help prepare you to move from AEM on-prem or Adobe Managed Services to Experience Manager as a Cloud Service.|
|October 2021|[Introduction to Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html)|Video |Learn how [!UICONTROL Cloud Acceleration Manager] can help you quickly and easily move to Experience Manager as a Cloud Service.|
|October 2021|[AEM Forms as a Cloud Service - Moving to AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en)|Video |Learn about use cases and features supported by AEM Forms as a Cloud Service.|
|October 2021|[Troubleshooting AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en)|Video |Learn how to troubleshoot and debug the AEM SDK, AEM as a Cloud Service and, the build and deploy process.|
|October 2021|[AEM [!UICONTROL Assets Microservices] - Moving to AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en)|Video |Learn how AEM Assets as a Cloud Service’s asset compute microservices allow you to automatically and efficiently generate any rendition for your assets, replacing this role of traditional AEM Workflow.|
|October 2021|[Search and indexing](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en)|Video |Learn about the AEM as a Cloud Service search indexes, how to convert AEM 6 index definitions to be AEM as a Cloud Service compatible, and how to deploy indexes to AEM as a Cloud Service.|
|October 2021|[[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en)|Video |Learn about AEM [!UICONTROL Dispatcher] for AEM as a Cloud Service, focusing on notable changes from [!UICONTROL Dispatcher] for AEM 6, the [!UICONTROL Dispatcher] conversion tool and how to use the Dispatcher Tools SDK.|
|October 2021|[[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en)|Video |Learn about Cloud Manager for AEM as a Cloud Service, and its differences with Cloud Manager for AEM on Adobe Manage Services (AMS).|
|October 2021|[Onboarding to AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en)|Video |Learn about onboarding to AEM as a Cloud Service starting from the contract phase all the way through setting up the environments using [!UICONTROL Cloud Manager].|
|October 2021|[Repository Modernization](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en)|Video |Learn about repository modernization, mutable and immutable content, package structure and the repository modernizer CLI tool.|
|October 2021|[AEM [!UICONTROL Modernization Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en)|Video |Learn how AEM [!UICONTROL Modernization Tools] are used to upgrade an existing AEM project and content to be AEM as a Cloud Service compatible.|
|October 2021|[AEM Modernization Tools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en)|Video |Learn how to think differently about AEM as a Cloud Service implementations.|
|October 2021|[Best Practice Analyzer and Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en)|Video |Learn how Best Practice Analyzer (BPA) and Cloud Acceleration Manager (CAM) provides a customized guide for migrating to AEM as a Cloud Service.|
|October 2021|[Maintaining Version History](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html)|Video |Learn how Adobe Workfront and Experience Manager [!UICONTROL Assets Essentials] helps you maintain versions of [!DNL Workfront] documents and Assets Essentials assets.|
|October 2021|[Sending documents and Linking assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en)|Video |Learn how to send Workfront documents to to Assets Essentials, and link Assets Essentials assets to Workfront.|
|October 2021|[Configuring the integration](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en)|Video |Learn how to configure the Adobe Workfront and Assets Essentials integration.|
|October 2021|[What’s a digital signature](https://docs.adobe.com/content/help/en/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html)|Video |Learn about certificate-based digital signatures, which comply with the strictest legal regulations around the world and provide the highest level of assurance of a signer’s identity.|
|October 2021|[Segment Builder in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#)|Video |Slice and dice your data with segmentation in Adobe Analytics. This video walks you through the [!UICONTROL Segment Builder] and gives a basic overview.|

{style="table-layout:auto"}

### Experience Manager release information {#aem-links}

Release notes and other release information links for Experience Manager are here:

* [[!DNL Experience Manager as a Cloud Service] release notes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=en)
* [[!DNL Experience Manager as a Cloud Service] release information](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [[!DNL Experience Manager Cloud Manager] release notes](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Automated Forms Conversion Service release notes](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Service Pack release notes](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack release notes](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
* [[!DNL Experience Manager Assets Dynamic Media] release notes](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=en)
* [[!DNL Experience Manager Brand Portal] release notes](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Experience Manager desktop app release notes](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [[!DNL Experience Manager Dispatcher] release notes](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=en)
* [Adobe Primetime release notes](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Livefyre release notes](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html)

### Other help resources for Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Guides](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Older Versions of Experience Manager Documentation](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] User Guide](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [[!DNL Dynamic Media Classic] Help Home](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Experience Manager Documentation: Recent Updates](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Icon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Latest Campaign product releases

Find out more about the latest capabilities, improvements, and fixes released:

* [Campaign v8 Release Notes](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html)
* [Campaign Classic v7 Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)
* [Campaign Standard Release Notes](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)

### New [!UICONTROL Campaign] courses and tutorials {#tutorials-campaign}

Latest tutorials and courses for Adobe Campaign.

|Published|Name|Application|Description |
| -----------| ---------- | ---------- | ---------- |
|September 2021|[Trouble shooting [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/troubleshooting.html)|Campaign V8 |Learn how to troubleshoot [!UICONTROL Control Panel].|
|September 2021|[Monitor databases](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/performance-monitoring/monitor-databases.html)|Campaign V8 |Learn how to monitor your instance's database usage with the [!UICONTROL Control Panel].|
|September 2021|[Allowlist IP addresses](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/instance-settings/allowlist-ip-address.html)|Campaign V8 |Learn how to add an IP range to Campaign Classic instances' allowlists and how to remove them from the allowlist using the [!UICONTROL Control Panel].|
|September 2021|[Allowlist IP ranges](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/allowlist-ip-range.html)|Campaign V8 |Learn how to add an IP address range to an allowlist in the [!UICONTROL Control Panel].|
|September 2021|[Add URL Permissions](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/instance-settings/add-url-permissions.html)|Campaign V8 |Learn how to establish a connection from your Adobe Campaign Classic instance to an external URL.|
|September 2021|[Connect to an SFTP Server](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/connect-to-sftp-server.html)|Campaign V8 |Learn how to connect to your SFTP server using a client SFTP application, using the keys you have stored in the [!UICONTROL Control Panel].|
|September 2021|[Generate an SSH Key](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/generate-ssh-key.html)|Campaign V8 |Learn how to generate an SSH key using a terminal and how to store the public version of the key in the [!UICONTROL Control Panel].|
|September 2021|[Control Panel - Monitor server capacity](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/monitor-server-capacity.html)|Campaign V8 |Learn how to monitor the storage capacity of your SFTP servers. |
|September 2021|[Control Panel - Get started with the Control Panel](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/get-started.html)|Campaign V8 |This article explains how to access the [!UICONTROL Control Panel] and what the prerequisites are to be able to work with the [!UICONTROL Control Panel].|
|September 2021|[Troubleshoot Adobe Campaign - Overview](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/overview.html?lang=en)|Campaign Standard |This section has been provided by Adobe Customer Support to help you troubleshoot issues you might encounter with Adobe Campaign Standard.|
|September 2021|[Missing zero ID record](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/login-and-client-console/fixing-zero-id.html?lang=en)|Campaign Classic |Learn how to fix the issue of zero (0) id.|
|September 2021|[Load balancer issues](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/administration/load-balancer-issues.html?lang=en)|Campaign Classic |Learn how to fix load balancer issues on instance restart.|
|September 2021|[Send campaign label to Analytics](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/integrations/missing-campaign-label.html?lang=en)|Campaign Classic |Learn how to fix missing campaign label in Analytics.|
|September 2021|[Disabled messages triggering e-mails](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/deliveries-and-channels/disabled-messages-sending-emails.html?lang=en)|Campaign Classic |Learn how to stop e-mails from disabled messaged.|
|September 2021|[Fix publishing errors](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/deliveries-and-channels/publishing-permissions-issues.html?lang=en)|Campaign Classic |Learn how to fix publishing errors for non-admin users.|
|September 2021|[Steps to change public resource URL from http to https](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/change-public-resource-url.html?lang=en)|Campaign Standard |Learn how to change the public resource URL from http to https|
|September 2021|[Fetch Delivery XML Data](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/workflows/query-delivery-output-names.html?lang=en)|Campaign Classic |Learn how to fetch delivery XML data.|
|September 2021|[Error while connecting to Experience Manager](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/error-aem-connection.html?lang=en)|Campaign Standard / Experience Manager |Learn how to resolve error `GetAEMContentList` of service `nms:delivery`, while connecting from Campaign Standard to Experience Manager.|
|September 2021|[Fix console login errors](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/login-and-client-console/console-login-errors.html?lang=en)|Campaign Classic |Learn how to fix errors encountered during console login.|
|September 2021|[How to troubleshoot a technical error while viewing a profile](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/technical-error-while-viewing-profile.html?lang=en)|Campaign Standard |Learn how to fix errors encountered during console login.|
|September 2021|[Unconditional stop in campaign workflow](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/workflows/unconditional-stop-workflow.html?lang=en)|Campaign Classic |Learn how to correctly perform an unconditional stop in workflow.|

{style="table-layout:auto"}

### Campaign help resources

* Adobe Campaign v8: [Help Center](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html) - [Implementation Guides](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard Documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [Release Planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7 Documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign Control Panel: [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - How-to-videos for [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Release notes for [!DNL Adobe Advertising Cloud].

* [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [New features in [!DNL Advertising Cloud Search]](#adcloud-search)

### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **September 28, 2021**

| Feature | Description |
| ------- | ----------- |
| Campaign management views | A "[!UICONTROL Creation date]" column is now available in custom column sets for the [!UICONTROL Campaigns], [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views. You can also filter the [!UICONTROL Placements] and [!UICONTROL Ads] views by [!UICONTROL Creation date]. |
| Programmatic guaranteed deals | (8 September release) You can now edit the [!UICONTROL Max Bid] for the default placement for a programmatic guaranteed (PG) deal. However, because PG deals always have a fixed CPM, only international clients should edit the [!UICONTROL Max Bid] to take into account currency exchange fees. |
|  | (8 September release) Users with the “[!DNL FreeWheel Programmatic Guaranteed]” permission can now submit an ad to the [!DNL FreeWheel Programmatic Creative API] from the [!UICONTROL Ads] view or the [!UICONTROL Placements] view. You still can submit an ad from the [!UICONTROL Deals] view. |

{style="table-layout:auto"}

### New features in [!DNL Advertising Cloud Search] {#adcloud-search}

Last updated: **September 28, 2021**

| Feature | Description |
| ------- | ----------- |
| Advertising Insights | Additional insights are available in beta mode. |

{style="table-layout:auto"}

## ![Icon](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

See the following links for Adobe Commerce release notes:

* [Adobe Commerce and Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Icon](/assets/target.png) [!DNL Target] {#target}

Last Updated: **August 3, 2021**

See [[!DNL Target] release notes](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en) for the latest release information.

## ![Icon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is a complete application for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo Engage] [release schedule](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) for the latest release schedule information and release notes.

## ![Icon](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] is a unified work management application for sharing ideas, creating content, managing complex processes, and doing their best work.

See the [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) page for a round-up of the latest information for all products.

## ![Icon](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

New videos, tutorials, or courses published for Adobe Document Cloud.

### Document Cloud courses and tutorials {#tutorials-doc-cloud}

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|October 2021|[Digital ID overview](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digitalid-overview.html)|Video |Learn how to use digital IDs from around the world with Adobe Sign.|
|October 2021|[Getting started with Adobe Sign for new senders](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html)|Video |If you’re new to using Adobe Sign, this tutorial is a great place to start. This comprehensive tutorial focuses on all the basics to get you up and running quickly with Adobe Sign.|
|October 2021|[Load PDF comments into InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html)|Video |In this 60-second video tutorial, learn how to load PDF comments back into InDesign after an Acrobat shared review. This digital workflow helps you complete revisions in record time.|
|October 2021|[Get a digital ID from [!DNL Intesi Group] (Qualified)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html)|Video |Learn how to obtain a qualified digital signing certificate from [!DNL Intesi] Group. Once registered and your identity is verified, [!DNL Intesi] Group issues you with a digital ID that is used to apply an Adobe Sign cloud signature.|
|October 2021|[Get a digital ID from [!DNL Intesi Group] (Qualified)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html)|Video |Learn how to use your Intesi Group digital ID to authenticate your identity and authorize a remote digital signature (cloud signature) on a document.|
|October 2021|[Get a digital ID from [!DNL Intesi Group] (Advanced)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html)|Video |Learn how to obtain an Advanced digital signing certificate from Intesi Group. Once registered and your identity is verified, Intesi Group issues you with a digital ID that is used to apply an Adobe Sign cloud signature.|
|October 2021|[Signing using [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html)|Video |Learn how to use your [!DNL Digidentity] digital ID to authenticate your identity and authorize a remote digital signature (cloud signature) on a document.|
|October 2021|[Get a digital ID from [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html)|Video |Learn how to obtain a digital signing certificate from [!DNL Digidentity]. Once registered and your identity is verified, [!DNL Digidentity] issues you with a digital ID that is used to apply an Adobe Sign cloud signature.|
|October 2021|[Detect differences between two PDFs](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html)|Video |Never make the mistake of working with the wrong version of a file. Quickly and accurately detect the differences between two PDF files to improve document review workflows.|
|October 2021|[Create PDF content while browsing with Microsoft Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html)|Video |Learn how to archive web pages to PDF on the fly with the Adobe Acrobat extension for Microsoft Edge. This Windows-only tool is invaluable for research projects and offline viewing of web-based information.|
|October 2021|[Convert email messages and attachments to PDF in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html)|Video |Learn how to archive email messages and attachments to PDF in Outlook for your projects. Learn to deliver information in a more professional and secure manner by automatically converting attachments to PDF. This tool is only available for Windows.|
|October 2021|[Mapping Metadata](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en)|Video |Learn how to configure metadata mapping between Workfront fields and Assets Essentials properties, as well as configuring Assets Essentials to display the mapped values.|

{style="table-layout:auto"}

For Document Cloud help, see:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud Learn & Support](https://helpx.adobe.com/support/document-cloud.html)

## ![Icon](/assets/creative-cloud-24.png) Creative Cloud for enterprise {#creative-cloud}

See [Creative Cloud for Enterprise Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.
