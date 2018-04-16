# Faceify
### Generative Adversarial Network for Faces


## Getting Started
- Create a python virtual environment
- Activate environment
- `pip install -r requirements.txt`
- `jupyter notebook`
- Run faceify.ipynb


## Description

The faceify notebook explores properties of an image generator, trained on the CelebA dataset, using the progressive generative adversarial network (GAN) approach. 

Using the notebook you can 

- Explore images produced by the generator, and do latent space interpolation between different images
- Find the image produced by the generator that is most similar to some other image located in the /targets directory. Note that this only works well if the initial image is *reasonably* close to an image in the CelebA dataset.

## Next Steps

- Starting with the pretrained generator and discriminator, unfreeze the top most layers and retrain on a database of images of faces from a different set of people (e.g. not celebrities). One such set which would be interesting would be physicists, since they have a particular look, and it would be interesting to see if the GAN can capture it as it does for celebrities. 

