---

title: Adobe Experience Cloud Release Notes
description: Template for Experience Cloud release notes
short-title: Release Notes Template
doc-type: release notes
last-update: July 2018
author: mfrei

---

# Adobe Experience Cloud Release Notes

New features and fixes in the Adobe Experience Cloud. 

>[!IMPORTANT]
>This page contains pre-release content and is subject to change prior to the XXXX release.

>[!NOTE]
>Subscribe to the [Adobe Priority Product Update] (https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. You will receive the notice three to five business days in advance of the release. New information published after the release will be marked with the publication date.

## Month 2018

+ Adobe Cloud Platform
+ Analytics Cloud
+ Marketing Cloud
+ Advertising Cloud

# Adobe Cloud Platform

Release notes for the Experience Cloud interface features and core services (accessed under the Platform group in the navigation menu). 
		
+ Activation
+ Administration
+ People
+ Experience Cloud Assets
+ Feed
+ Experience Cloud ID Service
+ Device Co-op
+ General Data Protection Regulation (GDPR) API
+ Data Connectors

## Activation

+ Launch, by Adobe

### Launch, by Adobe

For product documentation, see [Launcy, by Adobe] (https://marketing.adobe.com/resources/help/en_US/experience-cloud/launch/)

### Dynamic Tag Management

For product documentation, see [Dynamic Tag Management] (https://marketing.adobe.com/resources/help/en_US/dtm/).

### Auditor

### Triggers

For product documentation, see [Triggers] (https://marketing.adobe.com/resources/help/en_US/mcloud/triggers.html).

### Mobile Services

For product documentation, see [Mobile Services](https://marketing.adobe.com/resources/help/en_US/mobile/).

### Experience Cloud Mobile SDKs

For more information about the Mobile SDKs, see:[Android SDK 4.x for Experience Solutions] (https://marketing.adobe.com/resources/help/en_US/mobile/android/) and [iOS SDK 4.x for Experience Cloud
Solutions] (https://marketing.adobe.com/resources/help/en_US/mobile/ios/).

## Administration


## Activation


## Administration


## People


## Experience Cloud Assets


## Feed


## Experience Cloud ID Service


## Device Co-op


## General Data Protection Regulation (GDPR) API


## Data Connectors


# Analytics Cloud


# Marketing Cloud

+ Social
+ Target
+ Primetime
+ Campaign
+ Experience Manager (and Livefyre)


# Advertising Cloud


MD tips:
Here is an unordered list:

+ first item
+ second item
+ third item
  + indented item
  + indented item
    + Another level
+ fourth item

Here is an ordered list:

1. first item
1. second item
1. third item
   1. indented ordered item
   1. indented ordered second item
1. fourth item.

Here is a mixed ordered/unordered list:

1. first item
1. second item
1. third item
    + indented unordered item
    + indented unordered item
1. fourth item.

~~strikethrough text~~ uses the syntax \~\~word\~\~

### Code Block (in line)

#### When to use

Used to render a piece of code in-line in a sentence. Ideal to call out a cookie name, file name, value, or command that does not require a full-fenced code block.

#### Syntax

A code block uses single back ticks to enclose the code element you would like to highlight.

\`sample\`

#### Sample

Here is a `code sample` enclosed with single back ticks
fenced code blocks use 3 back ticks

### Code Block (fenced)

#### When to use {#when-to-use-fenced-code-blocks}

A fenced code block uses triple back ticks to enclose the code element you want to highlight.

#### Syntax {#fenced-code-block-syntax}

  ``` generic
  code block here
  ```

#### Sample {#fenced-code-block-sample}

```javascript
var visitor = Visitor.getInstance("INSERT-MARKETING-CLOUD-ORGANIZATION ID-HERE", {
     trackingServer: "INSERT-TRACKING-SERVER-HERE", // same as s.trackingServer
     trackingServerSecure: "INSERT-SECURE-TRACKING-SERVER-HERE", // same as s.trackingServerSecure

     // To enable CNAME support, add the following configuration variables
     // If you are not using CNAME, DO NOT include these variables
     marketingCloudServer: "INSERT-TRACKING-SERVER-HERE",
     marketingCloudServerSecure: "INSERT-SECURE-TRACKING-SERVER-HERE" // same as s.trackingServerSecure
});

```

### Horizontal Rule

Horizontal rules are *not supported*.

### Comments

You shouldn't be able to see text below this.
\<!-- standard comment code \-->

<!--
You can't see me
-->

#### Component Indicators

Special components are declared in a containing block quote using square brackets and an exclamation mark plus the reference for the type of block it is, eg:  `[!NOTE]`
This is Important:
> [!IMPORTANT]
> This is an IMPORTANT NOTE block. Etiam euismod auctor orci, id lobortis neque interdum faucibus. Integer sit amet
> tincidunt erat, nec commodo velit. Pellentesque iaculis tempus lectus eget cursus.

This is a Warning:
> [!WARNING]
> This is a WARNING NOTE block. Integer sit amet tincidunt erat, nec commodo velit. Pellentesque iaculis tempus lectus eget cursus.

This is a Note:
> [!NOTE]
> This is a STANDARD NOTE block that uses multiple paragraphs. Nam in consectetur diam. Nunc mauris nulla, venenatis non malesuada non, consequat sed nisl.
>
> Mauris feugiat suscipit dui in ultrices. Nullam hendrerit luctus ligula at congue.

And we have caution:
> [!CAUTION]
> This is a CAUTION NOTE block. Nunc mauris nulla, venenatis non malesuada non, consequat sed nisl. Mauris feugiat suscipit dui in ultrices. Nullam hendrerit luctus ligula at congue.

### Tables

A standard table:

| Title 1                                                                                                                                                                                                                   | Col 2        | Col 3                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | -------------------------------- |
| Some text in here                                                                                                                                                                                                         |     3456     | Another value                    |
| Duis commodo feugiat neque id malesuada                                                                                                                                                                                   | asdasdasdasd | eget iaculis mauris lacus nec mi |
| Nulla tristique bibendum pretium. Nam gravida leo egestas nisi laoreet scelerisque. Phasellus eget interdum tortor. Suspendisse lacinia imperdiet magna. Etiam euismod auctor orci, id lobortis neque interdum faucibus.  | a b c d E F  | 98230129 3761023761 023987       |

### Images

Adding an image into the page:

![Sample image alternate text](test-folder/media/test-folder-standards/response2.png)

### Adding a Video file from MPC (Adobe TV)

Videos won't natively render in Markdown. To display a video inline, use the component indicator `[!VIDEO]` and then the url.  We support 3 types of videos:

+ Adobe TV
  > [!VIDEO](https://video.tv.adobe.com/v/17187/)
+ Youtube
+ Other: Be sure to add a description to the link:
  >[!VIDEO](https://vimeo.com/95415863 "This is a video")

## Localization *Draft*

A-3 Components have a "Do Not Localize" option.  This will be supported on a block level basis, where the container block has all of the components for which localization is not needed.

>[!DONOTLOCALIZE]
> >[!NOTE] This won't be localized
>
> ![Unknown Error](unknown_error.png)
