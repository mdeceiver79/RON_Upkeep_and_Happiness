RON_Upkeep_and_Happiness
========================

A script to enchance the Rise of Nations experience.

This is a project to add a number of RTS/Civ/RPG features to the RTS and Nation building game Rise of nations.

On the first release I have put it here on github so other players/modders can tweak, edit and share the script. This is free to be used by anybody.

Initial discusion + aims and planned features here: http://steamcommunity.com/app/287450/discussions/3/35219681528358730/

Current Features:

Special Units: Units will occasionally be upgraded to a more powerful version, some units will have a condition attached to them. Eg Musketeers upgrading to Continental Marines if the player has lots of boats.

Upkeep: All units cost food. Miltiary units cost gold. Cavelry costs extra food, Ships and artillery cost wood. Tanks, metal ships and planes cost oil. More units of a type the higher the upkeep will be.

Peace when trading: Having a trade route between 2 nations decreases the chance of an AI player declaring war.

Political Naming: Size, political alignment and nation are taken into account when making a nations name. Eg A small roman team run by a senate would be Roman Republic. A small turkish team run by a Monarch would be Turkish Emirate. A large Russian team with capitalism would be Russian Federation. 

Culture: More of an abstract notion this is more used to support the other features (see naming and happiness)

Global Happiness: Overall measure of nation. If you are growing you will have good happiness, if you have taken lots of casualties , have have negative growth over a sustained period or don't have enough supplies to supply your army with upkeep you will suffer a happiness loss.

Local Happiness: Each city has a happiness measure. If the city belongs to a different culture, is over crowded or far from your capital the city will suffer a loss of happiness. Low happiness (local happiness < 20) might lead to the city being damaged or a rebellion.

Installation: 

Copy file into a new folder in /Scenario/scripts

You can then select the script as part of a quick battle config menu.
You can tell the script has started by some green text saying: "Upkeep script loaded."
