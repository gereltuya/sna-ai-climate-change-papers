# Network Analysis of AI x Climate Change papers on Google Scholar

## About the project

Since I would like to study AI methods and their application in Climate change mitigation and adaptation, for this coursework, I tried to analyze relevant papers and their authors as social networks.

![AI and climate change papers](./results/ai-climate-change-papers.png)

## Main results and methods used

### 1. Reading and analyzing initial data with Python and Pandas

![Papers data](./results/papers-data.png)

### 2. Preprocessing and cleaning data with Pandas

![Authors data](./results/authors-data.png)

### 3. Creating a graph with trios of (paper_1, paper_2, common_authors) with Networkx

![Creating a graph](./results/creating-graph.png)

### 4. Calculating betweenness and other centralities with Networkx

![Calculating centrality](./results/calculating-centrality.png)

### 5. Visualizing the graph with Matplotlib

![Visualizing the network](./results/visualizing-papers-network.png)

### 6. Modifying the graph and adding visual aids with Networkx and Matplotlib

![Visualizing central papers](./results/visualizing-central-papers.png)

![Identifying central papers](./results/identifying-central-papers.png)

## To replicate the results

### Requirements

```
pip install -r requirements.txt
```

After preparing the environment, please start the jupyter notebook [sna-ai-climate-change-papers.ipynb](https://github.com/gereltuya/sna-ai-climate-change-papers/blob/main/sna-ai-climate-change-papers.ipynb) and follow the code steps.

### Data

To run the data collection step in the notebook, you need to add your own SerpApi token, but you can skip the step and work on the downloaded data in the [data/](https://github.com/gereltuya/sna-ai-climate-change-papers/tree/main/data) folder.

### Code

Data preprocessing, cleaning, and analysis code was written from scratch by me.

Core of the Social network analysis code was taken from this [project by Julia Wu](https://github.com/hw355/sna_twitter), as used by me [on a similar coursework](https://github.com/gereltuya/sna-mongolia-tweets).
