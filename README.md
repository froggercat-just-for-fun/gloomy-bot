# Purpose

Providing user interfaces to various sheets and databases for dat gacha lyfe.

It might also be cool to have this tied to some of the other games that I play .... Sims 4, Harvest Moon ... I'm really wondering if there's an easy way to input data without hogging too much memory.

Currently, the following interfaces are planned:

* Star Ocean Anamnesis
  * [x] Airtable sheet with full data store
  * [] Easier UI via discord.
    * Auto-generate my Daily Results record to associate with my bars
    * Guess at which mutual i'm typing so I don't have to type full names and crap
    * Give me some quick stats on the mutual after I enter in the data
    * Provide a querying mechanism to see how a given mutual is doing
    * Ideally ... somehow improve the godawful speed of the Airtable UI things, I'm pretty sure it loads in all of the connected records in memory when I load a record tile.
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
  * [] Help me choose which characters I should focus on to do my best on my next event
    * Given a list of events I'm going to run this week, what parties should I make?
    * Even better ... generate the list of events I'm going to run this week.
  * [] Would be cool to have an ongoing events database to track rewards, exp ... although there's a google sheet for that
  * [] Would be cool to tell me if there are any character draws I should watch out for to increase my character stats
  * [] Would be cool to tell me where my status vulnerabilities are
  * [] Is there a way to tell whether my team is ready for HDT, etc. etc.
  * [] Tell me the difficulty of a given event based on my team stats
