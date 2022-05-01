# TigerGraph's Video-Recommendation-System

## Introduction
- This application is to get your favorite videos recommended powered by Graph Database based on provided keywords and the ability to pinpoint where the keyword was spoken in the videos! The dataset incorporates a variety of themes like finance, cryptocurrency, animals, astronomy, literature, authors, etc. 

- The topics analytics page will allow you to find an interactive topic model generated on the dataset that coordinates the similarity between different topics and the videos they belong to using Latent Dirichlet Allocation. 

- Head over to our explore visuals section to dive deep into the dataset by looking at various entities and a dynamic Cytoscape to visualize the network of keywords we are working with. You can observe how multiple keywords appear in different videos and the vast graph that connects them! 

## Setup Locally
- Clone this repository:

  `git clone https://github.com/atishaye/Video-Recommendation-System.git`
- Make sure the TigeGraph Cloud solution is running and is in ready state.
- Run All cells in the `TigerGraph's_Extern_Dashboard_Final.ipynb` file present in `Google Colab Notebooks` folder.
- For each Google Colab, you can find any required files in the `data` folder of this repository.
- In case of queries or for more detailed setup, refer to the <a href="https://medium.com/@btyagi/video-recommendation-system-561dd60e563b">blog </a>.

## Tools Used
- **TigerGraph Cloud**: TigerGraph Cloud is where we’ll create our solution and host our graph database. This will also contain all the data we’ll be using.
- **Plotly Express**: Plotly Express is a high-level library under Plotly to easily create nice visualisations.
- **Plotly Dash**: Plotly Dash is Plotly’s dashboarding library, and we’ll use it to built various components on our dashboard.
## Important Links
- <a href="https://medium.com/@btyagi/video-recommendation-system-561dd60e563b"> Medium Blog Link </a>
- <a href="https://drive.google.com/drive/folders/1k1nDWr2p4p63X2LegnFjBwqRhmjBl-Uh?usp=sharing"> External Drive Link </a>

## Glimpses

### General Overview Page
You can jump to the timestamp of the keywords in the videos and get your favorite videos recommended with cool visuals!

  ![General Overview Page](https://user-images.githubusercontent.com/55448429/166070187-c72fe759-3dfd-4723-92d0-64fe20ee05e1.gif)

### Named Entity Recognition Visualization

Named entity recognition (NER) aids in locating and classifying named entities in text into predefined categories such as the names of persons, organisations, locations, expressions of times, quantities, monetary values, percentages, etc. It helps in answering some real-world questions such as:
- Which companies were mentioned in the videos?
- Were specified products and names mentioned in the video?

![NER Vis](https://user-images.githubusercontent.com/55448429/166070211-cec8a791-d1d0-46fe-b925-762dc346e145.gif)

### Cytoscape

Dash Cytoscape is a graph visualization component for creating easily customizable, high-performance, interactive, and web-based networks. It extends and renders Cytoscape.

  ![Cytoscape](https://user-images.githubusercontent.com/55448429/166070258-2b46b595-ccc6-43e9-b256-6fba84a04f88.gif)

### Topic Modeling | pyLDAVis Visualization

We have performed topic modelling using a famous topic modelling technique Latent Dirichlet Allocation on our video transcripts datasets to extract the topics that are present in the videos which will aid in our visualizations.
  
  ![Topic Modeling](https://user-images.githubusercontent.com/55448429/166070281-c7adf4ca-a081-4b65-9426-d3b6dd2bffeb.gif)

## Frameworks
  ![TigerGraph App Framework](https://user-images.githubusercontent.com/55448429/166103973-d9e0f1b1-807c-4337-a928-d7b6c62b5a32.png)
> Here we can use Vosk, Google Speech Recognition or Facebook Model of Speech Recognition to generate transcripts.

  ![TigerGraph App Framework (2)](https://user-images.githubusercontent.com/55448429/166138726-f35ec02e-11cb-4da8-8618-2a683eb60468.png)

## Contributing

- Should be locally tested and well formatted.
- It is good practice to open an issue first and discuss your changes before submitting a pull request. This way, you can incorporate ideas from others before you even start.
- Please follow the GitHub PR workflow for your contributions.
- Fork this repo, create a feature branch, commit your changes and open a PR to this repo.

## Conclusion
We have built a video recommendation system with dynamic visualizations using TigerGraph, Plotly, and dash with
Follow the steps mentioned above to create your very own video recommendation system. You may add your visualizations using dash to create a customized UI according to you! Let us know how you feel about this project! If you have any queries on any aspect, feel free to contact the below mentioned.


<div align='center',style={'display':'flex'}> 
<a href="https://github.com/atishaye"> Atishaye Jain </a>
, <a href="https://github.com/bhavyatyagi"> Bhavya Tyagi </a>
 and <a href="https://github.com/janhavilande"> Janhavi Lande </a>
</div>
