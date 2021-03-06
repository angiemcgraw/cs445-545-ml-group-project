## PSU CS 445/545 Machine Learning Group Project
<hr />
<div align="center">

### Topic Modeling of COVID-19 Research Papers
_Brandon Le, Yves Wienecke, Angie McGraw, Tu Vu, Keaton Kraiger_
</div><br />

The COVID-19 pandemic is a major world event, having an extensive impact on the ebb and flow of society. The pandemic has significantly disrupted the manner in which people communicate and learn. One of the leading voices in the pandemic is the medical field, providing us a little light in these uncertain times. Given the credibility and influence of medical research papers, our group is interested in applying machine learning techniques to identify patterns and make sense of the madness. We hope to utilize natural language processing (NLP) to learn about the shift in research topics leading up to and during the pandemic. Moreover, we believe this project will help elucidate the shifts in scholarly conversation and how these topics change over time and possibly, by geographic location. Our motivation for this project stems primarily from the significant effect that COVID-19 has had on each of us and our communities. In addition, some of us have a connection to the medical field and see this situation as an opportunity to interweave experience in the fields of medicine and computer science. Although we are isolated from the community and living in our new realities, we are nevertheless interested in understanding the new realities of others. For the final project, our group is proposing to perform topic modeling on research papers obtained from the Allen Institute Database, by date of publication. Two of the algorithms that we will be looking at are word2vec and Latent Dirichlet Allocation (LDA). Once the algorithms are conducted, we plan to analyze and visualize our results.

This repository is structured to separate our **research, code, and dataset**. The `papers/` directory contains the project proposal and research paper associated with this project. The `code/` directory contains all of the python scripts used for downloading and preparing the dataset, running the topic modeling algorithms, and visualizing the results. The `data/` directory is the location in which the dataset will be stored, separated by city and date. This repository only shows examples of the structure of the data and will not include the complete datasets.
<br /><br />

The data for this project can be downloaded from [here](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge?select=metadata.csv). The file of interest is `metadata.csv` which should be placed into the `data` folder of this project. 

### To run the code
In the `src/` directory, there are two [Jupyter Notebooks](https://jupyter.org/), `TopicModel.ipynb` and `w2v_tsne.ipynb`. For ease, we recommend running the programs from the notebooks. You can download or clone this repository to your local machine. Once downloaded, please cd into the `src` directory and type 

```sh
jupyter notebook
```

from a terminal. This should open Jupyter and allow you to open either notebook. Once you have opened a notebook, navigate to `cell` and then `Run All` . 
