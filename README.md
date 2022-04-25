# FEH (Fire Emblem Heroes)
## Overview
Scraping data off [Fire Emblem Heroes Wiki -- Specialized charts](https://feheroes.fandom.com/wiki/Specialized_charts) and analyzing the data for fun.

Fire Emblem Heroes is a mobile strategy game that released in February 2017.

-------------------------------------------
## To Do
- Load dataframes into SQL database
- Run queries for fun, yay

-------------------------------------------
### Successfully scraped tables

- [Raw Level 40 Stats Table](Images/lvl40_stats_df_RAW.PNG)

  - [Split Hero column into Name and Epithet, and Weapon_Type column into Color and Generic Weapon Type](Images/lvl40_stats_df.PNG)
  
- [Hero Skills Table](Images/hero_skills_df.PNG)

- [Superassets and Superflaws Table](Images/super_assetflaws_df.PNG)

- [Hero Availabilty Table](Images/hero_availability_df.PNG)
  - Converted table to dataframe with hero names as first column
