# NBA Archetype Discovery Project

## Summary
With the rise of positionless basketball in the NBA, the traditional five positions on the court (PG, SG, SF, PF, C) are no longer descriptive enough for determining the on-court value and skillset of a player. Using various statistical methods and data mining techniques, this project aims to identify data-driven archetypes of players that exist beyond the traditional 5 archetypes and how they have impacted teams over time. By segmenting players into clusters using performance data drawn from NBA statistics over time, we can better understand the evolution of different player archetypes and outliers that may exist.

## Data Source
The main datasource for this project will be the [NBA API](https://github.com/swar/nba_api). This api is an open source abstraction on the main stats.nba.com, making it easier to query and work with NBA data in python. Data is partitioned to include both static, up to date player and team data that can be returned in the form of multiple formats such as JSON, DataFrames, or dictionaries making this library extremely easy to work with. There will be 2 main endpoints being used to start the project:

* **Leauge Dash Player Bio Stats**: This endpoint shows base player metrics such as their traditional position, weight and height.
* **Leauge Dash Player Stats**: This is the endpoint to retrieve all player information over the source of an entire season.
