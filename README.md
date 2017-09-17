# COMS2200A Big Data Society
## Crowdsourcing, Carleton University

## Overview

- 1. Create Accounts
- 2. Add photos to Mapillary
- 3. Research OSM Wiki
- 4. Edit OpenStreetMap features
- 5. Add Mapillary IDs to OpenStreetMap features
- 6. Create a report of which OSM tags was used in your edits

## 1. Accounts

**Note**: When creating the following accounts below, you might want to check your junk mail for the e-mail confirmation response.

### [Mapillary](https://mapillary.com)

Download the Mapillary App on one of your smart devices:

> https://help.mapillary.com/hc/en-us/categories/115000235529-Mapillary-apps

**Note:** Login using Facebook or Gmail, this application does require access to some personal information, like your name and image, from a Facebook or Gmail account. In addition, it asks to allow access to your camera and location.

![image](https://user-images.githubusercontent.com/550895/30525484-399b2ba0-9bd5-11e7-88f0-3ade8a4f4618.png)

### [GitHub](https://github.com)

Create a GitHub Account:

> https://github.com/join

![image](https://user-images.githubusercontent.com/550895/30525495-96828c82-9bd5-11e7-8415-2de1a4780717.png)

### [OpenStreetMap](https://www.openstreetmap.org)

Get an OpenStreetMap Account:

> https://www.openstreetmap.org/user/new

![image](https://user-images.githubusercontent.com/550895/30525504-c2a50a2e-9bd5-11e7-90dd-29749ceb94d3.png)

## 2. Add photos to Mapillary

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

While navigating to each of your photos, you can expand them to be fullscreen by clicking on the topright of the map which is located on the bottom left.

![image](https://user-images.githubusercontent.com/550895/28599439-8fea60c0-7178-11e7-8415-a7bf349d2f61.png)

### Copying Photo Keys

Using the web platform of Mapillary, expand the Image details by click on the 3 dots at the bottom right and expanding the Advanced Options. You will find both an **Imagey Key** & **Sequence Key**, these keys will be needed to submit to OpenStreetMap and for your assignment.

![image](https://user-images.githubusercontent.com/550895/30525820-453ef692-9bdc-11e7-9c36-e9b663887d75.png)

### OpenStreetMap

OSM (OpenStreetMap) is a crowdsourced database of Geographic real-world data.

- [ ] Make an [OpenStreetMap account](https://www.openstreetmap.org/user/new).
- [ ] Edit your first feature in OSM using [iD Editor](http://www.openstreetmap.org/edit?editor=id#map=16/45.3847/-75.6968).
- [ ] Learn more how to use [OSM iD editor](http://learnosm.org/en/beginner/id-editor/)

![image](https://user-images.githubusercontent.com/550895/28646997-8a09cc44-7232-11e7-93b5-816bb3134c13.png)

### Turbo Overpass

Turbo Overpass allows you to easily query OSM features based on specific metadata.

- [ ] Add a `mapillary` tag to an OSM feature using the appropriate Mapillary ID
- [ ] Generate an Overpass Query using the Wizard (`mapillary=*`)

![image](https://user-images.githubusercontent.com/550895/29582393-8b14044c-874a-11e7-96dd-a47704605521.png)

### Turbo Overpass - Example

Here's an example of an OC Transpo bus station which captures OSM features (bus stop, bench, garbage bin, newspaper stand) and tagging those featuers to a Mapillary ID.

- [ ] Open the following query: http://overpass-turbo.eu/s/rbf
- [ ] Click on Mapillary ID to open the Mapillary photo which the feature is referencing to.

![image](https://user-images.githubusercontent.com/550895/29582353-64524f4e-874a-11e7-93cb-16325fe7bc67.png)

## Deliverables

- Provide account credentials:
  - [ ] OpenStreetMap username (ex: [DenisCarriere](http://www.openstreetmap.org/user/DenisCarriere))
    - [ ] Add information to your OSM profile
  - [ ] Mapillary username (ex: [deniscarriere](https://www.mapillary.com/app/user/deniscarriere))
- Add a minimum of 25 photos to Mapillary & provide Mapillary IDs (ex: [`aMIdhFd4S2QYjx9aBqgK0w`](https://www.mapillary.com/map/im/aMIdhFd4S2QYjx9aBqgK0w))
- Add a minimum of 25 OSM features & provide OSM IDs (ex: [node/4413431972](https://www.openstreetmap.org/node/4413431972))
- Provide short written description of the OSM features you decided to added and references to the OSM wiki page
  - **Example**: If you tagged benches, explain which OSM tags was used and the OSM wiki reference [amenity:bench](http://wiki.openstreetmap.org/wiki/Tag:amenity:bench)
- Tag 5 OSM features with the most appropriate Mapillary photo IDs.
- Provide Turbo Overpass query link which shows those 5 features (ex: http://overpass-turbo.eu/s/rbf)

