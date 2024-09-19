# README for Mitigating Crash Risks in Work Zones: Causal Inference and Crash Modification Factors {supporting dataset}  
Safety21 University Transportation Center, University Transportation Centers (UTC) Program, U.S. Department of Transportation (USDOT)  
2024-09-18  

## Links  
Dataset Archive Link: <https://github.com/qguengerich/map_matching_work_zones>  
Final Report Archive Link: <https://rosap.ntl.bts.gov/view/dot/77512>

## Summary of Dataset  

In the U.S., a work zone crash occurred every five minutes during 2015 – 2019. It is still unclear the causes of those crashes, such as work zone configurations, weather conditions, work zone duration, and roadway characteristics. The causal impact of those potential factors to work zone crashes may vary substantially cross different types of roads and traffic flow characteristics. Agencies have been working on mitigating work zone crash risk by implementing work zone countermeasures, such as increasing work zone duration, left-hand merge, downstream lane shift, increasing the inside shoulder width, and two-way two-lane operations. The effectiveness of such countermeasures is typically evaluated by a Crash Modification Factor (referred to as CMF throughout this proposal), and more generally, Crash Modification Functions. To this end, crash modification factors (CMF) are typically unknown for work zones. For example, the Manual on Uniform Traffic Control De- vices (MUTCD) provides qualitative recommendations of signs, flaggers, or closure settings for work zones with different characteristics, but no quantitative CMFunctions. FHWA CMF clearinghouse only provides the CMFunctions for implementing left-hand merge and downstream lane shift in rural areas, and modifying shoulder width in urban areas. It is critical to understand the root causes of work zone crashes and propose effective strategies to reduce crash occurrences. This project will continue the work zone safety analysis models developed by CMU Mobility Data Analytics Center, by extending to a full set of all potential causal factors and deploying the models to a number of state agencies (e.g., PA, MD, CA). Based on the models, the team will also establish a systematic approach to estimate the CMF for work zones under various roadway and work zone characteristics. In addition, an online web-based traffic safety analysis tool for selected deployment partners will be developed. Up-to-date safety data from various data providers can be acquired, archived and analyzed to enhance the web application over time. The safety data providers include State and local agencies, Police Department, Waze, and other private data sources (such as INRIX and TomTom). The team will integrate and analyze large-scale crash and incident data, and developed an online tool to visualize and forecast crash types, frequencies and severity for an actual or hypothetical work zone deployments on each road segment, along with mitigating strategies for agencies’ decision making. This research is based upon funded research ‘Mobility Data Analytics Center’ in the years of 2016-2023, with the focus on data-driven safety analysis and improvement. In the past two years, the research team has started building a data engine and a prototype web application to demonstrate the feasibility of multi-source data-driven decision making for state DOTs. The research team started from the PA where they have close partnerships with many local entities, and have successfully applied their data analytics tools in several case studies. The research team's intension in this project is to update the safety analysis models for both PA and MD (possible for CA too), and develop Crash Modification Factors specifically for work zones on state owned roads, which fills the gap that CMFs were rigorously developed for roads without active construction projects. First, the research team will implement a rigorous causal inference model (from MAC’s prior research studies) to infer the causal effect of work zones on crash risk across different work zone configurations, roadway functional classifications, weather conditions, and traffic conditions. The causal forest model avoids potential spurious heterogeneous treatment effects (HTE) by systematically identifying the heterogeneity of treatment effects. In addition, the developed method incorporates the causal forest method with the fixed-effect variable representing road segments to mitigate the unobserved confounding bias in work zone safety studies.  

## Table of Contents  
A. [General Information](#a-general-information)  
B. [Sharing/Access & Policies Information](#b-sharingaccess-and-policies-information)  
C. [Data and Related Files Overview](#c-data-and-related-files-overview)  
D. [Methodological Information](#d-methodological-information)  
E. [Data-Specific Information for: Mitigating Crash Risks in Work Zones: Causal Inference and Crash Modification Factors {supporting dataset} [supporting dataset]](#e-data-specific-information)  
F. [Update Log](#f-update-log)  

**Title of Dataset:**  Mitigating Crash Risks in Work Zones: Causal Inference and Crash Modification Factors {supporting dataset}  

**Description of the Dataset:** In the U.S., a work zone crash occurred every five minutes during 2015 – 2019. It is still unclear the causes of those crashes, such as work zone configurations, weather conditions, work zone duration, and roadway characteristics. The causal impact of those potential factors to work zone crashes may vary substantially cross different types of roads and traffic flow characteristics. Agencies have been working on mitigating work zone crash risk by implementing work zone countermeasures, such as increasing work zone duration, left-hand merge, downstream lane shift, increasing the inside shoulder width, and two-way two-lane operations. The effectiveness of such countermeasures is typically evaluated by a Crash Modification Factor (referred to as CMF throughout this proposal), and more generally, Crash Modification Functions. To this end, crash modification factors (CMF) are typically unknown for work zones. For example, the Manual on Uniform Traffic Control De- vices (MUTCD) provides qualitative recommendations of signs, flaggers, or closure settings for work zones with different characteristics, but no quantitative CMFunctions. FHWA CMF clearinghouse only provides the CMFunctions for implementing left-hand merge and downstream lane shift in rural areas, and modifying shoulder width in urban areas. It is critical to understand the root causes of work zone crashes and propose effective strategies to reduce crash occurrences. This project will continue the work zone safety analysis models developed by CMU Mobility Data Analytics Center, by extending to a full set of all potential causal factors and deploying the models to a number of state agencies (e.g., PA, MD, CA). Based on the models, the team will also establish a systematic approach to estimate the CMF for work zones under various roadway and work zone characteristics. In addition, an online web-based traffic safety analysis tool for selected deployment partners will be developed. Up-to-date safety data from various data providers can be acquired, archived and analyzed to enhance the web application over time. The safety data providers include State and local agencies, Police Department, Waze, and other private data sources (such as INRIX and TomTom). The team will integrate and analyze large-scale crash and incident data, and developed an online tool to visualize and forecast crash types, frequencies and severity for an actual or hypothetical work zone deployments on each road segment, along with mitigating strategies for agencies’ decision making. This research is based upon funded research ‘Mobility Data Analytics Center’ in the years of 2016-2023, with the focus on data-driven safety analysis and improvement. In the past two years, the research team has started building a data engine and a prototype web application to demonstrate the feasibility of multi-source data-driven decision making for state DOTs. The research team started from the PA where they have close partnerships with many local entities, and have successfully applied their data analytics tools in several case studies. The research team's intension in this project is to update the safety analysis models for both PA and MD (possible for CA too), and develop Crash Modification Factors specifically for work zones on state owned roads, which fills the gap that CMFs were rigorously developed for roads without active construction projects. First, the research team will implement a rigorous causal inference model (from MAC’s prior research studies) to infer the causal effect of work zones on crash risk across different work zone configurations, roadway functional classifications, weather conditions, and traffic conditions. The causal forest model avoids potential spurious heterogeneous treatment effects (HTE) by systematically identifying the heterogeneity of treatment effects. In addition, the developed method incorporates the causal forest method with the fixed-effect variable representing road segments to mitigate the unobserved confounding bias in work zone safety studies.  

**Dataset Archive Link:** <https://github.com/qguengerich/map_matching_work_zones>  

**Authorship Information:**   

>  *Principal Data Creator*  
>  Name: Sean Qian ([0000-0001-8716-8989](https://orcid.org/0000-0001-8716-8989))   
>  Institution: Carnegie Mellon University [(ROR ID: https://ror.org/05x2bcf33)](https://ror.org/05x2bcf33)  
>  Address: 5000 Forbes Avenue, Pittsburgh, PA 15213   
>  Email: seanqian@cmu.edu  

>  *Lead Research Assistant*  
>  Name: Quintessa Guengerich ([0009-0006-6236-854X](https://orcid.org/0009-0006-6236-854X))  
>  Institution: Carnegie Mellon University [(ROR ID: https://ror.org/05x2bcf33)](https://ror.org/05x2bcf33)   
>  Address: 5000 Forbes Avenue, Pittsburgh, PA 15213    

>  *Lead Research Assistant*  
>  Name: Tao Tao ([0000-0001-9865-5985](https://orcid.org/0000-0001-9865-5985))  
>  Institution: Carnegie Mellon University [(ROR ID: https://ror.org/05x2bcf33)](https://ror.org/05x2bcf33)   
>  Address: 5000 Forbes Avenue, Pittsburgh, PA 15213      

>  *Organizational Contact Information*  
>  Institution: Safety21 National University Transportation Center [(ROR ID: https://ror.org/02jf59s11)](https://ror.org/02jf59s11)   
>  Website: <https://safety21.cmu.edu/>  
>  Address: 5000 Forbes Avenue, Pittsburgh, PA 15213  

**Date of data collection and update interval:** July 1, 2023-June 30, 2024   

**Geographic location of data collection:** Pennsylvania, United States [(GeoNames URI: https://www.geonames.org/6254927/pennsylvania.html)](https://www.geonames.org/6254927/pennsylvania.html)   

**Information about funding sources that supported the collection of the data:** This project was funded through the US Department of Transportation through the University Transportation Centers (UTC) Program. This project was executed through the Safety21 UTC led by Carnegie Mellon University. The contract number is [69A3551747111](https://rosap.ntl.bts.gov/gsearch?ref=docDetails&grants=69A3551747111).  

## B. Sharing/Access and Policies Information  

**Recommended citation for the data:**  

>  Safety21 University Transportation Center (UTC) (2024). *Mitigating Crash Risks in Work Zones: Causal Inference and Crash Modification Factors {supporting dataset}*. <https://github.com/qguengerich/map_matching_work_zones>  

**Licenses/restrictions placed on the data:** This document is disseminated under the sponsorship of the U.S. Department of Transportation in the interest of information exchange. The United States Government assumes no liability for the contents thereof.  

**Was data derived from another source?:** Yes. This study utilized  two main data sources in this research project, including the Road Condition Reporting System (RCRS) and the Pennsylvania state road network datasets, both of which are requested from the Pennsylvania Department of Transportation.   

This document was created to meet the requirements enumerated in the U.S. Department of Transportation's [Plan to Increase Public Access to the Results of Federally-Funded Scientific Research Version 1.1](https://doi.org/10.21949/1520559) and [Guidelines suggested by the DOT Public Access website](https://doi.org/10.21949/1503647), in effect and current as of December 03, 2020.  
 
## C. Data and Related Files Overview  

File List for the 100295_DATASET.zip  

>  1. Filename: cleaning_workzones_2018-2024.html   
>  Short Description:  HTML file that contains tables and information from the project.   

>  2. Filename: cleaning_workzones_2018-2024.ipynb  
>  Short Description:  Jupyter notebook version of the file with the same name.  

>  3. Filename: map_matching_workzones_in_bounds.html  
>  Short Description:  HTML file that contains tables and information from the project.  

>  4. Filename: map_matching_workzones_in_bounds.ipynb   
>  Short Description:  Jupyter notebook version of the file with the same name.  

>  5. Filename: MapMatchedWZs_desc.html  
>  Short Description:  HTML file that contains tables and information from the project.    

>  6. Filename: MapMatchedWZs_desc.ipynb  
>  Short Description:  Jupyter notebook version of the file with the same name.    

>  7. Filename: README.md   
>  Short Description:  README document for this dataset.  

## D. Methodological Information   

**Description of methods used for collection/generation of data:** We designed several modules to match work zones to the Pennsylvania road network given the work zone starting and ending coordinates, the state route number, and the direction of the respective roadway. This involves several steps, including steps taken to decrease the computation time via vectorization and filtering of the search space to limited possibilities. In general, the overall algorithm operates under the following assumptions:  
1. The correct state route number is recorded for each work zone. This means that each work zone should be mapped to their respective state route number, regardless of whether a different route is closer to the coordinates recorded.  
2. The direction recorded for each work zone is correct. This means that each work zone should be mapped to their respective state route number, going the direction recorded, regardless of whether the other direction is closer to the recorded coordinates of the work zone  

More methodology information can be found in the final report.    

**Instrument or software-specific information needed to interpret the data:** To best view the CSV files, use your default web-browser or Visual Studio Code. The markdown readme file may be read using any text editor, but is best rendered using a markdown previewer.  

## E. Data-Specific Information   

Due to a non-disclosure agreement with Pennslyvania DOT, the raw data files will not be shared for this project.   

## F. Update Log  

This README.txt file was originally created on 2024-09-18 by Peyton Tvrdy ([0000-0002-9720-4725](https://orcid.org/0000-0002-9720-4725)), Data Management and Data Curation Fellow, National Transportation Library <peyton.tvrdy.ctr@dot.gov>  
 
2024-09-18: Original file created  
