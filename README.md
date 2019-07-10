# Purpose

Providing user interfaces to various sheets and databases for dat gacha lyfe.

Currently, the following interfaces are planned:

* Star Ocean Anamnesis
  * [x] Airtable sheet with full data store
  * [] Easier UI via discord.
  * [] Importing data from the global soa spreadsheet?
  * [] Inventory management?
  * [] Bar suggestions
  * [] Is there a way to update my Airtable sheet calculations using the API so I can tweak things using my phone ...?
* Dragalia Lost
  * [x] Requirements
    * Which event should I be running right now?
    * How many runs will I need to reach my next goal?
  * [] DAQ identification
  * [] Database design
    * Preferable to store the data in a way that I could make multiple users easily
  * [] Inputting all of the data
    * Airtable? <- probably
    * Postgres db?
    * Google sheet? (Not even sure I can read it ... ok, apparently there is a nodejs library but I'd have to use a public spreadsheet)
      * This might be a cool feature to add to my SOA sheet if I still cared about that game.
  * [] UI via discord
  * [] Calculations to determine which event I should grind to get to my next goal
  * [] Design of some sort of tracking mechanism for stats or some such
    * Apparently I can import plotly into my nodejs app to get charts and graphs and junk
  * [] Calculations of how many runs I'll need (approximately) to complete my goal
  * [] Some sort of inventory management
  