# Wolves of the sea: Human wildlife conflict in an increasingly tense ocean

## Project Information

### Brief Summary

This project examines human-wildlife conflict in marine environments, an issue that has received less attention than its terrestrial counterpart despite being widespread and likely to increase with successful predator conservation. I explore whether management strategies from land-based conflicts can be applied to the ocean or if unique challenges require new solutions. I synthesize evidence of marine human-wildlife conflicts and highlights key differences that necessitate a marine-specific approach. I also emphasizes the importance of addressing both real and perceived conflicts, as well as underlying human-human conflicts. As predator populations recover, there is an urgent need for effective management strategies that balance marine conservation with human safety and industry.

### Abstract

Human-wildlife conflict has been receiving increased scientific and management attention, predominantly in terrestrial systems, as a side effect of successful predator conservation and recovery. These same conflicts exist in the ocean; however, they are mostly regarded in a region- or taxa-specific context despite evidence that human- wildlife conflict is prevalent across the global oceans and likely to increase as a result of successful conservation measures. Can the lessons learned from conflicts on land promote more sustainable success in the sea? Or, do ocean human-wildlife conflicts create unique challenges that require new solutions? This paper synthesizes evidence from human-wildlife conflicts in the ocean and provides initial suggestions for progressing with ef- fective management in the ocean. Humans have extensive experience managing conflict with terrestrial pre- dators and several of the strategies are transferable to marine predators, but several important differences be- tween systems necessitate a marine-specific focus and evaluation of existing mitigation strategies. Further, in managing marine wildlife conflict, it is crucial to recognize that perceived conflicts can be just as important as actual conflict and that, in many cases, human-human conflict is at the root of human-wildlife conflict. As efforts to recover important predator populations continue, humans are faced with the exciting opportunity and a new necessity to constructively manage these recoveries to continue to meet goals for marine conservation while simultaneously promoting human safety and industry in the seas.

### Author

**Ana Sofia Guerra, PhD**

### Institution

This work was conducted while funded by the University of California Santa Barbara

### Citation

Guerra, Ana Sofia. *"Wolves of the Sea: Managing human-wildlife conflict in an increasingly tense ocean."* **Marine Policy** 99 (2019): 369-373. [link](https://www.sciencedirect.com/science/article/abs/pii/S0308597X18303208)

## This Repo

This repo provides the code for visualizing data and developing three figures present in the paper:

#### **Figure 1**

Illustrates the difference between published scientific papers referencing human-wildlife conflict in marine (black) and terrestrial (gray) systems between **1990 and 2017**.

Searches were conducted using the following terms in *Web of Science*:\
- **"human-wildlife conflict"**\
- **"human wildlife conflict"**\
- **"predator conflict"**\
- **"wildlife"**

A paper was classified as marine if it was based on a marine system or, in reviews, if marine examples were mentioned.

#### **Figure 2: Evidence of Increasing Conflict in Selected Areas**

-   **(A)** Increase in depredation events per gear set by killer whales (*Orcinus orca*, black) and sperm whales (*Physeter macrocephalus*, gray) in Alaskan fisheries [1,2].\
-   **(B)** Increase in shark attacks per year in the USA (black) and Australia (gray) [3].

##### **References**

1.  **Peterson, M.J., et al.** (2013). *Killer whale (*Orcinus orca*) depredation effects on catch rates of six groundfish species: implications for commercial longline fisheries in Alaska.* **ICES Journal of Marine Science, 70**(7), 1220–1232.\
2.  **Schotte, R., & Pemberton, D.** (1999). *Development of a stock protection system for flexible oceanic pens containing finfish.* Fisheries Research and Development Corporation and Tasmanian Salmonid Growers.\
3.  **Chapman, B.K., & McPhee, D.** (2016). *Global shark attack hotspots: Identifying underlying factors behind increased unprovoked shark bite incidence.* **Ocean & Coastal Management, 133**, 72–84.

### Repo Structure

-   `wos_figures_script` for generating figures figures.
-   `data`: All the data are available upon request. They are contained in this folder and are sourced in code using relative paths.
-   `hwconflict_wos_search.csv`: Results from web of science search regarding human-wildlife conflict. (see methods).
-   `depredation_wos_search.csv`: Results from web of science search regarding depredation (see methods).
-   `conflict_lit_data.csv`: Data on whale depredation and shark attacks pulled from literature (see methods)

