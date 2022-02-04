# FCMs-and-Immunity
Data related to the manuscript entitled: Age and spatio-temporal variations in food resources modulate stress-immunity relationships in three populations of wild roe deer

This README file was generated on 2022-02-04 by Jeffrey Carbillet

GENERAL INFORMATION

1. Title of Dataset: Dataset related to the manucript entitled "Age and spatio-temporal variations in food resources modulate  stress-immunity relationships in three populations of wild roe deer"

2. Author Information
	A. Principal Investigator Contact Information
		Name: Carbillet Jeffrey / Hollain Marine
		Institution: Institute of Ecology and Earth Sciences, University of Tartu / -
		Address: Liivi 2, 51014 Tartu, Estonia / -
		Email: jeffrey.cm@live.fr / marine.hollain@gmail.com 

	B. Associate or Co-investigator Contact Information
		Name: Verheyden Hélène
		Institution: Université de Toulouse, INRAE, CEFS
		Address: 24 chemin de Borderouge, Castanet Tolosan, 31326, France
		Email: helene.verheyden@inrae.fr

	C. Associate or Co-investigator Contact Information
		Name: Gilot-Fromont Emmanuelle
		Institution: Université de Lyon, Université Lyon 1, UMR CNRS 5558 /Université de Lyon, VetAgro Sup
		Address: Villeurbanne Cedex, 69100 France / Marcy-l’Etoile, 69280, France
		Email: emmanuelle.gilotfromont@vetagro-sup.fr

3. Date of data collection: 2010 to 2019 for the Trois-Fontaines population / 2013, 2014 and 2016 to 2019 for the Chize population /2012 to 2017 fo the Aurignac population

4. Geographic location of data collection: Trois-Fontaines, France (48°43' N, 4°55' E) / Chizé, France (46°50' N, 0°25' W) / Aurignac, France (43°13' N, 0°52’ E)

5. Information about funding sources that supported the collection of the data: The study was funded by INRAE, VetAgro Sup and ONCFS/OFB, and was performed in the framework of the LABEX ECOFECT (ANR-11-LABX-0048) of Université de Lyon, within the program “Investissements d’Avenir” (ANR-11-IDEX-0007).


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: Use of these data for publications or presentations that do not receive approval from one of the contact information person are not allowed.

2. Links to publications that cite or use the data: Not yet available.


DATA & FILE OVERVIEW

1. File List: 
Chize-Data.csv - Data collected on roe deer from the Chizé population and used in analyses of the manuscript entitled "Age and spatio-temporal variations in food resources modulate  stress-immunity relationships in three populations of wild roe deer"
TroisFontaines-Data.csv - Data collected on roe deer from the Trois-Fontaines population and used in analyses of the manuscript entitled "Age and spatio-temporal variations in food resources modulate  stress-immunity relationships in three populations of wild roe deer"
Aurignac-Data.csv - Data collected on roe deer from the Aurignac population and used in analyses of the manuscript entitled "Age and spatio-temporal variations in food resources modulate  stress-immunity relationships in three populations of wild roe deer"

2. Relationship between files: Each file correspond to a dataset related to one the three studied populations.


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
Data were collected during capture sessions of roe deer as part of long-term capture-mark-recapture programs initiated in 1975, 1977 and 1996, in Trois-Fontaines, Chizé and Aurignac respectively.
Details on the procedure can be found here: Carbillet, J., Rey, B., Palme, R., Morellet, N., Bonnot, N., Chaval, Y., Cargnelutti, B., Hewison, A.J.M., Gilot-Fromont, E. and Verheyden, H., 2020. Under cover of the night: Context-dependency of anthropogenic disturbance on stress levels of wild roe deer Capreolus capreolus. Conservation physiology, 8(1), p.coaa086.
Details on the immune analyses can be found here: Carbillet, J., Rey, B., Lavabre, T., Chaval, Y., Merlet, J., Debias, F., Regis, C., Pardonnet, S., Duhayer, J., Gaillard, J.M. and Hewison, A.M., 2019. The neutrophil to lymphocyte ratio indexes individual variation in the behavioural stress response of wild roe deer across fluctuating environmental conditions. Behavioral Ecology and Sociobiology, 73(11), pp.1-13.
Details on the FCMs analyses can be found here: Palme, R., Touma, C., Arias, N., Dominchin, M.F. and Lepschy, M., 2013. Steroid extraction: get the best out of faecal samples. Wien Tierarztl Monatsschr, 100(9-10), pp.238-46.

2. Methods for processing the data: 
All data were processed using R version 3.5.1 (R Development Core Team 2018).

3. Instrument- or software-specific information needed to interpret the data: 
All analyses performed in the previously mentioned manuscript have been performed using R software version 3.5.1 (R Development Core Team 2018).

4. Standards and calibration information, if appropriate: NA

5. Environmental/experimental conditions: Data were collected in environmental conditions.

6. People involved with sample collection, processing, analysis and/or submission: Jeffrey Carbillet, Marine Hollain, Benjamin Rey, Rupert Palme, Maryline Pellerin, Corinne Regis, Anne Geffré, Jeanne Duhayer, Sylvia Pardonnet, François Debias, Joël Merlet, Jean-François Lemaître, Hélène Verheyden, Emmanuelle Gilot-Fromont.


DATA-SPECIFIC INFORMATION FOR: [Chize-Data.xlsx]

1. Number of variables: 25

2. Number of cases/rows: 494

3. Variable List: 
sex - sex of roe deer, either males (M) or females (F)
age - age of roe deer, in years
ID - unique ID for each roe deer
FGM - Faecal glucocorticoid metabolites, in ng per gram of wet faeces
delay - time delay between roe deer capture and data collection, in minutes
year - year of capture, in years
neutro - neutrophil concentrations, in 10^3 cells per mL
lympho - lymphocyte concentrations, in 10^3 cells per mL
eosino - eosinophil concentrations, in 10^3 cells per mL
baso - basophil concentrations, in 10^3 cells per mL
mono - monocyte concentrations, in 10^3 cells per mL
alpha1 - alpha-1 globulin concentrations, in mg per mL
alpha2 - alpha-2 globulin concentrations, in mg per mL
beta - beta globulin concentrations, in mg per mL
gamma - gamma globulin concentrations, in mg per mL
ha - hemagglutination scores, in titer
hl - hemolysis scores, in titer
hap - haptoglobin concentrations, in mg per mL
cohort - year of birth of roe deer, in years
weight - weight of roe deer, in Kg
yearquality - quality of a given year in terms of food ressources, expressed in Kg as it is indexed using the average weight (in Kg) of juveniles caught the following winter 
sector - three sectors are distinguished in this population according to the quantity and quality of resources. Sector 1 is composed of oaks (Quercus spp.) and hornbeams (Carpinus betulus) and is considered to be of better quality than the other two sectors, sector 2 is composed of oaks and Montpellier maples (Acer monspessulanum) and is considered to be of intermediate quality, and sector 3, composed of beeches (Fagus sylvatica) is the sector of worse quality.
juliandate - Julian date where the roe deer capture occured, in days
LogFGM - Log of FGM values
logFGM_C - Log of FGM values that have been centred around the mean (mean value of the variable that is subtracted from every value)
qualite_annee_C - quality of a given year in terms of food ressources that have been centred around the mean (mean value of the variable that is subtracted from every value)

4. Missing data codes: 
Empty cells when data are missing


DATA-SPECIFIC INFORMATION FOR: [TroisFontaines-Data.xlsx]

1. Number of variables: 22

2. Number of cases/rows: 498

3. Variable List: 
sex - sex of roe deer, either males (M) or females (F)
age - age of roe deer, in years
ID - unique ID for each roe deer
FGM - Faecal glucocorticoid metabolites, in ng per gram of wet faeces
delay - time delay between roe deer capture and data collection, in minutes
year - year of capture, in years
neutro - neutrophil concentrations, in 10^3 cells per mL
lympho - lymphocyte concentrations, in 10^3 cells per mL
eosino - eosinophil concentrations, in 10^3 cells per mL
baso - basophil concentrations, in 10^3 cells per mL
mono - monocyte concentrations, in 10^3 cells per mL
alpha1 - alpha-1 globulin concentrations, in mg per mL
alpha2 - alpha-2 globulin concentrations, in mg per mL
beta - beta globulin concentrations, in mg per mL
gamma - gamma globulin concentrations, in mg per mL
ha - hemagglutination scores, in titer
hl - hemolysis scores, in titer
hap - haptoglobin concentrations, in mg per mL
cohort - year of birth of roe deer, in years
weight - weight of roe deer, in Kg
yearquality - quality of a given year in terms of food ressources, expressed in Kg as it is indexed using the average weight (in Kg) of juveniles caught the following winter 
juliandate - Julian date where the roe deer capture occured, in days

4. Missing data codes: 
Empty cells when data are missing


DATA-SPECIFIC INFORMATION FOR: [Aurignac-Data.xlsx]

1. Number of variables: 24

2. Number of cases/rows: 261

3. Variable List: 
sex - sex of roe deer, either males (M) or females (F)
age - age of roe deer, either adults (>1 year) or juveniles (<1 year)
FGM - Faecal glucocorticoid metabolites, in ng per gram of wet faeces
weight - weight of roe deer, in Kg
logFGM_C - Log of Faecal glucocorticoid metabolites values, in ng per gram of wet faeces, that have been centred around the mean (mean value of the variable that is subtracted from every value)
year - year of capture, in years
neutro - neutrophil concentrations, in 10^3 cells per mL
lympho - lymphocyte concentrations, in 10^3 cells per mL
eosino - eosinophil concentrations, in 10^3 cells per mL
baso - basophil concentrations, in 10^3 cells per mL
mono - monocyte concentrations, in 10^3 cells per mL
alpha1 - alpha-1 globulin concentrations, in mg per mL
alpha2 - alpha-2 globulin concentrations, in mg per mL
beta - beta globulin concentrations, in mg per mL
gamma - gamma globulin concentrations, in mg per mL
ha - hemagglutination scores, in titer
hl - hemolysis scores, in titer
yearquality - quality of a given year in terms of food ressources, expressed in Kg as it is indexed using the average weight (in Kg) of juveniles caught the following winter 
sector - three sectors are distinguished in this population according to the quantity and quality of resources and openess of the habitat. The most open habitats (sector 1) offer more important and high-quality food resources for roe deer during most of the year, but can also be a source of higher exposure to stressors, such as road and human dwellings compared to the partially wooded area (sector 2) and woodland (sector 3) 
Delay_C - time delay between roe deer capture and data collection, in minutes, that have been centred around the mean (mean value of the variable that is subtracted from every value)
DateJ - Julian date where the roe deer capture occured, in days
juliandate_C - Julian date where the roe deer capture occured, in days, that have been centred around the mean (mean value of the variable that is subtracted from every value)
yearquality_C - quality of a given year in terms of food ressources, that have been centred around the mean (mean value of the variable that is subtracted from every value), raw data being expressed in Kg as it is indexed using the average weight (in Kg) of juveniles caught the following winter 
weight_C - weight of roe deer, in Kg, that have been centred around the mean (mean value of the variable that is subtracted from every value)

ID - unique ID for each roe deer

4. Missing data codes: 
Empty cells when data are missing
