---
title: Adobe Experience Cloud Release Notes
description: June 2019 Experience Cloud release notes
doc-type: release notes
last-update: June 2019
author: mfrei
---

# Early Access - Adobe Experience Cloud release notes

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
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform release notes

* See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) on Adobe.io for the latest updates to Experience Platform.

### Experience Platform Launch

* See [Experience Platform Launch](https://docs.adobelaunch.com/) for the latest information.

## Analytics {#analytics}

New features and fixes in Adobe Analytics:

* [New features and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices)

For product documentation, see [Analytics Help Home](https://marketing.adobe.com/resources/help/en_US/reference/).

### New features and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |  
| **Segmentation** | New attribution models for dimensions in segmentation:<ul><li>Repeating (Default): Includes instances + persisted values for the dimension.</li><li>Instance: Includes instances for the dimension.</li><li>Non-repeating instance: Includes unique instances (non-repeating) for the dimension.</li></ul>|
| **Segmentation** | New segment operators: **[!UICONTROL Equals Any of]** and **[!UICONTROL Does not Equal Any of]**. |
| **Debugger** | When logged in with your Adobe ID, you now have the option to retrieve post-processed hits in the Experience Cloud Debugger. Post-processed hits are server calls after they have gone through [!UICONTROL Processing Rules] and VISTA Rules, letting you validate [!UICONTROL Processing Rules] and your VISTA rules. **Note**: If you are using A4T (SupplementalDataID) the post-processing data will can take a few minutes to come back. |
| **Analysis Workspace:** | Added new out-of-the-box filters to the left rail search. Beyond what you see today (Dimensions, Metrics, Approved, etc.), new filters such as Calculated Metrics, Customer Attributes, eVars, Props, Video, etc. were added to make it easier to find the components you need. |  

**Analysis Workspace Fixes**

* Fixed an issue with localized Japanese date information in [!DNL Analysis Workspace] visualizations. (AN-180114)
* Fixed an issue that occurred after copying and pasting dimension items. Subsequent searches on the item resulted in an error. (AN-177394)
* Fixed an issue with the edit option missing in segment panels within freeform tables. (AN-171703)
* Fixed an issue with **[!UICONTROL Set as Landing Page]** feature not working when shared with a large set of recipients. (AN-163922)
* Fixed an issue where strings got vertically clipped in Real-time reports. (AN-175980)

**Other Analytics Fixes**

* Fixed an issue with Admin users being unable to enable **[!UICONTROL Success Events]**. (AN-176689)
* Fixed an issue that occurred when creating an alert with the **[!UICONTROL Exit Rate]** metric. (AN-177476)

### Important notices for Analytics administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
| Classification rule builder limits | Added June 5, 2019 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html).|
| New segment operator limits | Added May 31, 2019 | Starting on July 18, 2019, the segment operators "contains any of", "does not contain any of", "contains all of" and "does not contain all of" will be limited to 100 words per input field. The limit will be applied to all new and modified segments after this date. Existing segments that exceed the limit will continue to be supported, but cannot be modified or saved until the input field is reduced. These limits are being applied as part of a continued effort to improve query performance. |
| Upcoming support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Updated May 28, 2019 | The ability to import Numeric 2 and Date-Enabled classifications has been removed from the codebase. This change will take effect with the July 2019 Maintenance Release. If you have Numeric or Date-Enabled columns in your import file, those cells will be silently ignored, and any other data within that file will be imported as normal. <br/>Existing classifications can still be exported through the standard classification workflow, and will continue to be available in reporting. |
| Upcoming change to _Report Total_ calculations | Updated May 2, 2019 | On **June 13, 2019**, Adobe Analytics will make _Report Total_ calculations consistent across all dimensions and metrics. This will result in a change to the totals for some reports (typically, Prop or Customer Attributes reports). Prior to this change, some Report Totals inconsistently included or excluded the _Unspecified_ line item in the total, regardless of whether _Unspecified_ appeared in the report. <br/>As of June 13, 2019, _Unspecified_ will always appear in the report total, even if it does not appear as a line item in the report. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change. This change will affect Analysis Workspace, Reports & Analytics, Ad Hoc Analysis, Report Builder, and the Reporting API. |
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

**Fixes, Enhancements, and Deprecations**

* Audience Manager now only counts active algorithmic models against the usage limit.
* Resolved an issue causing algorithmic model reach not to be displayed for traits that use the corresponding model.
* Resolved an issue causing the contents of trait folders not to be displayed then the folder names contained parantheses and/or brackets.
* Resolved an issue causing trait sorting to fail when selecting only one trait type.
* Resolved an issue causing the trait folder tree to collapse to the [!UICONTROL All traits] view every time you created or update a new subfolder.
* Resolved an issue causing the VIEW_DATASOURCES permission to be required when attempting to delete a partner.
* Resolved an issue causing the [!UICONTROL Search] box in the [!UICONTROL Segments] page to search in all folders instead of the selected one.
* Resolved an issue blocking the [!UICONTROL Exclude Traits] table from being sorted through the header controls, when creating a new algorithmic model.
* Resolved an issue causing Audience Manager to crash when running any report with empty interval dates.

## Experience Manager {#aem}

New features, fixes, and updates in Adobe Experience Manager (AEM). Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance.

### Product releases

**Cloud Manager 2019.5.0**

The latest Cloud Manager release (2019.5.0) does not contain significant functional changes though it delivers a couple of bug fixes.

* [Release Notes for Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**XML Documentation for AEM**

The 3.3 release for the XML Documentation solution is now available. See the following release notes:

***Advanced map features***
* Add topic references by using either drag and drop from the repository view or using the horizontal bar and the element catalog.
* Add metadata on a topic ref, chunk, like nav title, format, scope, and so on.
* Clicking on the topic ref should open the topic in the editor (preview mode if not checked out and disable edit with checkout is enabled).
* Add Topic Head and Topic Group.
* Add bookmaps with Frontmatter (Topics, Preface, book list, notices, and so on) and Backmatter (Topics, Appendices, glossary, and so on).
* In Author mode, broken links are highlighted, breadcrumbs are shown, and Full Tags View is available.
* Ability to set map level attributes.
* Ability to set Title/BookTitle.
* Support for Reltables with the ability to add rel header, columns, drag/drop topics from the map and repository to the rel table, set linking, scope, and other parameters for the links, re-order links within the cell.
* Toolbar widget to insert before, insert after and insert element.
* Highlight if a condition is applied on a topic.
* Ability to edit multiple maps at a time (each map opens as a tab on the same browser).
* In the map panel and the repository view, on hover - show full topic title and file name.

***Full Tags View***

* Insert new tags between two elements.
* Copy and paste tags.
* Drag and drop tags at allowed and not allowed positions within a file.
* Expand and collapse tags.

***DITA-specific search enhancements***

* Provided a serialization tool to reindex selected content
* Users can use `contains` and `exact match` in their search. They can also search using the following parameters. :
    * Asset Metadata. For example, `file name`, `title`, or any custom metadata defined by the customer.
    * DITA Attribute Name and its value. For example, `platform=winOS`.
    * DITA Element Name and its value. For example, `author = Joe Smith`.
    * DITA Element Name and its applied attribute. For example, table with product=SpaceBase attribute name/value pair applied to it.
    * DITA topic and map metadata.
    * DITA information type. For exam[ple, map, topic, concept, and so on.
    * Root Folder Path where the asset is located.
    * Document state.
    * Checked-out status.
    * Modified date range.
    * CQ tags.
* It is possible to create complex queries by combining one or more of the above search parameters.

***Review feature changes***

* Tips for a reviewer:
    * Import all comments and incorporate the changes for on-going reviews before upgrading to the 3.3 build.
    * Ensure that multiple tabs are not open for the editor.
    * Ensure that the Full Tags view is not enabled.
    * Do not switch between Author mode and Source mode while the review is in progress.
* Ability to specify the version of my content which is to be reviewed.
* Ability to choose the versions of the selected topics based on a baseline, date, label or the currently active version, or specify the versions for each of the topics while creating a review.
* Ability to send same topic/map for review multiple times and author can access all reviews in review panel of editor.
* As an initiator, ability to push a later version of the content for the reviewers. The reviewers will get a notification when a new content is pushed for review.
* As an author, user will have the ability to see the review comments for all versions of their content in the review panel of the editor. Authors will be able to filter the comments by version number.
* As an author user will have the ability to view and import comments on an older version of the content in the editor which was under review.

***Miscellaneous***

* Create a new folder, topic, or map from the Repository view.
* View in Assets UI &ndash; Add a menu option for both folders and topics - "View in Assets UI". This option opens the Assets UI where the user can see the content tree on the left and all the files in List view on the right with all the assets menus on the top.
* A Review dashboard is now available as a Tile on the DITA project which tracks the review on a Reviewer Level and a Review Task Level.
* Added ability to convert IDML to DITA.
* Provide API to apply given label on all specified versions in a baseline.
* Enable an event after XHTML/DOCX to DITA conversion is complete. You can use this event to add specialized attributes to the converted content, or for any other custom logic that you need to implement.
* Baseline Performance Tab improvements were made. User needs to run a script on all existing baselines first.
* Enhancements were made to the XHTML to DITA conversion.
* DITA-OT Offloading for Publishing Optimization.
* Fixed sorting on the Type column in List view.
* Ability to now handle cascaded styles in Word to DITA conversion.

### Community

**[Cloud Manager Skill Builder webinar series](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Interested in learning how DevOps processes can simplify daily activities for Adobe Experience Manager management in the cloud? Cloud Manager provides the first-generation of cloud-native functionality for Adobe Experience Manager that enables cloud agility, whether your organization is beginning its DevOps transformation or is looking for strategies to augment existing DevOps processes. 

[In this monthly series](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/), you can learn directly from Adobe’s product team about how to get started and use Cloud Manager features to simplify Adobe Experience Manager management in the cloud.

You will learn the following:
* How to get started on Cloud Manager and setup the CI/CD Pipeline
* How Autoscaling and Transparent Service Delivery work and can simplify Adobe Experience Manager environment management in the cloud
* How to use the Cloud Manager API and integrate existing DevOps processes

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

### Campaign Classic 19.1 Spring Release

| Functionality | Description |
| ------------- | ----------- |
| Control Panel | To increase efficiency in your work as an Admin user, manage settings of your SFTP servers by monitoring storage, whitelisting IP addresses, and installing SSH keys for each instance. Please note Control Panel is only available for customers hosted on AWS as of today. [Log in through the Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/kb/control-panel.html) and the [how-to video](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html). |
| Audit Trail | As admin, increase productivity by monitoring and managing changes made within the Adobe Campaign Classic instance. The Audit Trail will log actions made on Source Schema, Workflow and Option. You can quickly see if an element has been created, modified or deleted.<br>For more information, refer to the [detailed documentation](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) and the [how-to video](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html).|
| Guardrail, Robustness & Scalability | A series of improvements has been added to Campaign Classic. Guardrail, robustness and scalability improvements are listed in [Campaign Classic Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| Secure SMS Messaging (TLS) | Secured SMS is now supported through the Extended Generic SMPP Connector. This allows an encrypted connection to the provider. <br> For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| Compatibility Matrix Update | With this new version, Adobe Campaign now supports the following database systems. Refer to the [Compatibility Matrix](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18c</li><li>MySQL 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>PostgreSQL 11</li></ul>|

See [Adobe Campaign Classic Release Notes](http://docs.campaign.adobe.com/doc/AC/en/RN.html) for fixes and improvements.

### Campaign Standard 19.2 Spring Release

| Functionality | Description |
| ------------- | ----------- |
| Control Panel | To help increase efficiency in your work as an Admin user, you can easily monitor capacity and manage settings of your instances (starting with SFTP servers management). <br> For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/kb/control-panel.html) and the [how-to video](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html). |
| Local notifications | Local notification messaging allows you to inform your users when new data becomes available within their mobile applications, even without having access to the Internet or the mobile application running in the foreground. Local notifications are triggered by a mobile application on a particular time and depending on an event.<br>For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Workflow enhancement - Add a payload to external signal activity | Start a workflow with a payload when defined conditions are successfully met from another workflow or a REST API call to integrate with your external systems. This also includes a new test activity where you can run tests on this functionality. <br>For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) and the [how-to video](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html).|
| Landing Pages enhancement - Google reCAPTCHA | Leverage Google reCAPTCHA to prevent spam on your landing pages without requiring any action from your customers. <br>For more information, refer to the [detailed documentation](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

For product documentation, see:

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Feature videos](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* TLS 1.0 has been disabled on all Adobe servers. For Android 4.x devices to connect to Adobe services through SSL, the SDK will now force TLS 1.1/TLS 1.2 when establishing a handshake.

## Advertising Cloud {#adcloud}

Updated:  June 5, 2019, for June 8 release
 
| Product    | Feature    | Description  |
| -----------| ---------- | ----------  |
| Search Campaigns, Label Classifications, and Constraints | Keyboard shortcuts | You can now use <b>Shift+Click</b> to select multiple, consecutive rows and <b>Ctrl+Click</b> to select multiple, non-consecutive rows. |
|  | Select All vs. Select All on Page | In data tables, when you select the top check box to select all rows, the new default is to select all of the rows on the page (based on whether you're viewing 25 rows, 50 rows, 100 rows, 200 rows, or Continuous Scroll). You still have an option to select all rows available. |  
| Default views, custom views, and stand-alone column customization settings | Column re-ordering | New Up and Down buttons allow you to reorder columns. You can still drag and drop columns to reorder them, like you could previously. |

## Target Standard/Premium 19.6.1 (June 25, 2019) {#target}

Refer to the Adobe Target Release Notes for the latest release information:

[Target release notes (prerelease)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Target release notes (current)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento is an e-commerce platform that provides online merchants with a flexible shopping cart system and control over the look, content and functionality of their online store. Magento is available in an open-source version and a fuller-featured commerce version.

Magento Commerce is part of Adobe Commerce Cloud and offers an eCommerce solution with enterprise power, unlimited scalability, and open-source flexibility for B2C and B2B experiences.

Release Notes for both our Open Source and Commerce editions can be found on the [Release Information](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) page.

## Primetime {#primetime}

Adobe Primetime is a multiscreen TV platform that helps media companies create and monetize engaging, personalized viewing experiences.

[Primetime Release Notes](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime Help Home](http://help.adobe.com/en_US/primetime/)
