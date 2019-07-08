---
title: Adobe Experience Cloud Release Notes
description: July 2019 Experience Cloud release notes
doc-type: release notes
last-update: July 2019
author: mfrei
---

# Adobe Experience Cloud release notes

New features and fixes in the Adobe Experience Cloud.

>[!NOTE]
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

**Release date: July 18, 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Experience Cloud core services and administration {#experiencecloud}

Release notes for the Experience Cloud interface, including [!UICONTROL Platform] core services and product administration.  

* [Core services](#core-services)
* [Experience Cloud ID Service](#ecid)
* [Mobile Services and Mobile SDK](#mobile)
* [Administration and developer](#admin)
* [Launch, by Adobe](https://docs.adobelaunch.com/) (links to product help)

### Core services {#core-services}

Features and fixes.

For product documentation, see [Experience Cloud and Core Services](https://marketing.adobe.com/resources/help/en_US/mcloud/)

### Experience Cloud ID Service {#ecid}

Features and fixes.

For product documentation, see [Experience Cloud ID service](https://marketing.adobe.com/resources/help/en_US/mcvid/).

### Mobile Services and Mobile SDK {#mobile}

**Features**

Description of new features. Use headings or a table.

**Fixes**

* Fix
* Fix
* Fix
* Fix

For product documentation, see [Mobile Services](https://marketing.adobe.com/resources/help/en_US/mobile/).

For more information about the Mobile SDKs, see: [Android SDK 4.x for Experience Solutions](https://marketing.adobe.com/resources/help/en_US/mobile/android/) and [iOS SDK 4.x for Experience Cloud
Solutions](https://marketing.adobe.com/resources/help/en_US/mobile/ios/).

### Administration and developer {#admin}

Features and fixes.

For product documentation, see [Experience Cloud ID service](https://marketing.adobe.com/resources/help/en_US/mcvid/).

## Analytics {#analytics}

* [New features and fixes in Adobe Analytics](#aa-features) 
* [Important notices for Analytics administrators](#aa-notices)
* [Media Analytics SDK for iOS & Android (formerly VHL SDK)](#aa-va)

### New features and fixes in Adobe Analytics {#aa-features} 

For product documentation, see [Analytics Help Home](https://marketing.adobe.com/resources/help/en_US/reference/).

| Feature/Enhancement    | Description  |
| -----------| ---------- |  
| Feature A  | Text |  
| Feature B  | Text |
| Feature C  | Text |

### Important notices for Analytics administrators {#aa-notices} 

* Note
* Note
* Note
* Note

### Media Analytics SDK for iOS & Android (formerly VHL SDK) {#aa-va}

| Feature    | Description  |
| -----------| ---------- |  
| Feature A  | Text |  
| Feature B  | Text |
| Feature C  | Text |

### Data Workbench {#aa-dwb}

See [Data Workbench release notes](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/) for the latest information.

### AppMeasurement {#appm}

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

See [AppMeasurement release history](https://marketing.adobe.com/resources/help/en_US/sc/appmeasurement/release/index.html) for a release history of AppMeasurement on the following platforms:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight, and .NET
* BlackBerry
* Java
* PHP
* Symbian

## Audience Manager {#aam}

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

## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

**Cloud Manager 2019.6.0**

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Release Notes for Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**XML Documentation 3.4**

The XML Documentation 3.4 solution is now available.

***Release notes***
	
* Support added for AEM 6.5.
* Editor changes:
    * Map level preview.
    * Tables - provided an option to copy an <entry> or a complete <row> within a table using copy and paste.
    * Tables - provided an option to select multiple cells in a column and straddle or merge them.
    * Tables - provided a way to set table column properties in the Author mode of the web editor.
    * Tables - provided a way to adjust column proportions and size in a standard table.
    * Tables - Selecting rows and columns in Author view.
    * Tables - Enabled styles and properties (align, valign) in web editor for table cell alignment.
    * Bug fixes to the Full Tags View including scenarios for copy and paste and drag and drop of content.
    * Show topic titles in Editor tabs.
    * Resolved performance issues in the web editor.
* Transfer baseline to the translated content during translation.
* Transfer condition preset during translation workflow.
* Added ability to apply labels to all dependents of a map from baseline.
* Provided a button to download the map with all the dependents as a zip.
* XHTML to DITA conversion improvements to the following:
    * The name of the generated DITAMAP is now identical to the name of the uploaded zip file.
    * Added support for additional HTML elements and attributes.
    * Support for concurrent html-zip file ingestion.
    * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* Provided audit logs to see who reverted to what version and why.
* AEM Site regeneration:
    * Disable regeneration for sub-maps.
    * Post generation workflows enabled for regeneration use cases.
    * Disable the regenerate option for a chunked topic and make the option available for parent topic where chunked attribute is applied.
* DITA search now works on AND logic in AEM Asset search.
* Results to not bring up the temporary files stored in the translation output folder.
* Baseline tab:
    * Performance improvements when opening a baseline.
    * Choosing topics by date to work on the client timestamp.
* API for deleting labels.

### Product maintenance

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1–Cumulative Fix Pack 20 (6.2.1.20), released June 6, 2019, is an important update that includes key customer fixes released since the general availability of AEM 6.2 SP1 December, 2016.

* [Release Notes](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html) 
* [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM 6.3.3.5, released July 3, 2019, is an important update that includes key customer fixes released since the general availability of AEM 6.3 April, 2017.

* [Release Notes](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0 **

AEM 6.4.5.0, released July 3, 2019, is an important update that includes key customer fixes released since the general availability of AEM 6.4 in April, 2018.

* [Release Notes](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM Forms CFP releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0** 

AEM 6.5.1.0, released July 3, 2019, is an important update that includes key customer fixes released since the general availability of AEM 6.5 in April, 2019.

* [Release Notes](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM Forms CFP releases]https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Self-help

**AEM cache invalidation update**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

### Additional resources

* [AEM 6.5 Learn & Support Home](https://helpx.adobe.com/support/experience-manager/6-5.html)
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

* Adobe Campaign Classic [19.1.2](http://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

For product documentation, see:

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

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
