Draft notes on the different type of projects that could conceivably go under the category of “open data news project”




https://github.com/fivethirtyeight/data/tree/master/congress-age
This is on the simpler scale, includes a short README explaining where the data came from and how it’s been changed, and the main data file (CSV) itself. There isn’t any scripts relating to fetching/wrangling the data or visualizing it.


https://github.com/TheUpshot/leo-senate-model
Contains a short README, the raw data, and the scripts needed to get the output that the public-facing story uses. The data seems to be hand-curated from a variety of sources. The scripts are in R and is more-or-less just-run-this-big-script.




https://github.com/washingtonpost/data-police-shootings
This is a situation in which updated data for an ongoing project is continually pushed public. The actual data collection mechanism (e.g. a spreadsheet, or whatever internal app they’ve decided to use) is hidden from the public. There’s an automated script that reads from the internal database and pushes an excerpted version of the data to Github. Some fields and rows are left out but the Git commit history is ostensibly unaltered.


https://github.com/TheUpshot/Bedfellows
This is a very specialized tool that produces output used in various Upshot stories. But it includes the seed data...the command-line tool just makes it easy for users to explore the data themselves.


https://github.com/dwillis/randpaul_donors
Not sure what story this is connected to, but contains a data fetching script and 100,000+ commits/updates, in an apparent attempt to collect data on a near real-time basis…




https://github.com/BuzzFeedNews/2016-04-federal-surveillance-planes
Contains raw data, a R Notebook narrative, and code to do the analysis and visualizations.


https://github.com/propublica/compas-analysis
One of the more comprehensive standalone examples: contains data in various stages of slicing/wrangling, a complete Jupyter notebook (R and Python via rpy2), standalone helper Python scripts, and a separate article explaining the methodology.




________________


http://boundaries.latimes.com/sets/
This is a curated collection of data that is useful for the LATimes but for California-based users in general. No scripts, just one-click downloads of the data in different formats.


https://propublica.github.io/congress-api-docs/
This is an API that contains data that the organization may use for their own stories.




https://projects.propublica.org/docdollars/
An example of a semi-transparent data project. Data was sent upon request to other news organizations. Other groups have to manually request and/or pay for the data. The application code nor the raw database behind the app is open-sourced. The tabula tool was partly developed and open-sourced during the course of the data collection of this project.