# StreetCompleteJSON ![GitHub file size](https://img.shields.io/github/size/goldfndr/StreetCompleteJSON/taginfo.json.svg)
JSON for StreetComplete

Included in [this GitHub repository](https://github.com/goldfndr/StreetCompleteJSON) are files relevant to maintaining a [taginfo project](https://taginfo.openstreetmap.org/projects) for the [StreetComplete app](https://github.com/westnordost/StreetComplete); [output here](https://taginfo.openstreetmap.org/projects/streetcomplete).

## Order
The ordering (sorting) of the JSON is as follows:
* Quests: Order matches that of [the quest types list](https://wiki.openstreetmap.org/wiki/StreetComplete/Quests). While that *can* lead to some [large](https://wiki.openstreetmap.org/w/index.php?title=StreetComplete/Quests&diff=1677832&oldid=1676648) [changes](https://github.com/goldfndr/StreetCompleteJSON/commit/2433c1a8a7c4b91a1436873af6c2430de7c0a5d8), it usually doesn't. The more frequent effect is that the JSON can lag behind [the most recent commits](https://github.com/westnordost/StreetComplete/commits/master) if quest types haven't yet been added to the list. [Other orderings are available](https://github.com/westnordost/StreetComplete/blob/master/app/src/main/java/de/westnordost/streetcomplete/quests/QuestModule.java) but the JSON currently also uses [quest icons from the OSM wiki](https://wiki.openstreetmap.org/wiki/Category:StreetComplete_Quest_Icon).
* Tags: Order within a quest is approximately derived from the code itself. Exceptions are likely if the same tag is used in more than one line in the code.

## Licensing
The JSON file(s) and CSV file(s) and MD file(s) have a [CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/) license.

For any images, the licensing terms are contained in [StreetComplete's authors.txt](https://github.com/westnordost/StreetComplete/blob/master/res/authors.txt) and you should expect CC BY-SA 4.0. Any images here are mirrored or derived from StreetComplete's source materials; please retrieve them from there so you don't need to give me credit.
