# webtrees module german-wars-battles-worldwide
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

![webtrees major version](https://img.shields.io/badge/webtrees-v2.1.x-green)
![webtrees major version](https://img.shields.io/badge/webtrees-v2.2.x-green)

![Latest Release](https://img.shields.io/github/v/release/hartenthaler/german-wars-battles-worldwide)

This module provides around 1,600 historical facts (in German language) for [webtrees](https://www.webtrees.net/) - Wars and Battles Worldwide (since 900)

The types of these events (revolt, siege, blockade, civil war, conquest, feud, campaign, combat, invasion, struggle, conflict, crusade, war, massacre, offensive, revolution, battle, naval battle, operation) are translatable.

As administrator you can modify how the historical events are presented in the timeline of a person by using the CSS&JS module
(see the [German webtrees manual](https://wiki.genealogy.net/Webtrees_Handbuch/Entwicklungsumgebung#Beispiel_-_Farben_bei_Historischen_Fakten_anpassen)).

<a name="webtrees"></a>
## webtrees

**[webtrees](https://webtrees.net/)** is an online collaborative genealogy application.
This can be hosted on your own server by following the [Install instructions](https://webtrees.net/install/).
If you are familiar with Docker, you might like to install **webtrees** using [this unofficial docker image](https://hub.docker.com/r/nathanvaughn/webtrees), or any other one.

<a name="requirements"></a>
## Requirements

This module requires **webtrees** version 2.0 or later.
This module has the same requirements as [webtrees#system-requirements](https://github.com/fisharebest/webtrees#system-requirements).

This module was tested with **webtrees** versions 2.0.11, 2.1.21 and 2.2.1.
All available themes and all other custom modules can be used together with this one.

<a name="installation"></a>
## Installation

This section documents installation instructions for this module.

1. Download the [latest release](https://github.com/hartenthaler/german-wars-battles-worldwide/releases/latest)
1. Unzip the package into your `webtrees/modules_v4` directory of your web server
1. Rename the folder to `german-wars-battles-worldwide`

## Usage
Activate this module as an admin (in Control Panel/Modules/Individual page/Historic events).

For wikipedia links in the notes Markdown formatting is used; this should be enabled for your tree. See Control panel/Manage family trees/Preferences and then scroll down to "Text" and mark the option "markdown".
If Markdown is disabled the links are still working, but the formatting isn't so nice.

Select as user "Historic events" at the "Facts and events" tab. 

<a name="upgrade"></a>
## Upgrade

To update simply replace the `german-wars-battles-worldwide` files
with the new ones from the latest release.

<a name="translation"></a>
## Translation

At the moment only the event types (chancellor, president) and metadata can be translated,
no other data.

You can use a local editor,
like Poedit or Notepad++, to make the translations and send them back to me.
You can do this via a pull request (if you know how) or by e-mail.

Discussion on translation can be done by creating an [issue](https://github.com/hartenthaler/german-wars-battles-worldwide/issues).

Updated translations will be included in the next release of this module.

There are now, beside English and German, no other translations available.

<a name="support"></a>
## Support

**Issues**: for any ideas you have, or when finding a bug you can raise an [issue](https://github.com/hartenthaler/german-wars-battles-worldwide/issues).

**Forum**: general webtrees support can be found at the [webtrees forum](http://www.webtrees.net/).

<a name="programming"></a>
## Adding new data, Programming and Testing

If you'd like to contribute to this module, great! You can contribute by

- Contributing historical facts: make you familiar with the structure of the event records; [create an issue](https://github.com/hartenthaler/german-wars-battles-worldwide/issues), then you can link your pull request.
- Contributing code: check out the issues for things that need attention. If you have changes you want to make not listed in an [issue](https://github.com/hartenthaler/german-wars-battles-worldwide/issues), please create one, then you can link your pull request.
- Testing: it's all manual currently, please [create an issue](https://github.com/hartenthaler/german-wars-battles-worldwide/issues) for any bugs you find.

<a name="license"></a>
## License

* Copyright (C) 2025 Hermann Hartenthaler
* Derived from **webtrees** - Copyright 2025 webtrees development team.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.

* * *