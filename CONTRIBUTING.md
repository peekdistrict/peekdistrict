## Contributing to the Global Sprint

Thanks for your interest in contributing to the 'Peek District' for Mozilla's Global Sprint 2017.

This is our Github presence during the Global Sprint running June 1-2, 2017.

I'll be based out of the Mozilla London office which is currently in the timezone UTC +1 or British Summer Time (BST).

These files will be changing, especially in the lead up to the that event date.

### Participation Guidelines

This project adheres to a [code of conduct](https://www.mozilla.org/en-US/about/governance/policies/participation/). By participating, you are expected to uphold this code. Please report unacceptable behavior to davross@protonmail.com.

---

### How to Get Started

To start, we are simply elaborating upon other people's work on Open Street Map (OSM). This is already not a unique project, and your contribution will assist a greater privacy effort globally. Open Source projects require many hands to make things progress. Even just a few minutes of your time will improve your knowledge, but the ultimate goal is to improve the data available.

As a reflection of this, we are initially using the same workflow already started in OSM (nicely seen in the Germany based project [Surveillance Under Surveillance](https://kamba4.crux.uberspace.de/)). We will not be using a collaborative database, as Open Street Map will handle this for us. You might feel a little overwhelmed at the beginning, but the basic workflow is this:

  * See a camera - types of cameras can be found [HERE](http://www.cepro.com/article/12_common_types_of_security_cameras/)
  * Note its location - write details on your hand, on a piece of paper, in an app, etc.
  * Create a node in OSM - using one of the apps detailed below
  * Tag the node with `man_made=surveillance`
  * In the comments add the hashtag #PeekDistrict (to help us see the affect of this project)
  * Save and upload the changes

If you have suggestions or changes to this initial workflow, [create an issue](https://github.com/peekdistrict/peekdistrict/issues), or submit a change as set out in the next section.

### How to Submit Changes to this Github Repo

Contributing to Peek District could take a number of forms. You might love correcting grammar, and spelling errors. You might be a coder, and have a concept in mind to help speed up our workflow. Suggestions, fixes, improvement, amplification, are just a selection.

Once you've identified one of the issues above that you feel you can contribute to, you're ready to make a change to the project repository!

  1. [Fork](https://help.github.com/articles/fork-a-repo/) **this repository**. This makes your own version of this project you can edit and use.
  2. [Make your changes](https://guides.github.com/activities/forking/#making-changes)! You can do this in the GitHub interface on your own local machine. Once you're happy with your changes...
  3. **Submit a** [pull request](https://help.github.com/articles/proposing-changes-to-a-project-with-pull-requests/). This opens a discussion around your project and lets the project lead know you are proposing changes.

First time contributing to open source? Check out this free series, [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

OK let's add some OSM data...

## Contributing Open Data to Peek District

### How to Map on Open Street Map

#### Login or Create Your Open Street Map Account

New users can signup [HERE](https://www.openstreetmap.org/user/new). If you already have an account you can login [HERE](https://www.openstreetmap.org/login).

If you're brand new to Open Street Map a great place to start is the [OSM Beginners Guide](http://wiki.openstreetmap.org/wiki/Beginners%27_guide) or [LearnOSM Getting Started on OSM](http://learnosm.org/en/beginner/start-osm/#beginning-osm-create-an-openstreetmap-account).

As a rather long standing open source project, Open Street Map has a large number of ways to contribute open data. More specifically to Peek District we will using one of the following:

#### Noting camera location:

  * local knowledge - locations might be near you every day, you could note them in a pad/draw a rough map, or use very recent memory (mark any approximations in OSM with `fixme=*`)
  * take a photograph or video recording - if the area is of tight security this may flag your activity. Do not put yourself in any risk. Your device may also allow you to GPS tag the location the image is taken.
  * GPS tagging in a smartphone app
    * ODK Connect (requires a more advanced workflow but allows you to locally collect into a spreadsheet/database) ([Android](https://play.google.com/store/apps/details?id=org.odk.collect.android))
    * ~OsmAnd ([Android](https://play.google.com/store/apps/details?id=net.osmand) [iOS](https://itunes.apple.com/app/id934850257))~ does not seem to allow creation of surveillance node
    * Maps.Me ([Android](https://play.google.com/store/apps/details?id=com.mapswithme.maps.pro) and [iOS](https://itunes.apple.com/app/id510623322))
    * Mapillary ([Android](https://play.google.com/store/apps/details?id=app.mapillary) and [iOS](https://itunes.apple.com/us/app/mapillary/id757286802))
    * OpenStreetCam ([Android](https://play.google.com/store/apps/details?id=com.telenav.streetview) and [iOS](https://itunes.apple.com/app/id1089548849))
    * and many more!

#### Creating a node and tag in OSM:

Most of those smartphone app allow you to also directly add a node into OSM. If you use one of the other methods, you will then need to add a node to OSM, along with its `man_made=surveillance` tag and #PeekDistrict in the comments

  * On the Web - OSM's ID editor [Wiki](https://wiki.openstreetmap.org/wiki/ID) and [Login](www.openstreetmap.org/login?referer=%2Fedit%3Feditor%3Did)
  * Desktop app - OSM's JOSM editor [Wiki](http://wiki.openstreetmap.org/wiki/JOSM) and [Download](https://josm.openstreetmap.de/). Note that JOSM will require you to download a limited section of the map. When you first successfully open it: click on the `Download map data` icon > zoom into your required location > right click to drag the map > left click to select an area > select `Download` button. JOSM will download the OSM data layer. You can download a number of additional layers from: top menu > imagery. For example, you could select satellite imagery, or one of the street-level imagery plugins we'll discuss next.

Note: mapping can be a little easier if you grab your mouse or graphic tablet. It's not essential.

#### Armchair Mapping

This method doesn not require you to leave your seat! You could even contribute to Peek District in the comfort of your home by looking for surveillance cameras using street-level imagery. This will be a little trickier, however. You will need to correlate what's going on in the imagery and attempt to plot it precisely into OSM. Using one of the above methods to add a node, tag, and commented hashtag, you can look through imagery and add a node when you see a camera. London is a great place if you're not sure where to start, but you can be mapping anywhere across the globe. Rather awesome that most of the tools already let you do this with street-level imagery:

  * Mapillary
    * [Web](https://www.mapillary.com/app)
    * ID (right side buttons > map data > photo overlay > Mapillary)
    * JOSM (add the Mapillary plugin > edit > preferences > plugins > mapillary > checkbox > OK | top menu > imagery > Mapillary))
  * OpenStreetCam
    * [Web](https://openstreetcam.org/map/) | [Web London centred](https://openstreetcam.org/map/@51.484803739516046,-0.20187377929687503,11z)
    * ID (more TBD this method is also missing from the [OSM wiki page](http://wiki.openstreetmap.org/wiki/Pick_your_mapping_technique#openstreetcam) but I assume it's the same as Mapillary?)
    * JOSM (to add the OpenStreetCam plugin > edit > preferences > plugins > openstreetcam > checkbox > OK | to activate plugin > top menu > imagery > OpenStreetCam) - any new imagery will appear as a light blue circular icon, with a white arrow indicating the photograph direction. (TBD add these steps to OSM wiki)
---
### Maintainers

The repository is currently maintained by [@bunnybooboo](https://github.com/bunnybooboo).

### How to Report Bugs

Notice a mistake? Please file any bugs, requests, or questions in [our issue tracker](https://github.com/mozilla/peekdistrict/peekdistrict/issues)
