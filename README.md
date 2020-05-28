# Setup GTM template
Install the XO tracking in a few clicks using the GTM template.

To install XO tracking in Google Tag Manager, you must first read the [📌 Getting started](https://attraqt.gitbook.io/developer-documentation/getting-started).

## Pre-requisites
You must have a GTM container configured and if possible a dataLayer containing the information to be tracked.
You must have a valid Attraqt account

# How to use the GTM Template

 - To add a new XO tag, go to the New button in the Tag section
 - Then in Tag configuration, click on Discover more tag types in the Community Template Gallery
 - Search for XO Activities Tracking

Now your tag configuration should look like this:
![enter image description here](https://gblobscdn.gitbook.com/assets/-M29DVDUqAIkkL2XX89z/-M8PIZjRKdcPHDVBynFO/-M8POaNUQ-Lx3EMABJqa/Capture%20d%E2%80%99e%CC%81cran%202020-05-28%20a%CC%80%2010.28.43.png?alt=media&token=a0632441-6bc6-4f56-99d5-e5ed25b75ce3)


Add your **trackerKey** in the field, and choose your action.

Each field is a variable, which means that you can configure multiple actions on the tag if your variable is dynamic. Otherwise, each tag in GTM will correspond to a tracking action.

The **target** is a set of key-values, the key corresponds to the type of object, and the value has the id of the object. See [📌 Getting started](https://attraqt.gitbook.io/developer-documentation/getting-started#what-is-an-activity) for more information.

**Identities** are also key-values. The key corresponds to the identity repository (available in the XO console) and the value to the visitor id. [More informations here.](https://attraqt.gitbook.io/developer-documentation/getting-started#managing-identities/)

You can add additional information in the **User information** and **Activity information** sections such as: user segments, Traits, metadata.


> *The **Advanced Settings** is not part of the XO tag configuration.*


##

#### Let's track a simple view activity
A basic tracking configuration for product events should look like this:

![](https://gblobscdn.gitbook.com/assets%2F-M29DVDUqAIkkL2XX89z%2F-M8PIZjRKdcPHDVBynFO%2F-M8PRba3HR6SjzoUCUsJ%2FCapture%20d%E2%80%99e%CC%81cran%202020-05-28%20a%CC%80%2010.41.49.png?alt=media&token=e2b509e3-eb3c-47aa-82a6-944fc546a712)


> *Some information are required for certain types of action. See the [📌 Getting started](https://attraqt.gitbook.io/developer-documentation/getting-started#what-is-an-activity) for more information.*

-   The **Source id** in Activity information is mandatory for actions such as clicking on a XO recommendation.
-   Some metadata are required for the **buy** action (price, orderId, quantity, currency)


When the configuration of the tag is complete, you must configure its triggering like any other tag.

> The tag does not need to be activated on pages with no tracking.

##

#### Let's track a purchase event
A basic tracking configuration for purchases events should look like this:

![](https://gblobscdn.gitbook.com/assets%2F-M29DVDUqAIkkL2XX89z%2F-M8PZhcLcMGiqCoEl2Ue%2F-M8P_KzFNOyJwc7Vn8QZ%2FCapture%20d%E2%80%99e%CC%81cran%202020-05-28%20a%CC%80%2011.20.12.png?alt=media&token=393ea1c5-6446-4626-a0c2-8b7442d09552)
