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

Latest update: **March 2021**

* [Adobe System Status](#status) (not updated)
* [Experience Cloud services and administration](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) and [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
  
Need help? Visit [Adobe Experience League](https://experienceleague.adobe.com/#home) to find product and technical documentation, Adobe-curated courses, video tutorials, quick answers, community insight, and instructor-led training.

## ![Icon](/assets/adobe.png) Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

Content forthcoming.

See [Adobe System Status - May 21, 2020](https://docs.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status) for the latest release information.

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud services and administration {#ecloud}

[Experience Cloud services and administration](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) documentation includes Customer Attributes, Audience Library ([!UICONTROL People] service), Activation, user and product management, and Experience Cloud cookies.

Content forthcoming.

## ![Icon](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Includes release update information for Experience Platform and Experience Platform Launch.

* [Experience Platform release notes](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). (January 27, 2021)
* [Experience Platform Launch release notes](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html). (January 13, 2021)

### Experience Platform tutorials and courses

New videos, tutorials, or courses published for Experience Platform and services.

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use Adobe Experience Platform to orchestrate a customer's journey at scale across experience channels, by intelligently anticipating every individual’s needs in real time.

### Latest product releases

Find out more about the latest capabilities, improvements, and fixes in the [Journey Orchestration Release Notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html).

### New Journey Orchestration courses and tutorials

New videos, tutorials, and courses published over the past month.

### More resources for Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

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
| Data Repair API updates | March 25, 2021 | A series of new scripts were added to the API tool to delete or edit Adobe Analytics data, including reserved variables, special variables, setting a new value, value matching, and manipulating URLs. |
| Analysis Workspace: [!UICONTROL Components] > [!UICONTROL User preferences] | March 25, 2021 | The [!UICONTROL Components] > [!UICONTROL User preferences] page enables you to manage [!UICONTROL Analysis Workspace] settings and its related components for your user. [!UICONTROL User preferences] applies to all new projects and panels. **Note:** the following settings have moved to the [!UICONTROL User preferences] page:<ul><li>Report Settings: Thousands separator (now called "Number format")</li><li>Report Settings: CSV separator</li><li>Workspace projects: Help > Enable tips</li><li>Workspace projects: Blank panel "Start new projects with this panel" option</li></ul> |
| Analysis Workspace: Histogram Smart Bucket Prediction | March 25, 2021 | Histogram Smart Bucket Prediction helps with high-cardinality-metrics histograms by automatically identifying the right width and number of buckets for your data spread. For low-cardinality metrics, the visualization behaves the same as it did previously. |

### New features in Customer Journey Analytics {#cust-journey}

| Feature | [General Availability](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Target Date | Description |
| ----------- | ---------- | ----- |
| Support for Analytics Dashboard | March 25, 2021 | CJA now supports the Mobile Scorecard Builder and the Mobile App. This allows executives and business users to see their cross-channel KPIs from CJA data, using the same app they may already be using for Adobe Analytics. |
| Analysis Workspace: [!UICONTROL Components] > [!UICONTROL User preferences] | March 25, 2021 | The [!UICONTROL Components] > [!UICONTROL User preferences] page enables you to manage [!UICONTROL Analysis Workspace] settings and its related components for your user. [!UICONTROL User preferences] applies to all new projects and panels. **Note:** the following settings have moved to the [!UICONTROL User preferences] page:<ul><li>Workspace projects: Help > Enable tips</li><li>Workspace projects: Blank panel "Start new projects with this panel" option</li></ul> |
| Analysis Workspace: Histogram Smart Bucket Prediction | March 25, 2021 | Histogram Smart Bucket Prediction helps with high-cardinality-metrics histograms by automatically identifying the right width and number of buckets for your data spread. For low-cardinality metrics, the visualization behaves the same as it did previously. |

### Fixes in Adobe Analytics {#aa-fixes}

* Fixed an issue where, after editing and saving a segment’s new owner, this new owner was not reflected in the Segment UI. (AN-234502; AN-250970; AN-250286)
* Fixed an issue that caused an App report suite to consume both primary server calls and mobile primary server calls. (AN-244029)
* Fixed an issue with slow UI response time when opening Workspace projects. (AN-242553)
* Fixed an issue with being unable to log in to Report Builder after upgrade to the latest version. (AN-248825)
* Fixed and issue with with user permissions for non-admin users: A user should have a permission as long as it’s added to at least one of their profiles in Admin Console. Adding users to profiles should only add to the permissions they have and should not remove anything they are already entitled to via other product profiles. (AN-242723)
* Fixed a language encoding issue with Data Feeds. (AN-249862)
* Fixed an issue with users being unable to access shared Workspace projects. (AN-247814)
* Fixed an issue with alert previews not matching number of triggered alerts. (AN-249392; AN-250804)

#### Additional Adobe Analytics fixes

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| ----------- | ---------- | ---------- |
| EOL of Full Processing Data Sources | March 10, 2021 | Adobe plans to deprecate full processing data sources in the future. As of March 25, 2021, new imports of this type can no longer be created. Please use [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) to import this type of data. |
| Reports & Analytics landing page options | February 19, 2021 | On March 25, 2021, options to set new Reports & Analytics dashboards or other content as your Adobe Analytics landing page will be removed. If you previously set a Reports & Analytics page as your custom landing page, it will continue to work until your landing page is modified in [!UICONTROL User Preferences]. As of March 25, 2021, you can no longer define new Reports & Analytics custom landing pages. |
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

### Audience Manager courses and tutorials {#tutorials-aam}

New videos, tutorials, or courses published for Audience Manager.

### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the [Onboarding Status Report](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html). In this issue, there was a discrepancy between the records in the report and the ones in the file uploaded by an onboarding partner. (AAM-57415)
* Fixed an issue causing incorrect duplicate segment mapping validation for **[!UICONTROL People-Based Destinations]**. (AAM-56631)
* Fixed an issue which blocked some users from accessing **[!UICONTROL Audience Reports]**. (AAM-57412)
* Patched a [!DNL Remote Code Execution] vulnerability which could be used by attackers to access sensitive data. (AAM-57495)

## ![Icon](/assets/aem.png) Adobe Experience Manager {#aem}

New features, fixes, and updates in Experience Manager. Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

>[!NOTE]
>
>Adobe recommends visiting the [Experience Manager release updates and roadmap](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) page to stay current on release information.

### Product releases

* **Experience Manager as a Cloud Service**

    New features in Experience Manager as a Cloud Service

  * **Experience Manager Sites as a Cloud Service**

    * **Headless Content Management Service**

      * [GraphQL API for Content Fragment Delivery](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html): Ability to query Content Fragments using GraphQL syntax, and schemas based on Content Fragment models, for output in JSON format.
      * [Authentication Support for GraphQL API Requests](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html): Ability to authenticate GraphQL API requests with access tokens for server-side APIs.
      * [The RemotePage Component](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html): Added support for viewing and editing external SPAs within AEM using.
      * [Editing an External SPA within AEM](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html): Added ability to upload a stand-alone single-page application to an AEM instance, add editable sections of content, and enable authoring.
      * Enhanced JSON output from GraphQL API, including ability to output rich text in JSON format and locales.
      * Support for nesting Content Fragment models to allow creating nested Content Fragment structures, via dedicated Content Fragment Reference data types or Content Fragment references inline in multiline text fields.
      * More validation rules available in Content Fragment model data types, including “unique”, “required” and “translatable”.
      * Ability tag Content Fragment models, and to allow Content Fragment creation in a folder with policies by tags or paths.
      * Usability enhancements in Content Fragment editor, including publish action and display of model a fragment is based on.
      * Ability to preview JSON output directly in Content Fragment editor.

    * **Progressive Web Apps (PWAs)**

      * [A Progressive Web App (PWA) version of a site](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html) can now be enabled at the project level via simple configuration.

  * **Experience Manager Assets as a Cloud Service**

    *  Experience Manager Assets as a Cloud Service is entitled to have a pre-configured Brand Portal instance. The Cloud Manager user can activate Brand Portal on Experience Manager Assets as a Cloud Service. See [activate Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html).
    
    *  Businesses can now source assets using Brand Portal. Asset sourcing feature leverages Brand Portal to help customers engage with agency users to source assets for new marketing campaigns, photoshoots and projects. See [asset sourcing in Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html).
    
    * The Brand Portal usage report now displays only the active users. The inactive users are not displayed now. Active users are the ones whose account is assigned to a product profile in the Admin Console. See [Brand Portal reports](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html).
    
    * In Brand Portal, a new download setting is introduced, that lets you create separate folder for each asset when downloading folders, collection, and so on. See [download settings](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html).

  * **Experience Manager Commerce as a Cloud Service**

    * **What's New?**

      * Product Experience Management: New ‘Commerce’ properties tab for Assets and Experience Fragments. This tab enables you to link products / categories to Assets and Experience Fragments. The tab also shows real-time data for linked products / categories, and a link to show details in the product console.
      * Released CIF Venia Reference Site - 2021.02.02 that includes the latest CIF Core Components version v1.7.0. Refer to [CIF Venia Reference Site](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02) for more details.
      * Released CIF Core Components v1.7.0. Refer to [CIF Core Components](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0) for more details.

    * **SDK Build Analyzers**

      The Experience Manager as a Cloud Service SDK Build Analyzer Maven plug-in detects problems in a maven project, including missing dependencies. It gives developers an opportunity to find issues during local development, well before deploying to Cloud environments with Cloud Manager.

      Two new analyzers have been added for this release:

      * repoinit analyzer
      * bundle-nativecode

      For more information, see the documentation [here](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing).

  * **Cloud Transition Tools**

    * **What is New in Content Transfer Tool**

      * New capability and UI added to Content Transfer Tool – User-Mapping Tool. This feature automatically maps existing user and groups to their Adobe Identity Management System IDs as part of the content migration activity.
      See [Using User Mapping Tool](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html).
      * Content Transfer Tool now migrates all groups and users referenced in the migration set including children.
      * Users are allowed to select certain paths under `/etc` when creating migration sets.

### **Community**

* **Adobe Developers Live 2021 | Complete Session list**

   By popular request, [here](https://adobe.ly/3cldljt) is an aggregated list of all the Experience Manager sessions occurring at Adobe Developers Live. All the recording and Q&A for each session is posted to their respective Contextual Threads.

* **List of latest Adobe Experience Manager content on Experience League | January 2021**

    The official source of Digital Experience technical content produced by Adobe. See the full list [here](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156).

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

Find out more about the latest capabilities, improvements and fixes released:

* [Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)

### New Campaign courses and tutorials

New videos, tutorials, and courses published over the past month.

|Published|Name|Solution|Description |
| -----------| ---------- | ---------- | ---------- |
|February 5, 2021|[Getting started with Adobe Campaign Classic for Business Users](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) |Campaign Classic |After completing this course, you will understand the concepts of Adobe Campaign Classic and know how to create your first marketing campaign. |
|February 1, 2021|[Introduction to multi-channel and cross-channel](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) |Campaign Classic |Understand the difference between multi-channel and cross-channel campaign and what the use cases for multi-channel and cross-channel campaigns are. |
|February 1, 2021|[Create a SMS Delivery](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) |Campaign Classic |Learn how to create a SMS delivery. |
|February 1, 2021|[Create cross-channel campaigns](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) |Campaign Classic |Learn how to create and execute a cross-channel campaign.|
|January 29, 2021|[Use Control Groups](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) |Campaign Classic |Understand the concept of control groups and learn how to use a control group for your delivery.|
|January 28, 2021|[Send and validate proofs](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) |Campaign Classic |Learn how to send and validate a proof. |
|January 28, 2021|[Design emails for deliverability](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) |Campaign Classic |Learn how to apply deliverability best practices.|
|January 28, 2021|[Create and design email deliveries](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) |Campaign Classic |Understand the process of creating an email delivery and learn how to design and personalize email content.|
|January 27, 2021|[Create event triggered campaigns](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) |Campaign Classic |Learn how to create an event triggered campaign and understand its uses.|

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
| [!UICONTROL Search Campaigns]<br> Reports| Advertising Cloud Search no longer reports new average position data for Microsoft Advertising campaigns. The Average Position column shows values of zero (0) for dates beginning 23 January. This is in preparation for Microsoft's deprecation of average position data in January 2021.<br>Average position data collected through 22 January is still available in reports. |

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
