# Molecule Representation Visualization

Compare how molecules are represented across different models.

TODO:
- Convert these notebooks into python script files.

1. trying to use mean value (or sum) of several token embeddings as the representation of a single molecule.
2. trying to use hidden states of last layer (layer 33 if embedding layer included) as the representation of a single molecule. It’s worth mentioning that the hidden state was guided by a prompt, and the final representation was the next token predicted during a single turn inference.