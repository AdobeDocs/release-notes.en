---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: October 2019
author: mfrei

---

# Early Access - Experience Cloud Release Notes - October 2019

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>
>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. New information published after the release will be marked with the publication date.

## Release date: October 10, 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Release notes for the Experience Platform, Experience Platform Launch, Identity Service, and security bulletins.  

* [Experience Platform Launch](#launch)
* [Security bulletins and advisories](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

New features and fixes in Adobe Analytics:

* [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |  
|Privacy Service API: CCPA|The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br><br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br><br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out of the selling of personal data.<br><br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/>CCPA in Analytics: (content forthcoming) <br><br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md)|
|Privacy Reporting: Analytics Admin Console|Enabling Privacy Reporting for Analytics adds a set of reserved variables to a report suite.  The variables are designed to assist in the collection of consumer consent data at a hit level.<br/>New Dimensions:<br/><ul><li>Consent Management Opt-Out</li><li>Consent Management Opt-In</li><li>Consent Management Variables: <!-- `[Link to new Consent Variables page in Analytics]()` --></li></ul>|
|Audio and Video Analytics: Privacy Support|Two new variables have been added to the Media Collection API:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul>These are optional variables that can be used to capture the status of a consumer’s consent at the time of the hit. [Media Collection API Documentation](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>The new Analytics Consent Management context data variables have been added to the Federated Analytics form. These variables are now available for use in flagging Opt Out of Sharing or Selling hits for federation. [Download Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form)|
|Analysis Workspace: Update to Freeform table totals|Freeform tables now include two totals, a **[!UICONTROL Table total]** and a **[!UICONTROL Grand total]**. The Table total row accounts for [report filters](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applied. Previously, only segmentation impacted totals. [Learn more](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>In addition, **[!UICONTROL Show Totals]** and **[!UICONTROL Show Grand Total]** options have been added to **[!UICONTROL Column Settings]**.<br/>With this change to Freeform totals, dependent visualizations will be updated (e.g. linked **[!UICONTROL Summary Number]** visualizations), as well as exported CSV and PDF data. |
|Analysis Workspace: Option to remove Unspecified/None|The ability to easily remove ‘Unspecified (None)’ has been added as an option to report filters.|
|Analysis Workspace: Deprecation of purple granularity components|Purple granularity time components (Minute, Hour, Day, Week, Month, Quarter, Year) have been deprecated. The purple time components have always behaved exactly like their orange dimension counterparts, so this change will simplify the experience. **No action** needs to taken if you previously used one of the purple time components.<br/>With this change, the purple **[!UICONTROL Time]** section has also been renamed to **[!UICONTROL Date Ranges]**.|

#### Fixes

* Analysis Workspace: Fixed an issue that resulted in incorrect search results when searching for dimension items in the left rail. (AN-185065)
* Fixed issues with being unable to delete or unpublish shared segments in Adobe Audience Manager (AAM). The fix is to not delete the segment if AAM is unresponsive. (AN-185882, AN-185883, AN-184607)
* Fixed a timeout issue with being unable to load segments in Ad Hoc Analysis. (AN-184654)
* Fixed an issue that occurred when the report suite you last used was subsequently hidden or you no longer had permissions to access this report suite. In this case, you could no longer log in through Experience Cloud. (AN-181777)
* Fixed a timeout issue in segments that made it difficult to create a VRS based on a segment. (AN-179684)
* Fixed an issue where data was truncated if there was an incorrect encoding in rare cases. (AN-186707)
* Yandex Search Engines are now properly broken out by country. (AN-181728)

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li>|
| Update to Analysis Workspace Freeform Table totals | September 12, 2019 | In October 2019, freeform table total rows will begin accounting for [report filters](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applied. To date, totals have accounted only for segmentation. With this change, dependent visualizations will update (e.g. linked [!UICONTROL Summary Number] visualizations), as well as exported CSV and PDF data.|
|Upcoming change regarding `createDate` field for Analytics users|August 30, 2019|In October or November 2019, the `createDate` field for Analytics users will be updated from US Pacific Time to a correctly formatted date/time value with time zone information. (AN-183468)|
| Support for Historical Timezone Offsets | August 8, 2019 | Analytics will now automatically handle timezone offsets for timestamped hits. Following this change on August 8, systems that load in data for historical processing will no longer need to adjust for timezone offsets before sending in the data. |
| Classification rule builder limits | Added June 5, 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html).|
| New segment operator limits | Added May 31, 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. The limit will be applied to all new and modified segments after this date. Existing segments that exceed the limit will continue to be supported, but cannot be modified or saved until the input field is reduced. These limits are being applied as part of a continued effort to improve query performance. |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Updated May 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change took effect with the July 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
| Change to _Report Total_ calculations | Updated July 9, 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. This resulted in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 18, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API. |
| Update to CSV downloads from Analysis Workspace | April 10, 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>The thousands separator is no longer included. The decimal separator will continue to be included, and will adhere to the format defined under **[!UICONTROL Components > Report Settings > Thousands Separator]**. Note: Numeric values that use a comma as the decimal separator will continue to be quoted in the exported CSV.</li><li>No currency symbols will be shown.</li><li>No percent symbols will be shown. Percentages will be in decimal form. E.g., 75% will be represented as 0.75.</li><li>Time will be shown in seconds.</li><li>Cohort tables will show raw values only; percentages will be removed.</li><li>If a number is invalid, an empty cell will be displayed.</li></ul>|
| Upcoming change to the Analysis Workspace Debugger command | April 4, 2019 | The Console command to turn on the Analysis Workspace Debugger is changing to adobeTools.debug.includeOberonXml on **June 13, 2019**. adobe.tools.debug.includeOberonXml will cease to function after that date. |
| Mobile browser version numbers | February 7, 2019 | Starting January 8, 2019, we changed the truncation level for mobile browser version numbers from 2 to 1. From that date forward, versions only display the first two levels (e.g. _Firefox 64.0.2_ is now reported as _Firefox 64.0_). |
| End of life for [!DNL Ad Hoc Analysis] | January 29, 2019 | On August 6, 2018, Adobe announced the intention to end-of-life [!DNL Ad Hoc Analysis]. An end-of-life date will be shared once available.<br/>For more information, including which versions of Java will be compatible during this period, visit [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | January 14, 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Data Feed: post_product_list column - size change | January 9, 2019 | On February 7, 2019, Adobe expanded the size of the post_product_list column from 64 KB to 16 MB. This change ensures that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values. If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| Management changes affecting inactive [!DNL Analytics Live Stream] endpoints | December 20, 2018 | Starting on February 1, 2019, [!DNL Live Stream] endpoints with no active consumer connections for 90 days may be disabled. You can reach out to Customer Care to inquire about your [!DNL Live Stream] endpoints and, if necessary, have them re-enabled. In addition, please ensure your consumer processes maintain a persistent connection, as intended by the design of the service, and that they are implemented to reconnect when the connection is disconnected or interrupted. |
| Update Adobe [!DNL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that [!DNL Report Builder] users download version v5.6.21 prior to February 2019. After that date, prior versions of [!DNL Report Builder] will no longer function. |

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

New features, enhancements, and fixes in Audience Manager.

**Fixes and Improvements**

* All customer accounts created after July 1st, 2019, will automatically be assigned a [!DNL Tableau] license, providing them access to their reports. If your account was created before July 1st, 2019, and you still do not have access to your [!DNL Tableau] reports, please contact Customer Care.
* We've fixed a bug that caused incorrect generation of activity traits and  artificially increased match rates and audience sizes. Following this fix, you may notice decreases in the size of segments created with auto-generated activity traits. This is normal, expected behavior (AAM-45371).
* We've removed invalid global device IDs from global data sources. See [Global Data Sources](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) to learn what valid device IDs should look like to be accepted by Audience Manager (AAM-41259).
* Fixed a bug causing the Segments page to stop responding when you attempt to delete a protected segment (AAM-49881).
* When editing destinations for Twitter Tailored Audiences, the [!UICONTROL Account] selector is now active only if the destination does not have a [!DNL Twitter Ads] account assigned (AAM-49975).
* Fixed a bug preventing users from disabling [!UICONTROL Audience Marketplace] data feeds when subscriptions are disabled (AAM-49640).
* We made several improvements related to the accessibility of the Audience Manager User Interface.
  
## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product Release

* **Cloud Manager 2019.9.0**

    * Cloud Manager 2019.9.0, released September 12, 2019, updates the security test criteria, adds downloadable monitoring graphs, and fixes some customer-reported usability issues.
    * [Release notes](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Product maintenance

* **AEM 6.3.3.6**

    AEM 6.3, Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 released September 25, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.3, April 2017.
    * [Release notes](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
    * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

    AEM 6.4, Service Pack 6.0 (6.4.6.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.4, April 2018.
    * [Release notes](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
    * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
    AEM 6.5, Service Pack 2.0 (6.5.2.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.5, April 2019.
    * [Release notes](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
    * [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Self-Help

* **Scene7: Reprocess Assets workflow**

    You can now reprocess assets in a folder that already has an existing processing profile that you later changed. 
    See [Reprocessing assets in a folder after you have edited its processing profile](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile).

* **Integration of Dynamic Media Viewers with Adobe Analytics and Adobe Launch**

    The Dynamic Media Viewers extension for Adobe Launch, along with the release of Dynamic Media Viewers 5.13, lets customers of Dynamic Media, Adobe Analytics, and Adobe Launch use events and data specific for the Dynamic Media Viewers in their Adobe Launch configuration.
    See [Integrating Dynamic Media Viewers with Adobe Analytics and Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **AEM desktop app**

    AEM desktop app 2.0 is now available for creatives, marketers, and line-of-business users, to work with AEM Assets.
    See the [AEM desktop app Release notes.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Core Components**
    * Learn about the localization features of Core Components and how they work with AEM templates.
    [See the example](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
    * Core Components 2.6.0 introduces an Experience Fragment Component. The component is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
    * New documentation for visual/similarity search capability.
    See [Find similar images](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch).
    * Connected Assets functionality now uses documents that are available on remote DAM deployment, in addition to images file formats.
    See [Use Connected Assets to share DAM assets in AEM Sites](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html).
    * Fresh content on asset searching and discovery. The _Search assets in AEM_ topic is your one-stop-shop for information on using, configuring, troubleshooting, limitations, and tips.
    See [Search assets in AEM](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html).

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

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.6 update](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) – build 9035

### Additional resources

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
