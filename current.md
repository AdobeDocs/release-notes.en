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
| Upcoming support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Updated May 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change will take effect with the July 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
|Upcoming change to _Report Total_ calculations | Updated May 2, 2019 | On **June 13, 2019**, Adobe Analytics will make _Report Total_ calculations consistent across all dimensions and metrics. This will result in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 13, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API. |
| Update to CSV downloads from [!DNL Analysis Workspace]| April 10, 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from [!DNL Analysis Workspace] to remove formatting from exported data.  <ul><li>The thousands separator is no longer included. The decimal separator will continue to be included, and will adhere to the format defined under **[!UICONTROL Components > Report Settings > Thousands Separator]**. Note: Numeric values that use a comma as the decimal separator will continue to be quoted in the exported CSV.</li><li>No currency symbols will be shown.</li><li>No percent symbols will be shown. Percentages will be in decimal form. E.g., 75% will be represented as 0.75.</li><li>Time will be shown in seconds.</li><li>Cohort tables will show raw values only; percentages will be removed.</li><li>If a number is invalid, an empty cell will be displayed.</li></ul>|
| Upcoming change to the [!DNL Analysis Workspace] Debugger command | April 4, 2019 | The Console command to turn on the [!DNL Analysis Workspace] Debugger is changing to adobeTools.debug.includeOberonXml on **June 13, 2019**. adobe.tools.debug.includeOberonXml will cease to function after that date. |
| Mobile browser version numbers | February 7, 2019 | Starting January 8, 2019, we changed the truncation level for mobile browser version numbers from 2 to 1. From that date forward, versions only display the first two levels (e.g. _Firefox 64.0.2_ is now reported as _Firefox 64.0_). |
| End of life for [!DNL Ad Hoc Analysis] | January 29, 2019 | On August 6, 2018, Adobe announced the intention to end-of-life [!DNL Ad Hoc Analysis]. An end-of-life date will be shared once available.<br/>For more information, including which versions of Java will be compatible during this period, visit [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Short Analytics report links | January 14, 2019 | Any short Analytics report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| End of Support for TLS 1.0 | Updated January 10, 2019 | As of February 11, 2019 Adobe Analytics reporting no longer supports TLS (Transport Layer Security) 1.0 encryption. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> As of February 20, 2019 Adobe Analytics data collection no longer supports TLS 1.0. With this change, Adobe no longer collects Analytics data from end users with older devices or web browsers that do not support TLS 1.1 or later. We do not expect this to have a significant impact on customer data or reporting. (If your website already does not support TLS 1.0, you will not be affected.) <br/>Beginning April 11, 2019, the Adobe Analytics Reporting API no longer supports TLS 1.0 encryption. Customers who access the API should verify that they will not be impacted. <ul><li>API clients using Java 7 with default settings will need [modifications to support TLS 1.2](https://www.java.com/en/configure_crypto.html). (Refer to _Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2_.) </li><li>API clients using Java 8 should not be impacted, because the default setting is TLS 1.2.</li><li> API clients using other frameworks will need to contact their vendors for details on TLS 1.2 support.</li></ul>|
| Data Feed: post_product_list column - size change | January 9, 2019 | On February 7, 2019, Adobe expanded the size of the post_product_list column from 64 KB to 16 MB. This change ensures that merchandising eVar values added to post_product_list during processing do not cause truncation of product and revenue values. If you have processes that ingest post_product_list values, please ensure those processes can handle values up to 16 MB in length, or will truncate the value at 16 KB to avoid data ingestion failures. |
| Management changes affecting inactive [!DNL Analytics Live Stream] endpoints | December 20, 2018 | Starting on February 1, 2019, [!DNL Live Stream] endpoints with no active consumer connections for 90 days may be disabled. You can reach out to Customer Care to inquire about your [!DNL Live Stream] endpoints and, if necessary, have them re-enabled. In addition, please ensure your consumer processes maintain a persistent connection, as intended by the design of the service, and that they are implemented to reconnect when the connection is disconnected or interrupted. |
| Update Adobe [!DNL Report Builder] due to end of support for TLS 1.0 | Sept. 7, 2018 | Due to the end of support for TLS 1.0, we recommended that [!DNL Report Builder] users download version v5.6.21 prior to February 2019. After that date, prior versions of [!DNL Report Builder] will no longer function. |

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
