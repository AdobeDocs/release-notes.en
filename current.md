---
title: Latest Release Notes
description: Learn about the latest release notes, new features, and new documentation for Experience Cloud products and services. Find new help and tutorials about Experience Cloud, Creative Cloud for Enterprise, and Document Cloud.
doc-type: release notes
last-update: March 2021
author: mfrei
---

# Adobe Experience Cloud Release Notes - March 2021 

![Banner](/assets/experience-cloud-banner-3.png)

Experience Cloud solutions and services are updated monthly. This page is your central location for finding the latest release updates, documentation, and tutorials for [!DNL Experience Cloud] and Experience Platform. You can also find new documentation for [!DNL Creative Cloud for Enterprise] and [!DNL Document Cloud].

>[!IMPORTANT]
>
>This page contains prerelease content and is subject to change prior to release dates.

>[!NOTE]
>
>Subscribe to the monthly [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to receive email notifications about updates to this page. This page is maintained throughout the month, so please check back regularly for updates to Adobe enterprise product and Experience League documentation.

Latest update: **March 19, 2021**

* [Adobe System Status](#status) (not updated)
* [Experience Cloud UI Components, Services, and Administration](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) and [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)
  
Need help? Visit [Adobe Experience League](https://experienceleague.adobe.com/#home) to find product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/adobe.png) Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

The most recent updates to Adobe System Status are found at [Adobe System Status - May 21, 2020](https://docs.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status) for the latest release information.

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud UI Components, Services, and Administration {#ecloud}

Not updated.

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Includes release update information for Experience Platform and Experience Platform Launch.

* [Experience Platform release notes](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). (February 24, 2021)
* [Experience Platform Launch release notes](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html). (January 13, 2021)

### Experience Platform tutorials and courses

New videos, tutorials, or courses published for Experience Platform and services.

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use Adobe Experience Platform to orchestrate a customer's journey at scale across experience channels, by intelligently anticipating every individual’s needs in real time.

### Latest product releases

February 2021 Release - Find out more about the latest capabilities, improvements, and fixes in the [Journey Orchestration Release Notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html).

### New Journey Orchestration courses and tutorials

New videos, tutorials, and courses published over the past month.

Published|Name|Type|Description  |
| -----------| ---------- | ---------- | ---------- |
|March 16, 2021|[Update profile action](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey)|Video |Learn how to update an existing Adobe Experience Platform profile with information coming from an event, a datasource, or using a specific value. |

### More resources for Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icon](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] is an Application Service integrated with Adobe Experience Platform. Use [!UICONTROL Offer Decisioning] to deliver the best offer and experience to your customers across all touch points at the right time.

### Latest product releases

February 2021 Release - Find out more about the latest capabilities in the [Offer Decisioning Release Notes](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new).

### More resources for Offer Decisioning

[Documentation](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en) - [How-to videos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Icon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Release date: **March 25, 2021**

* [New features in Adobe Analytics](#aa-features)
* [New features in Customer Journey Analytics](#cust-journey)
* [Fixes in Adobe Analytics](#aa-fixes)
* [Important notices for Analytics administrators](#aa-notices)
* [Analytics courses and tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### New features in Adobe Analytics {#aa-features}

| Feature | [General Availability](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Target Date | Description |
| ----------- | ---------- | ------- |
| Data Repair API updates | March 25, 2021 | The Data Repair API now supports standard variables including [!UICONTROL Page] and [!UICONTROL IP address], mobile and video variables, as well as custom props and eVars.  Values within variables can be deleted or new values can be set. The API now also offers filtering for URLs, query strings, at signs, and more. |
| Analysis Workspace: [!UICONTROL Components] > [!UICONTROL User preferences] | March 25, 2021 | The [!UICONTROL Components] > [!UICONTROL User preferences] page enables you to manage [!UICONTROL Analysis Workspace] settings and its related components for your user. [!UICONTROL User preferences] applies to all new projects and panels. **Note:** the following settings have moved to the [!UICONTROL User preferences] page:<ul><li>Report Settings: Thousands separator (now called "Number format")</li><li>Report Settings: CSV separator</li><li>Workspace projects: Help > Enable tips</li><li>Workspace projects: Blank panel "Start new projects with this panel" option</li></ul> |
| Analysis Workspace: [!UICONTROL Histogram] Smart Bucket Prediction | March 25, 2021 | [!UICONTROL Histogram] Smart Bucket Prediction helps with high-cardinality-metrics histograms by automatically identifying the right width and number of buckets for your data spread. For low-cardinality metrics, the visualization behaves the same as it did previously. |
| [!UICONTROL Usage Log] API | March 25, 2021 | This is a new v2.0 Analytics API that enables programmatic access to the same usage log data available under [!UICONTROL Admin] > [!UICONTROL Log] > [!UICONTROL Usage and Access Log]. Additional details around authentication, schema, and sample response are available [here](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md).

### New features in Customer Journey Analytics {#cust-journey}

| Feature | [General Availability](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Target Date | Description |
| ----------- | ---------- | ----- |
| Support for [!UICONTROL Adobe Analytics dashboards] | March 25, 2021 | [!UICONTROL Customer Journey Analytics] (CJA) now supports the [!UICONTROL Adobe Analytics dashboards Scorecard Builder] and the Mobile App. This allows executives and business users to see their cross-channel KPIs based on CJA data, using the same app they may already be using for Adobe Analytics. |
| Analysis Workspace: [!UICONTROL Components] > [!UICONTROL User preferences] | March 25, 2021 | The [!UICONTROL Components] > [!UICONTROL User preferences] page enables you to manage [!UICONTROL Analysis Workspace] settings and its related components for your user. [!UICONTROL User preferences] applies to all new projects and panels. **Note:** the following settings have moved to the [!UICONTROL User preferences] page:<ul><li>Workspace projects: Help > Enable tips</li><li>Workspace projects: Blank panel "Start new projects with this panel" option</li></ul> |
| Analysis Workspace: [!UICONTROL Histogram] Smart Bucket Prediction | March 25, 2021 | [!UICONTROL Histogram] Smart Bucket Prediction helps with high-cardinality-metrics histograms by automatically identifying the right width and number of buckets for your data spread. For low-cardinality metrics, the visualization behaves the same as it did previously. |

### Fixes in Adobe Analytics {#aa-fixes}

* Fixed an issue where, after editing and saving a segment’s new owner, this new owner was not reflected in the Segment UI. (AN-234502; AN-250970; AN-250286)
* Fixed an issue that caused an App report suite to consume both primary server calls and mobile primary server calls. (AN-244029)
* Fixed an issue with slow UI response time when opening [!UICONTROL Workspace] projects. (AN-242553)
* Fixed an issue with being unable to log in to [!UICONTROL Report Builder] after upgrade to the latest version. (AN-248825)
* Fixed and issue with user permissions for non-admin users: A user should have a permission as long as it’s added to at least one of their profiles in [!UICONTROL Admin Console]. Adding users to profiles should only add to the permissions they have and should not remove anything they are already entitled to via other product profiles. (AN-242723)
* Fixed a language encoding issue with [!UICONTROL Data Feeds]. (AN-249862)
* Fixed an issue with users being unable to access shared [!UICONTROL Workspace] projects. (AN-247814)
* Fixed an issue with [!UICONTROL Alert Previews] not matching the number of triggered [!UICONTROL Alerts]. (AN-249392; AN-250804)

#### Additional Adobe Analytics fixes

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| ----------- | ---------- | ---------- |
| [!UICONTROL Same-as-SiteCatalyst VISTA Processing] = ON | March 17, 2021 | On June 17, 2021, all report suites will be updated to have [!UICONTROL Same-as-SiteCatalyst VISTA Processing] set to ON.  This change will impact [!UICONTROL Data Warehouse] reporting by processing the data to match processing rules.  For questions or clarification, reach out to Adobe Customer Care. |
| EOL of [!UICONTROL Full Processing] [!UICONTROL Data Sources] | March 10, 2021 | Adobe plans to deprecate [!UICONTROL Full Processing] [!UICONTROL Data Sources] in the future. As of March 25, 2021, new imports of this type can no longer be created. Please use [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) to import this type of data. |
| Reports & Analytics landing page options | February 19, 2021 | On March 25, 2021, options to set new Reports & Analytics dashboards or other content as your Adobe Analytics landing page will be removed. If you previously set a Reports & Analytics page as your custom landing page, it will continue to work until your landing page is modified in [!UICONTROL User Preferences]. |
| EOL of Ad Hoc Analysis | Jan. 2021 | [!UICONTROL Ad Hoc Analysis] reached its end-of-life date on March 1, 2021. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| End-of-life for three Analytics API services | January 6, 2021 | On April 30, 2021, the following Analytics Legacy API services are slated to reach their end-of-life date and will be shut down. Any current integrations built using these services will stop working on that day.<ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs. |
| EOL of Adobe Data Connectors | July 13, 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. A new standard is available in the [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud). You can use that standard for any integration to continue to be offered and supported. The official end-of-life date is August 1, 2021. [Learn more...](https://docs.adobe.com/content/help/en/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

For the latest updates on AppMeasurement releases, please refer to [AppMeasurement for JavaScript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html).

### Analytics courses and tutorials {#tutorials-analytics}

New courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

### Analytics help resources

* [Adobe Analytics Product Documentation and Tutorials](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![Icon](/assets/audience-manager.png) Adobe Audience Manager {#aam}

AAM new features.

### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the [Onboarding Status Report](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html). In this issue, there was a discrepancy between the records in the report and the ones in the file uploaded by an onboarding partner. (AAM-57415)
* Fixed an issue causing incorrect duplicate segment mapping validation for **[!UICONTROL People-Based Destinations]**. (AAM-56631)
* Fixed an issue which blocked some users from accessing **[!UICONTROL Audience Reports]**. (AAM-57412)
* Patched a [!DNL Remote Code Execution] vulnerability which could be used by attackers to access sensitive data. (AAM-57495)

### Audience Manager courses and tutorials {#tutorials-aam}

New videos, tutorials, or courses published for Audience Manager.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|March 21, 2021|[Understanding Schemas and XDM in Real-time CDP for Audience Manager Users](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) |Video |As you move from Audience Manager to Real-time Customer Data Platform (Real-time CDP), you will encounter a few new concepts and practices. Schemas and XDM fall into that category. This video explains these concepts. |
|March 17, 2021|[Understanding Signals in Real-time CDP for Audience Manager Users](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) |Video |This video is meant for Audience Manager users who are moving to Real-time Customer Data Platform (Real-time CDP), and discusses how signals (key-value pairs) that you use in Audience Manager to build traits are used in Platform. |
|March 12, 2021|[Understanding Schemas and XDM in Real-time CDP for Audience Manager Users](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) |Video |As you move from Audience Manager to Real-time Customer Data Platform (Real-time CDP), you will encounter a few new concepts and practices. Schemas and XDM fall into that category. This video explains these concepts. |
|March 12, 2021|[Content Delivery on Experience Manager Cloud Service](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) |Event |Adobe Experience Manager as a Cloud Service has a powerful preconfigured content delivery architecture. Demonstrate how to make the best of optimized content delivery configurations |
|March 3, 2021|[Understanding Segments in Real-time CDP for Audience Manager Users](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) |Video |As you move from Audience Manager to Real-time Customer Data Platform, it is helpful to understand the differences in concepts. This video looks at the differences in segments and segment creation between Audience Manager and Real-time CDP. |
|March 3, 2021|[Understanding Traits in Real-time CDP for Audience Manager Users](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) |Video |As you move from Audience Manager to Real-time Customer Data Platform, it is helpful to understand the differences in concepts. This video addresses traits in Audience Manager and what the equivalent is in Real-time CDP. |
|March 3, 2021|[Course Introduction - Audience Manager Advanced Skills](https://video.tv.adobe.com/v/331788/?quality=12&learn=on) |Video |View this video to see what awaits you in the Audience Manager Advanced Skills course. |
|March 3, 2021|[Understanding 1st Party Data Ingestion in Real-time CDP for Audience Manager Users](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) |Video |This video discusses 1st-party offline data ingestion into Real-time Customer Data Platform (Real-time CDP) for those who have been using Adobe Audience Manager. We look at some of the main differences between the two products regarding data ingestion and shows how the Audience Manager Data Connector can be used as a stop gap until processes have been moved over to Real-time CDP. |
|March 1, 2021|[Commercialize your Owned Audiences by Offering on Audience Marketplace](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) |Video |In this video you will learn how to set up your data as a private or public data feed on the Audience Marketplace, making you a data provider of 2nd or 3rd party data. |
|March, 2021|[Creating and Managing Data Activation in Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.4) |Course |In this course, learn all about "activating" your audiences, I.e. sending audience data to destination partners in order to customize the experience for your end users. You'll learn the basics of destinations, how to choose the right destination for your needs, and also how to prepare and send audience data to social network destinations based on people, not cookies. |
|March, 2021|[Audience Manager Advanced Skills](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.5) |Course |Once you have mastered the basics of Audience Manager, take this course to learn about taking your Audience Management to the next level. Learn how to use AI with algorithmic models, how to use Profile Merge Rules to understand your customers as people instead of devices, and other great topics to extend the use of the DMP. |

## ![Icon](/assets/aem.png) Adobe Experience Manager {#aem}

New features, fixes, and updates in Experience Manager. Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

>[!NOTE]
>
>Adobe recommends visiting the [Experience Manager release updates and roadmap](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) page to stay current on release information.

### Product releases

* **AEM 6.5.8.0**
    AEM 6.5, Service Pack 8 (6.5.8.0 released March 11, 2021) is an important update that includes new features, key customer enhancements, improved performance, stability, and security, released since the general availability of AEM 6.5, April 2019.
  * [Release notes](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
  * [AEM Forms release deliverables](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

  * **AEM 6.4.8.4**
    AEM 6.4, Service Pack 8, Cumulative Fix Pack 4 (6.4.8.4 released February 25, 2021) is an important update that includes several internal and customer fixes since the general availability of AEM 6.4, Service Pack 8 (6.4.8.0), March 2020.
  * [Release notes](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
  * [AEM Forms release deliverables](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

    What is new on Experience Manager as a Cloud Service?

  * **Experience Manager Sites as Cloud Service**

    * [The RemotePage Component](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en): Added support for viewing and editing external SPAs within Experience Manager using.
    * [Editing an External SPA within Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en): Added ability to upload a standalone single-page application to an Experience Manager instance, add editable sections of content, and enable authoring.

  * **Experience Manager Assets as a Cloud Service**

    * Experience Manager Assets as a Cloud Service is entitled to have a pre-configured Brand Portal instance. The Cloud Manager user can activate Brand Portal on Experience Manager Assets as a Cloud Service. See [Activate Brand Portal using Brand Portal](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html).
    * Businesses can now source assets using Brand Portal. Asset sourcing feature uses Brand Portal to help customers engage with agency users to source assets for new marketing campaigns, photoshoots, and projects. See [Asset Sourcing overview](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en) in the Brand Portal Guide.
    * The Brand Portal usage report now displays only the active users. The inactive users are not displayed now. Active users are the ones whose account is assigned to a product profile in the Admin Console. See [Work with reports](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en) in the Brand Portal Guide.
    * In Brand Portal, a new download setting is introduced, that lets you create separate folder for each asset when downloading folders, collection, and so on. See [Asset Download](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en) in **Download assets from Brand Portal** in the Brand Portal Guide.

  * **Experience Manager Commerce as a Cloud Service**

    * Product Experience Management: Enrich product catalog pages individually with Experience Fragments.
    * Extended product console properties to show linked Assets and Experience Fragments, including action to quickly navigate to the associated content.
    * Released CIF Venia Reference Site - 2021.02.24 that includes the latest CIF Core Components version 1.8.0. See [CIF Venia Reference Site 2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24) for more details.
    * Released CIF Core Components version 1.8.0. See [CIF Core Components 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0) for more details.

  * **Cloud Manager**

    * Customers with environments that have pre-existing Custom Domain Name configurations for [IP Allow Lists](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn), [SSL Certificates](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn), and [Custom Domain Names](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn) now see a message about their previously existing configurations. They can also self-serve by way of the user interface.
    * Users with requisite permissions can now edit a Program, allowing them to do the following in a self-service manner:
      * Add Sites solution to an existing program with Assets or conversely.
      * Remove Sites or Assets from an existing program with both Sites and Assets.
      * Add second, unused solution entitlement either to an existing program, or as a new program.
    * **AEM Push Update** label is now displayed for both *Pipeline Execution* and *Activity* screens.
    * If an environment is hibernated, but there is also an Experience Manager update available, the **Hibernated** status takes precedence over **Update available**.
    * Users can now see their Cloud Manager roles by selecting **View Cloud Manager Roles** after navigating to the User Profile icon (top right) of Unified Shell.
    * The label **Application for Approval** has been relabeled to **Production Approval** for greater clarity.
    * The **Version** label has been relabeled to **Git Tag** in the Production pipeline execution screen.
    * The labels which define the behavior when important metrics do not meet the defined threshold have been relabeled to reflect their true behavior: **Cancel Immediately** and **Approve Immediately**.
    * The class and method deprecation lists have been updated based on version `2021.3.4997.20210303T022849Z-210225` of the Experience Manager Cloud Service SDK.
    * Cloud Manager Production pipeline now includes [Custom UI Testing](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing) capability.

### **Community**

* **Adobe Developers Live 2021 | Complete Session list**

    [Here](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) is an aggregated list of all the Experience Manager sessions occurring at **Adobe Developers Live**.

* **Adobe Summit 2021 | Complete Experience Manager Session list**

    [Here](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) is an aggregated list of all the Experience Manager sessions occurring at **Adobe Summit 2021**.

### Experience Manager release information

All Experience Manager release notes are maintained at the following pages:

* [Experience Manager release updates and roadmap](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager as a Cloud Service release information](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
* [Experience Manager Cloud Manager release notes](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Automated Forms Conversion Service release notes](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager 6.5 Service Pack release notes](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 Cumulative Fix Pack release notes](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience ManagerAssets Dynamic Media release notes](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Experience Manager Brand Portal release notes](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Experience Manager desktop app release notes](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)
* [Experience Manager Dispatcher release notes](https://docs.adobe.com/content/help/en/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre release notes](https://docs.adobe.com/content/help/en/livefyre/using/release-notes/c-rn.html)

### Experience Manager courses and tutorials

New videos, tutorials, and courses published over the past month.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February, 2021|[Production deployment with an AEM Publish environment](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) |Tutorial |In this tutorial, you will set up a local environment to simulate content being distributed from an Author instance to a Publish instance. You will also generate production build of a React App configured to consume content from the AEM Publish environment using the GraphQL APIs. Along the way, you will learn how to effectively use environment variables and how to update the AEM CORS configurations. |
|February, 2021|[Headless content management using GraphQL APIs](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) |Course |In this course, you will explore how AEM’s GraphQL APIs and headless capabilities can be used to power experiences surfaced in an external app. |
|February, 2021|[Launches - Feature Video](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) |Video |Launches in AEM Sites provide a way to create, author, and review web site content for future release. During the creation of the launch the production web site can continue to evolve and change day to day as it normally would. |
|February, 2021|[LinRelate and Unrelate Assets - Feature Videoktext](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) |Video |Learn how to establish and manage relationships between assets in AEM. |
|February, 2021|[Authenticating to AEM as a Cloud Service from an external application](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) |Course |In this course, you will learn how an external application can use Local Development Access Tokens and Service Credentials to programmatically authenticate to AEM as a Cloud Service over HTTP. |
|February, 2021|[Fill and Sign multiple forms in a mortgage application](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms) |Course |Sign a package of documents seamlessly using the AEM Forms and Sign integration. The data entered in form can be used to pre-populate subsequent forms in the package. |
|February, 2021|[Versionsing / Timewarp in AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) |Video |Timewarp is a feature of Adobe Experience Manager Sites that provides authors with a quick way to review the state of a page at specific time in the past. |
|February, 2021|[Foundation - Workflow Management](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) |Video |This video uses Workflow Models to demonstrate this set of capabilities, however they are also applicable to AEM Launchers. |
|February, 2021|[Experience Fragment Blocks](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) |Video |Building blocks are a subfeature of Experience Fragments. Building blocks enable content authors to reuse components across different variations of Experience Fragments.|
|February, 2021|[Workflow Editor](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) |Video |Workflow enables business process management in Experience Manager, and is used for automatic processing of content and well as facilitating governance and process requiring human decision making.  |
|February, 2021|[Closed User Groups in AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) |Video |Closed User Groups (CUGs) is a feature used to restrict access to content to a select group of users on a published site. This video shows how Closed User Groups can be used with Adobe Experience Manager Assets to restrict access to a specific folder of assets. |
|February, 2021|[Reports](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) |Video |AEM Assets provides an enterprise level reporting framework that scales for large repositories through an intuitive user experience. |
|February, 2021|[Smart Tags for images with AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) |Video |Smart tags for images augment AEM's search capabilities by automatically and intelligently adding metadata tags to image assets based on the contents of the image. |
|February 24, 2021|[Metadata Cascading, Visibility](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) |Video |Advanced metadata management allows users to create cascading field rules to form contextual relationships between metadata in AEM Assets. The video below demonstrates new dynamic rules for field requirement, visibility, and contextual choices. The video also details the steps needed for an administrator to apply these rules to a custom metadata schema. |
|February 24, 2021|[Project Masters](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) |Video |Deleting a master project results in unusable derived projects. |
|February 24, 2021|[Customizing Page Properties](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) |Video |Create a Technical Video on how to best extend and customize Page Properties. |
|February 24, 2021|[Translating Content Fragments](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) |Video |Learn how Content Fragments can be localized and translated with Adobe Experience Manager. Mixed-media assets associated with a Content Fragment are also eligible to be extracted and translated. |
|February 24, 2021|[Experience Fragments](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) |Video |Experience Fragments enables content authors to reuse content across channels including Sites pages and third-party systems. |
|February 24, 2021|[Enhanced Search Search Boost](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html) |Video |Learn about Search Boost. |

### Other Help resources for Experience Manager

* [Experience Manager as a Cloud Service guides](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Experience Manager 6.4 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Experience Manager 6.3 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Experience Manager 6.2 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of Experience Manager Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help Home](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)

## ![Icon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Latest product releases

Find out more about the latest capabilities, improvements, and fixes released:

* [Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)

### New Campaign courses and tutorials

New videos, tutorials, and courses published over the past month.

|Published|Name|Solution|Description |
| -----------| ---------- | ---------- | ---------- |
|February 23, 2021|[Deliverability - Metrics for deliverability](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) |Campaign Classic/Standard |Learn about key deliverability metrics to monitor and how to use them to identify a reputation issue. |
|February 23, 2021|[Deliverability - Bounces](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) |Campaign Classic/Standard |Learn about the different types of bounces. |
|February 23, 2021|[Deliverability - Complaints](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) |Campaign Classic/Standard |Learn about complaints which are registered when a user indicates that an email is unwanted or unexpected. |
|February 23, 2021|[Deliverability - Spam Traps](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) |Campaign Classic/Standard |Learn about the different types of bounces.|
|February 23, 2021|[Deliverability - Bulking and blocking](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) |Campaign Classic/Standard |Learn why ISPs place email messages in bulk folders or block them.|
|February 23, 2021|[Deliverability - Transition process - Infrastructure](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) |Campaign Classic/Standard |Learn what is required to properly construct an email infrastructure. |
|February 23, 2021|[Deliverability- Engagement](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) |Campaign Classic/Standard |Learn about the different types of engagement and why engagement matters for deliverability.|
|February 23, 2021|[Deliverability - Transition process: Targeting criteria](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) |Campaign Classic/Standard |Learn how to establish a positive reputation from the get-go to effectively build trust before rolling in your less engaged audiences.|
|February 23, 2021|[Deliverability - Transition process - ISP-specific considerations during IP warming](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) |Campaign Classic/Standard |Learn about the different rules and ways ISP providers have for looking at their traffic|
|February 24, 2021|[Deliverability - First impressions - introduction](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) |Campaign Classic/Standard |Learn how you can set yourself up for running a successful email program by making a good first impression in those areas.|
|February 24, 2021|[Deliverability - Transition process: Volume](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) |Campaign Classic/Standard |Understand how sending volume influences the deliverability of your email campaigns.|
|February 24, 2021|[Deliverability - First impressions - Address collection and list growth](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) |Campaign Classic/Standard |Learn what the best sources for new email addresses are, how to ensure high data quality, and alignment with legal guidelines.|
|February 25, 2021|[Deliverability - First impressions - Welcome email](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) |Campaign Classic/Standard |Learn what the key elements of  your welcome strategy should be.|
|February 25, 2021|[Deliverability - Transition process: Switching email platforms](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) |Campaign Classic/Standard |Learn how to transition smoothly when switching email platforms.|
|February 26, 2021|[Deliverability - Content best practices for optimal deliverability](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) |Campaign Classic/Standard |Tips for optimizing the content of your email for deliverability.|
|February 26, 2021|[Deliverability - Sender permanence](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) |Campaign Classic/Standard |Learn why it is important to establish a consistent sending volume.|
|February 26, 2021|[Deliverability - Ongoing monitoring](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) |Campaign Classic/Standard |Know which issues you need to look out for when monitoring your deliveries.|
|February 26, 2021|[Deliverability - Putting it in practice](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) |Campaign Classic/Standard |Four key pillars to success.|
|March 10, 2021|[Deliverability best practices for leaders, business users and administrators](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) |Campaign Classic |Learn key deliverability terms, concepts, and approaches to empower you to ensure your marketing program success.|

### Help resources

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/en/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [Latest documentation updates](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Latest documentation updates](https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Adobe Campaign Control Panel: [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html) - How-to-videos for [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Release notes for Adobe Advertising Cloud.

* [New features in Advertising Cloud DSP](#adcloud-dsp)
* [New features in Advertising Cloud Search](#adcloud-search)

### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 28, 2020**

| Feature    | Description  |
| -----------| ---------- |
| New Help | (October 28 release) The legacy help was replaced with updated pages, which are available from the Help link in the DSP main menu and are also available at all times from [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) |
| Campaigns | (October 28 release) The previous Campaigns Beta views are now the default Campaigns views, for quicker insights, simplified workflows, and customized views. |
| Private Inventory | (October 15 release) All users can now set up and edit deal ID details using a new deal ID form, which is a simplified version of the legacy [!UICONTROL Smart Ad Serving] form. To set up new deal ID details, go to **[!UICONTROL Inventory > Deals]**, click **[!UICONTROL Create]**, and then click **[!UICONTROL Deal ID Beta]**. |
| Placement Forecasting | (October 15 release) For placements with placement-level pacing, the [!UICONTROL Forecast] section of the placement settings includes a new [!UICONTROL Estimated Maximums] section, which indicates how much more capacity is available with the current targeting configuration. |

### New features in [!DNL Advertising Cloud Search] {#adcloud-search}

Last updated: **January 22, 2021, for January 23 release**

| Feature    | Description  |
| -----------| ---------- |
| [!UICONTROL Search Campaigns]<br> Reports| Advertising Cloud Search no longer reports new average position data for Microsoft® Advertising campaigns. The Average Position column shows values of zero (0) for dates beginning 23 January. This is in preparation for Microsoft's deprecation of average position data in January 2021.<br>Average position data collected through 22 January is still available in reports. |

### Ad Cloud tutorials and courses

Updated: **December 2, 2020**

## ![Icon](/assets/magento.png) [!DNL Magento] {#magento}

See Magento Commerce and Open Source [release notes](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) for the latest release information.

## ![Icon](/assets/target.png)[!DNL Target] {#target}

See [[!DNL Target] release notes](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release information.

## ![Icon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is a complete application for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo Engage] [release notes](https://docs.marketo.com/display/public/DOCS/Release+Notes) for the latest release information.

### Upcoming features

The following features are releasing throughout the quarter:

| Feature | Description |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>New account-based segmentation</li><li>Save dashboard-specific filters</li><li>Export Bizible dashboards as PDFs</li></ul> |
| Sales Connect | Compose Window and Command Center updates/enhancements |

### Deprecations

* **Asset API "_method" Parameter:** After September 2020, Asset API Endpoints will no longer accept `_method` to pass Query Parameters in a POST body to bypass URI length limitations.
* **Internet Explorer Support Deprecation:** Beginning with the July release on July 31, 2020, the Marketo Engage user interface will no longer be supported on Internet Explorer.

## ![Icon](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

New videos, tutorials, or courses published for Adobe Document Cloud.

For Document Cloud help, see:

* [Adobe Acrobat Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud Learn & Support](https://helpx.adobe.com/support/document-cloud.html)

## ![Icon](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

New tutorials for Creative Cloud Enterprise.

Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|March 5, 2021|[Customize the colors in an Adobe Stock Vector illustration](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html)|Video |Add polish to any project with a great-looking illustration. Find the perfect vector in Adobe Stock, and then match the colors to your project’s palette using Adobe Illustrator. |
|March 5, 2021|[Customize an Adobe Stock presentation template to look professional, yet eye-catching](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) |Video |Create a beautiful stylized presentation in minutes with images and templates from Adobe Stock and some easy-to-do special effects. |
|March 5, 2021|[Customize a loading screen animation with Adobe Stock and XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) |Video |Customize vector artwork from Adobe Stock to create a chilling loading screen animation for a mobile app.|
|March 5, 2021|[Create realistic photo composites with Adobe Stock images](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) |Video |Bring together two great Adobe Stock photos to draw people into your social posts. |
|March 5, 2021|[Create inspiring mood boards in no time with Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) |Video |Create a project mood board to relay information, ideas, visuals, and color palettes to teams/clients. |
|March 5, 2021|[Create cohesive brand imagery with beautiful gradients and Adobe Stock assets](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) |Video |Bring animation into your newsletter graphics with editable vectors for Adobe Stock. |
|March 5, 2021|[Create animations for email with Adobe Stock and Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) |Video | Empower your Emails with Stop-Action Animation with Adobe Stock and Photoshop.|
|March 5, 2021|[Create an interactive tourism photo with Adobe Stock and XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) |Video |Quickly create an interactive photo within your website prototype with Adobe Stock & XD.|
