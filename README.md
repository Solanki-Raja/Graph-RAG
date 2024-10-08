# Intro
<div align="center">
<img src="./Images/Figure 1. Node Generation.png" width="50%"/>
<br/>
</div>
Generate queried responses referenced against constructed graphs extracted from external RAG databases to retrieve highly contextual
and accurate responses against the LLM:
<br/>
<div align="center">
<img src="./Images/Figure 2. Outputted Response.png" width="50%"/>
<br/>
</div>

## Project Overview
In this project, we created a program that considers a database I compiled containing 58,067 
biomedical articles/research papers to act as a consultant for professionals specializing in 
cancer treatment development within the biomedical industry who need to stay up-to-date on the 
most relevant and important research being conducted in the field.  The program not only generates 
a response based on the user prompt, but also provides visual context that demonstrates the connections 
made by the model between different relationships within the database that was used to generate the answer provided to the user.  

## Project Methodology

The objective of this project was to implement emerging techniques for improving the 
performance of generative AI large language models (LLMs) under specific contexts.  In particular, the 
application of graph database construction in natural language processing (NLP) to provide better 
Retrieval-Augmented Generation (RAG) performance allows for an improved likelihood of both avoiding 
model hallucinations and generating more accurate responses compared to basic LLM querying alone.

## Project Paper
[Link](https://github.com/Solanki-Raja/Graph-RAG-LLM-Research-Consultant/blob/main/Graph%20Rag%20Project%20Write-Up.pdf) to our paper covering an overview of the project background, methods, and results:


### Built With

This project was built with the following technologies:

- Python
- Mistral
- LlamaIndex


## Setup
Here are some specific links that may be helpful.
[LlamaIndex](https://docs.llamaindex.ai/en/latest/module_guides/indexing/lpg_index_guide/),
[Mistral AI](https://docs.mistral.ai/guides/rag/)

## Data
The data comes from a compiled database of 58,067 biomedical articles/research papers.

[click Here](https://github.com/jameshopham/Datasets/blob/main/Combined_Clinical_Trials_Articles.csv ) to download the Dataset: 



## Contact

If you have any questions or suggestions, feel free to reach out to us:

- Connect with us on LinkedIn:


<div class="container">
  
  <div>
    <img src="./Images/1718304683335.jpeg" alt="Raja Solanki">
    <br>
    <a href="https://www.linkedin.com/in/solankiraja/" target="_blank">Raja Solanki</a>
  </div>
  <div>
    <img src="./Images/1706388570200.jpeg" alt="James Hopham">
    <br>
    <a href="https://www.linkedin.com/in/james-hopham-2440352a5/" target="_blank">James Hopham</a>
  </div>
</div>




