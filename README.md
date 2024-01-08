# Expanding-and-invading-plant-species-affect-small-mammal-ecology
Read Me
Expanding and invading plant species in sagebrush steppe affect multiple aspects of small mammal ecology.
Aaron C. Young1, Tracey N. Johnson2
1 College of Natural Resources, University of Idaho, 875 Perimeter Drive MS 1136, Moscow, Idaho 83844-1136, USA
2 College of Natural Resources, University of Idaho, 322 E Front Street, Boise, Idaho 83702, USA
Correspondence: Aaron C. Young, Department of Fish, Wildlife, and Conservation Ecology, New Mexico State University, 2980 S. Espina, Knox Hall 132, P.O. Box 30003, MSC 4901, Las Cruces, New Mexico, 88003-8003, USA. Email: aarony@nmsu.edu

ABSTRACT Invasion and expansion of non-native and native plants have altered vegetation structure in many terrestrial ecosystems. Small mammals influence multiple ecosystem processes through their roles as ecosystem engineers, predators, and prey and changes to vegetation structure can affect habitat use, community composition, and predator-prey interactions for this assemblage of wildlife. In the sagebrush (Artemisia spp.) shrublands of the western United States, invasion by non-native grasses and expansion of native conifer trees beyond their historical range has altered vegetation structure. These changes may potentially affect distributions and interactions of deer mice (Peromyscus maniculatus), which are generalist omnivores, and Columbia Plateau pocket mice (Perognathus parvus), more specialized granivores. To assess the extent to which altered habitat affects small mammal density, survival, and home-range size, we examined these aspects of small mammal ecology along a gradient of cheatgrass (Bromus tectorum) invasion and western juniper (Juniperus occidentalis) establishment in sagebrush shrublands in southwestern Idaho, USA. From 2017–2019, we used a spatially explicit mark-recapture design to examine attributes of small mammal ecology along an invasion gradient. We did not find support for an effect of cheatgrass cover on density or survival of either species. Home-range size of deer mice was 2.3 times smaller in heavier cheatgrass cover (60%) compared to areas with little or no cheatgrass cover. Density of deer mice was highest (5 individuals/ha) in areas with 10% juniper cover and decreased with increasing juniper cover, whereas density of pocket mice was positively influenced by shrub cover. Survival of deer mice declined as juniper stem density increased. Conversely, survival of pocket mice increased with increasing juniper stem density. We found evidence for interspecific interactions between these 2 species, in the form of a density-dependent effect of deer mice on pocket mouse home-range size. Home-range size for pocket mice was 2 times smaller in areas with the highest estimated density of deer mice compared to areas with low densities of deer mice. Our data provides unique information about how small mammals in the sagebrush steppe are affected by expanding and invasive plant species and potential ways that habitat restoration efforts, in the form of conifer removal, may influence small mammals. Understanding the response of small mammals to conifer expansion or removal may shed light on the demographic and numerical responses of other wildlife associated with the sagebrush biome, including predators.


Data and File Descriptions
captrapvegxl9.xls – Raw data file for all small mammal captures and recaptures, 2017 -2019, May-August. Contains two tabs; cap = record of individual animal captures, trapveg = trap specific vegetation measurements.
‘cap’ tab columns
•	Year = study year
•	Point = trapping grid; 2017 n = 148 traps/grid, 2018-2019 n = 64 traps/grid
•	Trap = Individual trap identifier within grid
•	Period = 1 or 2; two trapping sessions at each grid per year
•	session = study year
•	ID = PIT tag identifier
•	Occasion = day of trapping (1-9) at a specific grid an animal was captured or recaptured
•	species = species trapped at specific date and time. Only deer mouse (Peromyscus maniculatus, PEMA) and Columbia Basin pocket mouse (Perognathus parvus, PRPA) were analyzed.
•	moon.fraction = phase of the moon from absent = 0 to full = 1
•	day = study day
•	Detector = Trap identifier within individual grids
‘trapveg’ tab columns
•	Session = study year
•	Point = trapping grid; 2017 n = 148 traps/grid, 2018-2019 n = 64 traps/grid
•	Trap = Individual trap identifier within grid
•	x, y = coordinates for individual traps
•	Session1 = 5 day trapping effort; 1 = trap open, 0 = trap closed 
•	Session2 = 4 day trapping effort; 1 = trap open, 0 = trap closed 
•	Count.AR = Count of low sagebrush (Artemesia arbuscula) within 1 m of individual traps.
•	Height = Height (cm) of tallest low sagebrush within 1 m of individual traps.
•	Count.TR = Count of big sagebrush (Artemesia tridentata) within 1 m of individual traps.
•	Height = Height (cm) of tallest big sagebrush within 1 m of individual traps.
•	Native.Cover = Categorical cover estimate for native grass species within 1 m of individual traps.
•	Non.Native.Cover = Categorical cover estimate for non-native grass species within 1 m of individual traps.
•	Total.Cover = Combined categorical cover for non-native and native grass species within 1 m of individual traps.
•	Antelope = Count of antelope bitterbrush (Purshia tridentata) with in 1 m of individual traps.
•	Ant..Height = Height (cm) of tallest antelope bitterbrush within 1 m of individual traps.
•	Date = date of the morning traps were processed.

Folders
Survival
•	moon phase – 0-1, 0 = no moon, 1 = full moon
•	Survival juoc mean 7-2020 – juniper cover from the center of each grid at 50, 100, 150, and 200 m scales.
•	survival_covariates
o	count.juoc – physical count of all juniper stems within 50 m of the center of the trapping grid
o	den.juoc – conversion of count.juoc to density
o	den.all2 – den.juoc*den.juoc
o	m.hght – mean height (m) of juniper
NLCD Big Clips
Rasters of NLCD landcover variables for density analysis
JUOC rasters
Rasters of juniper cover estimated using a supervised classification and ground truthing. 
•	2017-2018 JUOC Raster – juniper cover 2017-2018
o	JUOC8x8Cover – used only as a reference to set map projection
•	2019 JUOC Raster – juniper cover 2019. A small amount of juniper was removed from one grid in fall 2018 which this raster accounts for.
Home Range
Density estimates for deer mice and pocket mice derived from density analyses. Used to test for inter- and intra-specific interactions.
