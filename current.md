---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
doc-type: release notes
last-update: May 2019
author: mfrei

---

# Adobe Experience Cloud release notes

New features and fixes in the Adobe Experience Cloud.

>[!IMPORTANT]
>>This page contains pre-release content and is subject to change prior to the planned release.

>[!NOTE]
>>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

**Release date: May 2019**

* [Experience Cloud core services and administration](#experiencecloud)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

## Experience Cloud core services and administration {#experiencecloud}

Release notes for the Experience Cloud interface, including [!UICONTROL Platform] core services and product administration.  

* [Launch, by Adobe](https://docs.adobelaunch.com/) (links to product help)

## Analytics {#analytics}

New features and fixes in Adobe Analytics:

* [New Features in Adobe Analytics](#aa-features)
* [Media Analytics SDK for iOS & Android (formerly VHL SDK)](#aa-va)
* [Important notices for Analytics administrators](analytics-important-notices.md)

For product documentation, see [Analytics Help Home](https://marketing.adobe.com/resources/help/en_US/reference/).

### New Features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |  
| **Analysis Workspace:** New _Include Repeat Instances_ Flow visualization setting  | The _Include Repeat Instances_ flow setting gives you the option to include or exclude repeated instances, such as Page Reloads. Additionally, all Flow visualizations are now based on instances only. |  
| **Ad Hoc Analysis:** Compatibility with Java 11  | Ad Hoc Analysis is now compatible with Java 11. Learn how to run [Ad Hoc Analysis on Java 11](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Data Collection:** New s_ecid cookie  | Added a new first-party server cookie, s_ecid, in which data collection stores the visitor's ECID. |

**Analysis Workspace Fixes**

* Fixed an issue affecting Time Spent on Page. Workspace reports will no longer use Page Name when calculating Time Spent buckets, enabling granular and bucketed hits to be counted. (AN-140479)
* Fixed Line visualization performance issues as part of a larger effort to improve Workspace performance. (AN-174878)
* Fixed an issue with lack of UTF-8 encoding in downloaded .csv files. (AN-178393)
* Fixed issues with slow Workspace project performance. (AN-177710)
* Fixed Line visualization display issues with small ranges in the granularity of the y-axis. (AN-176467)

**Other Analytics Fixes**

* Audience Analytics: Fixed an issue that occurred after an audience name was changed in Audience Manager (AAM) – the updated name was not reflected in Audience Analytics. (AN-176237)
* Fixed an issue that prevented users from saving Analytics segments in AAM. This was caused by existing AAM folders with mixed uppercase and lowercase names. We now treat all folders as case insensitive so that they will sync. (AN-177934)
* Fixed an issue that occurred when users logged in to Analytics via the Experience Cloud and then the session timed out. When resuming the session, the user was redirected to a faulty URL. (AN-176812)
* Fixed an issue with time zone offsets in Data Warehouse requests. (AN-177585)

## Audience Manager {#aam}

| Feature    | Description  |
| -----------| ---------- |  
| [IP Address Obfuscation](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html)  | Your company may desire to obfuscate IP address in many countries due to global privacy regulations. Audience Manager allows you to obfuscate visitor IP addresses on a global or country-by-country basis. |  
| [Custom Partner Integrations - Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html)  | This page lists custom integrations between Audience Manager and data partners. Audience Manager ingests cookie and mobile ID data from the Oracle Data Cloud for Audience Marketplace via inbound data files. The custom integration specifications described in this page refer only to inbound data files that contain mobile IDs (IDFA and Android Device IDs). |

**Fixes, Enhancements, and Deprecations**

* We added two new columns to the General Reports for Destinations. You can now see the Start Date and the End Date for a segment mapping to a destination. (AAM-44781)

## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

**Feature name**

Description of features.

**Feature name**

Description.

**Feature name**

Description.

**Core Components**

Description

### Self help

**Collaborative Documentation**

The following AEM documentation sets have been migrated to a new collaborative documentation platform.

* Doc name
* Doc name

### Additional resources

* [AEM 6.4 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Learn & Support home](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager User Guide](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older versions of AEM documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System release notes](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre release notes](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### Livefyre {#livefyre}

| Feature    | Description  |
| -----------| ---------- |  
| Feature A  | Text |  
| Feature B  | Text |
| Feature C  | Text |

**Fixes**

* Fix
* Fix
* Fix
* Fix

## Social {#soc}

| Feature    | Description  |
| -----------| ---------- |  
| Feature A  | Text |  
| Feature B  | Text |
| Feature C  | Text |

**Fixes**

* Fix
* Fix
* Fix
* Fix

## Campaign {#ac}

Adobe Campaign provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences.

* Campaign Classic 18.10.4 – build 8983
* Campaign Classic 18.10.5 – build 8984

See [Adobe Campaign Classic Release Notes](http://docs.campaign.adobe.com/doc/AC/en/RN.html) for fixes and improvements.

For product documentation, see:

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Feature    | Description  |
| -----------| ---------- |  
| Search Tools  | (Advertisers with Google Ads accounts) Advertising Cloud can optionally upload to Google Ads all conversion data it tracks for Google Ads campaigns that use the Advertising Cloud conversion tracking service. Daily uploads include the conversion value defined using the advertiser-level attribution model. All uploaded conversions are prefixed with "Adobe_ACS_" (such as "Adobe_ACS_Subscriptions" for the conversion "Subscriptions"). <br/> **Note:** The uploads won't include conversion data uploaded to Advertising Cloud from feed files. |  
