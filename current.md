---
title: Latest Release Notes
description: Learn about the latest release notes, new features, and new documentation for Experience Cloud products and services. Find new help and tutorials about Experience Cloud, Creative Cloud for Enterprise, and Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
---
# INTERNAL REVIEW - Adobe Experience Cloud Release Notes - June 2021 

![Banner](assets/experience-cloud-banner-3.png)

Experience Cloud applications and services are updated monthly. This page is your central location for finding the latest release updates, documentation, and tutorials for [!DNL Experience Cloud] and [!DNL Experience Platform]. You can also find new documentation for [!DNL Creative Cloud for Enterprise] and [!DNL Document Cloud].

>[!NOTE]
>
>Subscribe to the monthly [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to receive email notifications about updates to this page. This page is maintained throughout the month, so please check back regularly for updates to Adobe enterprise product and Experience League documentation.

Latest update: **June 9, 2021**

* [Experience Cloud UI Components, Services, and Administration](#ecloud)
* [Adobe System Status](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) and [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)
  
Need help? Visit [Adobe Experience League](https://experienceleague.adobe.com/#home) to find product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud Central UI Components {#ecloud}

Updates to [Experience Cloud central interface components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en), user and product management, and self-help on Experience League.

| Feature | Date |Description |
| ------- | ------- | ------- |
|Single Sign-on Support for Adobe Federated IDs|June 17, 2021|If you use Federated IDs, you can sign in to Experience Cloud without having to enter an email address or password. To use this feature, add `#/sso:@domain` to the Experience Cloud URL. <br>For example, assume that you own the domain `adobecustomer.com` and want to sign into Adobe Analytics. The URL would be: `https://experience.adobe.com/#/sso:@adobecustomer.com/analytics`.|
|Experience League Search |June 1, 2021 |Experience League documentation search has been improved. Navigate to [Experience League](https://experienceleague.corp.adobe.com/docs/?lang=en) and use the **[!UICONTROL Search]** field to locate tutorials, documentation, courses, and more. |

{style="table-layout:auto"}

## ![Icon](/assets/adobe.png) Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

The most recent updates to Adobe System Status are found at [Adobe System Status - May 21, 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=en) for the latest release information.

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Includes release update information and new documentation for Experience Platform and Experience Platform Launch.

* **May 26, 2021:** [Experience Platform release notes](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)
* **May 17, 2021:** [Experience Platform Data Collection release notes](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html) (formerly, Experience Platform Launch)

### Experience Platform tutorials and courses {#tutorials-platform}

New videos, tutorials, or courses published for Experience Platform and services.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|June 2021|[Prepare data](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html)|Video | Learn how to clean, prepare, and combine data from multiple datasets to create a dataset using Create Table AS (CTAS) and Spark SQL functions for reporting and dashboarding.|
|June 2021|[Copy schemas between sandboxes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html)|Video | Learn how to copy a schema from one sandbox to another in Adobe Experience Platform using the [!UICONTROL Export/Import Schema API]. Build and test your schemas in development sandboxes, then copy them to production. |
|June 2021|[Update schemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html)|Video |Learn the basic things to be aware of when updating existing schemas in Adobe Experience Platform.  |
|June 2021|[Schema building blocks](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html)|Video |Learn the key building block elements of Experience Data Model (XDM) schemas, including fields, data types, schema field groups, classes, and behavior.|
|June 2021|[Create classes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html)|Video |Learn how to create classes in Adobe Experience Platform for use in Experience Data Model (XDM) schemas.  |
|June 2021|[Configure relationships between schemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html)|Video |Learn how to configure a relationship between two schemas in Adobe Experience Platform. Relationships allow you to use one dataset as a lookup table for another.   |
|June 2021|[Create data types](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html)|Video |Learn how to create your own data types in Adobe Experience Platform for use in Experience Data Model (XDM) schemas.  |
|June 2021|[Convert your data model to an experience data model](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html)|Video |Learn how data architects can take their existing transactional data model and convert it to an Experience Data Model. This video shows the difference in modeling approaches using entity-relationship diagrams.  |
|June 2021|[Plan your data model](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html)|Video |Learn what to do before you start building your schemas in Adobe Experience Platform. Document your business use cases, understand your Platform license, know the product guardrails, and identify what data to ingest before finalizing your data model.  |
|June 2021|[Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html)|Video | Learn how to connect to [!UICONTROL Query Service] from various desktop client applications that supports `PostgreSQL` protocol and how to use `PostgreSQL` tools and drivers to connect and write queries.  |
|June 2021|[Adobe Defined Functions](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html)|Video | Learn how to use Adobe-defined functions in Adobe Experience Platform [!UICONTROL Query Service] to perform common business-related tasks on Experience Event data.  |
|June 2021|[Data exploration](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html)|Video | Learn how to validate ingested data, preview data, and explore statistical and analytical properties of data using SQL functions.  |
|June 2021|[Query Service Overview](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html)|Video |Learn about Query Service in Adobe Experience Platform and how it helps to understand customer behavior and generate impactful insights.  |
|June 2021|[Query Service UI Overview](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html)|Video | Learn how to write and execute queries, view previously executed queries, and access queries saved by others users within your IMS Organization in Adobe Experience Platform Query Service.|
|June 2021|[Query API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html)|Video | Learn how to write and execute queries, create schedule queries, and create a query template using Adobe Experience Platform [!UICONTROL Query Service API].|

{style="table-layout:auto"}

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use Adobe Experience Platform to orchestrate a customer's journey at scale across experience channels, by intelligently anticipating every individual’s needs in real time.

### Latest product releases

Find out more about the latest capabilities, improvements, and fixes in the [Journey Orchestration Release Notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en).

### More resources for Journey Orchestration

[Documentation](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=en) - [Release Notes](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [How-to videos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=en)

## ![Icon](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] is an Application Service integrated with Adobe Experience Platform. Use [!UICONTROL Offer Decisioning] to deliver the best offer and experience to your customers across all touch points at the right time.

### Latest product releases

April 2021 Release - Find out more about the latest capabilities in the [Offer Decisioning Release Notes](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new).

### More resources for Offer Decisioning

[Documentation](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en) - [How-to videos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Icon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Release date: **June 17, 2021**

* [New features in Adobe Analytics](#aa-features)
* [New features in Customer Journey Analytics](#cust-journey)
* [Fixes in Adobe Analytics](#aa-fixes)
* [Important notices for Analytics administrators](#aa-notices)
* [Analytics courses and tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### New features in Adobe Analytics {#aa-features}

| Feature | [General Availability](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - Target Date | Description |
| ----------- | ---------- | ------- |
| N/A | N/A |

{style="table-layout:auto"}

### New features in Customer Journey Analytics {#cust-journey}

| Feature | [General Availability](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - Target Date | Description |
| ----------- | ---------- | ----- |
| N/A | N/A |

{style="table-layout:auto"}

### Fixes in Adobe Analytics {#aa-fixes}

* Fixed an issue with the incorrect currency showing in the Revenue Real-Time report. (AN-254649)
* Updated the documentation on [eVar case sensitivity in reporting](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html). (AN-246438)
* Updated the documentation to better explain [Data Feed Implementation](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) and [here](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl). (AN-219485)
* Fixed issues with some data not being sent in the Data Warehouse report (AN-259951; AN-259712; AN-260107; AN-259953)

#### Additional fixes in Adobe Analytics or CJA

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| ----------- | ---------- | ---------- |
| Browser user agents reflect incorrect operating system versions for macOS | May 19, 2021 | All major browsers currently report users of macOS X 11 and above incorrectly as using macOS 10, as recorded in the browser's user agent string. This issue affects Adobe Analytics reporting, because it uses the user agent to determine device information like operating system. This inaccuracy is apparently in place to prevent compatibility issues for some websites. See this [Bugzilla ticket](https://bugs.webkit.org/show_bug.cgi?id=213622&utm_source=convertkit&utm_medium=email&utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) for reference. It is not clear when or if this issue will be rectified.<br>Some browsers initially recorded macOS 11 correctly, so there may be some traffic matching this value. However, because of the inaccurate reporting, filtering for operating system macOS 11 is not useful.<br>This issue is significant because starting with Safari on macOS 11, Apple updated ITP cookie expiry limitations to apply to CNAME implementations (see [WebKit blog post](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Before this update, these limitations applied only to client-side cookies set via JavaScript. This inaccuracy makes it difficult to assess how much traffic is using OS 11 and is thus impacted by the ITP change. You can learn more about cookies and Adobe Analytics [here](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html#cookies). |
| End-of-life for three Analytics API services | May 19, 2021 | On August 18, 2021, the following Analytics Legacy API services reached their end-of-life date and were shut down. Any current integrations built using these services stopped working on that day.<ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>Adobe has provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs. |
| 2021 ISO region updates | May 13, 2021 | Adobe will perform 2021 ISO region updates on May 21, 2021. Expect to see minor updates following this release. |
| EOL of Full Processing Data Sources | April 12, 2021 | Adobe plans to deprecate full processing data sources on July 31, 2021. As of March 25, 2021, new imports of this type can no longer be created. Please use [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) to import this type of data. |
|Sign in update to [!UICONTROL Report Builder] | April 9, 2021 | On January 14, 2021, the [!UICONTROL Report Builder] sign-in updates removed dependencies on legacy technologies and aligned the sign-in process with Experience Cloud. Experience Cloud uses your Enterprise ID (email and password). To ensure uninterrupted access to [!UICONTROL Report Builder], update the [!UICONTROL Report Builder] add-in to version 5.6.47 or later by July 22, 2021. Report Builder version 5.6.47 and later supports only the Experience Cloud sign-in and will not support single sign-on.|
| Data Feed and Data Warehouse IP Address Changes | April 6, 2021 | Starting June 17, the Data Feeds and Data Warehouse delivery system will be relocated within Adobe's data centers, and therefore can cause a change of external IP addresses visible to you. Adobe recommends that you confirm that all the IP CIDR blocks for the data center where your reports and feeds are sourced are present in firewalls for destination systems that you control. [Here is a full list of IP Address ranges to place into your firewall’s allowlists](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html#data-collection-and-ftp-ip-address-blocks). |
| Notice of upcoming Analytics menu changes | March 24, 2021 | On April 22, 2021, Adobe updated the **[!UICONTROL Components]**, **[!UICONTROL Tools]**, and **[!UICONTROL Admin]** dropdown menus in order to achieve some performance gains. All of these pages are still available under the **[!UICONTROL All Components]**, **[!UICONTROL All Tools]**, and **[!UICONTROL All Admin]** links - they will be removed from the dropdown menu. Here are the menu items that will be removed from the dropdown menu and placed on their respective link page:<br><br> [!UICONTROL Components]<ul><li>[!UICONTROL Bookmarks]</li><li>[!UICONTROL Dashboards]</li><li>[!UICONTROL Targets]</li><li>[!UICONTROL Calendar Events]</li><li>[!UICONTROL Scheduled Reports]</li><li>[!UICONTROL Report Settings]</li></ul>[!UICONTROL Tools]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search & Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL User Management]</li><li>[!UICONTROL Classification Importer]</li><li>[!UICONTROL Classification Rule Builder]</li><li>[!UICONTROL Data Sources]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Company Settings]</li><li>[!UICONTROL Logs]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Code Manager]</li><li>[!UICONTROL Exclude by IP]</li><li>[!UICONTROL Traffic Management]</li></ul> |
| Same-as-SiteCatalyst VISTA Processing ON | March 17, 2021 | On June 17, 2021, all report suites will be updated to have [!UICONTROL Same-as-SiteCatalyst VISTA Processing] set to ON. This change impacts Data Warehouse reporting by processing the data to match processing rules. For questions or clarification, reach out to Customer Care. |
| Reports & Analytics landing page options | February 19, 2021 | On March 25, 2021, options to set new Reports & Analytics dashboards or other content as your Adobe Analytics landing page were removed. If you previously set a Reports & Analytics page as your custom landing page, it continues to work until your landing page is modified in [!UICONTROL User Preferences]. |
| EOL of Adobe Data Connectors | July 13, 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. A new standard is available in the [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud). You can use that standard for any integration to continue to be offered and supported. The official end-of-life date is August 1, 2021. [Learn more...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=en) |

{style="table-layout:auto"}

### AppMeasurement {#appm}

For the latest updates on AppMeasurement releases, please refer to [AppMeasurement for JavaScript release notes](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en).

### Analytics courses and tutorials {#tutorials-analytics}

New courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|June 2021|[Getting Started with Customer Journey Analytics for Administrators](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1)|Course | Learn how to set up, configure, and administer Customer Journey Analytics. Learn some basic concepts to give you a foundation, and then move into more configuration steps. The course is then capped off with some recommendations on migrating calculated metrics and segments from Adobe Analytics to Customer Journey Analytics.|
|June 2021|[Configure internal site search reports](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en)|Video | Create and configure freeform tables in Analysis Workspace to analyze internal search functionality on your site.|
|June 2021|[Map Web SDK variables into Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en)|Video | Learn how to map analytics variables from the Web SDK through to Adobe Analytics using Processing Rules.  |
|June 2021|[Implement internal search variables using Web SDK](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en)|Video | Learn how to use the Web SDK to implement Adobe Analytics variables for an internal search term tracking use case. See the flow of data from the page to the Experience Edge, and then to Adobe Analytics.  |
|June 2021|[Implement internal search variables using AppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en)|Video | In this video, learn the steps of implementing internal site search variables for Adobe Analytics using Experience Platform Data Collection/Launch, including search term, number of results, and others.  |
|June 2021|[Defining your internal site search business requirements](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en)|Video | When deciding to track internal search on your site, it is important to first decide which aspects of search you want to track, and what actions can be taken from analyzing the results. This video walks through the documenting of business requirements.  |

{style="table-layout:auto"}

### Analytics help resources

* [Adobe Analytics Product Documentation and Tutorials](https://experienceleague.adobe.com/docs/analytics.html)

## ![Icon](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Fixes and improvements in Audience Manager.

### Fixes and Improvements {#aam-fixes-and-improvements}

* Released an enhancement to the [Activity Usage report](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) which now allows you to review data older than one year. (AAM-58268)
* Adobe provides Audience Manager customers with user access keys for the Audience Manager Amazon S3 buckets. For security reasons, the keys are now automatically disabled after 100 days of inactivity. For more information, refer to the question at the bottom of the page in the [Data collection and product integration FAQ](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Icon](/assets/aem.png) Adobe Experience Manager {#aem}

New features, fixes, and updates in Experience Manager. Adobe recommends customers with On-Premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

>[!NOTE]
>
>Adobe recommends visiting the [Experience Manager release updates and roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) page to stay current on release information.

### Product updates

* **Experience Manager 6.5.9.0**

    Experience Manager 6.5, Service Pack 9.0 (6.5.9.0 released May 27, 2021). This important update includes new features, key customer-requested enhancements, improved performance, stability, and security, released since the general availability of Experience Manager 6.5, April 2019.

  * [Release notes](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
  * [AEM Forms release deliverables](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### Experience Manager release information

All Experience Manager release notes are maintained at the following pages:

* [Experience Manager as a Cloud Service release information](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager release notes](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Automated Forms Conversion Service release notes](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Service Pack release notes](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack release notes](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
* [Experience Manager Assets Dynamic Media release notes](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=en)
* [Experience Manager Brand Portal release notes](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Experience Manager desktop app release notes](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Experience Manager Dispatcher release notes](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=en)
* [Livefyre release notes](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=en)

### New Experience Manager courses and tutorials {#tutorials-aem}

New videos, tutorials, and courses published over the past month.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|June 2021|[Implement the methods of the interface](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en)|Article | Learn how to implement the interface methods to create PDFs using Document Cloud REST API.  |
|June 2021|[Create service interface](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html)|Article | Define the methods in the interface that you want to expose.  |
|June 2021|[Create custom OSGi Configuration](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en)|Article | Learn about custom OSGi configuration to capture Adobe I/O project details.  |
|June 2021|[Create Content Analyzer](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en)|Article |Learn how to create the JSON part containing the information about the input parameters to the Create PDF REST call.|
|June 2021|[Create custom process step](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en)|Article | View the complete code of the custom process step that converts and replaces the native files with the converted PDFs. This custom step searches for all attachments under the folder name, which is provided as a process argument in the workflow. This custom process step uses the methods of the custom `DocumentCloudSDKService` to create PDFs.  |
|June 2021|[GraphQL Persisted Queries](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en)|Video | Learn how to enable, create update and execute Persisted Queries in AEM.  |
|June 2021|[Creating your first servlet in AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en)|Article | Build your first sling servlet to merge data with a form template.  |
|June 2021|[Creating your first OSGi Service with AEM forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en)|Article | Build your first OSGi service with AEM Forms to generate pdf by merging data with template.  |

{style="table-layout:auto"}

### Other Help resources for Experience Manager

* [Experience Manager as a Cloud Service Guides](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Experience Manager 6.2 Learn & Support Home](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Older Versions of Experience Manager Documentation](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Cloud Manager User Guide](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [Dynamic Media Classic Help Home](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Experience Manager Documentation: Recent Updates](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Icon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Latest product releases

Find out more about the latest capabilities, improvements, and fixes released:

* **New Adobe Campaign v8** with significant infrastructure, security, deliverability, and monitoring enhancements. By using [!DNL Snowflake], a cloud database technology, Adobe Campaign dramatically improves its scale and speed, with the ability to manage a more significant number of customer profiles, as well as much higher delivery rates and transactions per hour. Learn more in the [Campaign v8 documentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Adobe Campaign Classic v7 21.1.3 release**: Learn more in the [Campaign Classic v7 Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

* **Adobe Campaign Standard 21.2 release**: Learn more in the [Campaign Standard Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

### Campaign courses and tutorials {#tutorials-campaign}

|Published|Name|Solution|Description |
| -----------| ---------- | ---------- | ---------- |
|June 2021|[Integrate Campaign Standard with Analytics to optimize your email marketing](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2021.1.integration)|Campaign Standard |(Course) Learn how to integrate Campaign Standard with Adobe Analytics and optimize your email marketing strategies using real-time data. This course shows you how to build a Campaign Standard report in Adobe Analytics. Then, learn how to use Experience Cloud Triggers and Platform Launch to configure marketing and transactional messages based on customer activity. |

{style="table-layout:auto"}

### Help resources

* Adobe Campaign Standard: [Help Center](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=en) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=en) - [Release Planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=en) - [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=en)
* Adobe Campaign Classic: [Help Center](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=en) - [Release Notes](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [How-to videos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=en)- [Latest documentation updates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=en)
* Adobe Campaign Control Panel: [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [Release Notes](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - How-to-videos for [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=en) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=en)

## ![Icon](/assets/advertising-cloud.png) Advertising {#adcloud}

Release notes for [!DNL Adobe Advertising].

* [New features in Advertising DSP](#adcloud-dsp)
* [New features in Advertising Search](#adcloud-search)

### New features in [!DNL Advertising DSP] {#adcloud-dsp}

Last updated: **May 19, 2021 for May 5 release**

| Feature    | Description  |
| -----------| ---------- |
| Package Settings | A new [!UICONTROL Pacing Fill Strategy] option, "[!UICONTROL Slightly Ahead]," is available and is the default for new packages. This strategy accelerates delivery so that it’s 55-65% complete halfway through the flight duration. |

{style="table-layout:auto"}

### New features in [!DNL Advertising Search] {#adcloud-search}

Last updated: **May 19, 2021, for May 18 release**

| Feature    | Description  |
| -----------| ---------- |
| [!UICONTROL Notification Center Beta]| The [!UICONTROL Notification Center Beta] is available to all users. Use it subscribe to email and web notifications about account authentication errors, custom alerts that are triggered, and completion of the [!UICONTROL Advertising Insights] you generate.<br>You can view your notifications from either:<ul><li>The [!UICONTROL Notifications] panel, which opens from the Notifications link in the upper right of any page.</li><li>The [!UICONTROL Notification Center] at [!UICONTROL Insights & Reports >Notification Center Beta].</li></ul><br><b>Note:</b> Because of improvements to how notifications are stored, all existing notifications were cleared. |

{style="table-layout:auto"}

## ![Icon](/assets/magento.png) [!DNL Magento] {#magento}

See Magento Commerce and Open Source [release notes](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) for the latest release information.

## ![Icon](/assets/target.png)[!DNL Target] {#target}

See [[!DNL Target] release notes](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en) for the latest release information.

## ![Icon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is a complete application for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo Engage] [release notes](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/documentautomation.html#integrations) for the latest release schedule information.

## ![Icon](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

New videos, tutorials, or courses published for Adobe Document Cloud.

### Document Cloud courses and tutorials {#tutorials-doc-cloud}

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|June 2021|[Adobe Acrobat for Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html)|Video | Get access to time-saving PDF tools and e-signature workflows directly inside the Google Drive app.  |
|June 2021|[Try your hand at Fresco on the iPad (and iPhone)](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html)|Video | Explore a whole new world of digital drawing and painting with Adobe Fresco in this 15-minute hands-on workshop. Quickly learn to work with layers and clipping masks to conform paint and textures to a base shape.   |
|June 2021|[Decoding the Alphabet Soup of Graphic Formats](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html)|Video | PG, PNG, SVG, GIF, and EPS files are all commonly used in design, some for web pages, others for presentations, publications, and creative projects. But… what do they mean, and which should you pick? Find out in this 15-minute hands-on workshop.   |

{style="table-layout:auto"}

For Document Cloud help, see:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud Learn & Support](https://helpx.adobe.com/support/document-cloud.html)

## ![Icon](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

See [Creative Cloud for Enterprise Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.
