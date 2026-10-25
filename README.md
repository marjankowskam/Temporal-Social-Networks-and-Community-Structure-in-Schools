# Temporal Social Networks and Community Structure in Schools

**Summary:** Temporal network analysis of school contact data from SocioPatterns, exploring community structure, interaction patterns and gender mixing across age groups.

**Overview:**

This project investigates how social interaction patterns differ between younger and older primary-school children using the SocioPatterns face-to-face contact dataset collected in Lyon, France. It combines temporal network analysis, weighted graphs and community detection to study how children form groups during school breaks.

The analysis compares first- and fifth-grade classes using contact-duration distributions, temporal distances, reachability and temporal efficiency. Louvain community detection and modularity are used to examine group structure, alongside comparisons of same-gender and mixed-gender interactions. Additional experiments explore Girvan–Newman community detection and cosine-similarity-based edge weights.

The project examines how time aggregation and the choice of observation window affect conclusions about social networks. Exploratory findings suggest more mixing and less sharply separated communities among younger children, with conclusions limited by the small sample and short observation period.

Completed for UCL’s *COMP0123: Complex Networks and Online Social Networks* module.

**Topics:** temporal networks, social network analysis, network science, complex networks, community detection, Louvain algorithm, modularity, contact networks, SocioPatterns, computational social science.

## Main Experiments
- **Contact Duration Analysis**: `task7.ipynb`
- **Temporal Distances**: `task2.ipynb`
- **Community Detection**: `task2.ipynb`, `task5.ipynb`
- **Same versus Mixed-Gender Interaction**: `task_gender.ipynb`

## Appendices
- **Appendix A - Breaks during the Schoolday**: `task2.ipynb`
- **Appendix B - Other Community Detection Methods**: `task5.ipynb`
- **Appendix C - Normalization in Same vs. Mixed-Gender Interactions**: `task_gender.ipynb`
