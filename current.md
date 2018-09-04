---
description: New features and fixes in the Adobe Experience Cloud.
seo-description: New features and fixes in the Adobe Experience Cloud.
seo-title: Adobe Experience Cloud Release Notes
solution: Release Notes,Marketing Cloud,Analytics,Social,Target,Media Optimizer
title: Adobe Experience Cloud Release Notes
topic: Release notes
uuid: c56a1064-0f2c-4241-93c6-ca4b1f267763
index: y
internal: n
snippet: y
translate: y
---

# Adobe Experience Cloud Release Notes

New features and fixes in the Adobe Experience Cloud.


<!-- <p> 
 <note type="important">
   This page contains pre-release content and is subject to change prior to the 
  <b>August 9, 2018</b> release. 
 </note> </p> -->

>[!NOTE]
>
>Subscribe to the[ Adobe Priority Product Update ](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date. 



**August 2018** 

Latest update: **Updated August 9, 2018** 

* [ Experience Cloud and Core Services ](current.md#coreservices)
* [ Analytics ](current.md#analytics) (**August 21, 2018**)
* [ Audience Manager ](current.md#aam)
* [ Target ](current.md#target)
* [ Campaign ](current.md#campaign)
* [ Experience Manager ](current.md#experiencemanager) (and [ Livefyre ](current.md#livefyre))
* [ Advertising Cloud ](current.md#adcoud)
* [ Primetime ](current.md#primetime)

Release notes for the Experience Cloud interface and core services. Includes Mobile Services, Launch, by Adobe, Dynamic Tag Management, GDPR API, and Experience Cloud ID Service. 

<!-- Abhishek Shukla is the contact for this section. -->

* [ Experience Cloud Interface ](current.md#li_DCFCE35581CA4204BE67D2F8CD90FD36)
* [ General Data Protection Regulation (GDPR) API ](current.md#gdpr)
* [ Launch, by Adobe ](current.md#launch)
* [ Dynamic Tag Management ](current.md#dtm)
* [ Experience Cloud Mobile SDKs ](current.md#section_FD57C8A6E37244E6B3E2AEB0222230A6)

## Experience Cloud Interface {#experience_cloud_interface}

New features and fixes in the [!DNL  Adobe Experience Cloud] interface, including Assets, Feed, Notifications, and the People core service. 

**Fixes** 

* Made improvements on assets comment sync across Creative Cloud and Experience Cloud. (CORE-15971)
* Added a feature flag to control Experience Cloud-Creative Cloud asset sync. (CORE-15938)
* Made improvements to Audience segments creation, including better search and listing experience. (CORE-5833, CORE-14278)
* Fixed an issue that blocked folder sharing from the Marketing Cloud to the Creative Cloud. (CORE-16677)
See [ Experience Cloud Product Documentation ](https://marketing.adobe.com/resources/help/en_US/mcloud/) for product help. 

## Launch, by Adobe {#launch}

Launch release notes are updated regularly at [ https://docs.adobelaunch.com/getting-started/release-notes ](https://docs.adobelaunch.com/getting-started/release-notes). 

## Experience Cloud Mobile SDKs {#section_FD57C8A6E37244E6B3E2AEB0222230A6}

Fixes and updates to iOS and Android. 

<table id="table_6DB2F55C955943EB97DC25C96B6DF526"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Feature </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Version <b>4.16.1</b> </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_7CBCBF9FBF3544DDB7B4A5F824A3D322"> 
      <li id="li_6A06C5C3CA3E48C197F03CA6AEA9B4CC"> Analytics - Invalid timed action durations are now ignored. </li> 
      <li id="li_060DC8C1F2AD436E8C5E8576791CE377"> Visitor ID Service - Fixed a bug that prevented the MID from being generated in an unknown privacy setting. </li> 
      <li id="li_34B00AB52F2A47BE8C9C4020A2A30867"> General - Added support to opt-out of the Device Co-op. </li> 
      <li id="li_C6249F498AF04DCD95DA5A6F5D6145F8"> General - Fixed a bug that prevented deep-link URLs with encoded values from being properly handled. </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

Release date: **August 9, 2018** 

* [ Analytics - New Features ](current.md#features_analytics)
* [ Analytics - Fixes and Updates ](current.md#analytics-interface) (**August 8, 2018**)
* [ Analytics - Administration, Implementation, Developer ](current.md#analytics-implement) (**August 21, 2018**)
* [ Important Notices for Analytic Administrators ](current.md#analytics_notices) (**August 9, 2018**)

## New Features in Adobe Analytics {#features_analytics}

Enhancements and new features released in Adobe Analytics. 

<!-- <p>Include only new features for interfaces and reporting tools </p> -->

<table id="table_91D1FD20C4C1411292252364328677AF"> 
 <thead> 
  <tr> 
   <th colname="col01" class="entry"> Product </th> 
   <th colname="col1" class="entry"> Feature Name </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td> <p>Analysis Workspace </p> </td> 
  </tr> 
  <tr> 
   <td colname="col01"> </td> 
   <td colname="col1"> <p>Drop Zone Guides </p> </td> 
   <td colname="col2"> <p>These guides help you more easily understand what each drag-and-drop action does in each visualization. </p> <p> When you drag a component over a visualization, we will show actions like Add, Replace, Filter By, and Breakdown. We also added yellow guides that alert you when you are taking an action that is not recommended, such as stacking two metrics on top of one another (which leads to invalid data). </p> </td> 
  </tr> 
  <tr> 
   <td colname="col01"> </td> 
   <td colname="col1"> <p>Add Blank Panel option </p> </td> 
   <td colname="col2"> <p>We added a + symbol below the last panel to make it easier to add additional panels. </p> </td> 
  </tr> 
 </tbody> 
</table>


## Analytics - Fixes and Updates {#analytics-interface}

Fixes and minor updates applied to Adobe Analytics interface tools and components (Analysis Workspace, Reports &amp;amp; Analytics, Report Builder, and so on). 

<!-- <p>Include topics regarding Analytics &amp;gt; Components or Tools and interfaces. </p> -->

<table id="table_A51B298EEEB5482383505B8C5A79E1B9"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Product </th> 
   <th colname="col2" class="entry"> Fix or Update </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Calculated metrics </p> </td> 
   <td colname="col2"> <p><b> August 8, 2018</b> </p> <p>Fixed an issue that prevented legacy reporting interfaces (such as Reports &amp;amp; Analytics and Report Builder) from running reports using some types of calculated metrics. (AN-165961; AN-162973; AN-166044; AN-165730; AN-165543; AN-165917) </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Analysis Workspace </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_BA4583106C32478FAD127FDC3F0952B6"> 
      <li id="li_E02264FA7CA847FA8C41895B4A33A31B"> Fixed an issue with Donut visualization legends. In some cases, the legends were not displaying or displaying the wrong labels. (AN-164690; AN-164088; AN-164132) </li> 
      <li id="li_F6EF7ABABE1D41A9A365010317A8FB1C"> Fixed an issue that occurred when saving projects as PDFs. This issue resulted in visualizations getting cut off and legends not being visible. (AN-164219; AN-161951) </li> 
      <li id="li_4B53B12964F64A6CAB8439118669F5D5"> Fixed an issue with the Alert Builder interface that caused percentage settings, in some cases, to display in unexpected ways. (AN-163945) </li> 
      <li id="li_C970314340A44FA49091A6091271612F"> Fixed an issue where locking selection on a visualization was sometimes causing the selected granularity or data to change. (AN-164236; AN-162938) </li> 
      <li id="li_DFFBD2139C3646FCBFE3E490885188D0"> Fixed an issue that prevented the download of report suite data for multiple report suites simultaneously. (AN-162551) </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Data Workbench </p> </td> 
   <td colname="col2"> <p><b>Data Workbench 6.73 Updates</b> </p> 
    <ul id="ul_E6A3F8468D5146E1AFB24126A65CDD6F"> 
     <li id="li_AACD9273888D458B84DFCB35504E9D70"> Fixed an issue in Workstation where users were unable to sign in on some hardware with high resolution and high DPI . </li> 
     <li id="li_30534CF7FC7C492B8444F4287AA4613C"> Fixed an issue in server where Email was missing in Archive file names when using IMS login. </li> 
     <li id="li_36783AFCD2C140DD8E130758B9AE6A53"> Updated OpenSSL to version 1.1.0h which includes several vulnerability fixes and new SSL Ciphers. </li> 
     <li id="li_4177993A09DD4D8AB5FF59AE44161933"> Updated other open source libraries used by Data Workbench listed below to latest stable versions: 
      <ul id="ul_5EBCEB05B16E43C4BA988B61B4A29E9C"> 
       <li id="li_B339A0BD6EB4475AA10092ABF8CFA7F3"> libssh2 1.8.0 </li> 
       <li id="li_DD04CA61E84E4D8E87DEC7A312BE366A">Apache Xerces 3.2.1 </li> 
       <li id="li_6B5E4D8905284F05B8714B047B485BEE"> Apache Xalan 1.11 </li> 
       <li id="li_005A317BA95F46888F15DAC908E2432D"> libpng 1.6.34 </li> 
       <li id="li_023BD10AC7024AAEBA17420EB4606E32"> libarchive 3.3.2 </li> 
       <li id="li_80DEA440F6EF41CEA2FF169400C1EAAC"> zlib 1.2.11 </li> 
       <li id="li_A27BA51F3DE74E2E843BAF295CA0D957"> pcre 8.42 </li> 
      </ul> </li> 
     <li id="li_C13931DD23074A5480507CF030AC8302"> Added error logging when Lookup file row count exceeds more than supported 357913908 rows. </li> 
    </ul> <p>See <a href="https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/index.html" format="html" scope="external"> Data Workbench Release Notes </a> for cumulative release information. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Video Analytics </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_qw5_wwn_s2b"> 
      <li id="li_89C3C28C97A6493098DCFF11A2A1497D">Improved accuracy for tracking video ads: Ad tracking now occurs at one second intervals. </li> 
      <li id="li_826566F10CE34A8CAD4303BD24A36CC1">Improved player state management and error recovery: Added additional logic to better support maintaining player states, and to ensure accurate measurement, including identification of the "closed" state. </li> 
      <li id="li_C84E1B3B71DE4BD7916832AEE5B03A66">Enhanced input data validation with better debug logging. </li> 
      <li id="li_273E099082144CF0A95D8584AC396068">Optimized for session end, added a new Heartbeat "end" event. </li> 
      <li id="li_39D32E11E9D34B6DBA92B5EBD871441B">Miscellaneous bug fixes. </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Analytics - Developer, Administration, Data Collection, and Implementation {#analytics-implement}

Fixes and updates applied to Analytics administration tools, including implementation and developer (Web Services and SDKs). 

<!-- <p>Includes any topics under Analytics &amp;gt; Admin and Implementation or data collection items. </p> -->
Updated **August 21, 2018** (removed JavaScript 2.10 update, which occurs in September 2018). 

<table id="table_EB8261E817054C2F8B17C09D16DB3412"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Product / Feature </th> 
   <th colname="col2" class="entry"> Update </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Admin Console </p> </td> 
   <td colname="col2"> <p><b>User Migration:</b> Fixed an issue affecting user accounts after migrating to the Admin Console. (AN-160740; AN-160740; AN-165444; AN-165627) </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> </td> 
   <td colname="col2"> <p><b>Permissions:</b> Fixed an issue where the Report Suite Tools Access permission (Web Services &gt; Data Warehouse) was missing from the list of permissions. (AN-165064) </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> </td> 
   <td colname="col2"> <p><b>Report Suites:</b> Fixed an issue that prevented the download of report suite data for multiple report suites simultaneously. (AN-162551) </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Calculated metrics (localization) </p> </td> 
   <td colname="col2"> <p>Fixed a localization issue affecting some system-generated calculated metrics. (AN-164738) </p> </td> 
  </tr> 
 </tbody> 
</table>


## Important Notices for Analytics Administrators {#analytics_notices}


>[!IMPORTANT]
>
>Review the following table for important Analytics notices that may affect data collection, processing, APIs, product end-of-life, and so on.


<table id="table_E08D11345DD64677B46629651A0FFDBF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Notice </th> 
   <th colname="col02" class="entry"> Date Added or Updated </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>End of life for Ad Hoc Analysis </p> </td> 
   <td colname="col02"> <p>August 9, 2018 </p> </td> 
   <td colname="col2"> <p>On August 6, 2018, Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit <a href="https://spark.adobe.com/page/S9Bhp66VJ2fEn/" scope="external" format="https"> Discover Workspace </a>. </p> <p>We will not modify Ad Hoc Analysis to support Java 9+ from this point forward. If you upgrade to Java 9+, Ad Hoc Analysis will cease to function. Only Java 8 will be supported. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>End of Support for TLS 1.0 </p> </td> 
   <td colname="col02"> <p>July 18, 2018 </p> </td> 
   <td colname="col2"> 
    <ul id="ul_AB20C538470D490298CEEEC586E78DFE"> 
     <li id="li_4B1B15B5CD4E48408AD180A868E4FDCF">To minimize customer impact, we are delaying Adobe Analytics Reporting’s end of support for TLS 1.0 encryption. Starting September 13, 2018, <b>Adobe Analytics Reporting</b> will no longer support TLS (Transport Layer Security) 1.0 encryption. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. Because the Analytics reporting interface already requires a modern web browser, we do not anticipate issues. If you are unable to connect to Adobe Analytics reporting after September 13, you should upgrade your browser <a href="https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html" format="html" scope="external"> to the latest version </a>. </li> 
     <li id="li_2D362B576BB44F7AB607BAC83E82FDF1">Starting September 13, 2018,<b> Adobe Analytics Reporting API</b> will no longer support TLS 1.0 encryption. Customers who access the API should verify that they will not be impacted. 
      <ul id="ul_7AF48F929BEB452B86B9FD1ED384417F"> 
       <li id="li_1FDA77D1F1674330993108E177BA98BE">API clients using Java 7 with default settings will need <a href="https://www.java.com/en/configure_crypto.html" format="html" scope="external"> modifications to support TLS 1.2 </a>. (Refer to “Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2”.) </li> 
       <li id="li_F949D2E426464752A115492480CA5AEC">API clients using Java 8 should not be impacted because the default setting is TLS 1.2. </li> 
       <li id="li_6A422113BF774C07BE856B923B1933F6">API clients using other frameworks will need to contact their vendors for details on TLS 1.2 support. </li> 
      </ul> </li> 
     <li id="li_7644CA61FB6248EBB094E4DC0BCEFE57">Starting September 13, 2018, <b>Adobe Analytics Data Collection</b> will no longer support TLS 1.0. With this change, we will no longer collect Analytics data from end users with older devices or web browsers that do not support TLS 1.1 or later. <p><b>Note:</b> If your web site does not support TLS 1.0, you will not be impacted by the collection change. </p> </li> 
    </ul> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Update Adobe Report Builder due to end of support for TLS 1.0 </p> </td> 
   <td colname="col02"> <p>July 17, 2018 </p> </td> 
   <td colname="col2"> <p>Due to the end of support for TLS 1.0, we recommended that Adobe Report Builder (ARB) users download ARB v5.6.21 prior to September 13, 2018. <b>After that date, prior versions of ARB will no longer function</b>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>New help for the Analytics user migration </p> </td> 
   <td colname="col02"> <p>May 10, 2018 </p> </td> 
   <td colname="col2"> <p>We updated the Analytics user ID migration help with information about migrating Enterprise and Federated IDs to the Admin Console. </p> <p>See <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html" format="html" scope="external"> Migrate Analytics user accounts for Enterprise and Federated IDs </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Upcoming removal of Account Activity Report </p> </td> 
   <td colname="col02"> <p>May 10, 2018 </p> </td> 
   <td colname="col2"> <p>The Account Activity Report will be replaced by the Server Call Usage feature in the Adobe Analytics Summer Release. The Account Activity Report will be permanently removed on August 9, 2018. To view summary data about report suite traffic after August 9, 2018, use the Server Call Usage feature. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Changes to linear allocation models in Calculated Metrics </p> </td> 
   <td colname="col02"> <p>May 10, 2018 </p> <p>Effective <b>July 19, 2018</b> </p> </td> 
   <td colname="col2"> <p>On July 19th, Adobe Analytics will revise the way allocation models in calculated metrics are evaluated. As part of this change, calculated metrics that use a non-default allocation model will be migrated to new and improved attribution models. </p> <p><b>Marketing Channel Last Touch</b> and <b>Marketing Channel First Touch</b> allocation models will be migrated to new <b>Last Touch</b> and <b>First Touch</b> attribution models respectively. (Marketing Channels are not being deprecated, only the two allocation models that appear in calculated metrics). </p> <p>Additionally, we will correct the way linear allocation is calculated. If you use calculated metrics with linear allocation models, the reports may change slightly to reflect the new, corrected attribution model. </p> <p>This change to calculated metrics will be reflected in Analysis Workspace, Reports &amp;amp; Analytics, the Reporting API, Report Builder, and Ad Hoc Analysis. </p> <p>See the <a href="https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html" format="html" scope="external"> Calculated Metrics documentation </a> for more information about this change. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Anomaly Detection and Contribution Analysis functionality removed from Reports &amp;amp; Analytics </p> </td> 
   <td colname="col02"> <p>April 10, 2018 </p> </td> 
   <td colname="col2"> <p>Anomaly Detection and Contribution Analysis have been removed from the Reports &amp; Analytics feature set and are now available only via <a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/virtual-analyst.html" format="html" scope="external"> Analysis Workspace </a>. </p> <p>Adobe Analytics Select and Foundation customers have access only to “daily-granularity” <a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/anomaly_detection.html" format="html" scope="external"> Anomaly Detection </a> in Workspace. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe no longer issuing 3rd-party <span class="filepath"> s_vi </span> cookies for Safari </p> </td> 
   <td colname="col02"> <p>April 05, 2018 </p> </td> 
   <td colname="col2"> <p> On March 20, 2018, Adobe stopped issuing third-party <span class="filepath"> s_vi </span> cookies for the Safari browser. This change does not impact customers using first-party data collection cookies. This change also removes the visit and visitor inflation experienced by some customers, resulting from Safari ITP. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Update Report Builder before you migrate user IDs to the Admin Console </p> </td> 
   <td colname="col02"> <p>March 17, 2018 </p> </td> 
   <td colname="col2"> <p> 
   >[!IMPORTANT]
   >Update your installation of <a href="https://marketing.adobe.com/resources/help/en_US/arb/t_install_arb.html" format="html" scope="external"> Report Builder </a> to the latest version. This update is a pre-requisite for running the Analytics user ID migration to the Admin Console, beginning in April 2018. </p> </p> <p>See <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/" format="https" scope="external"> Analytics User Migration to the Admin Console </a> for migration information.
   </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Back-end changes that affect reporting </p> </td> 
   <td colname="col02"> <p>April 11, 2018 </p> </td> 
   <td colname="col2"> <p>A change to the (back-end) lookup mechanism is going to impact reporting in several ways. Please be aware that these changes went into effect around the <b>end of February, 2018</b>: </p> 
    <ul id="ul_7515E2E79FD94B8F8DFF4C2DBB9E6A84"> 
     <li id="li_F37C29245E064716AE2F3AC9C20A77BC"> Page renaming will no longer be allowed. Going forward, you will need to use <a href="https://marketing.adobe.com/resources/help/en_US/reference/classifications.html" format="html" scope="external"> classifications </a> to rename pages. Until the May 10, 2018 release, the system will continue to process the renamed pages as they are currently configured. Adobe is asking all customers to migrate to classifications by that date. After the May release, existing renames will no longer be honored and can change, retroactively, without notice. </li> 
     <li id="li_14CAB45EC2F2490BB6C8A912C66BB77C"> The URL replacement methodology is different. Previously, Adobe Analytics would store (mostly) the first URL associated with each page name each month. Going forward, we will store the most recent URL for each page name. </li> 
     <li id="li_E46207F194134AEA86F5CB2C8F26C76C">(<b>Updated April 11, 2018</b>) Category reports for roll-ups and current data in Reports &amp; Analytics are no longer provided. Deprecating category roll-up reports in the Web Service API is effective with the May 10, 2018, Adobe Analytics maintenance release. </li> 
     <li id="li_C699A0328CFD4AC4839C481710FE29AA"> There is no longer any support for page/prop data from before approximately January 2007 (in some cases, 2006). This only impacts pages, props and page events (i.e. custom links, exit links, download links). <p>Note:  This change does not impact reporting in Analysis Workspace or Data Warehouse. </p> <p>If you have data preceding these dates, expect the following: </p> 
      <ul id="ul_7CC6A7455BAF4ADCB7A626F2BB8A45B6"> 
       <li id="li_07D957DE7D6D4458AEA8B30910A8E8F9">Data will not combine correctly across the pre/post January 2007 boundary. </li> 
       <li id="li_96D1DF439E2842AE9E2FCF951ADFA9FB">Searches will not work against data before approximately Jan. 2007. </li> 
      </ul> </li> 
    </ul> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Upcoming support changes for Date-Enabled and Numeric Classifications </p> </td> 
   <td colname="col02"> <p>May 7, 2018 </p> </td> 
   <td colname="col2"> <p>In the May 10, 2018 Maintenance release, we will begin limiting the functionality of date-enabled and numeric classifications. These classification types will be removed from the <span class="uicontrol"> Admin </span> and <span class="uicontrol"> Classification Importer </span> interfaces. </p> <p>From that date on, no new date-enabled and numeric classifications can be added. Existing classifications can still be managed (uploaded to, deleted) through the standard classification workflow, and will continue to be available in reporting. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Upcoming support changes for Marketing Channel Cost and Budget </p> </td> 
   <td colname="col02"> <p>February 28, 2018 </p> </td> 
   <td colname="col2"> <p>In the April maintenance release, we will remove Marketing Channel Cost and Budget from the <span class="uicontrol"> Admin </span> &gt; <span class="uicontrol"> Marketing Channel </span> menu. No new cost and budget data can be added. Existing cost and budget data will continue to be available in reporting, but cannot be updated. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Code Manager - Legacy H Code </p> </td> 
   <td colname="col02"> <p>February 8, 2018 </p> </td> 
   <td colname="col2"> <p>Downloading legacy JavaScript (H code) from the Code Manager is no longer supported. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Data retention: Check and set your data retention policy for Adobe Analytics </p> </td> 
   <td colname="col02"> <p>February 1, 2018 </p> </td> 
   <td colname="col2"> <p><b>Background</b> </p> <p>The European Union’s General Data Protection Regulation (GDPR), which applies as from May 25, 2018, provides that Adobe, in its role as your data processor, must take appropriate measures to assist its customers in fulfilling access, deletion, and other requests from individuals. Applying appropriate, secure, and timely deletion policies is an important part of complying with this obligation. As a result, Adobe would like to work with you to implement a data retention policy before GDPR takes effect on May 25, 2018. </p> <p><b>What to expect</b> </p> <p>Unless you already have an Adobe Analytics data retention policy in place, Adobe will begin applying data retention as currently specified in customer contracts for Adobe Analytics, unless other arrangements are made. </p> <p>Most Adobe Analytics contracts state that Adobe may delete data after 25 months. Once a data retention policy is in place for your organization, it is enforced on a rolling monthly basis. Data retention for longer periods than 25 months is available for an additional fee. Data retention periods for shorter periods can also be configured by contacting Customer Care. </p> <p> You will soon receive an email with additional details for your organization. </p> <p>Data retention impacts all methods for accessing historical Adobe Analytics data, including but not limited to Reports &amp;amp; Analytics, Analysis Workspace, Report Builder, the Web Services Reporting APIs, data warehouse, and data feeds. </p> <p><b>Next steps</b> </p> <p>Identify stakeholders within your organization responsible for making decisions about data retention. Your organization is best placed to know the appropriate period for which Adobe Analytics data should be retained. </p> <p>Contact your Adobe Customer Success Manager if you have questions regarding data retention for Adobe Analytics. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>User account linking </p> </td> 
   <td colname="col02"> <p>October 26, 2017 </p> </td> 
   <td colname="col2"> <p>Analytics users no longer need to manually link their accounts between the Experience Cloud and Analytics. Users can contact their <a href="https://helpx.adobe.com/enterprise/help/aedash.html" format="html" scope="external"> Admin Console </a> administrator to request Analytics access. 
     <!--<xref href="https://jira.corp.adobe.com/browse/CORE-5526">https://jira.corp.adobe.com/browse/CORE-5526</xref>--> </p> <p>The Analytics user ID migration enables administrators to easily migrate user accounts from Analytics User Management to the Adobe Admin Console. After your users are migrated, they will have access to the purchased solutions and core services available in the Experience Cloud. </p> <p> <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/" format="https" scope="external"> Learn more about the Analytics User ID Migration </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Notice for API Methods affected by the migration to the Admin Console. </p> </td> 
   <td colname="col02"> <p>September 21, 2017 </p> </td> 
   <td colname="col2"> <p> Adobe will phase out the <span class="codeph"> Permissions </span> and <span class="codeph"> Company.GetLoginKey </span> API methods as part of our effort to migrate user access and management to the Admin Console. </p> <p> All Analytics companies that currently use these methods will receive a pre-migration notification beginning <b>March 31, 2018</b>. After receiving this notification, administrators will have 30 days before their migration starts, and these methods will cease to work for your company. </p> <p> To prepare for this event, view the list of affected APIs, and learn what Adobe recommends, see <a href="https://marketing.adobe.com/developer/documentation/analytics-administration-1-4/admin-api" format="https" scope="external"> Analytics Administration API 1.4 </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Calendar Events: Displaying top 20 most recent events </p> </td> 
   <td colname="col02"> <p>September 21, 2017 </p> </td> 
   <td colname="col2"> <p>To ensure optimal reporting performance, the 20 most recent calendar events will be displayed on trended and overtime graphs. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>geo_zip </p> </td> 
   <td colname="col02"> <p> August 23, 2017 </p> </td> 
   <td colname="col2"> <p> As of August 22, Adobe Analytics started determining <span class="codeph"> geo_zip </span> on all hits received during data collection. This update increases data accuracy, particularly for mobile devices. Previously, the <span class="codeph"> geo_zip </span> was set once per visit. Now, <span class="codeph"> geo_zip </span> can correctly change during a visitor's visit. The <span class="codeph"> geo_zip </span> field is not used in reporting, but surfaces in Data Feeds. </p> </td> 
  </tr> 
 </tbody> 
</table>



<table id="table_A6749BA62D5B40479B949EA1C64E4B7F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Feature </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <a href="https://marketing.adobe.com/resources/help/en_US/aam/instant-cross-device-suppression.html" format="https" scope="external"> Instant Cross-Device Suppression </a> </p> </td> 
   <td colname="col2"> <p>Instant Cross-Device Suppression is the ability to suppress users across multiple devices connected to them when a particular experience occurs on any of these devices. Use the Instant Cross-Device Suppression capability to deliver a consistent experience across devices to your users. </p> <p>This experience is made possible by the real-time unsegment capabilities in Audience Manager. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Fixes, Enhancements, and Deprecations** 

* The **Daily Trait Variation** report is now included in the **Other Reports** section.

Refer to the [ Adobe Target Release Notes ](https://marketing.adobe.com/resources/help/en_US/target/rn/) for the latest release information about the following products: 

* Target Standard and Premium
* Recommendations Classic
[!DNL  Adobe Campaign] provides an intuitive, automated way to deliver one-to-one messages across online and offline marketing channels. You can now anticipate what your clients want using experiences determined by their habits and preferences. 

For product documentation, see: 

* [ Adobe Campaign Classic Release Notes ](http://docs.campaign.adobe.com/doc/AC/en/RN.html)
* [ Adobe Campaign Classic Learn &amp;amp; Support ](https://helpx.adobe.com/support/campaign/classic.html)
* [ Adobe Campaign Standard Release Notes ](https://helpx.adobe.com/campaign/standard/rn/rn.html)
* [ Adobe Campaign Standard Learn &amp;amp; Support ](https://helpx.adobe.com/support/campaign/standard.html)

<!-- To learn more about Adobe Campaign, enable yourself at [ Adobe Digital Library ](https://digitalu.adobe.com/content/Enablement/en.html). -->


## AEM release notes {#section_8CD42C5750254AA88D6ACA7DBFA0D9A1}

Adobe recommends customers with on-premise deployments to deploy the latest patches to ensure higher stability, security, and performance. 


<table id="table_F4E7F10923004BF1AD49BACE86D4982E"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> </th> 
   <th colname="col2" class="entry"> Title </th> 
   <th colname="col3" class="entry"> Description </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1" morerows="1"> <p><b>Product releases</b> </p> </td> 
   <td colname="col2"> <p>Cloud Manager 2018.5.0 </p> </td> 
   <td colname="col3"> <p>Cloud Manager 2018.5.0 introduces new features such as CI/CD Pipeline Notifications and Scheduled Production Deployments. Bug fixes were also addressed. </p> <p>See <a href="https://helpx.adobe.com/experience-manager/cloud-manager/using/release-notes-2018-50.html" format="https" scope="external"> Release Notes </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>Core Components Release 2.1.0 </p> </td> 
   <td colname="col3"> <p>Release 2.1.0 of the <a href="https://helpx.adobe.com/experience-manager/core-components/user-guide.html" format="https" scope="external"> core components </a> is now available, introducing <a href="https://helpx.adobe.com/experience-manager/core-components/using/image.html" format="https" scope="external"> Image </a> component improvements, a new <a href="https://helpx.adobe.com/experience-manager/core-components/using/teaser.html" format="https" scope="external"> Teaser </a> component, and numerous bug fixes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1" morerows="4"> <p><b>Self-Help</b> </p> </td> 
   <td colname="col2"> <p>AEM 6.3 Feature Pack 24424 and Feature Pack 24425 </p> </td> 
   <td colname="col3"> <p> <a href="https://helpx.adobe.com/experience-manager/6-3/release-notes/content-services-fragments-featurepacks.html" format="https" scope="external"> Content Fragments Updates and Content Services Feature Pack </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p> Image Serving and Image Rendering API </p> </td> 
   <td colname="col3"> <p> Image Serving 6.6.1 and Image Rendering 6.6.1 is now available for Dynamic Media on AEM and Dynamic Media Classic (Scene7). </p> <p>See <a href="https://marketing.adobe.com/resources/help/en_US/s7/is_ir_api/is_api/r_about_this_release.html" format="https" scope="external"> About this release. </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>Viewers Reference Guide </p> </td> 
   <td colname="col3"> <p>Viewers 5.10.1 is now available for Dynamic Media on AEM and Dynamic Media Classic (Scene7). </p> <p>See <a href="https://marketing.adobe.com/resources/help/en_US/s7/viewers_ref/c_rn_07_17_18.html" format="https" scope="external"> Viewer Release Notes (5.10.1). </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>AEM 3D Assets 3.0.1 </p> </td> 
   <td colname="col3"> <p>This feature pack for AEM 6.4.1.0 adds 3D capabilities to AEM Assets/Dynamic Media - Hybrid mode. </p> <p>See <a href="https://helpx.adobe.com/experience-manager/6-4/release-notes/aem3d-release-notes.html" format="https" scope="external"> AEM 3D Release Notes. </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>Video Reporting </p> </td> 
   <td colname="col3"> <p> You can now configure video reporting across multiple installations of AEM Dynamic Media - Hybrid mode. </p> <p>See <a href="https://helpx.adobe.com/experience-manager/6-4/assets/using/config-dynamic.html#ConfiguringVideoReporting" format="https" scope="external"> Configuring Video Reporting. </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1" morerows="5"> <p><b>Community</b> </p> </td> 
   <td> <p>Where do you go to get insights from Adobe Experience Manager Experts on best practices for designing, developing, and deploying digital experiences? </p> <p>Adobe Systems wants you-our enterprise developers-enabled on the latest version of Adobe Experience Manager. Doing so can help you meet your marketing origination goals to gain and retain customers through digital experiences. We also know that taking time away from the office for training is challenging for many. You have options, however, to learn at your own pace, including where and when it works best for you. </p> <p>See our <a href="https://www.meetup.com/AEM-Technologist-Group/events/calendar/" format="https" scope="external"> calendar of upcoming events </a>, including the following resources: </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>Adobe IMMERSE </p> </td> 
   <td colname="col3"> <p>Our annual virtual enterprise developer conference was held in June; the 2018 live sessions are complete. However, you did not miss out! You can still hear helpful tips and tricks, get introduced to aspects of Adobe Experience Manager, and learn about the Adobe Cloud platform. </p> <p>You can purchase on-demand tickets for unlimited access to 90+ sessions. Go <a href="https://immerse18.adobe-devs.adobeevents.com/register/" format="https" scope="external"> here </a> and use discount code <span class="codeph"> He7B52 </span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>AEM GEMs Webinars </p> </td> 
   <td colname="col3"> <p>This webinar series provides an avenue for community experts to learn from Adobe Engineers, Product Managers, and other subject matter experts. Among other things, you learn best practices and tips when working with various aspects of Adobe Experience Manager. </p> <p>Sessions occur each Wednesday, 08:00 Pacific Time/17:00 Central European Summer Time. </p> <p>See upcoming sessions or watch past sessions <a href="https://helpx.adobe.com/experience-manager/kt/eseminars/gems/aem-index.html" format="https" scope="external"> here </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>Ask the AEM Community Expert Webinars </p> </td> 
   <td colname="col3"> <p>  This monthly webinar series provides insights into topics that were recently discussed in our <a href="https://landing.adobe.com/experience-league/" format="https" scope="external"> Experience League </a> | <a href="https://forums.adobe.com/community/experience-cloud/marketing-cloud/experience-manager" format="https" scope="external"> AEM HelpX Forum </a>. </p> <p>Sessions occur the last or second to last Tuesday of each month, 08:00 Pacific Time/17:00 Central European Summer Time. </p> <p>See upcoming sessions or watch past sessions <a href="https://helpx.adobe.com/experience-manager/kt/eseminars/ask-the-expert/atace-index.html" format="https" scope="external"> here </a>. </p> <p>Still need help? Join the AEM Community, introduce yourself and post your question <a href="https://forums.adobe.com/message/9643186?cid=AEMNewCommInvite13June_MU_1" format="https" scope="external"> here </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>3|Share presents Evolve </p> </td> 
   <td colname="col3"> <p>Occurs 15-17 August 2018, in San Diego, California. </p> <p>  Evolve18 is the community-driven conference focused on Adobe Experience Manager, Campaign, and Analytics for developers, marketers and IT leaders.  See how your peers across a variety of industries produce extraordinary digital experiences. Learn how Adobe Experience Manager works with Adobe Campaign and the Adobe Analytics Cloud. Gain insights on business and technical best practices. </p> <p>More information is available <a href="https://evolve.3sharecorp.com/" format="https" scope="external"> here </a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col2"> <p>Pro!Vision hosting the 8th annual adaptTo() Conference </p> </td> 
   <td colname="col3"> <p>Occurs 10-12 September 2018, at the Schinkelhalle, in Potsdam, Germany. </p> <p>The event this year is hosted in the Schinkelhalle and will be an interactive community experience. Our sponsors are providing you a platform to meet some of the most renowned Sling, Jackrabbit, and Felix developers. Additional sessions cover commercial implementations such as Adobe Experience Manager, with a focus on how the architecture is leveraged in these products. </p> <p>Do not forget the Hackathon! Get in touch with the best and brightest mobile web minds from the Apache/Adobe community membership. Speakers attend for free, Apache Committers receive a discount. </p> <p>More information is available <a href="https://adapt.to/2018/en/conference.html" format="https" scope="external"> here </a>. </p> <p>  Find local user group meet-ups <a href="https://www.meetup.com/pro/aem/" format="https" scope="external"> here </a>. If you do not see a local group but you are interested in starting one, send an email to <a href="mailto:aemusers@adobe.com" format="com" scope="peer"> aemusers@adobe.com </a> </p> </td> 
  </tr> 
 </tbody> 
</table>


## Additional resources {#section_B1FAFE0975E74070812BC036D994FBE3}


* [ AEM 6.4 Learn &amp;amp; Support home ](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [ AEM 6.3 Learn &amp;amp; Support home ](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [ AEM 6.2 Learn &amp;amp; Support home ](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [ Cloud Manager User Guide ](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [ Older versions of AEM documentation ](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [ Scene7 Publishing System release notes ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [ Livefyre release notes ](https://marketing.adobe.com/resources/help/en_US/livefyre/)

Released July 21, 2018 

<table id="table_A41D8C79DEE84AE59FE9C8D2D291FCD7"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Feature </th> 
   <th colname="col2" class="entry"> Description </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Search Advanced Campaign Management </p> </td> 
   <td colname="col2"> <p>The Advanced view now includes a Propagations tab. Each time you propagate data through a template, a summary is added to the Propagations tab, indicating an estimate of each entity type that was or would be created, paused, or deleted based on the propagation options. The estimate doesn't take into account changes made from within the search engine's own ad editor. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Search Campaigns </p> </td> 
   <td colname="col2"> <p>You can now sync, optimize, and report on your existing Google responsive search ads (RSAs), which use a beta ad format that consist of three headlines and two 90-character descriptions that Google pulls dynamically from a larger subset of ad elements. The ad elements for each resulting expanded text ad are synced with the Creative Type ”RSA.” Support for setting up responsive ads is available only in AdWords Ads Manager. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> </p> </td> 
   <td colname="col2"> <p>For oAuth-enabled accounts on Bing Ads, Google, Pinterest, and Yahoo Gemini, an optional Password field was added to the account settings. Enter a password when you want to encrypt and save the password so that the account manager can refresh tokens as needed. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> </p> </td> 
   <td colname="col2"> <p>oAuth tokens for Bing Ads accounts are now refreshed every month. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> </p> </td> 
   <td colname="col2"> <p>The Placements view now has two sub-views: Placements and Negatives. </p> <p>The Negatives sub-view allows you to create and delete campaign-level and ad group-level negative placements for the Google AdWords display network. The ability to edit negative placements will be available in a future release. You also can still manage negative placements in the campaign and ad group settings. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> </p> </td> 
   <td colname="col2"> <p>You can now lock and unlock any column. Locking a column locks that column and all other columns to the left of it into one static pane, and all columns to the right into another pane through which you can scroll horizontally. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Legacy Labels </p> </td> 
   <td colname="col2"> <p>Legacy labels will become read-only on 1 September (originally planned for 1 August). Performance data for labels will continue to be available in reports for longer. </p> </td> 
  </tr> 
 </tbody> 
</table>

Help for the Advertising Cloud is available in the product by clicking the Help icon ( **[!UICONTROL  ?]**) at the top of any page. 

**Experience Cloud and Community Resources** 

* [ Advertising Cloud Community ](https://forums.adobe.com/community/experience-cloud/advertising-cloud)
* [ Experience Cloud Release Notes ](https://marketing.adobe.com/resources/help/en_US/whatsnew/)

Adobe Primetime is a multiscreen TV platform that helps media companies create and monetize engaging, personalized viewing experiences. 

[ Primetime Release Notes ](http://help.adobe.com/en_US/primetime/release_notes/index.html) 
[ Primetime Help Home ](http://help.adobe.com/en_US/primetime/) 
