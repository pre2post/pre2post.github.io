---
title: "Scene Page"
layout: single
permalink: /docs/scene
sidebar:
  nav: "docs"
---

## Overview

The _Scene_ page shows information related to a single scene within the script, with tabs for:

* Text - the scene's text

* Set Ups - the list of set ups defined for the scene

* Coverage - visual representation of the portions of the scene covered by the set ups


## Text 

The _Text_ tab provides the scene text, showing the location, whether interior/exterior and time of day in a header block.

![](/assets/images/scene-text.png)


## Set-Ups

A `Set Up` represents a particular configuration of the lighting and camera equipment within a location for recording a scene.

When initially selecting the tab for a scene, there will be no set ups defined:

![](/assets/images/scene-setups-none.png)

Selecting the `+` button at the bottom right of the page will open a dialog to add a new set up:

![](/assets/images/scene-setup-add.png)

The Scene number will be displayed at the top of the page, along with the set up name. If the first setup for the scene, then the name will be blank. However subsequent setups will have a letter which will automatically be incremented for each new setup.

The `Shot Type` and `Camera Motion` are mandatory fields that need to be specified.

The `Shot Start` and `Shot End` fields are optionally. If not defined, then the set up will cover the complete scene - otherwise a portion of the scene can be specified. For long scenes, this can be useful in identifying only parts of the scene that need to be recorded with a particular configuration (i.e. set up).

Finally, there is an optional `Details` field that can be used to elaborate more on the Director of Photography's (DoP's) vision.

Once the set ups have been created, they will be summarised in the set ups list:

![](/assets/images/scene-setups.png)

The context menu associated with each list entry offers the ability to `Edit` and `Delete` the set ups.


## Coverage

The _Coverage_ tab provides a visual representation of the set ups and which parts of the scene they cover.

![](/assets/images/scene-coverage.png)

In the above example, the first two set ups (e.g. the default and `A`) extend over the whole scene, but `B` starts part way through.

