Provided are some of the tools that I have developed to display data from the iNaturalist API:

# Tools for ID-A-Thons

## ID-A-Thon Progress Bar

The [ID Progress Bar](id-progress.html) widget shows a configurable progress bar of the number of identifications for an ID-A-Thon event. It can be embedded in a journal post on iNaturalist as an iframe.

<iframe src="https://mickley.github.io/iNat-Tools/id-progress.html?own_observation=false&taxon_id=211194&place_id=10&d1=2024-11-09T00:00-08:00&d2=2024-11-09T23:59-08:00&goal=2000&mindisp=4000&name=ID-A-Thon 2024&d1comp=2024-11-08T00:00-08:00&d2comp=2024-11-08T23:59-08:00&namecomp=Previous Day" height="200" width="700" frameborder="0"></iframe>


## ID-A-Thon Leaderboard

The [ID Leaderboard](id-leaderboard.html) widget shows a leaderboard of identifications by user for an ID-A-Thon event. It can be embedded in a journal post on iNaturalist as an iframe.

<iframe src="https://mickley.github.io/iNat-Tools/id-leaderboard.html?own_observation=false&is_change=false&taxon_id=211194&place_id=10&d1=2024-11-09T00:00-08:00&d2=2024-11-09T23:59-08:00" height="300" width="450" frameborder="0"></iframe>

# Tools for Identifying

## Species Count Tool

The [Species Count](speciescount.html?place_id=1&taxon_id=40151) tool displays a list of taxa and the number of observations for each taxon for a given set of filters. It can be used to find species with few observations that might be incorrectly identified, cultivated, rare, otherwise interesting, or in need of more observations to be included in the vision model. For example, [this link](speciescount.html?reviewed=any&quality_grade=needs_id%2Cresearch&order=asc&project_id=168279&max_obs=1) shows all of the species in the [Flora of Oregon: Vascular Plants](https://www.inaturalist.org/projects/flora-of-oregon-vascular-plants) project that have only been observed once.
 
# iNatJS Javascript Wrapper Library

Hosted as a separate repository, [iNatJS](https://github.com/mickley/iNatJS), provides a flexible Javascript wrapper for interfacing with the iNaturalist API, and underpins the tools above. 