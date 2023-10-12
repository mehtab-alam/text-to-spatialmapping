<p> <img src="https://mood-h2020.eu/wp-content/uploads/2020/10/logo_Mood_cmjn_black-1.jpg" width="15%";"/></p> 

# Risk Mapping Dashboard: From text to Spatial Mapping
**MOOD Summer School 2023**  

# Summary

In this practical session, we will explore the process of transforming the Avian-Influenza article dataset into an informative dashboard using various visualizations. Specifically, we will focus on extracting location information from the text of the articles to create visual representations such as word clouds, top 10 countries, heatmap, map clusters, and choropleth maps, time-series heatmap.

During this session, our primary objective is not to assess the accuracy of individual events but rather to emphasize on the extraction of location data from the article dataset. By leveraging different techniques, we can uncover valuable insights and trends related to Avian Influenza outbreaks across different regions.

Through the application of visualization methods, we aim to present a comprehensive overview of the geographic distribution of these events. This will facilitate a deeper understanding of the global impact of Avian Influenza and its potential spread.

By the end of this session, participants will gain practical experience in location extraction, data transformation, and the creation of visually informative dashboards using the Avian-Influenza article dataset. 

An overview of the practical is shown in Figure below:

<p> <img src="https://drive.google.com/uc?export=download&id=1MeTWMtdaKtFONImz_XC_m_5L5Eevi9JG" width="100%";"/></p> 

# Datasets

**Avian-Influenza Dataset:**

The first dataset about the articles that contain events of Avian-Influenza extracted from PADI-web for the period 2018-2019 around the world. You can download the dataset from this **[link](https://drive.google.com/uc?export=download&id=1zIjfy-8exo7Fv111hOHDzonyE9D8j81c).**


The dataset containin 438 articles with following information: 
*   **id**: unique identifier of the article 
*   **title**: title of the article 
*   **text**: article text 
*   **url**: url of the source  
*   **type**: article is relevant/irrelevant e.g. relevant if it contain event(s)  
*  **treated** Manually treated by expert 
*  **published_at** date when the article was published online 
* **source** online article source 

__________________________________________________________________________



**Optional: West-Nile Virus (WNV) Europe Dataset:**

This dataset is about the articles contains the outbreaks of West-Nile Virus (WNV) extracted from PADI-web in Europe. Maybe we have the locations is outside of the Europe in it with some reference to the outbreaks but we are not concerned in the accuracy of the outbreak. You can download the dataset from this **[link](https://drive.google.com/uc?export=download&id=1GxkNcT4xviP5Yta0MMxPhLCHpyjleISO).** 

The information in the articles are more or less same with some extra information too ☺️. 

## [Cite this work](https://github.com/mehtab-alam/text-to-spatialmapping/)

```latex
@software{syed_text_to_spatial_2023,
    author = {Syed, Mehtab Alam and Arsevska, Elena and Roche, Mathieu and Teisseire, Maguelonne},
    doi = {10.5281/zenodo.8434873},
    license = {GNU GPLv3},
    title = {{Text to Spatial Mapping}},
    url = {https://github.com/mehtab-alam/text-to-spatialmapping/},
    version = {1.0.0},
    year = {2023}
}
```
