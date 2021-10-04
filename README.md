# LMM-case-study-master-BOE

Using LMM in behavioural ecology (personality traits) - Frédéric Silvestre

Biological context: 
The mangrove rivulus is a fish species living in the Caribbean mangroves, from Florida to Brazil. It is characterized by a unique breeding system: they alternate cross-fertilization (between males and hermaphrodites) and self-fertilization (in hermaphrodites). In the wild, we observe different levels of self-fertilization depending on the ratio males/hermaphrodites. The studied population in Florida has a very low level of males (and then more self-fertilization and a very low level of genetic diversity), while the studied population in Belize shows a high level of males (and then more cross-fertilization and higher genetic diversity). We are studying the behaviour of these fish, mainly what is called the personality traits (boldness, exploration, aggressiveness, etc). The question is to know if fish from the two studied populations show the same level of personality (meaning individuality) or if individuals from the population with low genetic diversity show less behavioural variability as well. The first hypothesis would involve epigenetic mechanisms. 

Dataset: 
We ran different personality tests in Florida and in Belize on about 40 individuals per population. Variables such as fish length/weight, water temperature/salinity, time of the day, etc have been recorded. Response variables are continuous and related to exploration and boldness. Importantly, each fish has been tested twice for each assay in order to evaluate the repeatability (among fish variability / (among + within fish variability)). 

Course support:
All the analysis is available on a RMD document. I will alternate the lecture between slides and the RMD document to show the codes and the choices we have to deal with. The RMD document will be available on my Github account.

Analysis workflow:
The following steps will be followed and explained.
- introduction of the biological question
- description of the dataset
- exploration of the data
- transformation of the variables
- creating the model (important notions are: fixed vs random effects; AIC; ML vs REML; varying intercept vs varying intercept+slope)
	- best random structure
	- best fixed structure
- model validation
- model visualization and interpretation
- calculate the adjusted repeatability 
- final biological interpretation

Ressources:
- Zuur et al. Mixed effects models and extensions in ecology with R
- Québec Centre for Biodiversity Science R Workshop Series: https://qcbsrworkshops.github.io/Workshops/

R main packages:
- lme4
- rptR
- car
- ggplot2




