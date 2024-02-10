
## Software requirements

The R scripts were prepared using R version 3.6.1 on Windows 11 Pro.
The following R packages were used in this analysis:

```
library(readr)
library(readxl)
library(writexl)
library(tidyverse)
library(reshape2) 
library(stringr)
library(scales)
library(tm)
library(lubridate)
library(viridis)
library(summarytools)
library(rnaturalearthdata)
library(rnaturalearth)
library(sf)
library(cowplot)
library(ggplot2)
library(tmap)
library(ggpubr)
library(RColorBrewer)
```


## Data

All the data that support the findings of this study are publicly available. Please refer to Supplementary Table 1 and Supplementary Table 2 for detailed data source information. 


## Code

All analysis code are deposited in the folder ***Code/*** 

### data preprocessing
```
05_AncillaryData_ISO3Code_shp.Rmd
05a_helper_capital cities.R
10_country_profileData_prepare.Rmd
11_Comtrade.Rmd
11_Comtrade_BACI_Pesticides.Rmd
11_FAO_FishStatJ.R
21_00_unify_format_before_MRIO_data_clean.Rmd
21_MRIO_data_clean.Rmd
22_09_prep_direction_data.Rmd
```

### scenario analysis & SDG score calculation
```
22_10_TNI_rel_not.Rmd
22_20_TNI_dst_ner.Rmd
22_22_FootprintDistance.Rmd
25_TNI_on_SDGs_Data.Rmd
```

## visualize result 
```
26_TNI_on_SDGs_Viz.Rmd
27a1_TNI_Networks_data.Rmd
27a2_TNI_Networks_plot.Rmd
27b_TNI_Networks_map.Rmd
```


## Contact
yingjieli DOT edu AT gmail DOT com
