# Getting started

## Get provisioned to use Adobe Places

Places requires special provisioning context with your regular Adobe Experience Platform provisioning context.

To get provisioned, complete the following tasks:

* In the Admin Console, ensure that your organization is provisioned with Places.  If you are not the Adobe administrator, contact the administrator to ensure the Places context in Admin Console.
* Ensure you are listed as a user under the Places and Launch product contexts in the Admin Console. For more information, see [Adding a user to Launch and Places](https://launch.gitbook.io/places-services-by-adobe-documentation/adding-a-user-to-launch-and-places).
* Ensure your mobile app property is configured in Adobe Launch with the Places extension installed.  For more information, see [Adobe Places \(Beta\)](https://aep-sdks.gitbook.io/docs/using-mobile-extensions/places-extension-1). 
* If your company has multiple Adobe organizations, ensure that you always select the organization that is provisioned for Places. This allows you to add your POIs and Libraries.

## Configure the Places extension and Places Monitor extension

For more information about configuring the Places extension and Monitor extension, see [Places extension ](https://aep-sdks.gitbook.io/docs/using-mobile-extensions/places-extension-1/places-extension)and [Places Monitor extension](https://aep-sdks.gitbook.io/docs/using-mobile-extensions/places-extension-1/places-monitoring-extension).

## Creating libraries and POIs

You can create libraries and POIs in one of the following ways:

* By using the web services. For more information, see [Places web services](https://launch.gitbook.io/places-services-by-adobe-documentation/places-rest-apis).
* By using the Places UI. For more information, see [Places UI](https://launch.gitbook.io/places-services-by-adobe-documentation/places-database-management-1). 

## Create an empty library in the Places database in the Places UI

1. Log into Adobe Places UI \(The user interface to visually add and manage the POIs and libraries\). 
2. Click on the **Libraries** tab.
3. Click **Create Library**.
4. Type the name.
5. Click **Confirm**.

## Create a new POI in the library in the Places UI

A point of interest \(POI\) is a location or a point on a map that is of interest to you. It can include locations like cafes, restaurants, and so on.

1. Log in to Adobe Places Services UI \([https://places.adobe.com](https://places.adobe.com)\) with your Adobe ID.
2. In the map view, click **+ New POI**. 
3. Complete the following steps in the **Details** section:

   a. Type a name.

   b. Select a library.

   c. Enter or select a radius.

   d. Select the icon that you want to use for your POI.

   e. Select a color for your POI icon.

   f. Type a category.

4. Complete the following steps in the **Location** section:

   a. Type an address.

   b. Type the city.

   c. Type the name of the state.

   d. Type the name of the country.

   e. Select or enter a latitude or longitude.

   f. Click **Drop Pin on Map**.

5. Complete the following steps in the **Metadata** section:

   a. Click **Add Metadata.**

   b. Type the key name.

   c. Type the key value.

6. Click **Confirm**. test

