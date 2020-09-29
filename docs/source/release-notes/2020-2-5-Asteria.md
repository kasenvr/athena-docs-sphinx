# Alpha 2020.2.5 Asteria Release Notes

This version of Vircadia is an update to 2020.2.4. It is compatible with the 2020.2.0-Asteria protocol. This version was released on September 6th, 2020.

## Interface (Codename Athena)

The numbers at the end of each item are the PR numbers in the Project Athena [repo](https://github.com/kasenvr/project-athena/).

#### General

* Application: Improve performance of entity updates. (#276)
* Application: Allow resolving of relative URLs when importing entities with JSON. (#586, #672)
* App: Add incremental suffix to cloned entities' names using the Create app. (#603)
* App: Update the `colorSpread` color-picker and other misc. fixes in the Create app. (#606)
* API: Add `About` JavaScript API to replace the now deprecated `HifiAbout` API. (#624)
* Application: Fix freezing when opening the Avatar app when custom bookmarks are present that do not have thumbnails. (#631)
* UI & Security: Improve the OAuth2 domain feature to not show on domains that do not have it enabled; also enable persistence of logins. (#639)
* App: Add update notification message on Interface start if a new version is available. (#658)

#### Miscellaneous

* Application: Code-signing has been re-enabled on Windows. (#303)
* Application: Improve the handling of C++ exceptions by Crashpad on Windows. (#441)
* App: Update the URLs to the default particle and image entities for the Create app. (#604)
* Docs: Update build docs to include parameters for building client and server only packages. (#652)
* Application & Docs: Update the application folder icons for Vircadia on OSX; update build docs for OSX to be more up to date. (#653)

## Domain Server

The numbers at the end of each item are the PR numbers in the Project Athena [repo](https://github.com/kasenvr/project-athena/).

#### General

* Server: Improve performance of entity updates. (#276)
* UX: New metadata fields added to improve domain details alongside the addition of an HTTP exporter that makes this data publicly available as JSON over HTTP if desired. (#465)
* UI: Updated text references from High Fidelity -> Vircadia in the `Assignment` tab of the domain-server panel. (#641)

## Metaverse Server (Codename Iamus)

The metaverse server has been renamed to [Iamus](https://github.com/kasenvr/iamus), known as Apollo's son in Greek mythology. It is beginning active testing with the wider Vircadia community. The [metaverse server interface](https://github.com/kasenvr/project-iamus-dashboard) is under continued development.

## Vircadia Launcher (Codename Pantheon)

[Vircadia's launcher](https://github.com/vircadia/pantheon-launcher) has not had any updates since the last release (2020.2.4 Asteria).

## Extra Applications

#### Explore App

The numbers at the end of each item are the PR numbers in the Project Athena [repo](https://github.com/kasenvr/project-athena/).

* The Explore app UI is getting a complete visual and interaction overhaul, courtesy of Vircadia collaborator Madders! (#654)

#### Community Apps

The numbers at the end of each item are the PR numbers in the Community Apps [repo](https://github.com/kasenvr/community-apps). 

There are a few apps in active development... The Slider app will be wrapped up as v1.0 soon. The Inventory app will see major improvements and the addition of a marketplace for community content. Alongside this, there are various apps and scripts created by collaborators awaiting addition to Vircadia's main repositories.

## Documentation

#### User Docs

The numbers at the end of each item are the PR numbers in the Vircadia-Docs-Sphinx [repo](https://github.com/kasenvr/vircadia-docs-sphinx). 

* Release notes for 2020.2.5 Asteria. (#76)

#### API Docs

The API docs are generated from the software source [repo](https://github.com/kasenvr/project-athena).
The latest live deployment source can be viewed [here](https://github.com/kasenvr/vircadia-api-docs).

* The `Stats` API was updated to include two new properties. (#276)
* The `About` API was added to replace the deprecated `HifiAbout` API. (#624)
