## Creating a Data Package for NES-LTER Fish Diet and Stable Isotope Data

This repository displays the workflow used to process the NES-LTER small pelagic fish diet and stable isotope data provided by the Llopiz lab in preparation for publication to the Environmental Data Initiative repository. Two packages were produced for the fish diet and stable isotope data respectively.

This workflow includes the following:
1) cleans the provided data
2) performs quality assurance on the data
3) assembles and outputs the final XML file for submission to EDI

**Base Requirements:**
- Microsoft Excel
- R and R studio (*packages:* tidyverse, readxl, lubridate, devtools, EMLassemblyline, EML, maps)

### Collaborators:
Justin Suca (creator), Joel Llopiz (PI), Stace Beaulieu (associate; co-PI for the NES-LTER project), Jaxine Wolfe (associate; metadata provider)

### Package Status:
The final version of the fish diet composition data package is published to the EDI repository and can be found [here](https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-nes.2.2).

The final version of the fish stable isotope data package is published to the EDI repository and can be found [here](https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-nes.3.1).