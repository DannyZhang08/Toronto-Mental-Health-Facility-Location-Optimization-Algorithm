In Toronto, disparities in access to mental health services across neighbourhoods highlight inequalities in geospatial placement, a critical factor influencing service utilization. As adolescents in Toronto continue to face high rates of mental health challenges, evidence-based resource allocation offers a solution for more equitable access to appropriate services. By analyzing geospatial infrastructure and census data for each of the city's 140 neighbourhoods, an algorithm was developed to identify optimal placements for mental health services, prioritizing underserved areas. Min-max normalization is applied to public transportation route density, median after-tax income, adolescent population, and existing service density, assigning neighbourhoods a score from 0 to 1 to indicate service need. DBSCAN clustering is then used to identify clusters of high-need neighbourhoods in close proximity. The top cluster, Thorncliffe Park and Flemingdon Park was analyzed further using a fixed-radius search to identify an optimal 500m placement radius that maximizes accessibility and ensures well-distributed services for adolescents. The service-needs heatmap aligns with other studies on mental health service accessibility in Toronto, with the highest-need neighbourhoods in this model corresponding to those with the lowest accessibility. The clustering algorithm achieved a silhouette score of 0.602, indicating moderately strong clusters with room for improvement. It is recommended that policymakers use this algorithm with real-time data and adjusted weightings to identify service "cold spots" for placement. Future research should incorporate additional filtered data and account for off-limits zones in the placement optimization process. This model is adaptable to similar urban environments, provided consistent factor datasets are available.
