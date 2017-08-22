# Crowdsourcing

COMS2200A Big Data Society - Crowdsourcing, Carleton University

## To Learn

### OpenStreetMap

OSM (OpenStreetMap) is a crowdsourced database of Geographic real-world data.

- [ ] Make an [OpenStreetMap account](https://www.openstreetmap.org/user/new).
- [ ] Edit your first feature in OSM using [iD Editor](http://www.openstreetmap.org/edit?editor=id#map=16/45.3847/-75.6968).
- [ ] Learn more how to use [OSM iD editor](http://learnosm.org/en/beginner/id-editor/)
![image](https://user-images.githubusercontent.com/550895/28646997-8a09cc44-7232-11e7-93b5-816bb3134c13.png)

### Mapillary

Mapillary is a crowdsourced streetview platform which allows anyone to add & see their GPS enabled photos.

- [ ] Create a [Mapillary account](https://www.mapillary.com).
- [ ] Download the [iOS](https://itunes.apple.com/us/app/mapillary-street-level-photos/id757286802?mt=8)/[Android](https://play.google.com/store/apps/details?id=app.mapillary&hl=en) application.
- [ ] Take some photos with your Mapillary mobile application.
- [ ] Upload GPS photos using Mapillary's web platform.

![image](https://user-images.githubusercontent.com/550895/28599439-8fea60c0-7178-11e7-8415-a7bf349d2f61.png)

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
  - [ ] OpenStreetMap username (ex: [DenisCarriere](http://www.openstreetmap.org/user/DenisCarriere)
    - [ ] Add information to your profile
  - [ ] Mapillary username (ex: [deniscarriere](https://www.mapillary.com/app/user/deniscarriere))
- Add a minimum of 25 photos to Mapillary & provide Mapillary IDs (ex: [`aMIdhFd4S2QYjx9aBqgK0w`](https://www.mapillary.com/map/im/aMIdhFd4S2QYjx9aBqgK0w))
- Add a minimum of 25 OSM features & provide OSM IDs (ex: [4413431972}(https://www.openstreetmap.org/node/4413431972))
- Provide short written description of the OSM features you decided to added and references to the OSM wiki page
  - **Example**: If you tagged benches, explain which OSM tags was used and the OSM wiki reference [amenity:bench](http://wiki.openstreetmap.org/wiki/Tag:amenity:bench)
- Tag 5 OSM features with the most appropriate Mapillary photo IDs.
- Provide Turbo Overpass query link which shows those 5 features (ex: http://overpass-turbo.eu/s/rbf)

