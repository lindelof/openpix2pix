# openpix2pix

Similar to the previous one, trained on a database of ~137k handbag pictures collected from Amazon and automatically generated edges from those pictures. If you draw a shoe here instead of a handbag, you get a very oddly textured shoe.

## Implementation 

The models were trained and exported with the pix2pix.py script from pix2pix-tensorflow. The interactive demo is made in javascript using the Canvas API and runs the model using Datasets section on GitHub. All the ones released alongside the original pix2pix implementation should be available. The models used for the javascript implementation are available at pix2pix-tensorflow-models.
