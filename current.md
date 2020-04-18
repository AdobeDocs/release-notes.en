---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: March 2020
author: mfrei

---

# Adobe Experience Cloud Release Notes - April 2020

![Banner](/assets/experience-cloud-banner-3.png)

New features and fixes in the [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

**Release date: April 2020**

(Specific release dates my vary.)

* [Adobe System Status](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(Release date change - see update on April 15)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to Target's help page)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to Primetime's help page)

Looking for the help home? See [Adobe Experience Cloud Documentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## ![Icon](/assets/adobe.png) Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

**What's new**

* Using your Adobe ID, you can subscribe to event notifications with more granularity, down to the product offering and add-on level. Furthermore in our latest release, the self-subscription process now recommends a selection of products and services based on your product entitlements. This should streamline the subscription process by reducing the number of decisions or clicks required to create your subscriptions, and most importantly, deliver more relevant notifications in your inbox. Get started at [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**New features and enhancements available today**

| Feature    | Description  |
| -----------| ---------- |
|Personalized subscriptions based on entitlements | <ul><li>Pre-selected subscription recommendations based on the user's DX entitlements.</li><li>Recommended subscriptions are highlighted at the top of the product list for quick visualization.</li><li>Email notifications received are relevant to the user’s product entitlements.</li></ul> |
|Easier Management of Subscriptions| <ul><li>**[!UICONTROL Manage Subscriptions]** has a new user experience to manage both product and event subscriptions.</li><li>New option to view and edit product and event subscriptions separately.</li><li>The **[!UICONTROL Delete]** option allows you to unsubscribe from a product or event subscription.</li><li>The one-click **[!UICONTROL Unsubscribe all]** option is available for the product subscriptions.</li><li>UX support is available for Web/Mobile/Tablet surfaces and localization in 19 languages.</li></ul> |

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud interface {#ecloud}

New features and fixes in the Experience Cloud interface:

* Experience Cloud [!UICONTROL Feed] page was deprecated. (EXC-8505)
* Experience Cloud login page was updated to reflect new branding elements. (EXC-10747)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

### Unified product domain

Adobe is updating the domain and interface header to unify and improve your experience across all Experience Cloud applications. These enhancements are designed to simplify your experience in small but important ways. These enhancements will not change your current workflows.

Updates include:

* New application URLs: `experience.adobe.com/<application name>`:
  * All products will eventually adopt this URL pattern. Look for new URLs to become effective throughout the month.
  * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Note:** Although the Experience Cloud interface supports these browsers, individual applications might not support every browser. (For example, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) does not support [!DNL Opera], and [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) does not support [!DNL Safari].)
  * ([!DNL Safari] only) The domain change may cause cookie issues in [!DNL Safari]. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Easier switching between your organizations or to a different application.
* Improved product help: [!UICONTROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. This change simplifies access to more content and helps you get the most out of Experience Cloud. Additionally, click **[!UICONTROL Help]** > **[!UICONTROL Feedback]** to report issues or share your ideas with Adobe.  

## ![Icon](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Release notes for the [!DNL Experience Platform,] including [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.  

### Journey Orchestration {#journey}

Using Adobe Experience Platform, orchestrate individual customer journeys at scale across experience channels by intelligently anticipating every individual’s needs in real time, wherever their journey takes them.

* [Documentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Release notes](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)
* [How-to videos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services and Mobile SDKs {#mobile}

Android 4.18.2 (3 April, 2020):

* In App Messaging: For security reasons, [!UICONTROL WebViews] created by the SDK now set property `setAllowFileAccess` equal to _false_.

iOS 4.19.2 (24 March, 2020):

* General: Fixed some leaks in [!DNL Target] code.

Unity 4.19.0 (10 March, 2020):

* Updated [!UICONTROL Unity Plugin] to use versions 4.19.0 of iOS and 4.18.0 or [!DNL Android].
* Exposed new acquisition method for [!DNL Android] to allow processing of a URL provided by [!DNL Google Play] Referrer APIs.

### Additional Experience Platform release information

* [Experience Platform Launch release notes](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).
* [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

## ![Icon](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>The Adobe Analytics April maintenance release has moved to May 21, 2020. For the latest Analytics release information, see [March release notes](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Important notices for Analytics administrators](#aa-notices) (Updated April 7, 2020)
* [AppMeasurement](#appm) 
* [New Analytics tutorials](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Feature    | Description  |
| -----------| ---------- |
|[!UICONTROL Customer Journey Analytics]: Automated Dataset Backfill|This new option lets you import all historical data for a connection in [!UICONTROL Customer Journey Analytics]. [Learn more](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html)|

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace]|April 7, 2020|In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. For example, assume the first hit of a visit has no value for eVars, but the second hit does. In [!UICONTROL Reports & Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit.|
|EOL of **[!UICONTROL Conversion Level]** setting|March 3, 2020|The non-functioning [Conversion Level](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of October, 2020.|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics began moving to a new domain - `https://experience.adobe.com/analytics.`<br>**Note:** This change applies to all users accessing Analytics with their Adobe ID or Enterprise ID. <ul><li>The domain change may cause cookie issues when loading Analytics in Safari. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul>|
|End of Life - Analytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL of Ad Hoc Analysis|Aug 6, 2018|Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 was released on March 5, 2020. 

### New Analytics tutorials {#tutorials-analytics}

|Content | Description |
| -----------| ---------- |
|[Adobe Labs (Technology Previews) with Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html)|Adobe Labs (Technology Previews) allows you to engage with emerging technologies, discover valuable insights, and influence future [!DNL Analytics] feature development and priorities.|
|[Improved Experience Cloud Audience Publishing](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html)  |Improvements have been made to [!UICONTROL Experience Cloud Audience Publishing]. You can now publish audiences (segments) and make them available six times faster. This reduces the current latency time from 48 hours to approximately 8 hours, and possibly faster, depending on traffic and segment size.  |
|[Multiple Report Suites in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html)  |Multiple report suites can be analyzed in a single [!UICONTROL Workspace] project by selecting report suites at the panel level. This allows you to conduct side-by-side panel analysis across different sets of data.  | 

See [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html) for product documentation.

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

New features and fixes in Adobe Audience Manager:

| Feature    | Description  |
| -----------| ---------- |  
|[Top Customer Support Issues](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html)|We've added a new section to our documentation portal, which includes answers to the most frequent questions received by our Customer Support team.|

* Fixed an issue causing inaccurate reporting of [Addressable Audiences](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) for segments containing mobile device IDs. Following this update, you may see an increase in your [Addressable Audiences](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html).
* Fixed an issue causing the [!UICONTROL Duplicate Test] and [!UICONTROL Duplicate Allocation Template] buttons in [!UICONTROL Audience Lab] not to work. (AAM-53388)
* Fixed an issue causing the [!UICONTROL Match Rate] and [!UICONTROL Segment Addressable Audiences] to be displayed as 0 when a destination is configured to export UUIDs. The [!UICONTROL Match Rate] and [!UICONTROL Segment Addressable Audiences] are now displayed as 100%. (AAM-51615)
* Fixed an issue causing trait names which contain special characters to be HTML-encoded twice. (AAM-54001)
* Fixed an issue blocking some users from switching to other Adobe Experience Cloud applications from the [!DNL Audience Manager] user interface. (AAM-52917)
* Fixed an issue blocking some users from creating a SHA256 data source for People-based destinations. (AAM-53525)
* Multiple accessibility improvements across the interface. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Icon](/assets/aem.png) Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Self-Help

* **AEM Newsletter**

    See the latest [Adobe Experience Manager Newsletter](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM as a Cloud Service - Configuring Dynamic Media Cloud Service**

    A new option is available when you configure Dynamic Media Cloud Service:

    **Selective Publish** - When you select this option it means that assets are auto published for secure preview only and can be explicitly published to AEM without publishing to DMS7 for delivery in the public domain.

    See [Configuring Dynamic Media Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamic Media - Smart Imaging**

    The entire Smart Imaging Help topic was updated with new information, including image asset examples that depict the added Smart Imaging optimization.

    See [Smart Imaging](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configuring Dynamic Media - Scene7 mode**

    A new Sync all content option is now available on the Dynamic Media Configuration page found in **[!UICONTROL Tools > Cloud Services]**.

    See [Creating a Dynamic Media Configuration](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets Brand Portal supports AEM Assets as a Cloud Service**

    You can now publish assets from AEM Assets as a Cloud Service to AEM Assets Brand Portal.

    See [Configure AEM Assets with Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) and [Publish assets to Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 released**

    Adobe Asset Link 2.0 supports working with multiple AEM environments and supports AEM as a Cloud Service. AEM supports marketers' needs to configure auto-run of asset processing workflow when assets are uploaded to a folder using Adobe Asset Link. 

    See [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html).

### New Experience Manager tutorials

|Content | Description |
| -----------| ---------- |  
|[Set Up Local Dispatcher Tools](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) |Learn about facilitating configuring, validating, and simulating [!UICONTROL Dispatcher] locally. |
|[Set up Development Tools for AEM Projects](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html)  |Adobe Experience Manager (AEM) development requires a minimal set of development tooling to be installed and set up on the developer machine. These tools support the development and building of AEM Projects.  |
|[Set up Local AEM Runtime](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html)  |Adobe Experience Manager (AEM) can be run locally using the AEM as a Cloud Service SDK's [!UICONTROL QuickStart Jar]. This allows developers to deploy to and test custom code, configuration, and content prior to committing it to source control, and deploy it to a AEM as a Cloud Service environment.  |
|[Navigation](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) |Explore the basics for navigation AEM Assets.  |
|[Versions](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) |Explore how AEM creates and maintains asset versions.  |
|[AEM - [!DNL Magento] Integration using the [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) |This video walks you through the setup of the integration between AEM and [!DNL Magento]. |
|[Introduction to the AEM Architecture Stack](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) |The CIF Project archetype creates a minimal Adobe Experience Manager (AEM) CIF project as a starting point for customer projects using CIF Core Components. |
|[Introduction to OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html)  |An introduction to OSGi, a dynamic modular architecture for Java applications that is the basis for Adobe Experience Manager.  |
|[Introduction to the Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html)  |An introduction to the [Java Content Repository (JCR) used by Adobe Experience Manager. |
|[Introduction to Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html)  |An introduction to [!DNL Sling], an open-source RESTful web framework that is part of Adobe Experience Manager's underlying technology stack. |
|[Introduction to Author and Publish Tier](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html )  |An introduction to the [!UICONTROL Author] and [!UICONTROL Publish] tiers as part of the architecture in Adobe Experience Manager.  |
|[Introduction to Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html)  |An introduction to the capabilities and features of the dispatcher as part of the AEM architecture.  |
|[Introduction to Component Development](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html)  |An overview of developing components with Adobe Experience Manager Sites. Includes an introduction to [!UICONTROL Dialogs], [!UICONTROL Sling Models], [!UICONTROL HTL Scripts], and [!UICONTROL Client-Side Libraries].  |
|[AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html)  |The AEM Project contains all of the code and configurations for an implementation. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects.  |
|[Understanding Core Components](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html)  |AEM [!UICONTROL Core Components] are a standard set components to be used with Adobe Experience Manager.  |
|[Using the AEM Quickstart Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html)  |Learn how to install and run a local instance of Adobe Experience Manager in just a few minutes with the [!UICONTROL AEM Quickstart jar].  |

### Additional help resources

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

## ![Icon](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

### New Campaign Standard tutorials {#tutorials-acs}

|Content | Description |
| -----------| ---------- |  
|[Profile Substitution - Testing email messages using targeted profiles](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html)  |Test your email messages using the Profile Substitution feature. |

### Additional Campaign help resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign Control Panel: [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Icon](/assets/magento.png) [!DNL Magento] {#magento}

For Magento release notes, see:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icon](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] is a complete applications for lead management and B2B marketers looking to transform customer experiences by engaging across every stage of complex buying journeys.

### Core Marketo Engage updates

See [!DNL Marketo] [release notes](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) for more information.

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
