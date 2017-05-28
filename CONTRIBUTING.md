### Contributing to the Global Sprint

Thanks for your interest in contributing to the 'Peek District' for the Mozilla's Global Sprint 2017.

This is our Github presence during the Global Sprint running June 1-2, 2017.

I'll be based out of the Mozilla London office which is currently in the timezone UTC +1 or British Summer Time (BST).

These files will be changing, especially in the lead up to the that event date.

### Participation Guidelines

This project adheres to a [code of conduct](https://www.mozilla.org/en-US/about/governance/policies/participation/). By participating, you are expected to uphold this code. Please report unacceptable behavior to davross@protonmail.com.

---

### How to Get Started

To start with, we are eleborating upon other people's work on Open Street Map. This is already not a unique project, and your contribution will assist a greater privacy effort globally.

As a reflection of this, we are initially using the same framework they have started. We will not be using a collaborative database, as Open Street Map will handle this for us.

If you have suggestions or changes to this initial workflow, [create an issue](https://github.com/peekdistrict/peekdistrict/issues), or submit a change as set out in the next section.

### How to Submit Changes to this Github Repo

Once you've identified one of the issues above that you feel you can contribute to, you're ready to make a change to the project repository!

  1. [Fork](https://help.github.com/articles/fork-a-repo/) **this repository**. This makes your own version of this project you can edit and use.
  2. [Make your changes](https://guides.github.com/activities/forking/#making-changes)! You can do this in the GitHub interface on your own local machine. Once you're happy with your changes...
  3. **Submit a** [pull request](https://help.github.com/articles/proposing-changes-to-a-project-with-pull-requests/). This opens a discussion around your project and lets the project lead know you are proposing changes.

First time contributing to open source? Check out this free series, [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

### Contributing Data to Open Street Map

#### How to Map on Open Street Map

As a rather long standing opens source project, Open Street Map has a large number of ways to contribute open data. More specifically to Peek District we will:

  1. add a node to the map
  2. tag the node as a point of interest with `man_made=surveillance`
  3. (TBD is this all we need?? The German project goes into way more depth. Camera type, owner, etc.)

Using one of the following:

  * local knowledge - locations might be near you every day, you could note them in a pad/draw a rough map, or use very recent memory (mark any approximations in OSM with `fixme=*`)
  * take a photograph or video recording - if the area is of tight security this may flag your activity.
  * GPS tagging - ODK Connect (requires a more advanced workflow but allows you to locally collect into a spreadsheet/database) ([Android](https://play.google.com/store/apps/details?id=org.odk.collect.android)), for more simpler workflows - OsmAnd ([Android](https://play.google.com/store/apps/details?id=net.osmand) [iOS](https://itunes.apple.com/app/id934850257)), Maps.Me ([Android](https://play.google.com/store/apps/details?id=com.mapswithme.maps.pro) and [iOS](https://itunes.apple.com/app/id510623322)), Mapillary ([Android](https://play.google.com/store/apps/details?id=app.mapillary) and [iOS](https://itunes.apple.com/us/app/mapillary/id757286802)), OpenStreetCam ([Android](https://play.google.com/store/apps/details?id=com.telenav.streetview) and [iOS](https://itunes.apple.com/app/id1089548849)) etc.
  
Most of those smartphone app allow you to also directly add a node into OSM. If you use one of the other methods, you will then need to add a node to OSM along with a tag (remember it's `man_made=surveillance` that we'll be) using one of the following: 

  * On the Web - OSM's ID editor [Wiki](https://wiki.openstreetmap.org/wiki/ID) and [Login](www.openstreetmap.org/login?referer=%2Fedit%3Feditor%3Did)
  * Desktop app - OSM's JOSM editor [Wiki](http://wiki.openstreetmap.org/wiki/JOSM) and [Download](https://josm.openstreetmap.de/)

You could even contribute to Peek District in the comfort of your home by looking for surveillance cameras using street-level imagery:

  * Mapillary 
    * [Web](https://www.mapillary.com/app)
    * ID (right side buttons > map data > photo overlay > Mapillary)
    * JOSM (add the Mapillary plugin > edit > preferences > plugins > mapillary > install | top menu > imagery > Mapillary)) 
  * OpenStreetCam
    * [Web](https://openstreetcam.org/map/) | [Web London centred](https://openstreetcam.org/map/@51.484803739516046,-0.20187377929687503,11z)
    * (more TBD this method is also missing from the [OSM wiki page](http://wiki.openstreetmap.org/wiki/Pick_your_mapping_technique#openstreetcam) but I assume it's the same as Mapillary?)

### Maintainers

The repository is currently maintained by [@bunnybooboo](https://github.com/bunnybooboo).

### How to Report Bugs

Notice a mistake? Please file any bugs, requests, or questions in [our issue tracker](https://github.com/mozilla/peekdistrict/peekdistrict/issues)
