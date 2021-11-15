---
title: Latest Release Notes
description: Learn about the latest release notes, new features, and new documentation for [!DNL Experience Cloud] products and services. Find new help and tutorials about [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: 
---
# Adobe Experience Cloud Release Notes - November 2021

![Banner](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] applications and services are updated monthly. This page is your central location for finding the latest release updates, documentation, and tutorials for [!DNL Experience Cloud] and [!DNL Experience Platform]. You can also find new documentation for [!DNL Creative Cloud for enterprise] and [!DNL Document Cloud].

>[!NOTE]
>
>Subscribe to the monthly [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to receive email notifications about updates to this page. This page is maintained throughout the month, so please check back regularly for updates to Adobe enterprise product and Experience League documentation.

Release month: **November 2021**

Latest update: **November 15, 2021**

* [[!DNL Experience League] Events](#events) (Updated November 15, 2021)
* [[!DNL Experience Cloud Central Interface Components] & Administration](#ecloud)
* [Adobe [!UICONTROL System Status]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics) and [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud) (**October 27, 2021**)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Need help? Visit [Adobe Experience League](https://experienceleague.adobe.com/#home) to find product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/experience-league.png) [!DNL Experience League] Events {#events}

Experience League Events are a great place to get answers from product experts at Adobe. Check out our 

* Community Q&A Coffee Breaks
* Experience League Live video events (also available on demand)
* Adobe Developer's Live

Schedules and events are as follows:

### Experience League Live{#exl-live}

[Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) is a live streaming show produced by the Experience League team. It’s a chance to connect with Adobe product experts and learn actionable tips, tricks, and strategies you can apply with the Adobe Experience Cloud applications.

|Event Date|Time |Event Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |---------- |
|November 18, 2021 |12 p.m. (EST) |[Go live faster than ever, with quick site creation in Adobe Experience Manager](https://www.youtube.com/watch?v=7-Lcw5PejhI)|Live Video Event|Deploy a feature-rich, personalized web experiences in days, without back-end development. Learn how to use a low-code approach to create a site in Adobe Experience Manager by using a pre-defined [!UICONTROL Site Template]. Join us for a live presentation and demo with Adobe Product Managers Shankari Panchapakesan, Gabriel Walt, and Danny Gordon. You may even see some live coding!|
|October 21, 2021 |12 p.m. (EST) |[Who clicked that? Advanced reporting on link clicks with Adobe Analytics](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)|On demand|Reporting on user interaction with your web or mobile property is a critical piece of understanding your customer’s journey. With Adobe Analytics you can understand the who, what, why, and where of every click in your application. Learn from Adobe Analytics experts their top tips for using Activity Map classifications and custom attribution to better understand user engagement.|

{style="table-layout:auto"} 

For past episodes, see [Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en).

### Community Q&A Coffee Breaks{#coffee}

Spend an hour with a special guest and submit your questions in Experience League Communities, where you can get questions answered from product experts at Adobe!

|Event Name|Date & Time|Application|Type|Description |
| -----------| ---------- | ---------- | ---------- |---------- |
|Adobe Target - Setup and Admin UI, A4T Integration, AEM Integration, General UI |December 8th (Wed.) @ 8 am PT |Adobe Target|Forum Q&A|We'll be joined by Robert Calangiu, aka @Robert_Calangiu,  Senior Product Manager for Adobe Target, in the Adobe Target Community to chat directly with you about your Adobe Target questions pertaining to his areas of expertise. <br>[Details](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-12-8-21-8am-pt-robert-calangiu/td-p/426697)|
|Adobe Campaign - Data Import via other Applications |December 2, 2021 @ 8 am PT |Adobe Campaign |Forum Q&A |Data Import via other applications - Best practices to import data via SFTP/APIs using technical workflows with Zariely Garcia, Senior Technical Consultant. <br>[Details](https://forms.office.com/Pages/ResponsePage.aspx?id=Wht7-jR7h0OUrtLBeN7O4UuYOxSr9BdGsLPtk3ITDIdUMFYwT0REQTk5RDZPTjlEWFlSUk1XWTBHVy4u&wdLOR=cEEEC3C73-227C-457C-AA83-44CC08D697B9).|

{style="table-layout:auto"} 

### Adobe Developer's Live{#dev-live}

|Event Name|Date & Time|Topic|Type|Description |
| -----------| ---------- | ---------- | ---------- |---------- |
|October 4 - 5, 2021|On demand |[Adobe Developers Live](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en)|Video |Missed the event or looking for a replay of a specific session? Find them on Experience League. Developers Live showcases the latest tech advances and developer tools powering design, content creation workflows, document services, and customer experience management across industries. View the keynote address, learn about Analytics APIs, client data layer, Adobe I/O open-source projects, and much more.| 

For more videos, visit the [Adobe Experience League Channel](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) on YouTube.

## ![Icon](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] & Administration {#ecloud}

| Feature | Description |
| ------- | ------- |
|Home Page |Experience Cloud home footer information has been moved to the user profile card, including Legal Notices and language selection in Preferences. |
|AEP Dashboards |[!DNL Helios Lite] provides chart recommendations within the Experience Platform widget creation workflow. Given a data selection (currently single variable data selection), [!DNL Helios] recommends an appropriate visualization to accompany that data selection.|
|AEP Dashboards |[!DNL Instory] provides ML-based written narration and captions for charts. It decorates charts in the AEP Dashboards page with relevant bullet points calling out major changes and incidents in the graphed data. |

{style="table-layout:auto"}

**More help resources on [!DNL Experience Cloud Central UI Components] & Administration**

* Administration help for [Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) and user management
* Help and release notes for [Places - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Help on [People - Customer Attributes and Audience Library](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icon](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

(Find the latest release information for [!DNL Adobe System Status] in the [May 21, 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=en) release notes.)

## ![Icon](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Includes release update information and new documentation for Experience Platform and [!UICONTROL Mobile SDK].

**September 29, 2021**

See [Experience Platform release notes](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html) for all the details.

### Experience Platform tutorials and courses {#tutorials-platform}

Latest videos, tutorials, or courses published for Experience Platform and services.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|November 2021|[ Data Collaboration in the First-party Data Context ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=en#)|Video |Delivering on the experience promise, with access to less data. Whether you’re an advertiser, publisher, or agency, this webinar helps unlock the opportunities for data collaboration in a future without third-party cookies.|
|October 2021|[[!DNL Platform] Administration](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin)|Course |Learn about administration activities for Experience Platform, including permission and sandbox management.|

{style="table-layout:auto"}

### Adobe Mobile SDK

See [Release notes and change logs](https://aep-sdks.gitbook.io/docs/release-notes) for the Adobe Experience Platform Mobile SDKs.

## ![Icon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Release date: **October 28, 2021**

* [New features in Adobe Analytics](#aa-features)
* [New features in Customer Journey Analytics](#cust-journey) 
* [Fixes in Adobe Analytics](#aa-fixes)
* [Important notices for Analytics administrators](#aa-notices)
* [Analytics courses and tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### New features in Adobe Analytics {#aa-features}

| Feature | Description | [General Availability](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Target Date |
| ----------- | ---------- | ------- |
| Minute-level date ranges in Analysis Workspace | You can apply a minute-level date range under the advanced settings of your panel calendar or when building a custom date range. If you are reporting on a date range that spans many days, start time applies to the first day and end time applies to the last day in your range. | October 18, 2021 |
| [!UICONTROL Media Playback Time Spent] | Adobe Streaming Media Playback [!UICONTROL Time Spent] provides valuable insight into viewer engagement and enables media organizations to derive deeper, more granular insights with minute-by-minute user engagement through advanced time spent analysis with day-parting capabilities. You can observe the amount of time spent viewing your media streams at a specific point in time. You can split the playback duration by different granularities, including new 5 minute, 15 minute, and 30-minute granularities. [Learn more](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | October 18, 2021 |
| Quick [!UICONTROL Segment Builder] | Allows business users to quickly apply basic segments in a simplified, in-line project workflow. No need to go to the [!UICONTROL Segment Builder]. [Learn more](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | October 21, 2021 |
| Analysis Workspace Left Rail Search Improvements | Left rail search 1) prioritizes exact matches above broad matches, in addition to continuing to account for component recency and relevancy. 2) It highlights matched characters to make search results more understandable. 3) It's easier to find classifications related to a dimension. 4) Finally, it supports wildcard (`*`) searching to more easily find specific components that you need. Note: Wildcard searching does not yet work at the dimension item level. | October 21, 2021 |
| Dark Theme | [Dark theme](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/user-preferences.html?lang=en#dark-theme) is available as a display option. | October 21, 2021 |

{style="table-layout:auto"}

### New features in Customer Journey Analytics {#cust-journey}

| Feature | Description | [General Availability](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html) - Target Date |
| ----------- | ---------- | ----- |
| Minute-level date ranges in Analysis Workspace | You can apply a minute-level date range under the advanced settings of your panel calendar or when building a custom date range. If you are reporting on a date range that spans many days, start time applies to the first day and end time applies to the last day in your range. | October 18, 2021 |
| Quick [!UICONTROL Filter Builder] | Allows business users to quickly apply basic segments in a simplified, in-line project workflow. No need to go to the [!UICONTROL Filter Builder]. [Learn more](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html) | October 21, 2021 |
| Analysis Workspace Left Rail Search Improvements | Left rail search 1) prioritizes exact matches above broad matches, in addition to continuing to account for component recency and relevancy. 2) It highlights matched characters to make search results more understandable. 3) It's easier to find classifications related to a dimension. 4) Finally, it supports wildcard (`*`) searching to more easily find specific components that you need. Note: Wildcard searching does not yet work at the dimension item level. | October 21, 2021 |
| Dark Theme | [Dark theme](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/user-preferences.html?lang=en#dark-theme) is available as a display option. | October 21, 2021 |
| Lookback window for dimension allocation | A look-back window of up to 90 days is added to the dimension allocation setting under Persistence in the Data Views configuration. [Learn more](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html)| October 28, 2021 |

{style="table-layout:auto"}

### Fixes in Adobe Analytics {#aa-fixes}

* Fixed an issue with being unable to delete alerts in the Alert Manager. (AN-270656)
* Fixed an issue with Data Warehouse requests failing intermittently. (AN-273713, AN-272790)
* Fixed issues with Classifications not updating. (AN-272211)

### Fixes in Customer Journey Analytics {#cja-fixes}

* Fixed CJA performance issues (error messages while loading projects). (AN-269451, AN-270649)
* Fixed an issue in CJA where Session Starts did not match Flow Entries for Page Names. (AN-273501)
* Fixed an issue with the Fallout report in CJA not functioning properly. (AN-269761)

#### Additional fixes in Adobe Analytics

AN-263327; AN-267807; AN-269757; AN-272789; AN-272888; AN-273155; AN-273320; AN-273369; AN-273405; AN-273469; AN-273581; AN-273642; AN-273688; AN-273988; AN-274007; AN-274030; AN-274156; AN-274188; AN-274226

#### Additional fixes in CJA

AN-270649

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| ----------- | ---------- | ---------- |
| EOL for three Analytics API services | September 16, 2021| On **October 20, 2021**, the following Analytics Legacy API services will reach their end-of-life date and be shut down. Any current integrations built using these services stop working on that day.<ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>Adobe has provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe I/O](https://developer.adobe.com/console) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs. |
| EOL for Full Processing in Data Sources | October 18, 2021 | On **January 31, 2022**, Adobe will end of life Full Processing, which enables users to ingest offline hit data into Analytics. This capability is available via [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). [Learn more](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=en) |

{style="table-layout:auto"}

### AppMeasurement {#appm}

For the latest updates on AppMeasurement releases (Version 2.22.2), please refer to [AppMeasurement for JavaScript release notes](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en).

### Analytics courses and tutorials {#tutorials-analytics}

Latest courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|November 2021|[Segment containers in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=en)|Video (updated) |In this video, learn how to use the containers and hear some examples of each type of container.|
|November 2021|[Sequential Segmentation in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=en#)|Video (updated) |Learn how to build a segment in Analysis Workspace from sequences of behaviors on your site or in your application.|
|November 2021|[Before/After Sequences in Sequential Segmentation](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=en)|Video (updated)|Learn how to segment in Adobe Analytics so that you get only the data from before or after a specific user path.|
|November 2021|[Report Builder for Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html)|Video |With Report Builder's simple and flexible drag and drop UI, you can create complex data queries and custom reports from Customer Journey Analytics data, all within Excel.|
|October 2021|[Using Visualizations to Tell your Data Stories](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations)|Course |Learn the basics about visualizations, including how to add them to a project, get data into them, and what each visualization can show you. Learn how to configure the settings to get the exact data you need. Also, get some tips and use cases to help you make visualizations practical to your regular analysis.|

{style="table-layout:auto"}

### Analytics help resources

* [Adobe Analytics Product Documentation and Tutorials](https://experienceleague.adobe.com/docs/analytics.html)

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Fixes and improvements in Audience Manager.

* Resolved an issue causing all API calls to return an `Undocumented` error when being performed through the Swagger interface. (AAM-59190)
* Resolved an issue causing incorrect user roles to be assigned to partners in some situations. (AAM-59451)
* Resolved an issue causing the API to require case-sensitive authentication headers. (AAM-58528)

## ![Icon](/assets/aem.png) Experience Manager {#aem}

Adobe recommends visiting the [Experience Manager release updates and roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) page to stay current on release information.

### Release Overview Videos

* [October 2021 Release Overview](https://video.tv.adobe.com/v/338253) video of new features.
* [September 2021 Release Overview](https://video.tv.adobe.com/v/337381) video of new features.

### Community

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 4-5 October 2021, 7:00 PDT

    Adobe Developers Live brings together Adobe developers and experience builders with diverse backgrounds and a singular purpose – to create incredible end-to-end experiences. This two-day conference features important developer updates, technical sessions, and community networking opportunities.

    Adobe product teams across Experience Cloud, Document Cloud, and Creative Cloud showcase the latest technological advances and developer tools powering design, content creation workflows, document services, and customer experience management across industries.

    Adobe has 20 Experience Manager sessions planned. Spread the word!

  * [Complete session list](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
  * [Free registration &ndash; Log in to RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
  * [Adobe Developers Live Community](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127)

### New Experience Manager courses and tutorials {#tutorials-aem}

New videos, tutorials, and courses published over the past month.

|Published|Name|Description |Type|Version |
| -----------| ---------- | ---------- |---------- | ---------- |
|November 2021|[Adobe Experience Manager Sites Basics](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=en)|Video series |Learn how to create rich and engaging customer experiences in Adobe Experience Manager in this five-part webinar series. Start with the building blocks of content authoring while learning the fundamental concepts and operations. Learn about sites admin features and basics of handling digital assets within AEM. Later, discover features that can help you save time and be more efficient by reusing the content and delivering it across channels.|AEM Sites |
|November 2021|[Planning your Move to AEM as a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration)|Course |Learn about the considerations of moving to AEM as a Cloud Service and the available tools that simplify the process.|AEM CS |
|November 2021|[Moving to AEM as a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration)|Course |Learn how to successfully move from AEM 6 to Experience Manager as a Cloud Service.|AEM CS |
|November 2021|[Download Interactive DoR](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=en#create-custom-servlet)|Video |Learn how to download an interactive DoR with the Adaptive Form data.|AEM Forms |
|November 2021|[Adobe Experience Manager as a Cloud Service Experts Series](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=en)|Video series |Learn about Adobe Experience Manager (AEM) as a Cloud Service from Adobe’s expert engineers who build it, and Professional Services team who delivers it. Join Adobe’s experts in exploring what AEM as a Cloud Service is, how it compares with AEM 6, and how to move from AEM 6 to AEM as a Cloud Service.|AEM CS |
|November 2021|[Service Users](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=en)|Video |Learn how to create and use Service Users in your AEM code to provide controlled, programmatic access to the AEM repository.|AEM CS |

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

## ![Icon](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

See the following links for Adobe Commerce release notes:

* [Adobe Commerce and Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### New Adobe Commerce tutorials {#commerce-tutorials}

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|November 2021|[Adobe Commerce Videos and Tutorials](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=en)|Tutorial home |These tutorial resources include video series that provide a high-level view of topics, and individual videos that target specific tasks and processes. The collection is designed to provide helpful content for backend developers, frontend developers, system administrators, merchants, and other roles within your organization.|

## ![Icon](/assets/target.png) [!DNL Target] {#target}

Last Updated: **October 20, 2021**

See [[!DNL Target] release notes](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en) for the latest release information.

## ![Icon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Latest Campaign product releases

Find out more about the latest capabilities, improvements, and fixes released:

* [Campaign v8 Release Notes](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html)
* [Campaign Classic v7 Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)
* [Campaign Standard Release Notes](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) 

### New [!UICONTROL Campaign] courses and tutorials {#tutorials-campaign}

Latest tutorials and courses for Adobe Campaign.

|Published|Name|Description |Type|Version |
| -----------| ---------- | ---------- |---------- | ---------- |
|November 2021|[Connect Campaign to Experience Platform as a destination](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=en)|Video |Learn how to activate an Adobe Experience Platform segment to a destination using the Amazon S3 connection type.|AEP & Campaign V8|
|November 2021|[Integrate with Experience Platform - Overview](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=en)|Video |Learn how share data between Campaign and Experience Cloud.|AEP & Campaign V8|
|November 2021|[Import recipient data from Experience Platform and send an email](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=en)|Video |Learn how to configure an external account in Adobe Campaign to import recipient data from Adobe Experience Platform to Campaign. Understand how to create a workflow to upload and target the recipients received from the Experience Platform.|AEP & Campaign V8|
|November 2021|[Use SOAP APIs in workflows](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en)|Video tutorials |Learn how to use Adobe Campaign Soap API’s and create an advanced delivery workflow based on the data received via the API.|Campaign V8|

{style="table-layout:auto"}

### Campaign help resources

* Adobe Campaign v8: [Documentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html) - [Implementation Guides](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard Documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [Release Planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7 Documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign Control Panel: [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html) - [Release Notes](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - How-to-videos for [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html)

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

With Adobe Journey Optimizer, you can manage scheduled omnichannel campaigns and one-to-one moments for millions of customers from a single application — and the entire journey is optimized with intelligent decisioning and insights.

### Latest Journey Optimizer product releases

Find out more about the latest capabilities, improvements, and fixes in the [Journey Optimizer Release Notes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

### Journey Optimizer tutorials and courses {#tutorials-ajo}

Latest Journey Optimizer tutorials:

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|October 2021|[Configure and Manage Data in [!DNL Journey Optimizer] for Data Engineers](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2)|Course |Learn how to configure and manage data required for journey management in Journey Optimizer.|
|October 2021|[Get started with [!DNL Journey Optimizer] for Journey Administrators and Managers](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1)|Course |Learn everything you must know to create your first journey.|
|October 2021|[Configure [!DNL Journey Optimizer] for Journey Administrators](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1)|Course |Understand the [!DNL Journey Optimizer] architecture and points of integration. Learn how to configure [!DNL Journey Optimizer].|

{style="table-layout:auto"}

### More resources for [!DNL Journey Optimizer]

* [Journey Optimizer documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [Release rotes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)
* [Decision Management documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html) - [Release notes](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Icon](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Use Experience Platform to orchestrate a customer’s journey at scale across experience channels, by intelligently anticipating every individual’s needs in real time.

### Latest [!DNL Journey Orchestration] product releases

Find out more about the latest capabilities, improvements, and fixes in the [[!DNL Journey Orchestration] release notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html).

#### More resources for [!DNL Journey Orchestration]

* [Journey Orchestration documentation](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html) - [Release notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [How-to videos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html) - [Latest documentation updates](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![Icon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is a complete application for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo Engage] [release schedule](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) for the latest release schedule information and release notes.

## ![Icon](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] is a unified work management application for sharing ideas, creating content, managing complex processes, and doing their best work.

See the [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) page for a round-up of the latest information for all products.

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Release notes for [!DNL Adobe Advertising Cloud].

* [New features across [!DNL Advertising Cloud]](#adcloud-all)
* [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [New features in [!DNL Advertising Cloud Search]](#adcloud-search)

### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you'll need to make some changes to enable ID stitching. See "[Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html)." |

{style="table-layout:auto"}

### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a new report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher won't approve all of the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP "[!DNL Tremor]" ([!DNL Telaria]) is now "[!DNL Magnite CTV]."</li><li>In the coming weeks, [!DNL Rubicon]" will change to "[!DNL Magnite DV+]," where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatic guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatic guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |

{style="table-layout:auto"}

### New features in [!DNL Advertising Cloud Search] {#adcloud-search}

Last updated: **October 7, 2021**

| Feature | Description |
| ------- | ----------- |
| [!UICONTROL Reports], [!UICONTROL Notification Center] | (October 9 release) All email notifications for reports, which Advertising Cloud Search sends when a custom or scheduled report has completed or failed, are now handled by [!UICONTROL Notification Center]. Email notifications and web notifications are enabled by default for reports, but you can optionally change the notification settings. With this change:<ul><li>Email recipients are restricted to users who are registered, authenticated users of Advertising Cloud Search and have access to the advertiser account. This feature ensures that no confidential data is sent to unauthorized users.</li><li>The format and contents of the email uses the [!UICONTROL Notification Center] template, which includes more details of the report and includes direct download links for all report formats.</li><li>Report notifications are a new notification type, with its own notification preferences, in [!UICONTROL Notification Center].</li></ul>If you use any automation to pull reports from email notifications, you may need to update the filtering logic to ensure process continuity. |
| Advertising Insights | Additional insights are available in beta mode. |

{style="table-layout:auto"}

## ![Icon](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

New videos, tutorials, or courses published for Adobe Document Cloud.

### Document Cloud courses and tutorials {#tutorials-doc-cloud}

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|November 2021|[Workspace basics](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html)|Video (updated) |Learn how the Acrobat DC interface makes it easy to access files and tools across desktop, web, and mobile devices with a consistent workspace experience.|
|November 2021|[Work anywhere with Acrobat web](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html)|Video |Learn how to handle business document requests from anywhere using the Acrobat web tools in your browser.|
|November 2021|[Create PDFs in Office for the web ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html)|Video |Learn how to create PDF files without ever leaving your Microsoft® Office for web apps. This add-on requires a subscription to Acrobat DC for teams or Acrobat DC for enterprise subscription.|
|November 2021|[Collaborate in real time](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html)|Video |Move your projects forward by collecting comments, collaborating on responses, and tracking progress on your documents all in real time, from anywhere.|
|November 2021|[ Productivity on the go](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html)|Video |Do more right from your tablet or mobile phone with the Acrobat Reader mobile app.|

{style="table-layout:auto"}

For Document Cloud help, see:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud Learn & Support](https://helpx.adobe.com/support/document-cloud.html)

## ![Icon](/assets/creative-cloud-24.png) Creative Cloud for enterprise {#creative-cloud}

See [Creative Cloud for enterprise tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.
