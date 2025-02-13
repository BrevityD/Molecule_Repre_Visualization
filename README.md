# Molecule Representation Visualization

Compare how molecules are represented across different models.

TODO:
- Convert these notebooks into python script files.

1. trying to use mean value (or sum) of several token embeddings as the representation of a single molecule.
2. trying to use hidden states of last layer (layer 33 if embedding layer included) as the representation of a single molecule. It’s worth mentioning that the hidden state was guided by a prompt, and the final representation was the next token predicted during a single turn inference.

### Some Results:

#### tSNE

![tsne+ratio1](figures/(tsne)model_id4+ratio1+average.png)

#### PCA

![pca+ratio0](figures/(pca)model_id4+ratio0+average.png)
![pca+ratio10](figures/(pca)model_id4+ratio10+average.png)
![pca+lastlayer+ratio0](figures/(pca)last_layer_model_id4+ratio0.png)
![pca+lastlayer+ratio1](figures/(pca)last_layer_model_id4+ratio1.png)