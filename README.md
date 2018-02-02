# Census-Data-Anywhere

Census-Data-Anywhere is an R package that can score a given map for partisanship, according to Dr. Kenneth Mayer's model outlined in his expert testimony provided to analyze the efficiency gaps in Wisconsin's Legislative District Plan.
His expert testimony can be located here: https://static1.squarespace.com/static/559c1a7be4b0a2650c6c39b3/t/559d3dcae4b041328d05ed30/1436368330313/Exhibit+2.pdf

This package assumes a user has a map of a particular state on which they have newly-defined voter tabulation districts (VTDs). This package then adds block-level demographic data from the 2010 Decennial Census to the user's map. With newly-added demographic data, this package then assigns this block-level information to the user-defined voter tabulation districts through a spatial calculation. This allows each new geography to carry counts of the voter eligible population by race, fit to the specific VTDs the user inputs.

With this powerful information, the user is now able to score their given map for partisan leans, according to Mayer's model outlined on page 13 of his paper.

The user will be able to access this tool through a Shiny app, hosted online. 

In order to use this app, the user does need to have a Census API key. They can access one here: https://api.census.gov/data/key_signup.html
