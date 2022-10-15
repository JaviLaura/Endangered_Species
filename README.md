# Endangered_Species
The Red List of Threatened Species, founded in 1964, is the world's most comprehensive inventory of the global conservation status of biological species. It uses a set of criteria to evaluate the extinction risk of thousands of species and subspecies. With its strong scientific base, the IUCN Red List is recognized as the most authoritative guide to the status of biological diversity. IUCN has tasked you with vizualizing data from their API in order to better understand the current state of endangered species worldwide.

Part 1
Begin by creating a histogram of the count of endangered species per country. Then add this information into a DataFrame and analyze the summary statistics to describe the distribution of endangered species across countries. Specifically, do a few countries contain most of the endangered species, or is it distributed evenly? Why does the graph appear the way it does?

API Source: https://apiv3.iucnredlist.org/api/v3/docs?ref=apilist.fun

Juni API Access Token: 9bb4facb6d23f48efbf424bb05c0c1ef1cf6f468393bc745d42179ac4aca5fee

Part 2:
Now investigate the counts of categories amongst endangered species. Vizualize this as a lineplot! Plot the category codes on the x-axis, and the counts on the y-axis. Even though the categories are discrete categorical variables, we'll use a lineplot since there is a progression in severity that we want to capture (Least Concern -> Extinct).

Possible categories and respective descriptions are found in the dictionary below.
