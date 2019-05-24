---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: June 2019
author: mfrei

---

# Adobe Experience Cloud release notes

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE]
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

**Release date: June 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform release notes

Version number: x.x

* See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) on Adobe.io for the latest updates to Experience Platform.

### Experience Platform Launch

* See [Experience Platform Launch](https://docs.adobelaunch.com/) for the latest information.

### Experience Cloud ID Service

Releasing **June 2019**

* 
* 
* 

## Analytics {#analytics}

New features and fixes in Adobe Analytics:

* [New features and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)

For product documentation, see [Analytics Help Home](https://marketing.adobe.com/resources/help/en_US/reference/).

### New features and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |  
| **AppMeasurement** | Features |
| **Analysis Workspace:**   |  |  
| **Ad Hoc Analysis:**   |  |
| **Data Collection:** |  |

**Analysis Workspace Fixes**

* 
* 
* 
* 

**Other Analytics Fixes**

* 
* 
* 
* 

### Important notices for Analytics administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|Upcoming change to _Report Total_ calculations | April 16, 2019 | On **June 13, 2019**, Adobe Analytics will make _Report Total_ calculations consistent across all dimensions and metrics. This will result in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 13, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API. |
| Update to CSV downloads from Analysis Workspace| April 10, 2019 | Starting on April 11, 2019, several changes will be made to CSV downloads (and Copy to Clipboard) from Analysis Workspace to remove formatting from exported data.  <ul><li>The thousands separator will no longer be included. The decimal separator will continue to be included, and will adhere to the format defined under **Components** > **Report Settings** > **Thousands Separator**. Note: Numeric values that use a comma as the decimal separator will continue to be quoted in the exported CSV.</li><li>No currency symbols will be shown.</li><li>No percent symbols will be shown. Percentages will be in decimal form. E.g., 75% will be represented as 0.75.</li><li>Time will be shown in seconds.</li><li>Cohort tables will show raw values only; percentages will be removed.</li><li>If a number is invalid, an empty cell will be displayed.</li></ul>|
| Upcoming change to the Analysis Workspace Debugger command | April 4, 2019 | The Console command to turn on the Analysis Workspace Debugger is changing to adobeTools.debug.includeOberonXml on **June 13, 2019**. |
| Upcoming support changes for Date-Enabled and Numeric Classifications | February 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change will take effect with the June 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
| Significantly updated the documentation on the getPercentPageViewed plug-in. | February 12, 2019 | [https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html) |
| Admin > General Account Settings |  February 7, 2019| * The setting _Replace the last octet of IP addresses with 0_ is enabled by default for any new report suites created in the London Data Center after January 2019, but only if the settings for those report suites are copied from a template listed in the Admin Console. Report suites whose settings are duplicated from other report suites inherit all settings from the selected report suite.<br/> * The setting _IP Obfuscation_ is no longer enabled by default for all customers with a report suite set in EMEA. |
| Mobile browser version numbers | February 7, 2019 | Starting January 8, 2019, we changed the truncation level for mobile browser version numbers from 2 to 1. From that date forward, versions only display the first two levels (e.g. _Firefox 64.0.2_ is now reported as _Firefox 64.0_). |
| End of life for Ad Hoc Analysis | Updated January 29, 2019 | On August 6, 2018, Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available.<br/>For more information, including which versions of Java will be compatible during this period, visit [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Short Analytics report links | January 14, 2019 | Any short Analytics report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| End of Support for TLS 1.0 | Updated January 10, 2019 | On February 11, 2019 Adobe Analytics reporting will no longer support TLS (Transport Layer Security) 1.0 encryption. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. If you are unable to connect to Adobe Analytics reporting after February11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Beginning February 20, 2019 Adobe Analytics data collection will no longer support TLS 1.0. With this change, Adobe will no longer collect Analytics data from end users with older devices or web browsers that do not support TLS 1.1 or later. We do not expect this to have a significant impact on customer data or reporting. (If your website already does not support TLS 1.0, you will not be affected.) <br/>Beginning April 11, 2019, the Adobe Analytics Reporting API will no longer support TLS 1.0 encryption. Customers who access the API should verify that they will not be impacted. <ul><li>API clients using Java 7 with default settings will need [modifications to support TLS 1.2](https://www.java.com/en/configure_crypto.html). (Refer to _Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_.) </li><li>API clients using Java 8 should not be impacted because the default setting is TLS 1.2.</li><li> API clients using other frameworks will need to contact their vendors for details on TLS 1.2 support.</li></ul>|
| Update Adobe Report Builder due to end of support for TLS 1.0 | September 7, 2018 | Due to the end of support for TLS 1.0, we recommended that Adobe Report Builder (ARB) users download ARB v5.6.21 prior to February 7, 2019. **After that date, prior versions of ARB no longer function.** |
| Update to CSV downloads from Analysis Workspace | January 9, 2019 | Starting on February 7, 2019, CSV downloads (and Copy to Clipboard) from Analysis Workspace will no longer include the thousands separator. Note: The Analysis Workspace UI will continue to show the thousands separator. Additionally, the decimal separator will continue to be included, and will adhere to the format defined under **[!UICONTROL Components]** > **[!UICONTROL Report Settings]** > **[!UICONTROL Thousands Separator]**. |
| Data Feed: post_product_list column - size change | January 9, 2019 | On February 7, 2019, Adobe plans to expand the size of the post_product_list column from 64 KB to 16 MB. This change is intended to ensure that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values. If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| Management changes affecting inactive Analytics Live Stream endpoints | December 20, 2018 | Starting on February 1, 2019, Live Stream endpoints with no active consumer connections for 90 days may be disabled. You can reach out to Customer Care to inquire about your Live Stream endpoints and, if necessary, have them re-enabled. In addition, please ensure your consumer processes maintain a persistent connection, as intended by the design of the service, and that they are implemented to reconnect when the connection is disconnected or interrupted. |
| Dallas FTP server migration (ftp2.omniture.com) | October 19, 2018 | On October 23, 2018, if you connect to ftp2.omniture.com via the SFTP protocol, you might be required to re-accept the SJ1 site's host identifier. This issue applies only to October 23. See [Upgrading Adobe FTP Servers](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/ftp_upgrade.html). |
| Update to Mobile Device dimension | October 16, 2018 | On September 26, Adobe updated its device lookup to Device Atlas's 2.1 API. This caused more detailed devices (e.g. Apple iPhone 7, Apple iPhone 8 Plus, etc.) to appear in the Mobile Device dimension for some browsers. This new level of device detail should be used directionally as is does not extend to all devices and browser types at this time. |
| End of support for Internet Explorer 11 | Sept. 12, 2018 | Adobe will end support for Internet Explorer 11 within Adobe Analytics on November 13, 2018. Please switch to Microsoft Edge or another supported browser as soon as possible. |
| End of life for Ad Hoc Analysis | August 9, 2018 | On August 6, 2018, Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). We will not modify [!UICONTROL Ad Hoc Analysis] to support Java 9+ from this point forward. If you upgrade to Java 9+, [!UICONTROL Ad Hoc Analysis] will cease to function. Only Java 8 will be supported. |
| Update Adobe [!UICONTROL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that [!UICONTROL Report Builder] (ARB) users download ARB v5.6.21 prior to February 2019. After that date, prior versions of ARB will no longer function. |
| New help for the Analytics user migration | May 10, 2018 | We updated the Analytics user ID migration help with information about migrating Enterprise and Federated IDs to the Admin Console. See [Migrate Analytics user accounts for Enterprise and Federated IDs](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html). |
| Upcoming removal of Account Activity Report | May 10, 2018 | The Account Activity Report will be replaced by the Server Call Usage feature in the Adobe Analytics Summer Release. The Account Activity Report will be permanently removed on August 9, 2018. To view summary data about report suite traffic after August 9, 2018, use the Server Call Usage feature. |
| Changes to linear allocation models in Calculated Metrics | Effective July 19, 2018 | On July 19th, Adobe Analytics will revise the way allocation models in calculated metrics are evaluated. As part of this change, calculated metrics that use a non-default allocation model will be migrated to new and improved attribution models. [!UICONTROL Marketing Channel Last Touch] and [!UICONTROL Marketing Channel First Touch] allocation models will be migrated to new [!UICONTROL Last Touch] and [!UICONTROL First Touch] attribution models  espectively. ([!UICONTROL Marketing Channels] are not being deprecated, only the two allocation models that appear in calculated metrics). Additionally, we will correct the way linear allocation is calculated. If you use calculated metrics with linear allocation models, the reports may change slightly to reflect the new, corrected attribution model. This change to calculated metrics will be reflected in [!UICONTROL Analysis Workspace], [!UICONTROL Reports & Analytics], the [!UICONTROL Reporting API], [!UICONTROL Report Builder], and [!UICONTROL Ad Hoc Analysis]. See the [Calculated Metrics](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html) documentation for more information about this change. |
| [!UICONTROL Anomaly Detection] and [!UICONTROL Contribution Analysis] functionality removed from [!UICONTROL Reports & Analytics] | April 10, 2018 | Anomaly Detection and Contribution Analysis have been removed from the Reports & Analytics feature set and are now available only via Analysis Workspace. Adobe Analytics Select and Foundation customers have access only to “daily-granularity” Anomaly Detection in Workspace. |
| Adobe no longer issuing 3rd-party s_vi cookies for Safari | April 05, 2018 | On March 20, 2018, Adobe stopped issuing third-party s_vi cookies for the Safari browser. This change does not impact customers using first-party data collection cookies. This change also removes the visit and visitor inflation experienced by some customers, resulting from Safari ITP. |
| Back-end changes that affect reporting | April 11, 2018 | A change to the (back-end) lookup mechanism is going to impact reporting in several ways. Please be aware that these changes went into effect around the end of February, 2018: Page renaming will no longer be allowed. Going forward, you will need to use classifications to rename pages. Until the May 10, 2018 release, the system will continue to process the renamed pages as they are currently configured. Adobe is asking all customers to migrate to classifications by that date. After the May release, existing renames will no longer be honored and can change, retroactively, without notice. <br/>The URL replacement methodology is different. Previously, Adobe Analytics would store (mostly) the first URL associated with each page name each month. Going forward, we will store the most recent URL for each page name. (Updated April 11, 2018) Category reports for roll-ups and current data in Reports & Analytics are no longer provided. Deprecating category roll-up reports in the Web Service API is effective with the May 10, 2018, Adobe Analytics maintenance release. There is no longer any support for page/prop data from before approximately January 2007 (in some cases, 2006). This only impacts pages, props and page events (i.e. custom links, exit links, download links). Note: This change does not impact reporting in Analysis Workspace or Data Warehouse. If you have data preceding these dates, expect the following: Data will not combine correctly across the pre/post January 2007 boundary. Searches will not work against data before approximately Jan. 2007. |
| Upcoming support changes for Date-Enabled and Numeric Classifications | May 7, 2018 | In the May 10, 2018 Maintenance release, we will begin limiting the functionality of date-enabled and numeric classifications. These classification types will be removed from the Admin and Classification Importer interfaces. From that date on, no new date-enabled and numeric classifications can be added. Existing classifications can still be managed (uploaded to, deleted) through the standard classification workflow, and will continue to be available in reporting. |
| Upcoming support changes for Marketing Channel Cost and Budget | February 28, 2018 | In the April maintenance release, we will remove Marketing Channel Cost and Budget from the Admin > Marketing Channel menu. No new cost and budget data can be added. Existing cost and budget data will continue to be available in reporting, but cannot be updated. |
| Update Report Builder before you migrate user IDs to the Admin Console | March 17, 2018 | **Important:** Update your installation of Report Builder to the latest version. This update is a pre-requisite for running the Analytics user ID migration to the Admin Console, beginning in April 2018. |
| Code Manager - Legacy H Code | February 8, 2018 | Downloading legacy JavaScript (H code) from the Code Manager is no longer supported. |
| Data retention: Check and set your data retention policy for Adobe Analytics | February 1, 2018 | **Background:** The European Union’s General Data Protection Regulation (GDPR), which applies as from May 25, 2018, provides that Adobe, in its role as your data processor, must take appropriate measures to assist its customers in fulfilling access, deletion, and other requests from individuals. Applying appropriate, secure, and timely deletion policies is an important part of complying with this obligation. As a result, Adobe would like to work with you to implement a data retention policy before GDPR takes effect on May 25, 2018.<br/>**What to expect:** Unless you already have an Adobe Analytics data retention policy in place, Adobe will begin applying data retention as currently specified in customer contracts for Adobe Analytics, unless other arrangements are made. Most Adobe Analytics contracts state that Adobe may delete data after 25 months. Once a data retention policy is in place for your organization, it is enforced on a rolling monthly basis. Data retention for longer periods than 25 months is available for an additional fee. Data retention periods for shorter periods can also be configured by contacting Customer Care. You will soon receive an email with additional details for your organization. <br/>Data retention impacts all methods for accessing historical Adobe Analytics data, including but not limited to Reports & Analytics, Analysis Workspace, Report Builder, the Web Services Reporting APIs, data warehouse, and data feeds. **Next steps:** Identify stakeholders within your organization responsible for making decisions about data retention. Your organization is best placed to know the appropriate period for which Adobe Analytics data should be retained. Contact your Adobe Customer Success Manager if you have questions regarding data retention for Adobe Analytics. |
| User account linking | October 26, 2017 | Analytics users no longer need to manually link their accounts between the Experience Cloud and Analytics. Users can contact their Admin Console administrator to request Analytics access. The Analytics user ID migration enables administrators to easily migrate user accounts from Analytics User Management to the Adobe Admin Console. After your users are migrated, they will have access to the purchased solutions and core services available in the Experience Cloud. [Learn more about the Analytics User ID Migration](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/). |

## Audience Manager {#aam}

| Feature    | Description  |
| -----------| ---------- |  
|  |  |  
|  |  |

**Fixes, Enhancements, and Deprecations**

* 
* 
* 

## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

**AEM version**

Text

* [What's New in Adobe Experience Manager 6.5](https://www.adobe.com/marketing/experience-manager/new.html)
* [Release Notes for Adobe Experience Manager 6.5](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Feature**

Text

### Product maintenance

**AEM version**

Text

**Feature**

Text

### Self-Help

**Feature**

Text

**Feature**

Text

### Additional resources

* [AEM 6.5 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older versions of AEM documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System release notes](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre release notes](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

Text

See [Adobe Campaign Classic Release Notes](http://docs.campaign.adobe.com/doc/AC/en/RN.html) for fixes and improvements.

For product documentation, see:

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Feature    | Description  |
| -----------| ---------- |  
|  |  |
|  |  | 

## Target Standard/Premium {#target}

This release includes the following features, changes, and enhancements:

(The issue numbers in parentheses are for internal Adobe use.)

### Feature updates

|Feature / Enhancement | Description |
| --- | --- |
| | |
| | |
| | |

### Enhancement, fixes, and changes

* Toolbar icons display appropriately after you cancel loading of a page within the VEC. If specific actions cannot be performed until after the page is fully loaded, the associated toolbar icons are disabled. (TGT-33811)
* You can now list and navigate more easily through offer folders in the Asset picker instead of navigating through a flat folder hierarchy. (TGT-33725)

Refer to the [Adobe Target Release Notes](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release information about the following products:

* Target Standard and Premium
* Recommendations Classic

## Magento {#magento}

Magento is an e-commerce platform that provides online merchants with a flexible shopping cart system and control over the look, content and functionality of their online store. Magento is available in an open-source version and a fuller-featured commerce version.

Magento Commerce is part of Adobe Commerce Cloud and offers an eCommerce solution with enterprise power, unlimited scalability, and open-source flexibility for B2C and B2B experiences

Release notes for both our Open Source and Commerce editions can be found on the [Release Information](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) page.

## Primetime {#primetime}

Adobe Primetime is a multiscreen TV platform that helps media companies create and monetize engaging, personalized viewing experiences.

[Primetime Release Notes](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime Help Home](http://help.adobe.com/en_US/primetime/)
