# SPOT
SharePoint Objects Tools - aka **SPOT** - is a set of tools created with the Microsoft Power Platform for objects in SharePoint Online. It is created to improve business solutions created with the Microsoft Power Platform using SharePoint Online as a data store.

SharePoint is no part of the Microsoft Power Platform though SharePoint lists and SharePoint document libraries are often used when creating business solutions with this powerful platform. To have a proper ALM (Application Lifecycle Management) for important business solutions, using Power Platform solutions is a de facto standard nowadays. SharePoint objects cannot be included in Power Platform solutions though. Because there is no built-in ALM functionality in SharePoint too, I have created SPOT.

In its core, **SPOT** is build to:
* create a definition containing SharePoint objects.
* create a deployment package based on the created definition and its previous version.
* deploy the deployment package.
  * The following object actions are supported: Create and Delete.
* validate the existence of SharePoint objects based on a definition.

**SPOT** consists of several canvas apps (Microsoft Power Apps) and many cloud flows (Microsoft Power Automate).

## Canvas apps (Power Apps)
* SPOT - Definition
![SPOT - Definition_1](https://github.com/formsandflows/SPOT/assets/35654198/0fb6cb5e-373f-4d4d-a83d-00d370007279)

* SPOT - Deployment
![SPOT - Deployment_2](https://github.com/formsandflows/SPOT/assets/35654198/04610028-21a1-407c-9dfe-b65c7917aa68)
![SPOT - Deployment_1](https://github.com/formsandflows/SPOT/assets/35654198/52a76146-7769-472c-bcfe-9fadb17ff1a2)

* SPOT - Validation
![SPOT - Validation_1](https://github.com/formsandflows/SPOT/assets/35654198/53874675-bff3-44f0-a546-86f18b770e14)

## Cloud flows (Power Automate)
In general, SPOT will consist of a cloud flow per object type and per object action (Create, Update, Delete and Validate). The available cloud flows depends on the version of SPOT. The first release of SPOT consists of 17 cloud flows. All cloud flows are called from a canvas app.

Links to general documentation can be found [here](https://www.formsandflows.nl/redirects/spot-github-documentation).

## Feature request
You can use the form on [this](https://www.formsandflows.nl/redirects/spot-github-feature-request) page to submit a feature request for **SPOT**.

## Report an issue
You can use the form on [this](https://www.formsandflows.nl/redirects/spot-github-report-issue) page to report an issue with **SPOT**.

If **PACo** is useful to you, I would very much appreciate it if you bought me a coffee: [https://www.buymeacoffee.com/rickbakker](https://www.buymeacoffee.com/rickbakker) 👍

And with that, I wish you a lot of fun creating your business solutions with the Microsoft Power Platform and of course also with PACo 😁👊

Rick
