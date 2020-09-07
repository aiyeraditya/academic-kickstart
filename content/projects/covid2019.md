---
title: Reporting COVID19 PCR Results
summary: Where I used Python and Selenium make reporting COVID19 test results efficient
date: "2018-06-28T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: "COVID19 efforts"
  image: ""
---

In April 2020, the Bangalore Life Sciences Cluster at Bangalore set up a COVID19 testing center at inStem (Institute for Stem Cell Science and Regenerative Medicine). I headed code development, patient data handling, and reporting results, as a volunteer at the testing center. 

The Bangalore Life Science Cluster (BLiSC) is a hub, comprised of 3 institutions in Bangalore; the National Center for Biological Sciences (NCBS), the Institute for Stem Cell Science and Regenerative Medicine (inStem), and the Center for Cellular and Molecular Platforms (C-CAMP).  __Example of Research at these places__

Research capacity at BLiSC was almost completely shut down in April. Given the research at BLiSC, the infrastructure required for PCR testing COVID19 samples was available. So were highly skilled personnel, trained in the biosafety protocols and required molecular biology techniques for conducting COVID tests. After expadited approval from the Government of Karnataka and the Indian Council for Medical Research (ICMR), BLiSC started receving throat swabs from hospitals in and around Bangalore, for COVID19 testing on 13 April 2020.

5 teams of volunteers, headed by professors at inStem and NCBS were recruited. 
* The Scientific Staff Team receives samples and delivers them to the BSL2 facility. This team also ensures that the other groups have everything they need. 
* The Mastermix team prepares the mix in appropriate concentrations and quantities for the PCR tests. 
* The BSL2 Team aliquots samples recieved from the hospitals, assign labels, and inactivates the virus. 
* The PCR team does the PCR tests on the inactivated samples. 
* The Data-Handling team adds patient information given by the hospital into a database, and reports results to ICMR and the State government (I co-managed the Data handling team while at the testing center)

When hospitals send the samples, they also send a Specimen Referral form, with patient details, illness history, collection site details, and the hospital details. In the month of April and May, these were physical 2-3 page forms. As they were recieved from the hospital, and were assumed to be infected, photos of each form (front and back) were taken and relayed to the DataHandling team. Using an interface designed by ___ with a ___ database backend, the details were manually input to a locally maintained database. Once the results from the PCR tests were available, these detailas were fed into the database, and patient reports were generated. These were printed and signed by the testing center in-charges, Prof. Colin Jamora and Prof. Dr. Raghu Padintaj. The signed forms were scanned, sorted, and sent to the hospitals that sent the samples. All the patient details and results then have to be uploaded on to the ICMR desinged portal. This contains over 50 fields.

Without any automation, the task of the Data-Handling team was daunting. Full of redundancies, the task was also frustrating. 


### Video From the BLiSC COVID Testing Center (audio in Hindi & English)
{{< youtube 8UN_JfKGVzY >}}