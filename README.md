# DnD Monsters

A data streaming project which follows the movements of several DnD monsters using `PySpark` and `Kafka`.

## Project Overview

Monsters have landed on Earth!

You must create a monster tracker to monitor their movements.

When a monster is inside a country, they cause damage to the population. However, when a monster is at sea, no damage is done.

## Challenges

- Create a field called damage; if the population is greater than 1, then divide the population by 1000 and multiply that by the strength of the monster, otherwise just return the monster strength.
- Create one stream to the console which shows the name of the country and how much damage it has taken
- Create another stream to the console which shows a dataset with the mosnters and how much damage they have caused

<hr>

Licensed under MIT.