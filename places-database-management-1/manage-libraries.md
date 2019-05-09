# Manage libraries in the Places UI

A library is a collection of POIs. You can have up to 150,000 POIs in a library, and there can be up to 100 libraries per Experience Cloud organization.

There are various ways to organize your POIs into libraries depending what is most useful to your organization. Some customers might prefer to create a separate library for each mobile app, while other customers might use libraries to group specific types of POIs such as coffee shops, parks, hotels, and so on. For example, a major entertainment company might have a library that comprises their outdoor venues in one library and their retail stores in another library. A city government might have a library that comprises all of the buildings in the city and another library that comprises all of the parks in the city.

Libraries are defined by the following:

| Keys: | Description: |
| :--- | :--- |
| ID | A unique identifier assigned to the library at creation. |
| Name | A friendly name given to a library. |
| Rank | These rankings can be ignored if there are no overlapping geofences in your organization. If there are overlapping POIs, we recommend that you put each of the geofences in separate libraries, so they can be weighted relative to each other. A user can only be in one geofence at a time.   The highest ranking of the geofences a user is in determines his or her current geofence membership. If there geofences have the same library ranking, the smallest geofence is the user's current geofence.   The SDK is also aware of _Last entered_ and _Last exited_ POIs, so you have complete control of how you want your rules to fire based on user interaction with your POIs. |

## Create a library

1. Log into Adobe Places with your Adobe ID.
2. Click on the **Libraries** tab.
3. Click **Create Library**.
4. Type the name.
5. Click **Confirm**.

## Change the rank of a library in the Places UI

1. Log into Adobe Places with your Adobe ID.
2. On the **Libraries** tab, review the current ranking of your libraries. The libraries are arranged in priority order, with the highest ranking library at the top left, and the lowest ranking library on the bottom right.
3. Click the icon at the top left of the library, and drag the library to the new rank. 

## Rename a library

1. Log in to Adobe Places with your Adobe ID.
2. Click the **Library** tab.
3. Click the edit \(pencil\) icon.
4. Enter the new name.
5. Click **Save**.

## Delete a library

1. Log in to Adobe Places with your Adobe ID.
2. Click the **Library** tab.
3. Click the delete \(trash can\) icon.
4. Click **Confirm**.

