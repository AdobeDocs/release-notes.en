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

### Interface enhancements

Adobe is updating the domain and interface header to unify and improve your experience across all Experience Cloud applications. These enhancements are designed to simplify your experience in small but important ways. These enhancements will not change your current workflows. They include:

* New solution URLs: `experience.adobe.com/<application name>.` Adobe recommends updating your bookmarks accoringly. For example, `https://experience.adobe.com/target, https://experience.adobe.com/analytics,` and so on.
* Easier switching between your organizations or to a different application.
* Improved product help: The [!UICONROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. This change simplifies access to more content helps you get the most out of Experience Cloud. We’ve also added a feedback feature in the [!UICONTROL Help] menu, making it easier to report issues or share your ideas.  
* Improved notifications: The [!UICONTROL Notifications] drop-down menu now has two tabs, one for your own product notifications and one for global product announcements.

Note: The Feed page was deprecated in December, 2019. Look for an in-product deprecation notice.

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
|Analysis Workspace – Freeform Table Builder |The new Freeform Table Builder will be released later in January, 2020. It lets you set up a table with all the components you want, and then build (render) the table. This new feature saves time when building tables that answer deeper, multi-dimensional queries. (Previously, the table was rendered every time you added a component or breakdown, thus adding processing time.) In addition, this feature offers:<ul><li>**Preview**: You can preview the format of a table before spending time to build it.</li><li>**Breakdown by position**: You can set dimension rows to "breakdown by position", instead of “by specific item”.</li><li>**Manual row ordering**: You can manually order table rows, so that you can achieve the exact arrangement desired. Previously, rows could only be sorted by a metric column (or alphabetically sorted when static).</li><li>**Row and breakdown levels**: You can set your row and breakdown levels for every dimension row. Previously, Workspace defaulted to certain ranges that could not be changed until the table was built.</li></ul>Associated documentation will be published when this feature releases later in January.|
|New "Identified State" dimension for Cross-Device Analytics|We are adding a new dimension called "identified state" to CDA virtual report suites. The dimension has two possible values, "Identified" and "Unidentified". "Identified" means that the person has been identified by the device graph. "Unidentified" means that the person has not been identified by the device graph.<br>This means that CDA users can now create calculated metrics such as "device graph coverage", a metric which describes how many of the people within the virtual report suite are known by the device graph. This is helpful for troubleshooting CDA compression rates. If few people are identified, the level of stitching will be low.|
|VRS Support in Data Warehouse API|Virtual Report Suites will now be available for use via the Data Warehouse API. Previously, they were only available via the Data Warehouse UI. Customers using the Data Warehouse API can now see and query virtual report suites.|

#### Fixes

* Fixed an issue with alert notifications not being delivered to phone numbers in Egypt. (AN-197079)
* Fixed multiple issues with the DFA Data Connector. (AN-193281, AN-193075, AN-193484, AN-193737)
* Reports & Analytics: Fixed an issue with the Product Conversion Funnel report getting cut off and showing unclear numbers. (AN-186901)
* Fixed an issue that prevented users from switching report suites in Workspace projects that were based on report suites with the new Classifications architecture. (AN-199076)
* Fixed an issue that prevented the Cumulative function in Calculated Metrics from working properly. (AN-184257)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics will move to new domain - https://experience.adobe.com/analytics. This change may cause cookie issues when loading Analytics in Safari. Unchecking "Prevent cross-site tracking" in the Safari Privacy Preferences will enable cookies across domains (and all cross-site experiences), and allow Analytics to function on this new Adobe Experience Cloud domain. Users can use other browsers without issue, since this only affects Safari users.|
|EOL of **[!UICONTROL View Archive]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the **[!UICONTROL View Archive]** option in the Dashboard Manager (**[!UICONTROL Components > Dashboards]**).|
|EOL of **[!UICONTROL Enforce IP Login Restrictions]** option|Oct. 30, 2019|Announcing the January, 2020, end-of-life date for the IP login whitelisting (**[!UICONTROL Enforce IP Login Restrictions]**) functionality under the **[!UICONTROL Admin > Company Settings > Security]** menu.|
|Updated handling to SameSite attribute on cookies | October 15, 2019 | In August 2019, Adobe announced that it added the SameSite cookie setting to all cookies set by Analytics. An update in logic is applied where:<ul><li>All third-party cookies that are not based on Webkit have SameSite attribute set to `none`.</li><li>All other cookies do not have the SameSite attribute set.</li></ul>|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li>|
| Update to Analysis Workspace Freeform Table totals | September 12, 2019 | In October 2019, freeform table total rows will begin accounting for [report filters](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applied. To date, totals have accounted only for segmentation. With this change, dependent visualizations will update (e.g. linked [!UICONTROL Summary Number] visualizations), as well as exported CSV and PDF data.|
|Upcoming change regarding `createDate` field for Analytics users|August 30, 2019|In October or November 2019, the `createDate` field for Analytics users will be updated from US Pacific Time to a correctly formatted date/time value with time zone information. (AN-183468)|
| Support for Historical Timezone Offsets | August 8, 2019 | Analytics will now automatically handle timezone offsets for timestamped hits. Following this change on August 8, systems that load in data for historical processing will no longer need to adjust for timezone offsets before sending in the data. |
| Classification rule builder limits | Added June 5, 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html).|
| New segment operator limits | Added May 31, 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. The limit will be applied to all new and modified segments after this date. Existing segments that exceed the limit will continue to be supported, but cannot be modified or saved until the input field is reduced. These limits are being applied as part of a continued effort to improve query performance. |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Updated May 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change took effect with the July 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
| Change to _Report Total_ calculations | Updated July 9, 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. This resulted in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 18, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API.<br>**Note**: This _Report Total_ calculation is now called _Grand Total_. See "Analysis Workspace: Update to Freeform table totals" above. |
| Update to CSV downloads from Analysis Workspace | April 10, 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>The thousands separator is no longer included. The decimal separator will continue to be included, and will adhere to the format defined under **[!UICONTROL Components > Report Settings > Thousands Separator]**. Note: Numeric values that use a comma as the decimal separator will continue to be quoted in the exported CSV.</li><li>No currency symbols will be shown.</li><li>No percent symbols will be shown. Percentages will be in decimal form. E.g., 75% will be represented as 0.75.</li><li>Time will be shown in seconds.</li><li>Cohort tables will show raw values only; percentages will be removed.</li><li>If a number is invalid, an empty cell will be displayed.</li></ul>|
| Upcoming change to the Analysis Workspace Debugger command | April 4, 2019 | The Console command to turn on the Analysis Workspace Debugger is changing to adobeTools.debug.includeOberonXml on **June 13, 2019**. adobe.tools.debug.includeOberonXml will cease to function after that date. |
| Mobile browser version numbers | February 7, 2019 | Starting January 8, 2019, we changed the truncation level for mobile browser version numbers from 2 to 1. From that date forward, versions only display the first two levels (e.g. _Firefox 64.0.2_ is now reported as _Firefox 64.0_). |
| End of life for [!DNL Ad Hoc Analysis] | January 29, 2019 | On August 6, 2018, Adobe announced the intention to end-of-life [!DNL Ad Hoc Analysis]. An end-of-life date will be shared once available.<br/>For more information, including which versions of Java will be compatible during this period, visit [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | January 14, 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Data Feed: post_product_list column - size change | January 9, 2019 | On February 7, 2019, Adobe expanded the size of the post_product_list column from 64 KB to 16 MB. This change ensures that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values. If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| Management changes affecting inactive [!DNL Analytics Live Stream] endpoints | December 20, 2018 | Starting on February 1, 2019, [!DNL Live Stream] endpoints with no active consumer connections for 90 days may be disabled. You can reach out to Customer Care to inquire about your [!DNL Live Stream] endpoints and, if necessary, have them re-enabled. In addition, please ensure your consumer processes maintain a persistent connection, as intended by the design of the service, and that they are implemented to reconnect when the connection is disconnected or interrupted. |
| Update Adobe [!DNL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that [!DNL Report Builder] users download version v5.6.21 prior to February 2019. After that date, prior versions of [!DNL Report Builder] will no longer function. |
|Privacy Service API: CCPA|The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br><br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br><br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out from the selling of personal data.<br><br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md)|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Fixes and features added to Audience Manager.

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
