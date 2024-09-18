### Accompanying code for: "Brief Communication: Monitoring snow depth using small, cheap, and easy-to-deploy ground surface temperature sensors" (O4788)

LA-UR-24-29902

Temporally continuous snow depth estimates are vital for understanding changing snow patterns and impacts on permafrost in the Arctic. We trained a random forest machine learning model to predict snow depth from variability in ground surface temperature. The motivation behind this approach is that with increasing snow depth, ground surface temperature becomes less variable. To our knowledge, this is the first time that small ground surface temperature sensors have been used to estimate snow depth. The model performs well at sites where the model was trained and at pan-arctic evaluation sites (RMSE <= 0.15 m). Small temperature sensors are cheap and easy-to-deploy, so this technique enables spatially distributed and temporally continuous snowpack monitoring to an extent previously infeasible. The model is flexible and can be applied to datasets retroactively to retrieve snow depth estimates at additional sites. This code package includes a *.joblib file of the trained random forest model and a *.ipynb file showing how to clean input data, train the random forest model, and apply the model.  

Due to limitations of the training dataset, the model cannot predict snow depths greater than 1.5 m. The model is trained using collocated snow-ground interface and snow depth data collected at the NGEE Arctic Teller 27 and Kougarok 64 study sites on the Seward Peninsula of Alaska (Wang et al., in prep). Training data and model design is further described in the related publication (https://doi.org/10.5194/egusphere-2024-2249) and in the associated dataset user guide (doi:10.15485/2371854). 

#### Included files: 
-	rf_seward.joblib  This file contains the trained random forest model, which can be downloaded and applied to new datasets (e.g. see related iButton datasets).
-	RF_Seward_Code_Examples.ipynb This jupyter notebook shows examples for how to train the random forest model, clean input datasets, and generate snow depth predictions.

See LICENCE.md for license and header information related to this code. 


#### Please cite the related publication: 

Bachand, C. L., Wang, C., Dafflon, B., Thomas, L. N., Shirley, I., Maebius, S., Iversen, C., Bennett, K. E. Brief Communication: Monitoring snow depth using small, cheap, and easy-to-deploy ground surface temperature sensors. In review. https://doi.org/10.5194/egusphere-2024-2249

#### Related dataset: 

Claire Bachand, Chen Wang, Baptiste Dafflon, Lauren Thomas, Ian Shirley, Sarah Maebius, Colleen Iversen, Katrina Bennett. 2024. Machine learning snow depth predictions at sites in Alaska, Norway, Siberia, Colorado and New Mexico. Next Generation Ecosystem Experiments Arctic Data Collection, Oak Ridge National Laboratory, U.S. Department of Energy, Oak Ridge, Tennessee, USA. Dataset accessed on [INSERT_DATE] at https://doi.org/10.15485/2371854.


#### Related iButton Datasets: 

Katrina E. Bennett, Robert Bolton, Emma Lathrop, Lauren Thomas, Shannon Dillard, Julian Dann. 2023. iButton snow temperature measurements at Teller 27 and Kougarok 64 from 2019-2020, Seward Peninsula, Alaska. Next Generation Ecosystem Experiments Arctic Data Collection, Oak Ridge National Laboratory, U.S. Department of Energy, Oak Ridge, Tennessee, USA. Dataset accessed on [INSERT_DATE] at https://doi.org/10.5440/1996564

Katrina Bennett, Shannon Dillard, Lauren Thomas, Claire Bachand, Greta Miller, Bob Bolton, Julian Dann, Adam Collins, Rutuja Chitra-Tarak.  2022. iButton and Tinytag snow temperature measurements at Teller 27 and Kougarok 64 from 2021-2022, Seward Peninsula, Alaska. Next Generation Ecosystem Experiments Arctic Data Collection, Oak Ridge National Laboratory, U.S. Department of Energy, Oak Ridge, Tennessee, USA. Dataset accessed on [INSERT_DATE] at https://doi.org/10.5440/1996546

Katrina Bennett, Claire Bachand, Lauren Thomas, Eve Gasarch, Evan Thaler, Ryan Crumley.  2023. iButton and Tinytag snow temperature measurements at Teller 27 and Kougarok 64 from 2022-2023, Seward Peninsula, Alaska. Next Generation Ecosystem Experiments (NGEE) Arctic, ESS-DIVE repository. Dataset. https://doi.org/10.15485/2319246


#### NGEE Arctic Project Summary
The Next-Generation Ecosystem Experiments: Arctic (NGEE Arctic), was a research effort to reduce uncertainty in Earth System Models by developing a predictive understanding of carbon-rich Arctic ecosystems and feedbacks to climate. NGEE Arctic was supported by the Department of Energy’s Office of Biological and Environmental Research.

The NGEE Arctic project had two field research sites: 1) located within the Arctic polygonal tundra coastal region on the Barrow Environmental Observatory (BEO) and the North Slope near Utqiagvik (Barrow), Alaska and 2) multiple areas on the discontinuous permafrost region of the Seward Peninsula north of Nome, Alaska.

Through observations, experiments, and synthesis with existing datasets, NGEE Arctic provided an enhanced knowledge base for multi-scale modeling and contributed to improved process representation at global pan-Arctic scales within the Department of Energy’s Earth system Model (the Energy Exascale Earth System Model, or E3SM), and specifically within the E3SM Land Model component (ELM).



