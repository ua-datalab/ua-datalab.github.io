
## Data Science Learning Path

We present 12 topics in the data science learning path, providing learning objectives, related skills, subtopics, and references/resources for each. The goal is to give graduate students a structured and comprehensive program to acquire data science expertise, including hands-on experience with real-world open-source tools and libraries.

```
   eth["`**Ethics**`"] --> ds
   ds --> stats["`**Statistics**`"]
   eth --> stats
   C --> cdci["`**Model Deployment and Productionization**`"]
   D --> cdci
   ds --> cdci
   eth --> C
   eth --> D
```


```mermaid
flowchart TB
   subgraph ds ["`**General Data Science**`"]
   introds["`**Intro to Data Science and Machine Learning**`"] --> pyds["`**Python for Data Science**`"]
   end
   subgraph C ["`**Classical Machine Learning**`"]
   class["`**4.Classification Algorithms**`"] --> ensemble["`**5. Ensemble Methods**`"] --> UL["`**6. Unsupervised Learning**`"]
   end
   subgraph D ["`**Deep Learning**`"]
   introdl["`**Intro to Deep Learning**`"] --> RNN["`**Recurrent Neural Networks and Sequence Models**`"] --> Gen["`**Generative Models**`"]  --> TL["`**Transfer Learning and Fine Tuning**`"]
   end

```


```mermaid
flowchart TB
   subgraph ds 
   introds-->pyds
   end
   subgraph C ["`**Classical Machine Learning**`"]
   class["`**4.Classification Algorithms**`"]-->ensemble["`**5. Ensemble Methods**`"]-->UL["`**6. Unsupervised Learning**`"]
   end
   subgraph D ["`**Deep Learning**`"]
   introdl["`**Intro to Deep Learning**`"]-->RNN["`**Recurrent Neural Networks and Sequence Models**`"]-->Gen["`**Generative Models**`"]-->TL["`**Transfer Learning and Fine Tuning**`"]
   end

```


A: General Data Science

1. Introduction to Data Science and Machine Learning

2. Python for Data Science

B: Statistics

3. Statistical Learning and Regression Models

C: Classical Machine Learning

4. Classification Algorithms

5. Ensemble Methods

6. Unsupervised Learning

D: Deep Learning

7. Introduction to Deep Learning

8. Recurrent Neural Networks and Sequence Models

9. Generative Models

10. Transfer Learning and Fine-tuning

E: Continuous Integration Continuous Development

11. Model Deployment and Productionization

F: Ethics

12. Ethical Considerations in Data Science




## Working with different data types.

Next you will find five specialized data science learning paths that branch off from the core topics in the previous section. Each specialized path includes a learning objective, related skills, subtopics, and references/resources.


```mermaid
  flowchart LR;
      A@{shape:processes, label: "Data types"}-->B["`**Working with Numeric and Categorical Data**`"];
      A-->C["`**Computer Vision and Image-based Learning**`"];
      A-->D["`**Time Series Analysis and Forecasting**`"];
      A-->E["`**Natural Language Processing**`"];
      A-->F["`**Speech and Audio Processing**`"];
      click B href "https://github.com/ua-datalab/mlpaths/wiki/Working-with-Numeric-and-Categorical-Data" "Open this in a new tab" _blank
      click C href "https://github.com/ua-datalab/mlpaths/wiki/Computer-Vision-and-Image%E2%80%90based-Learning" "Open this in a new tab" _blank
      click D href "https://github.com/ua-datalab/mlpaths/wiki/Time-Series-Analysis-and-Forecasting" "Open this in a new tab" _blank
      click E href "https://github.com/ua-datalab/mlpaths/wiki/Natural-Language-Processing" "Open this in a new tab" _blank
      click F href "https://github.com/ua-datalab/mlpaths/wiki/Computer-Vision-and-Image%E2%80%90based-Learning" "Open this in a new tab" _blank


```




