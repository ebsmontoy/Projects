# INFO-I-513 Final Project

This page documents instructions for the final project (Baseball Project.ipynb). The main thing is to download the tables used from the Lahman Baseball Database (Although they are also included in the GitHub):

Home page for the Lahman Baseball Database: https://sabr.org/lahman-database

Description of database structure: https://sabr.app.box.com/s/2q4p9j72orkim18j9ghjjqfras5m68nl/file/2084264159478

List of the different tables: https://sabr.app.box.com/s/y1prhc795jk8zvmelfd3jq7tl389y6cd

For this project, I used the Teams.csv, Batting.csv, BattingPost.csv, and SeriesPost.csv files.

Once loaded, the project file should run as normal with the different funtions and filters present.

The conpow_adder function assists in making and formatting ratios of any tables with contact hits and power hits.
Other functions are for streamlining formatting such as condensing the winning tables and adding ratio lines to plots.

Standard Python modules are used such as pandas, matplotlib.pyplot, seaborn, and sklearn.
However, mord is used for ordinal regression and XGBoost was used as a last minute observation so those modules are in this notebook.
