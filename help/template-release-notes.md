---
title: "[Product name] release notes"
description: Find new features, enhancements, fixes, and planned changes for [Product name], organized by release date.
doc-type: release notes
last-update: Month YYYY
author: your-alias
---

<!--
HOW TO USE THIS TEMPLATE
Delete every HTML comment (like this one) before you publish.
Replace every [bracketed placeholder]. Delete any section that doesn't apply, but keep the order of the sections that remain.

WHY THIS STRUCTURE
- One pattern for every product, so readers (and AI tools that summarize release notes) find the same things in the same places.
- One release = one H2 with a date in the heading. One feature = one heading (H4 under "New features" in a release, H3 under "Coming soon"). Each entry carries the same labeled fields: Release date, Availability, and Learn more.
- Status is always written as text (General Availability, Limited Availability, Beta, Sandbox, Deprecated). Never rely on a badge, color, or icon alone.
- Planned items live only in "Coming soon." Released items live only under a release. Never mix them.
- Each entry makes sense on its own, because search and AI tools often retrieve a single entry without the rest of the page.

STYLE (see https://experienceleague.adobe.com/en/docs/authoring-guide/using/style-guide/basic-editorial-guidance)
- Sentence case for all headings. Keep headings to about five words, except release headings, which follow the pattern below.
- Present tense, active voice. Say what the reader can now do: "Create audiences from CSV files," not "A new CSV feature has been added."
- Dates: full month, day, and four-digit year, such as October 15, 2026. Never use numeric-only dates or partial dates.
- Wrap UI labels in [!UICONTROL ...] and product names in [!DNL ...].
- Use the Oxford comma. Avoid semicolons and em dashes. Keep sentences under about 35 words.
- Use descriptive link text, such as [Create an audience from a CSV file](URL). Don't use "click here" or bare URLs.
- Add alt text to every image that describes the goal or feature shown.
-->

# [Product name] release notes {#top}

Last update: **Month D, YYYY**

[One or two sentences: what this page covers and how [Product name] is delivered. For example: "This page lists new features, enhancements, and fixes for [!DNL Product name]. Updates are delivered continuously, and this page is updated within [N] business days of each release."]

>[!NOTE]
>
>[Optional. Use only to point readers of other editions or deployment models to their release notes. Example: "For on-premise or Managed Services deployments, see [link text](URL)."]

## Releases at a glance {#at-a-glance}

<!-- One row per release, newest first. Keep "Highlights" to three items or fewer. Link each release to its section below. -->

| Release | Release date | Highlights |
| ------- | ------------ | ---------- |
| [[Release identifier]](#release-identifier) | [Month D, YYYY] | <ul><li>[Highlight]</li><li>[Highlight]</li><li>[Highlight]</li></ul> |
| [[Release identifier]](#release-identifier-2) | [Month D, YYYY] | <ul><li>[Highlight]</li><li>[Highlight]</li></ul> |

## Coming soon {#coming-soon}

>[!IMPORTANT]
>
>Planned items are subject to change. Dates are targets, not commitments.

<!--
List planned items here, using the same entry format as released items (see the next section).
For each, use "Planned date" instead of "Release date."
Use "TBD" when no date is set.
When an item ships, move it under its release section and change "Planned date" to "Release date."
If an item slips, move it to "Postponed" and keep the original date.
-->

### [Feature name] {#feature-name-planned}

[One or two sentences describing what readers will be able to do.]

* **Planned date:** [Month D, YYYY or TBD]
* **Availability:** [General Availability | Limited Availability | Beta | Sandbox]
* **Learn more:** [Descriptive link text](URL)

## [Release identifier] ([Month D, YYYY]) {#release-identifier}

<!--
Release heading pattern: "[Version or period label] ([Month D, YYYY])".
Examples: "Release 7.4.5 (October 15, 2026)", "October 2026, release 2 (October 20, 2026)", "Version 26.10.2 (October 15, 2026)".
Use the same label style for every release on the page. Newest release first.
For continuously delivered products with no versions, use the release date alone: "October 15, 2026".
-->

Release date: **[Month D, YYYY]**

[Optional one-sentence summary of the release theme.]

### New features {#release-identifier-features}

<!--
One H4 per feature under this H3, in order of importance to the reader.
Entry rules:
1. The H4 title is a noun phrase naming the feature, in sentence case.
2. Sentence 1 states what readers can do now. Sentence 2 (optional) adds the key benefit or condition.
3. Put prerequisites, limits, and required actions in the labeled fields or a callout, not buried in the description.
4. Always include Release date, Availability, and Learn more.
5. Add "Applies to" only when the feature is limited to an edition, region, or deployment model.
Example:
  #### Stop action journey activity
  Remove a profile from up to five inbound activities or experiences without ending its journey.
  * **Release date:** October 12, 2026
  * **Availability:** General Availability
  * **Learn more:** [Use the Stop action activity](URL)
-->

#### [Feature name] {#feature-name}

[One or two sentences describing what readers can do now.]

* **Release date:** [Month D, YYYY]
* **Availability:** [General Availability | Limited Availability | Beta | Sandbox]
* **Applies to:** [Optional. Edition, region, or deployment model.]
* **Learn more:** [Descriptive link text](URL)

>[!IMPORTANT]
>
>[Optional. Use for required actions, features that are off by default, or features that need a support request. State the action first.]

#### [Feature name] {#feature-name-2}

[One or two sentences describing what readers can do now.]

* **Release date:** [Month D, YYYY]
* **Availability:** [General Availability | Limited Availability | Beta | Sandbox]
* **Learn more:** [Descriptive link text](URL)

### Enhancements {#release-identifier-enhancements}

<!-- Use a table for short, parallel items that don't need their own heading. Delete this section if there are none. -->

| Area | Enhancement | Learn more |
| ---- | ----------- | ---------- |
| [Product area] | [One sentence stating what readers can do or what is now better.] | [Link text](URL) |
| [Product area] | [One sentence.] | [Link text](URL) |

### Fixes {#release-identifier-fixes}

<!--
One row per fix. Write each description as "Fixed an issue where [symptom]." State the symptom a reader would see, not the internal cause.
Include the reference ID when one exists (for example, a Jira key). Delete this section if there are none.
-->

| Area | Description | Reference |
| ---- | ----------- | --------- |
| [Product area] | Fixed an issue where [symptom]. | [ID] |
| [Product area] | Fixed an issue where [symptom]. | [ID] |

### Security updates {#release-identifier-security}

<!-- Describe what is fixed and what the reader must do. Do not describe exploit details. Delete this section if there are none. -->

[One or two sentences stating what the update addresses.]

>[!IMPORTANT]
>
>[State the required action first. Example: "Restart the server to complete deployment."]

### Deprecations and end of life {#release-identifier-deprecations}

<!-- Delete this section if there are none. Always give the date and the replacement. -->

| Feature or capability | Effective date | What to do |
| --------------------- | -------------- | ---------- |
| [Name] | [Month D, YYYY] | [Replacement and migration link.] |

## Postponed {#postponed}

<!-- Delete this section if nothing is postponed. Keep the original date so readers can see the slip. -->

| Feature | Original date | New date | Learn more |
| ------- | ------------- | -------- | ---------- |
| [Feature name] | [Month D, YYYY] | [Month D, YYYY or TBD] | [Link text](URL) |

## Additional release notes {#additional-release-notes}

<!-- Link to related products, SDKs, APIs, or earlier release notes (archive). Delete this section if there are none. -->

* [Descriptive link text](URL)
* [Descriptive link text](URL)

<!--
PRE-PUBLISH CHECKLIST
[ ] Front matter title, description, doc-type, last-update, and author are filled in.
[ ] "Last update" line shows today's date, in the format Month D, YYYY.
[ ] Releases are in reverse chronological order, and every release heading includes a date.
[ ] Every feature entry has Release date, Availability, and Learn more.
[ ] Availability is written as text and uses one of the approved terms.
[ ] Nothing future-dated appears outside "Coming soon" or "Postponed."
[ ] "Releases at a glance" matches the sections below it.
[ ] Headings use sentence case. All heading IDs are unique and lowercase with hyphens.
[ ] No comments, placeholders, or empty sections remain.
-->
