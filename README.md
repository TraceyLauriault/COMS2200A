# COMS2200A Big Data Society
## Crowdsourcing, Carleton University

## Overview

1. [3 accounts](#accounts)
2. [20 Mapillary Photo keys](#mapillary)
3. [OSM Photo Metadata Tags](#openstreetmap)
4. [Uploading & Tagging photos in OSM](#upload)
5. [Reflection](#reflection)

# Accounts

## 1. 3 Accounts

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

### [OpenStreetMap](https://www.openstreetmap.org)

Get an OpenStreetMap Account:

> https://www.openstreetmap.org/user/new

![image](https://user-images.githubusercontent.com/550895/30525504-c2a50a2e-9bd5-11e7-90dd-29749ceb94d3.png)

# Mapillary

## 2. 20 Mapillary Photo keys

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

### Copying Photo Keys

Using the web platform of Mapillary, expand the Image details by clicking on the 3 dots at the bottom right and expand the Advanced Options. You will find both an **Imagey Key** & **Sequence Key**, you will need these keys to submit to OpenStreetMap and for your assignment.

- **Image Key**: This key is the unique identifer of the individual image (this will be the key used in your assignment & tagging into OpenStreetMap)
- **Sequence Key**: This key identifies the entire sequence of the entire photo collection.

![image](https://user-images.githubusercontent.com/550895/30525877-df64775a-9bdd-11e7-8c31-734b4a93d29f.png)

# OpenStreetMap

## 3. OSM Photo Metadata Tags

OSM (OpenStreetMap) is a crowdsourced database of Geographic real-world data.

### Edit your first feature in OSM using [iD Editor](http://www.openstreetmap.org/edit?editor=id#map=16/45.3847/-75.6968).

Once your Mapillary photos have been uploaded, you are ready to map your first feature in OpenStreetMap using your street level photos you've collected around your neighbourhood.

Using the iD Editor, zoom in to the location of where your Mapillary photos were taken.

[Click here to Zoom in to Carleton University](https://www.openstreetmap.org/#map=16/45.3846/-75.6962)

![image](https://user-images.githubusercontent.com/550895/30526012-a89f6966-9be0-11e7-8bad-458a763f02f3.png)

Click on the Edit button on the top left and the map will change to a satelitte view with an edit menu on the left hand side.

![image](https://user-images.githubusercontent.com/550895/30526013-ccba1d6e-9be0-11e7-9fd2-6b0f5472186f.png)

Once you've zoomed in to the area you want to map, we will enable the Mapillary previews by click on the **Map Data (F key)** on the right hand side and toggling the **Photo Overlay Mapillary** checkbox.

![image](https://user-images.githubusercontent.com/550895/30526044-64a6b204-9be1-11e7-82ca-068d73f40e76.png)

Now you are able to see both OpenStreetMap features & Mapillary photos in the iD Editor. You can preview the Mapillary photos by clicking one of the yellow dot on the map.


### Example

For an example, we will be adding this lamp post to OpenStreetMap and also including the Mapillary tag to the feature.

[Mapillary Image Key:  **baanWFHhhgFXzxwbBoOyPw**](https://www.mapillary.com/app/?pKey=baanWFHhhgFXzxwbBoOyPw&focus=photo)

![image](https://user-images.githubusercontent.com/550895/30526093-72184000-9be2-11e7-82ce-5e540a2c229d.png)

In the iD Editor we will be adding a feature using the [`highway=street_lamp`](http://wiki.openstreetmap.org/wiki/Tag:highway%3Dstreet_lamp) tag. Select the **Point** geometry shape and click on the map where the Lamp Post would be located based on the Mapillary photo & Satelitte imagery. Once you've created a point you will have have to define the type of point, search for `Street Lamp` in the left hand side.

![image](https://user-images.githubusercontent.com/550895/30526169-1c1aca4a-9be4-11e7-9a9c-b388480ca7a0.png)

Once your OSM feature is created and tagged as a `highway=street_lamp` we will now need to add the Mapillary key to the OSM Feature. In the **All tags** section, click on the (+) to expand a new field and add `mapillary=<MAPILLARY KEY>`.

![image](https://user-images.githubusercontent.com/550895/30526123-341e451e-9be3-11e7-808d-1750e4d4eb78.png)

# Upload

## 4. Uploading & Tagging photos in OSM

Once you've added your OSM Feature with the appropriate Mapillary Key you are ready to upload these changes to the live OpenStreetMap database.

1. Click on the Save button in the top menu, there will be a number next to it which indicates how many features you will be adding/modifying.
2. Include a `Changeset Comment` which describe which type of edit you've made (ex: Added Street Lamp Post).
3. Include both **Sources** & **Hashes**
  - source=`Mapillary`
  - hashes=`#COMS2200A`
4. Upload changes to OSM.

![image](https://user-images.githubusercontent.com/550895/30526225-fa8b0bf0-9be4-11e7-8bc6-f0fead168bc5.png)


# 5. Reflection

Provide short written description of the OSM features you decided to added and references to the OSM wiki page


### Example

If you've added a bench in OpenStreetMap & Mapillary, explain which OSM tag you've used and reference the OSM wiki article [amenity:bench](http://wiki.openstreetmap.org/wiki/Tag:amenity:bench).
