# COMS2200A Big Data Society

> Crowdsourcing, Carleton University

## Overview

1. [Create 3 accounts](#accounts)
2. [Add 20 Mapillary Image keys](#mapillary)
3. [OSM Photo Metadata Tags](#openstreetmap)
4. [Uploading to OpenStreetMap](#upload)
5. [Reflection](#5-reflection)
6. [FAQ](#faq)

## OSM References

- [LearnOSM](learnosm.org)
- [TeachOSM](teachosm.org)
- [How to Query your OSM edits](#how-to-query-your-osm-edits)

## Goal

For this assignment the goal would be to add Amenity based features to OpenStreetMap using Mapillary photos. While collecting your photos around the Carleton University campus, here are some of the amenity features that would be worth collecting:

- [Street Lamps](http://wiki.openstreetmap.org/wiki/Tag:highway=street_lamp)
- [Benches](http://wiki.openstreetmap.org/wiki/Tag:amenity=bench)
- [Drinking Fountains](http://wiki.openstreetmap.org/wiki/Tag:amenity=drinking_water)
- [Waste Baskets](http://wiki.openstreetmap.org/wiki/Tag:amenity=waste_basket) ([Recyling containers](http://wiki.openstreetmap.org/wiki/Tag:amenity=recycling))
- [Historical Monuments](http://wiki.openstreetmap.org/wiki/Tag:historic=monument)

# Accounts

## 1. Create 3 Accounts

**Note**: When creating the following accounts below, you might want to check your junk mail for the e-mail confirmation response.

### [Mapillary App](https://mapillary.com)

Download the Mapillary App on one of your smart devices:

> https://help.mapillary.com/hc/en-us/categories/115000235529-Mapillary-apps

**Note:** Login using Facebook or Gmail, this application does require access to some personal information, like your name and image, from a Facebook or Gmail account. In addition, it asks to allow access to your camera and location.

![image](https://user-images.githubusercontent.com/550895/30525484-399b2ba0-9bd5-11e7-88f0-3ade8a4f4618.png)

### [GitHub](https://github.com)

Creating a GitHub Account will allow you to submit issues related to the assignment.

> https://github.com/join

![image](https://user-images.githubusercontent.com/550895/30525495-96828c82-9bd5-11e7-8415-2de1a4780717.png)

![image](https://user-images.githubusercontent.com/550895/30525949-6d051906-9bdf-11e7-9406-a36b5722bbb9.png)

### [OpenStreetMap.org](https://www.openstreetmap.org)

Get an OpenStreetMap Account:

> https://www.openstreetmap.org/user/new

![image](https://user-images.githubusercontent.com/550895/30525504-c2a50a2e-9bd5-11e7-90dd-29749ceb94d3.png)

# Mapillary

## 2. Add 20 Mapillary Image keys

Mapillary is a crowdsourced streetview platform which allows anyone to add & see their GPS enabled photos.

Select one of the upload methods (Option A or B).

### Option A: Take some photos using the Mapillary mobile application.

**Note**: Your mobile device will need to have a good GPS signal to capture photos, enabling your mobile internet will help increase your GPS signal.

![image](https://cdn.cultofmac.com/wp-content/uploads/2015/12/mapillary003.jpg)

Once your photos have been captured using the Mapillary app you will be able to upload them once you've connected to a WiFi network.

### Option B: Upload GPS photos to Mapillary's web platform.

For those who would only own a GPS enabled Camera, you can also upload photos directly to Mapillary web platform using their upload page.

![image](https://user-images.githubusercontent.com/32044518/30525790-722c06fa-9bdb-11e7-8917-4c1857001671.png)

![image](https://user-images.githubusercontent.com/550895/30525639-62d420c8-9bd8-11e7-8d62-aed07b6d1dbd.png)

After uploading photos to Mapillary, it will take at least 24 hours for the photos to be readily available to preview on the online platform.

You should receive an email from Mapillary stating your upload is now published.

![image](https://user-images.githubusercontent.com/550895/30525677-0891a8e6-9bd9-11e7-9074-e8e05ff1ed6c.png)

Once your uploads are published, you can select your profile on the right hand side and preview each of your photo sequences (image tracks).

![image](https://user-images.githubusercontent.com/550895/30525686-431f7bd2-9bd9-11e7-9fbf-b9300564e367.png)

### Copying Image Keys

Using the web platform of Mapillary, expand the Image details by clicking on the 3 dots at the bottom right and expand the Advanced Options. Here you will find both an **Imagey Key** & **Sequence Key**, you will only need the **Image Key** to submit to OpenStreetMap and for your assignment.

- **Image Key**: This key is the unique identifer of the individual image (this will be the key used in your assignment & tagging into OpenStreetMap)
- **Sequence Key**: This key identifies the entire sequence of the entire photo collection.

![image](https://user-images.githubusercontent.com/550895/30525877-df64775a-9bdd-11e7-8c31-734b4a93d29f.png)

# OpenStreetMap

## 3. OSM Photo Metadata Tags

> OSM (OpenStreetMap) is a crowdsourced database of Geographic real-world data.

## OSM Tutorials

- [TeachOSM.org](http://teachosm.org/en/)
- [LearnOSM.org](http://learnosm.org/en/)

Once your Mapillary photos have been uploaded, you are ready to map your first feature in OpenStreetMap using your street level photos you've collected around your neighbourhood.

## Research OSM Tag

The main resource to find the appropriate OpenStreetMap tag will be in the [OpenStreetMap Wiki](https://wiki.openstreetmap.org/wiki/Main_Page). An alternate way to find how to tag features in OSM would be to use Google.

Enter the following in the search `"OSM bench"` in Google and typically the OSM Wiki reference will be found as the first result.

![image](https://user-images.githubusercontent.com/550895/30551646-1b83717e-9c69-11e7-8834-dc61138a16ac.png)

Inside the OSM Wiki you will find a description/overview/tagging schema, this will help understand the metadata tags used to map an OpenStreetMap feature.

![image](https://user-images.githubusercontent.com/550895/30551684-4380affc-9c69-11e7-89fa-c016c7deec56.png)

## Map OSM Feature

Using the iD Editor, zoom in to the location of where your Mapillary photos were taken.

[Click here to Zoom in to Carleton University](https://www.openstreetmap.org/#map=16/45.3846/-75.6962)

![image](https://user-images.githubusercontent.com/550895/30526012-a89f6966-9be0-11e7-8bad-458a763f02f3.png)

Click on the Edit button on the top left and the map will change to a satelitte view with an edit menu on the left hand side.

![image](https://user-images.githubusercontent.com/550895/30526013-ccba1d6e-9be0-11e7-9fd2-6b0f5472186f.png)

Once you've zoomed in to the area you want to map, we will enable the Mapillary previews by click on the **Map Data (F key)** on the right hand side and toggling the **Photo Overlay Mapillary** checkbox.

![image](https://user-images.githubusercontent.com/550895/30526044-64a6b204-9be1-11e7-82ca-068d73f40e76.png)

Now you are able to see both OpenStreetMap features & Mapillary photos in the iD Editor. You can preview the Mapillary photos by clicking one of the yellow dot on the map.


### Example - How to Link Mapillary Image to OpenStreetMap

For this example we will be:

1. Adding Street Lamp Post to OpenStreetMap.
2. Linking Mapillary Image Key to OSM street lamp post ([Mapillary Image Key:  **baanWFHhhgFXzxwbBoOyPw**](https://www.mapillary.com/app/?pKey=baanWFHhhgFXzxwbBoOyPw&focus=photo))

![image](https://user-images.githubusercontent.com/550895/30526093-72184000-9be2-11e7-82ce-5e540a2c229d.png)

These are the steps to add a feature in OSM using the iD editor:

1. Select the **Point** geometry shape located in the top menu.
2. Click on the map where the Lamp Post would be located based on the Mapillary photo & Satelitte imagery.
2. Define the type of point, search for `Street Lamp` in the left hand side. This will add the [`highway=street_lamp`](http://wiki.openstreetmap.org/wiki/Tag:highway%3Dstreet_lamp) tag to your OpenStreetMap point feature.

![image](https://user-images.githubusercontent.com/550895/30526169-1c1aca4a-9be4-11e7-9a9c-b388480ca7a0.png)

Once your OSM feature is created and tagged as a [`highway=street_lamp`](http://wiki.openstreetmap.org/wiki/Tag:highway%3Dstreet_lamp) we will now need to add the Mapillary Image Key to the OSM Feature. In the **All tags** section, click on the (+) to expand a new field and add `mapillary=<MAPILLARY IMAGE KEY>`.

![image](https://user-images.githubusercontent.com/550895/30526123-341e451e-9be3-11e7-808d-1750e4d4eb78.png)

# Upload

## 4. Uploading to OpenStreetMap

Once you've added your OSM Feature with the appropriate `Mapillary Image Key` you are ready to upload these changes to the live OpenStreetMap database.

1. Click on the Save button in the top menu, there will be a number next to it which indicates how many features you will be adding/modifying.
2. Include a `Changeset Comment` which describe which type of edit you've made (ex: Added Street Lamp Post).
3. Include both **Sources** & **Hashes**
  - source=`Mapillary`
  - hashes=`#COMS2200A` (used for reference)
4. Upload changes to OSM.

![image](https://user-images.githubusercontent.com/550895/30526225-fa8b0bf0-9be4-11e7-8bc6-f0fead168bc5.png)


## How to Query your OSM edits

With [Overpass Turbo](http://overpass-turbo.eu/), you can query your own OSM edits based on your OSM username.

### Steps

- Go to http://overpass-turbo.eu
- Zoom into Carleton University
- Select the Wizard
- Use the the following query `user:OSM_ACCOUNT` (ex: `user:DenisCarriere`)
- Run **build and run query**
- You should see your edits highlighted in blue
- Click on each feature to see full OSM metadata

<img width="838" alt="screen shot 2017-10-11 at 2 17 03 pm" src="https://user-images.githubusercontent.com/550895/31458751-fda875d6-ae8e-11e7-985d-93885884957b.png">

![image](https://user-images.githubusercontent.com/550895/31458871-54c81ea2-ae8f-11e7-82aa-c11749494ee7.png)


# 5. Reflection

Provide a 2 page reflection document to CULearn. In this document you considered the 3 platforms, the process of capturing data all the way to the posting of your final photo in OSM, you will discuss challenge, insights, things you found enjoyable, provide suggestions on how to improve the process, and etc.. You will express what you learned.  End your reflection by discussing this form of databased citizenship.


### Example

If you've added a bench in OpenStreetMap & Mapillary, explain which OSM tag you've used and reference the OSM wiki article [amenity=bench](http://wiki.openstreetmap.org/wiki/Tag:amenity=bench).


# FAQ

Reference the [GitHub Issue](https://github.com/TraceyLauriault/COMS2200A/issues) section for FAQ
