# Plant carbon dataset
This is a global dataset of plant carbon stocks and fluxes for terrestrial, freshwater and marine ecosystems. `Carbon.csv` contains all data which I compiled from the various datasets provided to me by Just Cebrián. These original datasets are archived in the folder `Original` for completeness. The folder `References` contains the original bibliographies provided by Just. Iterations of this dataset have been used in many publications, listed here in chronological order:

- Cebrián J, Duarte CM (1994) The dependence of herbivory on growth rate in natural plant communities. *Functional Ecology* 8:518–525. https://doi.org/10.2307/2390077.
- Cebrián J, Duarte CM (1995) Plant growth-rate dependence of detrital carbon storage in ecosystems. *Science* 268:1606–1608. https://doi.org/10.1126/science.268.5217.1606.
- Duarte CM, Cebrián J (1996) The fate of marine autotrophic production. *Limnology and Oceanography* 41:1758–1766. https://doi.org/10.4319/lo.1996.41.8.1758.
- Griffin MPA, Cole ML, Kroeger KD, Cebrián J (1998) Dependence of herbivory on autotrophic nitrogen content and on net primary production across ecosystems. *The Biological Bulletin* 195:233–234. https://doi.org/10.2307/1542856.
- Cebrián J (1999) Patterns in the fate of production in plant communities. *The American Naturalist* 154:449–468. https://doi.org/10.1086/303244.
- Cebrián J (2002) Variability and control of carbon consumption, export, and accumulation in marine communities. *Limnology and Oceanography* 47:11–22. https://doi.org/10.4319/lo.2002.47.1.0011.
- Cebrián J, Lartigue J (2004) Patterns of herbivory and decomposition in aquatic and terrestrial ecosystems. *Ecological Monographs* 74:237–259. https://doi.org/10.1890/03-4019.
- Cebrián J (2004) Role of first-order consumers in ecosystem carbon flow. *Ecology Letters* 7:232–240. https://doi.org/10.1111/j.1461-0248.2004.00574.x.
- Cebrián J (2004) Grazing on benthic primary producers. In: Nielsen SL, Banta GT, Pedersen MF (eds) *Estuarine nutrient cycling: the influence of primary producers*. Springer, Dordrecht, pp. 153–185. https://doi.org/10.1007/978-1-4020-3021-5_6.
- Cebrián J, Shurin JB, Borer ET, Cardinale BJ, Ngai JT, Smith MD, Fagan WF (2009) Producer nutritional quality controls ecosystem trophic structure. PloS One 4:e4929. https://doi.org/10.1371/journal.pone.0004929.
- Lartigue J, Cebrián J (2009) Ecosystem productivity and carbon flows: patterns across ecosystems. In: Levin SA, Carpenter SR, Godfray HCJ, Kinzig AP, Loreau M, Losos JB, Walker B, Wilcove DS (eds) *The Princeton Guide to Ecology*. Princeton University Press, Princeton, pp. 320–329. https://doi.org/10.1515/9781400833023.320.
- Cebrián J (2015) Individuals scale up carbon flow in ecosystems. *Proceedings of the National Academy of Sciences* 112:2303–2304. https://doi.org/10.1073/pnas.1500705112.

`Carbon.csv` is structured into these variables:

- `Reference` Citation
- `Ecosystem` Original category with levels "aquatic" and "terrestrial"
- `Community` Original category with levels "communities of marine phytoplankton", "communities of freshwater phytoplankton", "marine benthic microalgal beds", "freshwater benthic microalgal beds", "marine macroalgal beds", "seagrass meadows", "meadows of freshwater submerged macrophytes", "freshwater and marine marshes", "mangroves", "temperate and tropical grasslands", "tundra shrublands and grasslands" and "temperate and tropical shrublands and forests"
- `Biome` New category with levels "Phytoplankton", "Microphytobenthos", "Macroalgal forest", "Seagrass meadow", "Mangrove forest", "Saltmarsh", "Wetland", "Grassland", "Woodland" and "Tundra"
- `Plant` New category with levels "Algae", "Marine angiosperms" and "Terrestrial plants"
- `Net primary production (g C m^-2 y^-1)`
- `Leaf production (g C m^-2 y^-1)`
- `Plant biomass (g C m^-2)`
- `Detrital production (g C m^-2 y^-1)`
- `Detrital leaf production (g C m^-2 y^-1)`
- `Detrital biomass (g C m^-2)`
- `Herbivory (g C m^-2 y^-1)`
- `Herbivore biomass (g C m^-2)`
- `Decomposition (g C m^-2 y^-1)`
- `Total consumption (g C m^-2 y^-1)` Sum of `Herbivory (g C m^-2 y^-1)` and `Decomposition (g C m^-2 y^-1)`
- `Accumulation (g C m^-2 y^-1)`
- `Export (g C m^-2 y^-1)`
- `k (d^-1)` Exponential decay constant
- `Detrital nitrogen (%)`
- `Detrital phosphorus (%)`
- `Plant nitrogen (%)`
- `Plant phosphorus (%)`

Luka Seamus Wright, 7th January 2026
