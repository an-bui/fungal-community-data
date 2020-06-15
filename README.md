# fungal-community-data
Data and analysis to accompany Bui et al. 2020, "Soil fungal community richness and diversity are highest in arid environments along a climatic space-for-time substitution."

### Soil characteristics
#### Data
- soil_data.csv: data for subset (n = 27) of trees sampled, with site, %N, %C, P (mg/kg soil), %organic matter, total exchange capacity (meq/100g soil), NO3 (ppm), NH4 (ppm), pH, gravimetric water content (g). 
#### Analyses
- analysis of variance

### Fungal community composition
#### Data
- otu_paths.csv: taxonomic paths for all OTUs detected using FUNGuild
- fungal_abundance.csv: abundance of OTUs across samples
#### Analyses
- species richness
- species diversity
- Non-metric Multidimensional Scaling

### Community convergence
#### Data
- boot_data-1000.csv: final results of 1000 bootstrapped iterations of community convergence calculation 
#### Analyses
- community convergence: for a single community (i.e. tree), we calculated the ratio between the Euclidean distance between site centroids and the Euclidean distance between the community and its own site centroid (Supplemental Figure 2)

### Ectomycorrhizal functional traits
#### Data
- ecto_OTU_traits: fungal OTUs with functional trait assignments
#### Analyses
- chi square goodness of fit
