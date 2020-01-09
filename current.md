---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: January 2020
author: mfrei

---

# INTERNAL REVIEW - Adobe Experience Cloud Release Notes - January 2020

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE] 
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

**Release date: January, 16 2020**

* [Adobe System Status](#status)
* [Experience Cloud interface and core services](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services and Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

Looking for the help home? See [Adobe Experience Cloud Documentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] provides detailed information, status updates, and email notifications about Adobe cloud products and services outage, disruption, and maintenance events. Check it out at [status.adobe.com](https://status.adobe.com/).

**What's new**

* Using your Adobe ID, you can subscribe to event notifications based on your product, region, and event preferences. Users who configure their subscription preferences are notified of only relevant product incident and maintenance events as soon as they are opened, updated, or closed. Get started at Get started at [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**New features and enhancements available today**

| Feature    | Description  |
| -----------| ---------- |
|Subscribe to proactive email notifications | <ul><li>Support for Experience Cloud, Creative Cloud, Document Cloud, Adobe Experience Platform, and Adobe Services</li><li>Support for region and event type preferences</li></ul> |
|Manage notification preferences | <ul><li>Edit and save notification preferences at any time</li><li>Unsubscribe from notifications at any time</li></ul> |
|Get personalized and faster email delivery | <ul><li>Event notifications are sent as soon as events are opened, updated, or closed</li><li>Receive only the relevant event notifications matching your configured preferences</li><li>Receive localized notifications based on the language configured in your account preferences</li></ul> |
|Get personalized in-product notifications | <ul><li>Events matching your notification preferences and product entitlements appear in the Announcements panel</li></ul>|

## Experience Cloud interface and core services {#ecloud}

New features and fixes in the Experience Cloud interface, including administration and core services (customer attributes, audiences, triggers, cookies, and so on).

### Domain name change

Adobe is updating the domain and interface header to unify and improve your experience across all Experience Cloud applications. These enhancements are designed to simplify your experience in small but important ways. These enhancements will not change your current workflows. They include:

* New solution URLs: `experience.adobe.com/<application name>.` New URLs will become effective throughout the month. Adobe recommends updating your bookmarks accoringly.
* Easier switching between your organizations or to a different application.
* Improved product help: The [!UICONROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. This change simplifies access to more content helps you get the most out of Experience Cloud. We’ve also added a feedback feature in the [!UICONTROL Help] menu, making it easier to report issues or share your ideas.  
* Improved notifications: The [!UICONTROL Notifications] drop-down menu now has two tabs, one for your own product notifications and one for global product announcements.

**Note:** The [!UICONTROL Feed] page is being deprecated in January, 2020. Look for an in-product deprecation notice.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Cloud cookies

Adobe is adjusting the `same-site` setting on cookies to prepare for changes Chrome will make in Chrome 80 (to be released in February 2020).

You do not need to make changes unless you have a 1st-party domain that you do not use for cross-domain tracking (such as friendly 3rd-party domains). If you have a 1st-party domain like that, you can request that the domain be set to `Lax` as opposed to the default `None`. You can request that change through Adobe Customer Care. [More…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Release notes for the Experience Platform, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Platform Release Notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## Mobile Services and Mobile SDKs {#mobile}

January 16, 2020: Version 4.18.0
 
* Acquisition - Added a new API, `Analytics.processGooglePlayInstallReferrerUrl(final String url)`, to support Google Play Install Referrer APIs.

For more information about the Install Referrer APIs, see [Still Using InstallBroadcast? Switch to the Play Referrer API by March 1, 2020]( https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html).

## [!DNL Analytics] {#analytics}

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- | 
|Analysis Workspace – Freeform Table Builder |With Table Builder enabled, you can drag and drop in many dimensions, breakdowns, metrics and segments to build tables that answer more complex business questions. Data will not update immediately; instead, it will update once you click [!UICONTROL Build], saving you time once you know what table you want to construct. In addition, this feature offers:<ul><li>**Preview**: You can preview the format of a table before spending time to render real data.</li><li>**Flexible Row and breakdown settings**: You can set your row and breakdown levels for every dimension row. Previously, Workspace imposed defaults that could not be changed until after the data was returned.</li><li>**Breakdown by position**: You can set dimension rows to always _breakdown by position_, instead of _by specific item_ (default).</li><li>**Manual static row ordering**: You can manually order static rows, so that the table rows are displayed exactly as you need them. Previously, static rows could only be sorted by a metric column or alphabetically.</li></ul>Associated documentation will be published when this feature releases later in January.|
|New [!UICONTROL Identified State] dimension for Cross-Device Analytics (CDA)|We are adding a new dimension called [!UICONTROL Identified State] to CDA virtual report suites. The dimension has two possible values, _Identified_ and _Unidentified_. _Identified_ means that the person has been identified by the device graph. _Unidentified_ means that the person has not been identified by the device graph.<br>This means that CDA users can now create calculated metrics such as [!UICONTROL Device Graph Coverage], which describes how many of the people within the virtual report suite are known by the device graph. This metric is helpful for troubleshooting CDA compression rates. If few people are identified, the level of stitching will be low.|
|VRS Support in Data Warehouse API|Virtual Report Suites will now be available for use via the Data Warehouse API. Previously, they were only available via the Data Warehouse UI. When using the Data Warehouse API, you can now see and query virtual report suites, but only if the segments applied to a Virtual Report Suite are compatible with Data Warehouse.|
|Privacy Service API: CCPA|The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act became effective on January 1, 2020.<br><br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br><br/>The Privacy Service supports requests to opt out from the selling of personal data.<br><br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md)|

#### Fixes

* Fixed an issue with alert notifications not being delivered to phone numbers in Egypt. (AN-197079)
* Fixed multiple issues with the [!DNL DFA Data Connector]. (AN-193281, AN-193075, AN-193484, AN-193737)
* Reports & Analytics: Fixed an issue with the Product Conversion Funnel report getting cut off and showing unclear numbers. (AN-186901)
* Fixed an issue that prevented users from switching report suites in Workspace projects that were based on report suites with the new Classifications architecture. (AN-199076)
* Fixed an issue that prevented the [!UICONTROL Cumulative] function in [!UICONTROL Calculated Metrics] from working properly. (AN-184257)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|End of Life - Anallytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)  to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs|
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics will begin moving to a new domain - https://experience.adobe.com/analytics.<ul><li>This change may cause cookie issues when loading Analytics in Safari. Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. You can use other browsers without issue, since this only affects Safari users.</li><li>This change may cause Activity Map to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul>|
|EOL of **[!UICONTROL View Archive]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the **[!UICONTROL View Archive]** option in the Dashboard Manager (**[!UICONTROL Components > Dashboards]**).|
|EOL of **[!UICONTROL Enforce IP Login Restrictions]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the IP login whitelisting (**[!UICONTROL Enforce IP Login Restrictions]**) functionality under the **[!UICONTROL Admin > Company Settings > Security]** menu.|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|Upcoming change regarding `createDate` field for Analytics users|August 30, 2019|In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468)|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Fixes and features added to Audience Manager.

### New features, enhancements, and fixes in Audience Manager {#aam-features}

| Feature    | Description  |
| -----------| ---------- | 
|[California Consumer Privacy Act (CCPA) Support and Privacy Documentation Overhaul](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | The [California Consumer Privacy Act (CCPA)](https://www.caprivacy.org/about), which came into effect on January 1st, 2020, provides California residents new rights regarding their personal information and impose data protection responsibilities on certain entities that conduct business in California. <br> <br> Audience Manager helps you comply with your obligations under privacy regulations, through privacy tools like the [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) for data access and delete requests. <br><br> We have updated the current [opt-out management](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) process to include opting out of any declared ID (e.g. CRM ID). In case of opt-out by declared ID, the declared ID and the last linked device will be opted out of Audience Manager data collection. Opt-out requests now also send unsegment requests to [destination partners](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) who support this feature, both in batch and real time. <br><br> Additionally, we've redesigned our [Data Security](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html), [Data Privacy](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html), and [Data Governance](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) documentation, to make it easier for you to find the information required to comply with the aforementioned regulations.|

### Fixes and Improvements {#aam-fixes-and-improvements}

* We fixed a bug in the [!UICONTROL Create Destination] workflow where, upon selecting **[!UICONTROL Integrated Platforms]** as Category, the Basic Information section would disappear and the workflow would be impossible to complete. (AAM-52397, AAM-52414)
* We fixed a bug where the Create/edit destinations page would not load in the Apple Safari and Mozilla Firefox browsers. (AAM-51784)
  
## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product maintenance

* **AEM 6.5.3.0**
    AEM 6.5, Service Pack 3.0 (6.5.3.0 released December 12, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.5, April 2019.
    * [Release notes](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
    * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

    AEM 6.4, Service Pack 7.0 (6.4.7.0 released December 12, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.4, April 2018.
    * [Release notes](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
    * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

    AEM 6.3, Service Pack 3, Cumulative Fix Pack 7 (6.3.3.7 released December 12, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.3, April 2017.
    * [Release notes](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
    * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

    AEM Desktop App 2.0.1.1 provides an update for Single Sign-On with Okta and ability to specify the location of temporary files in Preferences. Support for AEM 6.3.x is deprecated for Desktop App 2.x with this release.
    * [Release notes](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 ends support for AEM 6.3.x**

    Support for AEM 6.3.x has been deprecated in Adobe Asset Link since April 2019. Adobe Asset Link 1.1 removes support for AEM 6.3.x as of January 13, 2020.
    * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### Product releases

* **Automated Forms Conversion Service**

    Automated Forms Conversion Service, the service to automatically convert PDF forms to beautiful mobile-ready HTML Forms, became available for general consumption on December 12, 2019.

    * [Introduction](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
    * [Configure the service](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
    * [Convert PDF forms to adaptive forms](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)    

### Self-Help

* **Previewing 3D Assets**

    AEM 6.5 supports the upload, delivery, and interactive preview of 3D assets as part of the authoring process. The interactive 3D viewer is available from the asset details page in AEM. The viewer includes, among other things, a collection of interactive camera controls that let you orbit, zoom, and pan the 3D asset.
    See [Previewing 3D assets](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html).

* **Core Components**

    Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Project Archetype**

    The [ui.frontend module](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) of the [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) is a useful and flexible tool to make front-end development for your AEM project easier.

### Additional resources

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

### Documentation resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Release Planning](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
