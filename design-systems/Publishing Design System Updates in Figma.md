# Publishing Design System Updates in Figma

This documentation is intended as a starting point for how design teams at CivicActions can approach design system updates. While the outlined process reflects current best practices, specific steps may vary depending on team workflows, tooling configurations, or evolving design system norms. Always consult with your specific team for guidance on exceptions, edge cases, or changes to this process.

**On this page:**

* 1 [Audience](#Audience)
* 2 [Purpose](#Purpose)
* 3 [Why this matters](#Why-this-matters)
* 4 [Responsibilities of the Design System Maintainer](#Responsibilities-of-the-Design-System-Maintainer)
* 5 [Step-by-Step Process](#Step-by-Step-Process)
  * 5.1 [1\. Plan the Update](#1.-Plan-the-Update)
  * 5.2 [2\. Final QA](#2.-Final-QA)
  * 5.3 [3\. Publish the Library](#3.-Publish-the-Library)
  * 5.4 [4\. Log the Update](#4.-Log-the-Update)
  * 5.5 [5\. Notify the Team](#5.-Notify-the-Team)
* 6 [Recommended Cadence](#Recommended-Cadence)
* 7 [Definition of Done](#Definition-of-Done)

* * *

# Audience

Design System Maintainers

* * *

# Purpose

A step-by-step guide for publishing changes to the Design System library so they can be used in product design files.

* * *

# Why this matters

Keeping the design system library up to date ensures that all product teams benefit from the latest improvements, bug fixes, and standardized components. Publishing consistently helps reduce design debt and maintain visual consistency across all teams.

* * *

# Responsibilities of the Design System Maintainer

You are responsible for:

* Publishing component and style changes
* Communicating changelogs
* Preventing unintended or breaking updates
  

* * *

# Step-by-Step Process

## 1\. Plan the Update

* Review changes made to the system: new components, styles, tokens, etc.
* Ensure components are:
  * Properly named
  * Structured with Auto Layout and variants
  * Documented with descriptions
* Prepare a draft of the changelog.
  

## 2\. Final QA

* Use test frames to validate that components work as expected.
* Confirm alignment, padding, and interaction behavior.
* Check naming conventions and token usage.
  

## 3\. Publish the Library

* Open the Design System Figma file.
* In the "Assets" panel of the left sidebar, click the library icon to open the "Manage libraries" modal
* Click “Publish”.
* In the “Description of changes” field, write a summary of the update.
* Carefully review the list of changes and deselect anything unfinished or experimental.
* Click “Publish”.
  

## 4\. Log the Update

Update your Changelog document to include the following info:

> **📅 Date of publish**
> 
> * Summary of updates
> * Notes on deprecated or breaking changes
> * Links to updated files or reference pages
>   

## 5\. Notify the Team

Tag designers in a message using your team’s preferred messaging platform and include the following info:

> **🎉 Design System Update Published \[Insert Date\]!**
> 
> * **What's new:**
>   * \[Insert updates\]
> * **Action needed:**
>   * Open your files and apply updates. Read our document to learn how. \[Insert link to “Applying Design System Updates” document\]
> * **Changelog:**
>   * View latest updates. \[Insert link to Changelog document\]
> * **Questions:**
>   * Thread them to this message!
>     

* * *

# Recommended Cadence

The table below is just an example of different cadences a team could use. This can be changed to meet the needs of your team, but the most important thing is that you’re publishing updates regularly.

| Frequency | Timing | Trigger |
| :-- | :-- | :-- |
| Bi-weekly | Every other Tuesday | End of sprint |
| Ad hoc | As needed | Once a batch of updates is completeFor critical bugs and urgent releases |

* * *

# Definition of Done

* Library is published and reviewed
* Changelog is posted
* Team has been notified
* Key files have been spot-checked
