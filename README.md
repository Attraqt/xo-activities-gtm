# XO Activities GTM template

- [Prerequisite](#prerequisite)
- [Getting started](#getting-started)
- [Example configurations](#example-configurations)

This GTM template will, in just a few clicks, allow you to collect user activities.

Before getting started, you might want to read our [📌 Getting started](https://attraqt.gitbook.io/developer-documentation/getting-started).

# Prerequisite
- A GTM container (A well-maintained data layer will speed-up the process)
- An Attraqt tracker key

# Getting started

To use the GTM template you need to add it to your workspace.
You can find the template at [this link](https://tagmanager.google.com/gallery/#/owners/Attraqt/templates/xo-activities-gtm) or in Tag configuration, click on *Discover more tag types in the Community Template Gallery* and search for **XO Activities Tracking**.

1. In the **Tag** section, click on the **New** button
2. Selected the **XO Activities Tracking** template

Your tag configuration form should look like this:

![XO Activities Tracking GTM template configuration form](https://gblobscdn.gitbook.com/assets/-M29DVDUqAIkkL2XX89z/-M8PIZjRKdcPHDVBynFO/-M8POaNUQ-Lx3EMABJqa/Capture%20d%E2%80%99e%CC%81cran%202020-05-28%20a%CC%80%2010.28.43.png?alt=media&token=a0632441-6bc6-4f56-99d5-e5ed25b75ce3)

Enter your **trackerKey**, and choose a value for the **action** field.

The **target** is a set of key-values. The key corresponds to the type of object, and the value has the id of the object. You can learn more about targets [here](https://attraqt.gitbook.io/developer-documentation/getting-started#what-is-an-activity).

**Identities** are also key-values. The key corresponds to the identity repository (available in the XO console) and the value to the visitor id.
You can learn more about targets [here](https://attraqt.gitbook.io/developer-documentation/getting-started#managing-identities).

You can add additional information in the **User information** and **Activity information** sections (user segments, traits, etc.).

> Depending on the **action**, some additional fields might be required. See the [📌 Getting started](https://attraqt.gitbook.io/developer-documentation/getting-started#what-is-an-activity) for more information.

# Example configurations

## Minimal **view** activity
A minimal configuration for product view events could look like this:

![](https://gblobscdn.gitbook.com/assets%2F-M29DVDUqAIkkL2XX89z%2F-M8PIZjRKdcPHDVBynFO%2F-M8PRba3HR6SjzoUCUsJ%2FCapture%20d%E2%80%99e%CC%81cran%202020-05-28%20a%CC%80%2010.41.49.png?alt=media&token=e2b509e3-eb3c-47aa-82a6-944fc546a712)

## Minimal **purchase** activity
A minimal configuration for product purchases events could look like this:

![](https://gblobscdn.gitbook.com/assets%2F-M29DVDUqAIkkL2XX89z%2F-M8PZhcLcMGiqCoEl2Ue%2F-M8P_KzFNOyJwc7Vn8QZ%2FCapture%20d%E2%80%99e%CC%81cran%202020-05-28%20a%CC%80%2011.20.12.png?alt=media&token=393ea1c5-6446-4626-a0c2-8b7442d09552)
