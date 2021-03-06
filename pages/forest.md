## Call of the Forest: Detection of Animal Species in Tropical Landscape

[Dennis Dominic Diego](https://www.linkedin.com/in/dennis-dominic-diego),
[Jason Dolorso](https://www.linkedin.com/in/jasondolorso/), 
[Cymon Marcaida](https://www.linkedin.com/in/cymonmarcaida/), 
[Matthew Romero](https://www.linkedin.com/in/matmatromero)  
Asian Institute of Management

[<img src="../images/Rainforest.png"/>](https://raw.githubusercontent.com/jasondolorso/jasondolorso.github.io/master/images/Rainforest.png)

### Executive Summary
<p align="justify">
The presence or absence of certain animal species in an environment indicates the health of the ecosystem. It is one measurement, among many others on how human activities impacts our natural environment. We can look back to the United States in the 1950s where the constructions of canals and levees atlerted the flow of water in the everglades which caused negative impact to the environment. This resulted to an anual decline of wading birds nesting in the area due to the dwindling population of prey.

Identifying the presence or absence of bird species in an area is one of the ingishgtful measure of environmental impact. Unfortulately in most cases, hearing the sound of the birds are easier than seeing them. This is especially true on dense forests where the horizon is covered by the thick canopies of trees and the forest trail is full of leaves, branches, and tall grasses which makes it hard for humans to traverse. With these challenges in specie identification in tropical rainforests, we look into the capabilities of audio identification to identify the species. Specifically we want to know `how can we determine the biodiversity of a rainforest by classifying the sounds of the species that are heard in the forest audio recording?`

Using data from an ongoing kaggle competition whose goal is to identify 24 birds and frog species using audio files, we cleaned and processed data using amazon web service architecture and dask library to handle large amount of data. From the audio files, we generated a mel spectrogram image of the a specific animal specie in the audio recording which we then used as input to our deep learning model.

Cloud computing was used to handle the relatively big data involved (57.32 GB of audio files) through Amazon Web Services. AWS S3 was used as the storage and an EC2 instance was the platform to process the data through Dask dataframe and PySpark. We achieved an 85% accuracy using resnet-50 to classify and identify the specie of a specific mel-spectrogram. The result was achieved by averaging five iterations of training using a stratified 5 fold train-test split. The resulting model was then used to infer specific specie on a raw audio file. 
</p>

---

*Full text article and source codes can be provided upon request*.


