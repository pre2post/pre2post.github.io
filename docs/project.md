---
title: "Project Page"
layout: single
permalink: /docs/project
sidebar:
  nav: "docs"
---

## Overview

The Project page is displayed when a project is selected from the top level page of the app.

The project page has tabs representing the following areas:

* **Scenes** - the scenes within the script
* **Characters** - the list of characters that had dialogue within the script
* **Locations** - the list of locations that were associated with each scene
* **Crew** - the crew that will be working on the project


## Scenes

When the _Scenes_ tab is selected, it shows a list of the scenes within the script. Each entry shows the Scene number, the Location name (using the aliased name if appropriate), the Coverage (i.e. how much of the scene has been covered by a Set Up) and the percentage _Completed_ (i.e. how many of the Set Ups have had Takes recorded).

This image shows how the list of Scenes looks before any Set Ups or Takes have been defined:

![](/assets/images/project-scenes-no-coverage.png)

When Set Ups have been defined, it will be reflected in the _Coverage_ percentage. Once Takes have then been associated with those Set Ups, the _Completed_ percentage will represent that fact.

![](/assets/images/project-scenes-with-coverage.png)

The context menu for a Scene only includes one item currently:

![](/assets/images/project-scenes-menu.png)


### Send a Scene Report

Once a Scene has been completed, i.e. all appropriate Takes have been recorded for each Set Up, then a report can be sent to an editor to provide the information about all of the Takes.

This information can be a useful aid to help the editor identify which may be the best Takes for forus on, as the report includes information about the Set Ups and their coverage, as well as each Take with their optional comments and approvals.


## Characters

The _Characters_ tab displays the list of character names that are associated with dialogue within the script.

![](/assets/images/project-characters.png)

Each character entry in the list identifies the number of scenes and dialogues the character is associated with.

## Character Alias

Occasionally a script will contain references to a character but spelt in different ways. In this situation, the app would include each variation of the spelling as a different character.

To improve usability and reporting from the app, the app provides the capability to define an entry in this list as an alias of another character. This capability is available via a menu on the character entry.

Once a character is setup as an alias of another character, the list entry is changes to reflect this information.

## Locations

The _Locations_ tab displays the list of location names that are associated with scenes in the script.

![](/assets/images/project-locations-no-aliases.png)

Each location entry in the list also identifies the number of scenes that are associated with the location.

## Location Alias

As with the characters tab described above, the same location may be named slightly differently in different scenes within a script - however they represent the same location, and would ideally be associated with a single name.

The app offers the capability to define an entry in the location list as an alias of another location in the list. First step is to select the _Set Alias For..._ context menu item associated with the location entry that is the alias:

![](/assets/images/project-locations-menu.png)

The next step is to select the location the selected entry is an alias for. So in our example, we want the location **BATHROOM (HALWAY)** to be an alias for the **HALLWAY** location:

![](/assets/images/project-locations-alias-dialog.png)

Once the alias has been defined, the list entry will be updated to reflect that it is an alias for another location:

![](/assets/images/project-locations-aliases.png)

When viewing a scene that was previously associated with the alias location, it will now show the aliased location.


## Crew

The _Crew_ tab can be used to define the list of crew associated with the project.

Crew members become relevant in the following situations:

* The Director and DoP will be displayed on the clapperboard, if the app is used to announce a take and simulate the clapperboard

* The Producer(s) and Director(s) will be included in the Scene Reports

* Crew members can optionally be assigned a departmental reponsibility to approve a Take

The initial tab will contain no entries. At the bottom right of the page there are two buttons:

* Import from Contacts - contacts can be added from your Contacts book, automatically obtaining the phone number and email address if defined.

* Add a new Contact - define a contact's details from scratch.

![](/assets/images/project-crew-none.png)

If adding a new contact using the `+` button, then the app will displayed the following dialog to obtain the relevant information.

The Approval Responsibility field is optional, but can enable the crew member to provide their approval of a Take.

The Roles field enables one or more roles to be associated with the crew member.

![](/assets/images/project-crew-new-dialog.png)

If importing a contact, this will display the entries in the Contacts. Once an entry is selected it will be added to the Contacts tab list. If the imported crew member requires a role and/or approval responsibility to be configured, then select the `Edit` item from the crew member's context menu.

![](/assets/images/project-crew-list.png)

The context menu for each crew entry in the list offers the ability to `Edit` and `Delete` an entry.
